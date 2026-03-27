+++
date = "2026-03-19"
title = "Class 17: Universal Basic Income"
author = "Kate McCray, Lara Mahajan, Shreeja Tangutur, Mandy Le, Lily Egenrieder"
+++

**Blogging Team [3]**: Kate McCray, Lara Mahajan, Shreeja Tangutur, Mandy Le, Lily Egenrieder

## News: 2025 Turing Award & Quantum Cryptography 
[Slides](https://www.dropbox.com/scl/fi/widoyn6lalsj8wq0r17pv/cs4501ha-s26-class17.pdf?rlkey=vkzen2akyuka09meizenkrq9h&e=2&dl=0)

**Presented by:** Professor David Evans  

### Articles
1. Wiesner, S. (1983). *Conjugate Coding*. ACM SIGACT News, 15(1).  
   [PDF](https://aihumanityclass.github.io/docs/quantum1983.pdf)

2. Metz, C. (2026, March 18). *Turing Award Goes to Inventors of Quantum Cryptography*.  
   The New York Times.  
   https://www.nytimes.com/2026/03/18/technology/turing-award-winners-quantum-cryptography.html

3. Brubaker, B. (2026, March 18). *Quantum Cryptography Pioneers Win Turing Award*.  
   Quanta Magazine.  
   https://www.quantamagazine.org/quantum-cryptography-pioneers-win-turing-award-20260318/

4. Levy, S. (2026, March 18). *A Quantum Leap for the Turing Award*.  
   Wired.  
   https://www.wired.com/story/a-quantum-leap-for-the-turing-award/

5. Srividya, B. V., & Sasi, S. (2021). *Polarization of photons* [Figure 2]. In An emphasis on quantum cryptography and quantum key distribution. IntechOpen.    https://www.researchgate.net/figure/Polarization-of-photons_fig2_349445239


---

### Understanding Quantum Cryptography

Quantum cryptography is often described as the future of secure communication, but in practice it sits somewhere between a brilliant idea and an impractical dream. At its core are strange properties of quantum physics: light behaves as both a wave and a particle, and exists in multiple states at once (superposition) until observed. When measured, it collapses into a single, random state based on a probability distribution. This unpredictability is reinforced by the quantum uncertainty principle, which states that the more precisely you know one property of a particle (like position), the less you can know about another (like momentum). As a result, quantum information cannot be perfectly copied (known as the “no-cloning” principle) unlike classical bits, which can be duplicated exactly. Photons also have polarization (often described as “spin”), and by passing them through vertical, horizontal, or angled filters, we can encode information. 


<center>
<img src="/images/photons.png" width=60% alt=""></img><br>
Source: Bharadwaja, S. (2021). An Emphasis on Quantum Cryptography and Quantum Key Distribution
</center>

---

For example, a vertically polarized photon will always pass through a vertical filter but never through a horizontal one, while a 45° filter only lets it pass about 50% of the time. If you send a stream of photons, about half will pass through mismatched filters, and the ones that pass will adopt the filter’s polarization. This ability to control and test photon polarization is what makes quantum encoding possible.

These ideas led to the concept of quantum money, banknotes encoded with a secret sequence of photon polarizations known only to the bank. To authenticate a note, the bank uses matching filters (vertical, horizontal, or angled). Correctly aligned photons pass with near 100% accuracy, while diagonal ones pass about 50%, creating a recognizable pattern. However, the key challenge is that you cannot measure the sequence without disturbing it, any attempt to copy or learn it destroys the information. Even if a photon passes through a filter, you cannot tell whether it was correctly aligned or just passed by chance. This makes quantum money theoretically unforgeable but impractical, since authentication destroys the note and the quantum states are difficult to store. A more practical application is Quantum Key Distribution (QKD), where two parties share a secret sequence of polarization filters to securely communicate. Any eavesdropping introduces detectable errors because measurement alters the photons. Still, QKD requires expensive, specialized infrastructure, is sensitive to noise and distance, and competes with strong classical encryption. As a result, despite heavy investment, quantum cryptography remains powerful in theory but limited in practice.

---

## Lead Team Presentation: AI, Automation, and Universal Basic Income 
[Slides](https://docs.google.com/presentation/d/1IHQ2mNCiK1Zhkc0y5FjKCvQ_xsgEhsYlxHavihtIvzU/edit?slide=id.p#slide=id.p)

**Presented by:** Group 7  

### Articles
1. Heller, N. (2018). *Who Really Stands to Win from Universal Basic Income?*  
   The New Yorker.  
   https://www.newyorker.com/magazine/2018/07/09/who-really-stands-to-win-from-universal-basic-income

2. Rodriguez, M. (2026). *Universal Basic Income Is Already Here*.  
   LinkedIn.  
   https://www.linkedin.com/pulse/universal-basic-income-already-here-miguel-rodriguez-pmvve/

3. Cheng, D. (2024). *What You Really Mean When You Claim to Support UBI for Job Automation*.  
   LessWrong.  
   https://www.lesswrong.com/posts/8CY9TCK2oaGPrDheY/what-you-really-mean-when-you-claim-to-support-ubi-for-job

---

### What Is Universal Basic Income?

“Robots, we are told, will drive us from our jobs.” This concern, highlighted by Nathan Heller in The New Yorker, reflects a growing reality: as artificial intelligence and automation advance, they may significantly reduce the demand for human labor. Tasks that once required human effort, from data processing to customer service and even creative work, are increasingly being handled by machines. While technological progress has always reshaped the workforce, AI raises the stakes by potentially replacing not just manual labor, but also high-skill, white-collar jobs. This shift creates an urgent question: if fewer people are needed to work, how will people earn a living? The team discussed Universal Basic Income (UBI) as a proposed solution which is defined as a fixed payment given to every adult regardless of income or employment status with no work requirement. The idea is simple: provide a financial safety net that ensures everyone can meet basic needs in an economy where stable jobs may no longer be guaranteed.

An argument in support that was discussed is that it could fundamentally improve how people live and make decisions. Chris Hughes notes, “The further you get from subsistence, the easier it is to ask fundamental questions like: what do I want, and how do I get it?” When people are not constantly worried about survival, they gain the freedom to pursue education, care for family, start businesses, or explore meaningful work beyond just earning money. Contrary to common fears, real-world UBI pilot programs show that people do not waste unconditional cash; instead, they tend to invest in their futures, support their families, and make more stable long-term plans. This challenges the traditional assumption that guaranteed income reduces motivation. Additionally, as AI generates enormous wealth, often concentrated among those who build and own these technologies, UBI offers a way to redistribute some of that value more broadly across society. Related ideas like Universal Basic Capital (UBC) go even further, suggesting that people should not only receive income but also share ownership in the assets that generate wealth. As automation continues to expand, the urgency of these discussions grows: UBI is no longer just a theoretical concept, but a potential response to a rapidly changing economic reality.

The presentation next pivoted to discussing the criticisms of Universal Basic Income. One major argument comes from Nicolas Berggruen and Nathan Gardels, who state that “UBI… does not alter the dynamic of inequality.” The idea is that simply redistributing income equally doesn’t change the deeper structures that create inequality in the first place.

Another common criticism is more emotional: “Junkies, alcoholics, scam artists — do we really want to hand these people monthly checks?” This reflects a broader fear that guaranteed income could reduce the incentive to work. If people can survive on UBI alone, some argue they may choose not to work at all. On the employer side, businesses may feel less pressure to raise wages if workers already have a financial cushion.


<center>
<img src="/images/income.png" width=60% alt=""></img><br>
Rodríguez, M. (2023). Universal Basic Income: Is It Already Here? LinkedIn. Figure retrieved from: 

(Source: [Linkedin](https://www.linkedin.com/pulse/universal-basic-income-already-here-miguel-rodriguez-pmvve/))
</center>

---

Funding UBI is another major challenge. One estimate from The New Yorker suggests that giving every American $1,000 a month would cost $3.9 trillion, roughly equal to the entire federal budget. That level of spending raises huge questions about sustainability and long‑term economic impact.

---

### Discussion Question: How Do We Solve These Problems?

The class discussed several possible solutions and alternatives. One issue is corporate offshoring, where companies move overseas to avoid higher taxes or regulations, which would make funding UBI even harder.

Another idea was shifting the focus from UBI to universal healthcare, which most developed countries already have. Universal healthcare benefits everyone equally, whereas UBI gives proportionally more help to lower‑income individuals. Some students argued that healthcare might be a more equitable starting point.

UBI might only become politically viable after a major crisis. For example, mass unemployment caused by automation. Without such a shock, the political will might not be there.

Another alternative raised was negative income tax, where only people below a certain income threshold receive money from the government. This avoids giving money to people who don’t need it and shifts more of the tax burden to high earners (e.g., those making over ~$500,000).

The team then presented several real‑world UBI pilot programs:
- Stockton, CA: $500/month to low‑income residents → recipients were more likely to find full‑time jobs.
- Finland: payments to unemployed individuals → little change in unemployment.
- India & Uganda: village‑level cash transfers → increased entrepreneurship and earnings.
- Kenya: large‑scale UBI → major improvements in stability and well‑being.


<center>
<img src="/images/tax.png" width=60% alt=""></img><br>
LessWrong Community. (n.d.). What You Really Mean When You Claim to Support UBI for Job Loss. LessWrong. Figure retrieved from: 

(Source: [Lesswrong](https://www.lesswrong.com/posts/8CY9TCK2oaGPrDheY/what-you-really-mean-when-you-claim-to-support-ubi-for-job))
</center>

---
Across all programs, the most consistent benefits were lower stress and financial anxiety, higher life satisfaction, better ability to plan for the future, improved health and education outcomes (especially in developing regions). This demonstrated how UBI could help maintain a baseline quality of life.

To explore these results further, the lead team conducted a Menti Poll asking the following questions: 

- If AI and automation eliminate a large number of jobs, should the government provide UBI?
    - Yes: 19 students
    - No: 8 students
        - Students who were unsure raised thoughtful concerns about uncertainty about large‑scale implementation, fear that UBI might preserve a flawed economic system instead of encouraging a better one, hope for alternatives like Universal Basic Capital (UBC), where people build wealth through shared investment funds, belief that regulation could prevent job loss in the first place
        - The “no” group had two main arguments: Why should middle‑ and upper‑class people get UBI if they don’t need it? People shouldn’t get money if they don’t contribute to society.
        - Additional points of pushback included questions such as 
            - If robots eventually do most blue‑collar jobs, what happens when there are no traditional ways to “contribute”?
            - Just because we can automate everything doesn’t mean we should
            - If there are no productive jobs left, how do we rethink incentives, purpose, and meaning?
- The class then discussed lobbying and how difficult it would be to pass UBI if large firms oppose it. One student raised a deeper question: What is the purpose of life: to produce, or to live? COVID shifted many people’s values toward recreation, family, and well‑being rather than constant productivity
---

<center>
<img src="/images/class_shot.png" width=60% alt=""></img><br>
Source: Menti Poll from Discussion 
</center>

- Finally, when asked how long it would take to see a significant reduction in jobs due to AI, answers varied. One person said 30 years, but others pointed out that even a 1% job loss is 70,000 jobs. Cultural shifts can change everything in just a few years.
