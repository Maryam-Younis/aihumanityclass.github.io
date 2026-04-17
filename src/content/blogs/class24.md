+++
title = "Class 24: Detecting AI Generated Content"
author = "Aaryan Asthana, Jason Chin, Sarah Petchel, Taylor Petrofski, Katherine Anne Rukavina"
date = "2026-04-14"
+++


**Blogging Team [4]**: Aaryan Asthana, Jason Chin, Sarah Petchel, Taylor Petrofski, Katherine Anne Rukavina

## News: Claude Mythos and Project Glasswing

**Presented by Professor Evans**: [Download Slides](/docs/cs4501ha-s26-class23.pptx)

### Articles Discussed

1. Fort, Stanislav. (2026, April 7). AI Cybersecurity After Mythos: The Jagged Frontier. Aisle. https://aisle.com/blog/ai-cybersecurity-after-mythos-the-jagged-frontier?utm_source=google&utm_medium=cpc&utm_campaign=na-dynamic&utm_content=search&utm_term=&gad_source=1&gad_campaignid=23674247412&gbraid=0AAAABDBwDHk6CYcfDr72D5V6AW4MLBs4C&gclid=Cj0KCQjwy_fOBhC6ARIsAHKFB79K2TlNdlqOnAH6Va-i_7TwOfrsZA66y-4JuH_OFKYF0C4FwwATplUaAky-EALw_wcB 

  
2. Carlini, Nicholas, et al. (2026, April 7). Assessing Claude Mythos Preview’s cybersecurity capabilities. red.anthropic.com. https://red.anthropic.com/2026/mythos-preview/ 

## Discussion:

<center>
<div style="display: flex; justify-content: center; gap: 20px;">
  <img src="/images/claude_mythos.png" width="300">
  <img src="/images/project_glasswing.jpeg" width="300">
</div>
</center>

Professor Evans opened class with news about Anthropic’s latest model. Anthropic announced a new model that will not be released to the public for approximately one month, though 40 partner companies have been granted early access to identify security vulnerabilities before the broader launch. The delay is because the model is considered too capable at cybersecurity tasks to release without careful vetting first.

To illustrate whether that caution is justified, Prof. Evans walked the class through a recent case in which AI tools were used to discover a 27-year-old bug in OpenBSD, originally written by Niels Provos in 1998. The bug involved code that fails to check the start of a range, with a second condition where the start is simultaneously at or below a hole’s start and strictly above the highest bit acknowledged. When asked whether they were surprised that such an old vulnerability had gone undetected, the class generally said no. Codebases of that age and scale contain enormous amounts of untested legacy code, and this one had been exploitable for 27 years without anyone catching it.

The economics of the discovery also came up. While the total compute cost was reported at around $20,000, Prof. Evans noted that this number does not account for the human effort behind the testing harness. The specific run that found the bug actually cost less than fifty dollars, which the class agreed was not a representative picture of what the project actually required. The harness itself matters at least as much as the model, and cheaper models were also capable of finding the same error.

The class then discussed whether AI tools like this benefit attackers or defenders more. There was skepticism that guardrails on public models would be effective, since many people searching for security vulnerabilities are doing so for legitimate reasons. For large organizations like Google, the resources exist to deploy these tools defensively at scale. For older, unmaintained codebases, though, the advantage tilts toward attackers. All an attacker needs is one vulnerable entry point across billions of lines of code. AI also enhances the human side of attacks, assisting with social engineering and deception in ways that go beyond exploiting code. The class noted that defenders need to become just as technically sophisticated as attackers, though large companies do hold more resources overall. 

Prof. Evans closed on an optimistic note, reflecting Anthropic’s stated long-term view on the trajectory of these tools. He also showed the class a photo of a real glasswing butterfly, noting that the name is intended to represent transparency. The class found this somewhat ironic, since the butterfly’s transparent wings actually make it nearly invisible in its natural environment, giving the impression that Anthropic could be hiding things rather than revealing them.


---

## Lead Topic: Detecting AI Generated Content

