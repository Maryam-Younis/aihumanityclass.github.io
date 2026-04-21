+++
date = "16 Apr 2026"
draft = false
title = "Class 25: Ask Anything"
author = "Team 6"
+++

**Blogging Team 6**: Zach Bernas, Clare O’Dwyer, Michelle Hu, Suhanee Singh, Mina Tunley

---

## 📢 **Announcement: Teams should sign up for a final presentation time [at this link](https://docs.google.com/spreadsheets/d/1HSYpXlVMYVt5mhAu4o34xSm-6jVyj4FaF_uvWGoYU1k/edit?usp=drivesdk)!**

---

**Slides:** [[PDF](https://www.dropbox.com/scl/fi/vir817kheay3crd0rn558/cs4501ha-s26-class24.pdf?rlkey=dzi7v0re0xowi1gizf1n36jlt&dl=0)]

## **Advice for Presentations**

Don't:

- Have too many bullet lists or text
- Read from a script
- Have generic slide titles like "Background" or "Introduction"
- Display unclear data or pictures

Do:

- Have meaningful titles or no titles if not needed
- Choose to display data and graphs that make sense for the medium (presentation)
- Ask your team's amicrit/navamigo for feedback

---

## **Pitfalls in Data Display**

**A Review of Anthropic's Figures in [_Labor market impacts of AI_](https://www.anthropic.com/research/labor-market-impacts)**

### **Figure 1**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure1.png" width="60%" alt="Anthropic Figure 1">
</center>

Problems:

- Graphs should get across a lot of information quickly— the user has to put in a lot of effort to only learn 3 numbers
- Horizontal and vertical axes are not explained or obvious
- Presents uncertain data in an overly precise way, without any explanation of what is actually plotted
- Too much text in the caption
- The text is too small

### **Figure 2**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure2.png" width="60%" alt="Anthropic Figure 2">
</center>

Problems:

- Wrong choice of plot (radar plots are useful when the goal is to quickly compare many plots)
- Requires decoding with a key
- Title and caption duplicate
- No thought put into the colors
- Categories are not ordered meaningfully

(See the [slides for suggested improvements](https://www.dropbox.com/scl/fi/vir817kheay3crd0rn558/cs4501ha-s26-class24.pdf?rlkey=dzi7v0re0xowi1gizf1n36jlt&dl=0)].)


### **Figure 3**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure3.png" width="60%" alt="Anthropic Figure 3">
</center>

Problems:

- Ugly and boring
- Too much text
- The text is too small and difficult to read
- Title and caption duplicate
- Tables should not have lines separating columns or rows as their most visible feature
- Its called a "Figure" but is really a "Table"

(See the [slides for a slight improvement](https://www.dropbox.com/scl/fi/vir817kheay3crd0rn558/cs4501ha-s26-class24.pdf?rlkey=dzi7v0re0xowi1gizf1n36jlt&dl=0)].)

### **Figure 4**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure4.png" width="60%" alt="Anthropic Figure 4">
</center>

Positives:

- Scatterplots convey a lot of information quickly
- Interesting points are labeled directly in the graph

Problems:

- Text is too small
- 0 on the y-axis represents the threshold of positive and negative change, but it is not emphasized
- The labels are clunky and labeled points having a different shape is confusing
- Color is not used to distinguish points
- If slope is important, label it. Trendline itself is questionable, and heavily influenced by a few datapoints

### **AI and Data Visualization**

AI can be a useful tool for data visualization, but do not plug your data into AI blindly because it will probably not create an accurate representation of the data. You should use AI for reformatting data or getting code to create graphs. [UVA StatLab](https://library.virginia.edu/data/statlab), which provides free statistics consulting to students, also has the service of auditing and verifying AI output.

### **Final Exhortations on Data Presentation**

1. No self-respecting computer scientist uses Excel (or something even worse like Google Sheets) to generate a data visualization.
2. No one who cares about presenting data uses the default colors.
3. Don’t make your audience put more effort into understanding your graphic you put into making it. 


### **Why Does Anthropic Have Bad Graphics?**

One student suggested a cynical take that Anthropic purposely uses unclear graphics to misrepresent data, prevent viewers from understanding their data, and encourage support of their narrative. Prof. Evans believes that this take gives Anthropic more credit than they are actually due, and that these bad graphics are a result of specialized people no longer being hired and rsearchers assuming that they can make good graphics themselves, probably with AI.

[Note: On April 17 (the day after this class), Anthropic announced [**Claude Design**](https://www.anthropic.com/news/claude-design-anthropic-labs). Presumably Anthropic does have some competent graphic designers who worked on this, although the examples in the demo video are not great in my (Dave) opinion.]

---

## **Prof. Evans' Ask Me Anything**

This class is aiming for something in between Donald Knuth's [“All Questions Answered” event](https://youtu.be/CDokMxVtB3k?si=JeSFiSNZ0fyGIo9O&t=2043) at Stanford and Reddit AMAs (most popular one of all time is [the owner of a McDonald’s burger from 1995](https://www.reddit.com/r/AMA/comments/1m9uhhe/my_mate_and_i_have_been_keeping_the_same/)).

### _"What’s your p(doom)? (probability that AI will end humanity)"_

Sam Altman’s p(doom) is 0.5. Prof. Evans’ is essentially 0. If doom means the end of humanity and good, this probability is negligible and distracts from investing effort in solving problems.

### _"Do you think AI has had more positive or negative influence on CS majors? Do you think people are learning more or less?"_

Prof. Evans thinks we are the last generation at an advantage over others because we were exposed to AI later than others so had an opportunity to develop lots of skills and understanding with direct motivation that won't be available to next generation, who will have a harder time to learn what we learned. This is similar to the difference between us and those who grew up learning assembly and compilers, but not as significant as us and the next generation. AI is the not the primary reason for the tough job market for entry CS roles.

He hopes that we still have fun doing things manually or learning low level skills as a hobby, althought there probably will not be a lot of jobs for those anymore. Things that were really painful or tedious are easier now. Learning is easier and more fun because of AI tools, and people who take advantage of that will learn a lot.

### _"How did you get involved in AI court cases?"_

A former student who set up an ISP to sue spammers asked Prof. Evans to testify in a case against a spammer to prove that the packet headers were forged. U.S. and Plaintiff States v. Google LLC (2020) was Prof. Evan’s second court case. A PhD student did research on Google’s management of 3rd party cookies and data privacy with advertisers. Prof. Evans wrote a blog post on Google’s privacy decisions, which may have been how he got involved. He was involved in the remedy phase of the anti-trust case, which sought to require Google to share data on user search behaviors. Google argued they couldn’t do this without compromising privacy. He is currently on a LLM privacy case and only takes cases that are fun and that he supports.

Further Reading:

- Serge Egelman, [_Suing Spammers for
Fun and Profit_](https://www.usenix.org/system/files/login/articles/1737-Egelman.pdf). USENIX login;, April 2004.
- [More details on U.S. v. Google](https://www.purduegloballawschool.edu/blog/news/google-landmark-case)
- [Prof. Evans' Remedies Hearing Exhibit (2025) for U.S. v. Google](https://www.justice.gov/atr/media/1397911/dl?inline)

### _"What AI-related prediction from >5 years ago are you most/ least proud of?"_

Five years ago, Prof. Evans gave a talk on jobs for humans in the future at a fundraising event about AI affecting jobs. He was very optimistic about no one losing jobs and everyone having jobs that take advantage of their humanity, and he thinks this is still true.

> “I never make predictions and I never will” - Paul Gascoigne

**Dave's note:** I don't think I answered this question well at the time, so will add some more now. The most concrete recorded set of predictions I've made is [from this cs4414: Operating Systems class](https://rust-class.org/class-23-invent-the-future.html) (making predictions in 2014 for what will be in 2029). I'm a bit embarrassed about my "end to world poverty" implied prediction, and the timing on Prediction #4 may be off by a few years (although that remains to be seen). For some more narrow predictions (focused on multi-party computation), the predictions I made in [this 2014 talk](https://www.cs.virginia.edu/~evans/talks/ampc2014/) I think have turned out to look quite good.

From a financial standpoint, the worst predictions I've made have been telling people not to buy bitcoin since about 2009. Someone who ignored my advice and invested $1000 in bicoin back then would have around a billion dollars today (on the other hand, they probably would have lost their private key, and then it would be worth $0). I was still discouraging students in my [Cryptocurrency Classes](https://bitcoin-class.org/0/) (2015) from buying bitcoin, and if they had ignored me and invested $1000 then it would only be worth about half a million dollars today. Fortunately, I also tell students not to take financial advice from CS professors, so don't feel too bad about anyone who actually is not rich now because they didn't follow my advice.

I guess the biggest implied AI-related predictions I made were deciding AI (and robotics in particular) was less interesting to work on than programming languages and then security back when I was an undergraduate student, around 1991. And then, being convinced that security issues related to AI was a good area to start working in around 2015. I didn't think of these as "predictions", just following curiosity and opportunity to work on the things that seemed most interesting, but at some level, every decision we make about what to spend our time on is a prediction about the short-term and long-term future. 

 
### _"Are you satisfied with how the class has gone?"_

Yes, and Prof. Evans is looking forward to project presentations. This is different from most CS classes. This class is dependent on student contributions, and most students have prepared interesting things/facilitated interesting discussion. Attendance and coming on time has been tough. Prof. Evans believes we are capable of deciding whether something is worth our time.

### _"What is an ethical dilemma or hardest choice you’ve faced during your career?"_

Prof. Evans has not necessarily had any ethical dilemmas in research. Sometimes the research of students is not worth publishing, leading to competing interests between professor and students. Most difficulty comes from figuring out how to help individual students succeed, which for PhD students sometimes means telling them they should be doing something else.

### _"Would you decorate your home/office with AI generated art?"_

Prof. Evan’s current office has art painted on the wall by his daughter. He currently has no AI-generated art on display, but has no prohibition on it. Most art he likes has personal meaning attached to it.

**Dave's note:** You should stop by to check out my daughter's wall painting!

### _"What do you think is the biggest problem with CS students currently? Any advice to be a better student and scientist?"_

Students know their own problems better than he does. However, CS recently became the default major for many people given its popularity. When Prof. Evans started teaching, CS was less popular and the few students were very passionate. With growth, more students started selecting CS as the "default major" and under external pressure to pick a major with good job opportunities. The trend is shifting again and more students are likely to be truly interested in CS.

### _"What is your favorite use of AI?"_

Writing code using languages and APIs he personally does not understand, which removes some of the tedious work.

### _"What is the most awesome AI-generated video you have seen?"_

_πHard_ (2026), "starring" Neil deGrasse Tyson, Elon Musk, Stephen Hawking, Mr. Beast, Bill Gates, and more.

<center style="margin: 30px">
<a href="http://www.youtube.com/watch?feature=player_embedded&v=CNbmoVdirxw" target="_blank">
 <img src="http://img.youtube.com/vi/CNbmoVdirxw/mqdefault.jpg" alt="PI HARD | Official Trailer 2026 | AI OR DIE Productions" width="400" border="10" />
</a>
</center>

### _"What is the most offensive AI-generated video you have seen?"_

AI Actress Tilly Norwood's music video _Take The Lead_ (2026).

<center style="margin: 30px">
<a href="http://www.youtube.com/watch?feature=player_embedded&v=G7V2Biy3omw" target="_blank">
 <img src="http://img.youtube.com/vi/G7V2Biy3omw/mqdefault.jpg" alt="Tilly Norwood | Take The Lead (Official Music Video)" width="400" border="10" />
</a>
</center>
