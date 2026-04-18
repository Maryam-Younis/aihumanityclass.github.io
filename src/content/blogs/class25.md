+++
date = "16 Apr 2026"
draft = false
title = "Class 25: Ask Anything"
author = "Team 6"
+++

**Blogging Team [6]**: Zach Bernas, Clare O’Dwyer, Michelle Hu, Suhanee Singh, Mina Tunley

---

## 📢 **Announcement: Teams should sign up for a final presentation time [at this link](https://docs.google.com/spreadsheets/d/1HSYpXlVMYVt5mhAu4o34xSm-6jVyj4FaF_uvWGoYU1k/edit?usp=drivesdk)!**

---

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

## **Pitfalls in Data Display: A Review of Anthropic's Figures**

**Article:** [Labor market impacts of AI](https://www.anthropic.com/research/labor-market-impacts)

### **Figure 1**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure1.png" width="60%" alt="Anthropic Figure 1">
</center>

Problems:

- Graphs should get across a lot of information quickly— the user has to put in a lot of effort to only learn 3 numbers
- Horizontal and vertical axes aren not explained or obvious
- Presents uncertain data as definitive
- Too much text in the caption
- The text is too small

### **Figure 2**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure2.png" width="60%" alt="Anthropic Figure 2">
</center>

Problems:

- Wrong choice of plot (radio plots are for comparing multiple related categories)
- Requires decoding with a key
- Title and caption duplicate
- No thought put into the colors
- Categories are not ordered meaningfully

### **Figure 3**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure3.png" width="60%" alt="Anthropic Figure 3">
</center>

Problems:

- Ugly and boring
- Too much text
- The text is too small and difficult to read
- Title and caption duplicate
- Tables should not have lines separating columns

### **Figure 4**

<center style="margin: 30px">
<img src="/images/class_25_blog/figure4.png" width="60%" alt="Anthropic Figure 4">
</center>

Positives:

- Scatterplots convey a lot of information quickly
- Labels are in the graph

Problems:

- Text is too small
- 0 on the y-axis represents the threshold of positive and negative change, but it is not emphasized
- The labels are clunky and labeled points having a different shape is confusing
- Color is not used to distinguish points
- If slope is important, label it

### **AI and Data Visualization**

AI can be a useful tool for data visualization, but do not plug your data into AI blindly because it will probably not create an accurate representation of the data. You should use AI for reformatting data or getting code to create graphs. [UVA StatLab](https://library.virginia.edu/data/statlab), which provides free statistics consulting to students, also has the service of auditing and verifying AI output.

### **Final Exhortations on Data Presentation**

- Do not use Excel or Google Sheets
- Do not use default colors
- Do not make your audience put in more effort understanding your graphic than you put into making it

### **Why Does Anthropic Have Bad Graphics?**

One student suggested a cynical take that Anthropic purposely uses unclear graphics to misrepresent data, prevent viewers from understanding their data, and encourage support of their narrative. Prof. Evans believes that this take gives Anthropic more credit than they are actually due, and that these bad graphics are a result of specialized people no longer being hired and rsearchers assuming that they can make good graphics themselves, probably with AI.

---

## **Prof. Evans' Ask Me Anything**

This class is aiming for something in between Donald Knuth's [“All Questions Answered” event](https://youtu.be/CDokMxVtB3k?si=JeSFiSNZ0fyGIo9O&t=2043) at Stanford and Reddit AMAs (most popular one of all time is [the owner of a McDonald’s burger from 1995](https://www.reddit.com/r/AMA/comments/1m9uhhe/my_mate_and_i_have_been_keeping_the_same/)).

### **"What’s your p(doom)? (probability that AI will end humanity)"**

Sam Altman’s p(doom) is 0.5. Prof. Evans’ is essentially 0. If doom means the end of humanity and good, this probability is negligible and distracts from investing effort in solving problems.

### **"Do you think AI has had more positive or negative influence on CS majors? Do you think people are learning more or less?"**

Prof. Evans thinks we are the last generation at an advantage over others because we were exposed to AI later than others; the next generation will have a harder time to learn what we learned. This is similar to the difference between us and those who grew up learning assembly and compilers, but not as significant as us and the next generation. AI is the not the primary reason for the tough job market for entry CS roles.

He hopes that we still have fun doing things manually or learning low level skills as a hobby, althought there probably will not be a lot of jobs for those anymore. Things that were really painful or tedious are easier now. Learning is easier and more fun because of AI tools, and people who take advantage of that will learn a lot.

### **"How did you get involved in AI court cases?"**

A former student who set up an ISP to sue spammers asked Prof. Evans to testify in a case against a spammer to prove that the packet headers were forged. U.S. and Plaintiff States v. Google LLC (2020) was Prof. Evan’s second court case. A PhD student did research on Google’s management of 3rd party cookies and data privacy with advertisers. Prof. Evans wrote a blog post on Google’s privacy decisions, which may have been how he got involved. He was involved in the remedy phase of the anti-trust case, which sought to require Google to share data on user search behaviors. Google argued they couldn’t do this without compromising privacy. He is currently on a LLM privacy case and only takes cases that are fun and that he supports.

Further Reading:

- [More details on U.S. v. Google](https://www.purduegloballawschool.edu/blog/news/google-landmark-case)
- [Prof. Evans' Remedies Hearing Exhibit (2025) for U.S. v. Google](https://www.justice.gov/atr/media/1397911/dl?inline)

### **"What AI-related prediction from >5 years ago are you most/ least proud of?"**

Five years ago, Prof. Evans gave a talk on jobs for humans in the future at a fundraising event about AI affecting jobs. He was very optimistic about no one losing jobs and everyone having jobs that take advantage of their humanity, and he thinks this is still true.

> “I never make predictions and I never will” - Paul Gascoigne

### **"Are you satisfied with how the class has gone?"**

Yes, and Prof. Evans is looking forward to project presentations. This is different from most CS classes. This class is dependent on student contributions, and most students have prepared interesting things/facilitated interesting discussion. Attendance and coming on time has been tough. Prof. Evans believes we are capable of deciding whether something is worth our time.

### **"What is an ethical dilemma or hardest choice you’ve faced during your career?"**

Prof. Evans has not necessarily had any ethical dilemmas in research. Sometimes the research of students is not worth publishing, leading to competing interests between professor and students. Most difficulty comes from figuring out how to help individual students succeed.

### **"Would you decorate your home/office with AI generated art?"**

Prof. Evan’s current office has art painted on the wall by his daughter. He currently has no AI-generated art on display, but has no prohibition on it. Most art he likes has personal meaning attached to it.

### **"What do you think is the biggest problem with CS students currently? Any advice to be a better student and scientist?"**

Students know their own problems better than he does. However, CS recently became the default major for many people given its popularity. When Prof. Evans started teaching, CS was less popular and the few students were very passionate. With growth, more students are in the major for job opportunities. The trend is shifting again and more students are likely to be truly interested in CS.

### **"What is your favorite use of AI?"**

Writing code using languages and APIs he personally does not understand, which removes some of the tedious work.

### **"What is the most awesome AI-generated video you have seen?"**

_πHard_ (2026), "starring" Neil deGrasse Tyson, Elon Musk, Stephen Hawking, Mr. Beast, Bill Gates, and more.

<center style="margin: 30px">
<a href="http://www.youtube.com/watch?feature=player_embedded&v=CNbmoVdirxw" target="_blank">
 <img src="http://img.youtube.com/vi/CNbmoVdirxw/mqdefault.jpg" alt="PI HARD | Official Trailer 2026 | AI OR DIE Productions" width="400" border="10" />
</a>
</center>

### **"What is the most offensive AI-generated video you have seen?"**

AI Actress Tilly Norwood's music video _Take The Lead_ (2026).

<center style="margin: 30px">
<a href="http://www.youtube.com/watch?feature=player_embedded&v=G7V2Biy3omw" target="_blank">
 <img src="http://img.youtube.com/vi/G7V2Biy3omw/mqdefault.jpg" alt="Tilly Norwood | Take The Lead (Official Music Video)" width="400" border="10" />
</a>
</center>
