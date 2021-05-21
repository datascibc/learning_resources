# Learning Resources for Clinical Data Science
This is an overview for those from a clinical background to begin a career in statistics / data science / machine learning.
Re-training in this field requires that you unlearn most of what you have been taught about statistics. Forget tests of significance. Most importantly, it requires a significant comitment of time, energy and love. But it's extremely rewarding.

## Path to Data Science (Short Version)
Below is a comprehensive path to learning data science, focussed around the R statistical computer language. We choose R because its powerful, free and has a thriving online community. We've tried a lot of different things and have listed what we feel were of most use. Everyone is different, so if you found something particularly useful, let us know so we can add it to the list. Ultimately the langugage doesn't matter, and Python is equally a good choice. Our recommendation would be to pick one language and become very proficient in it.

**There is no shortcut to advancing in this field**. Find a project, something that you feel passionate about, and get stuck in; learn by doing. A fantastic reasource to start is the tidyverse and R for data science, availible for free online here: http://r4ds.had.co.nz

# Skill development (The Long Version)
Below is a list of some areas that are important to develop on your journey into clinical data science. These are aimed at someone who is interested and motivated, but from a clinical background, and so not formally trained in these methods. I have inlcuded links to amazon for books, but mostly just for reference. Ask for a link to a shared dropbox folder for electronic materials for the majority of them, plenty of others are published online for free. We also keep other copies in the lab which we are happy for you to borrow (please ask first).

## Maths
- The foundation of data science is rooted in probability and statistics. As clinicians this can be extremely limiting in the long run as we typically have at most an A-level in maths (often from a very long time ago). Key areas to focus on are:
  - Probability
  - Linear algebra
  - Statistical notation
- It isn't necessary to become completely independently proficient in these areas. Rather, the focus should be to gain an intution for what is going on. Ultimately you want to become an applied researcher, but some core theory is required.
- Once you have these basic tools, you will have the basic skills to understand the language of statistics and make the most out of your data (... and get away from hypothesis testing!). All that is needed here is a conceptual overview of how these things work.

The following resources are extremely useful:
- Harvard Stat 110 (https://www.youtube.com/watch?v=KbB0FjPg0mw&list=PL2SOU6wwxB0uwwH80KTQ6ht66KWxbzTIo)
  - The stategic practice is availible here (https://projects.iq.harvard.edu/stat110/home)
- Introduction to Probability (https://www.amazon.co.uk/Introduction-Probability-Chapman-Statistical-Science-ebook/dp/B00MMOJ19I/ref=sr_1_3?ie=UTF8&qid=1516904017&sr=8-3&keywords=introduction+to+probability) the companion text book to the above course
- Khan academy (www.khanacademy.com)
- 3Blue1Brown (https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw)

Other resources for statistics:
- Discovering statistics using R; Field. A good high level overview with practical applicatons in R.
- Statistical rethinking (https://www.amazon.co.uk/Statistical-Rethinking-Bayesian-Examples-Chapman/dp/1482253445/ref=sr_1_1?ie=UTF8&qid=1516907232&sr=8-1&keywords=statistical+rethinking). This book is a full course in bayesian statistics. It takes a narrative approach, and goes easy on the maths. You'll get a lot more out of it if you have covered the STAT110 course first.

### Online Courses
There has been an explosion in the availibility of online courses. They vary from free to expensive, and their quality is often not related to cost. Here we compile a list of the best:

|             Name            |           Subject           |                                   Website                                   | Cost | Rating      |
|:---------------------------:|:---------------------------:|:---------------------------------------------------------------------------:|:----:|-------------|
|   Essence of Linear Algebra |              Linear Algebra |          https://www.youtube.com/channel/UCYO_jab_esuFRV4b17AJtAw/playlists | Free | 5/5         |
| The World of Maths          | General Maths at all levels | www.khanacademy.com                                                         | Free | 5/5         |
| Machine Learning - Coursera | ML                          | https://www.coursera.org/learn/machine-learning                             | £58  | Recommended |
| Maths for Machine Learning  | Linear Algebra, Multivariate Calculus, PCA              | [Coursera](https://www.coursera.org/specializations/mathematics-machine-learning), [Youtube (FREE!)](https://www.youtube.com/watch?v=T73ldK46JqE&list=PLiiljHvN6z1_o1ztXTKWPrShrMrBLo5P3) | £48/Free  | 4/5         |


## R
- Datacamp.com is an excellent resource that uses gamification for learning the basics of R. Beyond learning how R works, it's use can be rather limited as it teaches a fairly shallow understanding of the topic. After you have got to grips with the basics, move away and start to get hands on with your own project
- Learn tidy data practices here https://www.tidyverse.org/
- R for data science http://r4ds.had.co.nz/
- Advanced R (https://www.amazon.co.uk/Advanced-Chapman-Hall-Hadley-Wickham/dp/1466586966/ref=sr_1_1?s=books&ie=UTF8&qid=1516907344&sr=1-1&keywords=advanced+R). Really excellent book by Hadley Wickham (a don in the R universe). Great to help push your programming to the next level. Also free online.
- Data Science for Doctors: This is a shameless plug for our own course that we run at the RCoA every few months. It provides a comprehensive introduction to R for the uninitiated.

## Python
- [CHME0031: Software Development with Python for Health Data Science](https://www.ucl.ac.uk/health-informatics/software-development-python-health-data-science) is an MSc module run by the IHI. UCL-registered students will be able to audit this course for free which will give you access to videos + Jupyter notebooks on moodle. Starts from scratch and includes examples relevant to healthcare.
- [Research Software Engineering](https://github.com/UCL/rsd-engineeringcourse) also offered through the Alan Turing Institute, but all content is freely available on github for self-directed learning. Detailed Jupyter notebooks covering all aspects of scientific software development with Python. This is definitely NOT a beginner course, you will need some decent experience with another language (suggested = reasonable experience in at least one compiled language, such as C++, C, or Fortran, and at least one dynamic language, such as Python, Ruby, Matlab or R). 

## UNIX
- vim adventures (www.vimadventures.com) is a brilliant way to learn your way around vim (a unix based text editor).
- William E. Shotts has written an ebook on unix which is open source and a great overview of how unix works http://linuxcommand.org/tlcl.php

## Databases
- [W3 schools SQL Tutorials](https://www.w3schools.com/sql/default.asp) basic examples of all SQL functions, a good place to start.
- [Apache Spark by Example](https://sparkbyexamples.com/) does what it says on the tin, a lot of examples transferable to/from SQL.

## Specific Statistical Topics
- Machine Learning - "An Introduction to Statistical Learning", James, Spriner. Solid basic introduction to the common methods used in machine learning. Accessible, written for R and lots of practice questions.
- - Machine Learning - "The Elements of Statistical Learning: Data Mining, Inference & Prediction", Hastie, Springer. As above, but not R focussed. [Freely available online](https://web.stanford.edu/~hastie/Papers/ESLII.pdf).
- Mixed Effects Models - "Mixed Effects Models and Extensions in Ecology with R" Zuur, Springer. Absolutely brilliant and accessible books to the topic of modelling correlated data. Be a little cautious of their model selection proceedures however, as they are questionable.

## Interesting Reads
- The Book of Why (causal inference)
- Observation and Experiment
- The Lady Tasting Tea, Salsburg (history of statistics)

## Lab Meetings
- We meet every Wednesday afternoon (14:00-15:30) to discuss ongoing projects. Everyone is welcome to attend and watch or present. No matter the size, scale or complexity, we would encourge you to present any work as a way to crowd source solutions to problems and figure out what the next step might be.