**Presented by Team 12**  
[Slides](https://docs.google.com/presentation/d/1A_QQLj_ZGDUJVOwENPCR1o0dzG9XHxq03DiJ5y9bJSQ/edit?slide=id.p#slide=id.p)

**Reading:**

- Hanlin Zhang, Benjamin L. Edelman, Danilo Francati, Daniele Venturi, Giuseppe Ateniese, Boaz Barak. Watermarks in the Sand: Impossibility of Strong Watermarking for Generative Models. ICML 2024. [PDF]

- Labs, P. (2025). How Pangram detects AI-generated content. Pangram Labs. https://www.pangram.com/research/how-it-works 

**Tools**

- [Panagram AI Detector](https://www.pangram.com/)
- [GPTZero](https://gptzero.me/)

## Overview

<center><img src="/images/watermarkex.png" width=50% alt=""></img><br>

*Figure: example of watermarked image vs regular image [(source)](https://electronics.howstuffworks.com/cameras-photography/tips/how-to-place-watermarks-on-pictures.htm)*
</center>

Team 12 opened with a poll: should AI-generated content carry a watermark? 

The team walked through three reasons:

- The first was training data integrity. There is growing concern about model collapse, the phenomenon where AI systems trained on AI-generated content begin to degrade over time. AI-authored conference papers are up 370% since 2023, which makes this more than a theoretical risk. 

- The second reason was deception. Deepfakes and synthetic media erode public trust, and a voice deepfake has already been used to scam a CEO out of $243,000. 

- The third was honesty in academic and professional contexts, where the question of who actually wrote something carries real consequences.

Team 12 then explained the technical landscape of detection. Two main approaches exist. Fine-tuned encoder classifiers like BERT perform well but operate as black boxes and require labeled training data. Hybrid methods like XGBoost combined with writing style features are more interpretable but need carefully crafted features and tend to generalize poorly. Detection technology is improving, with Pangram claiming 99.85% overall accuracy on the models it was trained on and EditLens achieving 94% accuracy in distinguishing human from AI text more broadly. That said, these numbers come with the caveat that accuracy on training-distribution data may not hold as models continue to change.

Team 12 also explained how watermarks work. The model is induced to embed a detectable signal in its output, making later identification easier. The vulnerability, though, is simple… just keep generating. Each successive iteration dilutes the watermark signal until it disappears when outputs are merged or reformatted into a single image or document.

## Activity

<center><img src="/images/AIwatermark.png" width=50% alt=""></img><br>

*Figure: example of watermarked AI-generated image vs regular image [(source)](https://www.pcmag.com/news/google-creates-imperceptible-watermark-for-ai-generated-images) *
</center>

The class participated in a hands-on exercise. Given AI-generated examples, including a poem, a short essay, and a piece written in the style of a fifth-grader, students had five to seven minutes to modify the text until an AI detector classified it as human. The findings were interesting. Simply adding modifiers to make the writing less concise kept the AI score at 100%. One student managed to bring a piece to 0% by strategically changing key words. Changing analogies and punctuation proved particularly effective.

Prof. Evans offered a pointed observation in response to the results. If a piece gets to 0% through human effort alone, it may not be a false negative. If AI tools were used to get it there, then it is.

## Discussion

The class addressed two broader questions. The first was whether policies should require AI companies to build watermarks into their model outputs, or whether it should be left to individual companies. The class was skeptical of mandates, given how easily watermarks can be removed. A distinction emerged between media types. For images and videos, watermarks seem more valuable because misinformation spreads faster than the public’s ability to question it. For text, the case is weaker. One question that stuck with the class was whether a watermark even matters if no one is in a position to care whether something is fake.

The second question was whether the increased use of AI-generated content is detrimental to academia. A related concern came up during that conversation. If AI defaults to a particular vocabulary and writing style, human writers may gradually absorb those same patterns. The em dash was raised as a now-common AI tell. At some point, the line between AI and human writing may blur not because detectors improve, but because human writing starts to look more like AI.

---

## Additional References

Additional Sources

- Katherine Thai, Bradley Emi, Elyas Masrour, Mohit Iyyer. EditLens: Quantifying the Extent of AI Editing in Text. ICLR 2026. [PDF]

- Bradley Emi. AI Conference Papers are Increasingly Being Written by AI: up 370% since 2023. 30 September 2024.

- Bradley Emi. Pangram Predicts 21% of ICLR Reviews are AI-Generated. 18 November 2025.