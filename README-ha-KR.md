# 소프트웨어 엔지니어를 위한 머신러닝 공부법: 하나 하나 차근차근 배워나가는 기계학습

<p align="center">
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers">
    <img alt="Top-down learning path: Machine Learning for Software Engineers" src="https://img.shields.io/badge/Machine%20Learning-Software%20Engineers-blue.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/stargazers">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
  <a href="https://github.com/ZuzooVn/machine-learning-for-software-engineers/network">
    <img alt="GitHub forks" src="https://img.shields.io/github/forks/ZuzooVn/machine-learning-for-software-engineers.svg">
  </a>
</p>

본 문서는 [Google Interview University](https://github.com/jwasham/google-interview-university)에서 영감을 받아 작성되었습니다.

## 본 문서에 대하여

이 문서는 모바일 앱 개발자였던 제가 머신러닝(기계학습) 엔지니어로 직종변경을 하는 과정에서 개안해낸 학습방안입니다.

접근성을 제일 중점에 두고 이 가이드라인을 작성하였는데, 초보자들도 큰 수학적 배경지식 없이 쉽게 따라할 수 있을 것입니다.
소프트웨어 엔지니어가 만든 소프트웨어 엔지니어들을 위한 머신러닝 학습법이기에 매우 실용적이며, 결과중심적인 과정이 될 것입니다.

개선방안이나 문제점을 발견하시면 언제든지 알려주시기 바랍니다.

>본 문서에서 링크되어 있는 자료들의 대부분은 영어로 되어있으며, 한글 번역본 혹은 자막이 제공되어있지 않을 수 있습니다.
---

## 목차

- [본 문서에 대하여](#본-문서에-대하여)
- [이 학습방안은 뭐가 다른거죠?](#이-학습방안은-뭐가-다른거죠?)
- [사용방안](#사용방안)
- [작자에 대하여](#작자에-대하여)
- [머신러닝을 배우고 응용는데엔 박사학위가 필요없다구요](#머신러닝을-배우고-응용는데엔-박사학위가-필요없다구요)
- [링크되어 있는 비디오 자료에 대하여](#링크되어-있는-비디오-자료에-대하여)
- [필수 선행지식에 대하여](#필수-선행지식에-대하여)
- [The Daily Plan](#the-daily-plan)
- [동기부여가 필요할 것 같습니다](#동기부여가-필요할-것-같습니다)
- [머신러닝에 대한 기초지식](#머신러닝에-대한-기초지식)
- [Machine learning mastery](#machine-learning-mastery)
- [쉽고 재미있는 머신러닝](#쉽고-재미있는-머신러닝)
- [Inky Machine Learning](#inky-machine-learning)
- [Machine learning: an in-depth, non-technical guide](#machine-learning-an-in-depth-non-technical-guide)
- [Stories and experiences](#stories-and-experiences)
- [머신러닝 알고리즘들에 대하여](#머신러닝-알고리즘들에-대하여)
- [초보자를 위한 서적](#초보자를-위한-서적)
- [실용적이 전문서적](#실용적인-전문서적)
- [캐글 해결과제들](#캐글-해결과제들)
- [Video Series](#video-series)
- [MOOC 온라인 공개수업](#MOOC-온라인-공개수업)
- [기타 자료들](#기타-자료들)
- [오픈소스 참여자가 되는 방법](#becoming-an-open-source-contributor)
- [머신러닝 괸련 게임](#머신러닝-괸련-게임)
- [머신러닝 관련 팟캐스트](#머신러닝-괸련-팟캐스트)
- [머신러닝 관련 커뮤니티](#머신러닝-괸련-팟캐스트)
- [머신러닝 관련 학회](#머신러닝-괸련-학회)
- [머신러닝 면접 질문들](#머신러닝-면접-질문들)
- [My admired companies](#my-admired-companies)

---

## 이 학습방안은 뭐가 다른거죠?

I'm following this plan to prepare for my near-future job: Machine learning engineer. I've been building native mobile applications (Android/iOS/Blackberry) since 2011. I have a Software Engineering degree, not a Computer Science degree. I have an itty-bitty amount of basic knowledge about: Calculus, Linear Algebra, Discrete Mathematics, Probability & Statistics from university.
Think about my interest in machine learning:
- [Can I learn and get a job in Machine Learning without studying CS Master and PhD?](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD)
    - *"You can, but it is far more difficult than when I got into the field."* [Drac Smith](https://www.quora.com/Can-I-learn-and-get-a-job-in-Machine-Learning-without-studying-CS-Master-and-PhD/answer/Drac-Smith?srid=oT0p)
- [How do I get a job in Machine Learning as a software programmer who self-studies Machine Learning, but  never has a chance to use it at work?](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work)
    - *"I'm hiring machine learning experts for my team and your MOOC will not get you the job (there is better news below). In fact, many people with a master's in machine learning will not get the job because they (and most who have taken MOOCs) do not have a deep understanding that will help me solve my problems."* [Ross C. Taylor](https://www.quora.com/How-do-I-get-a-job-in-Machine-Learning-as-a-software-programmer-who-self-studies-Machine-Learning-but-never-has-a-chance-to-use-it-at-work/answer/Ross-C-Taylor?srid=oT0p)
- [What skills are needed for machine learning jobs?](http://programmers.stackexchange.com/questions/79476/what-skills-are-needed-for-machine-learning-jobs)
    - *"First, you need to have a decent CS/Math background. ML is an advanced topic so most textbooks assume that you have that background. Second, machine learning is a very general topic with many sub-specialties requiring unique skills. You may want to browse the curriculum of an MS program in Machine Learning to see the course, curriculum and textbook."* [Uri](http://softwareengineering.stackexchange.com/a/79717)
    - *"Probability, distributed computing, and Statistics."* [Hydrangea](http://softwareengineering.stackexchange.com/a/79575)

I find myself in times of trouble.

AFAIK, [There are two sides to machine learning](http://machinelearningmastery.com/programmers-can-get-into-machine-learning/):
- Practical Machine Learning: This is about querying databases, cleaning data, writing scripts to transform data and gluing algorithm and libraries together and writing custom code to squeeze reliable answers from data to satisfy difficult and ill-defined questions. It’s the mess of reality.
- Theoretical Machine Learning: This is about math and abstraction and idealized scenarios and limits and beauty and informing what is possible. It is a whole lot neater and cleaner and removed from the mess of reality.

I think the best way for practice-focused methodology is something like ['practice — learning — practice'](http://machinelearningmastery.com/machine-learning-for-programmers/#comment-358985), that means where students first come with some existing projects with problems and solutions (practice) to get familiar with traditional methods in the area and perhaps also with their methodology. After practicing with some elementary experiences, they can go into the books and study the underlying theory, which serves to guide their future advanced practice and will enhance their toolbox of solving practical problems. Studying theory also further improves their understanding on the elementary experiences, and will help them acquire advanced experiences more quickly.

 It's a long plan. It's going to take me years. If you are familiar with a lot of this already it will take you a lot less time.

## 사용방안
아래 제가 제시하는 학습플랜은 목차대로 처음부터 끝까지 차근차근 배워나가는 것을 추천합니다.

이 문서는 GitHub(깃허브) 취향의 마크다운을 기반으로 작성되었으며, 본 가이드를 이용하여 머신러닝을 공부하는 유저들이 체크오프 할 수 있는 할일목록(TODO List)들 역시 마크다운으로 작성되어 있습니다.

- [x] 새로운 브랜치를 만들어, 완료한 목록들을 이런 방식으로 괄호안에 x를 기입하여 성과를 트래킹해보세요.

[깃허브 취향 마크다운에 대하여](https://guides.github.com/features/mastering-markdown/#GitHub-flavored-markdown)

## 작자에 대하여 
I'm a Vietnamese Software Engineer who is really passionate and wants to work in the USA.

How much did I work during this plan? Roughly 4 hours/night after a long, hard day at work.

I'm on the journey.

- Twitter: [@Nam Vu](https://twitter.com/zuzoovn)

| ![Nam Vu - Top-down learning path: machine learning for software engineers](http://sv1.upsieutoc.com/2016/10/08/331f241c8da44d0c43e9324d55440db6.md.jpg)|
|:---:|
| USA as heck |

## 머신러닝을 배우고 응용는데엔 박사학위가 필요없다구요

머신러닝 관한 전문서적을 펼쳐보면 선행대수학, 벡터미적분학, 혹은 추상통계학을 베이스로 한 문단들이 매우 빈번하여 도대체 어디서 부터 학습을 시작하여야 하며, 무엇을 배워야 이런 전문서적들을 좀 더 쉽게 소화할 수 있는지 가늠하기 힘든경우가 많습니다. 아래 링크들을 참고해보세요.

- [수학을 잘 못해도 머신러닝을 배울 수 있을까요?](http://machinelearningmastery.com/what-if-im-not-good-at-mathematics/)
- [머신러닝 알고리즘들을 수학적 배경없이 이해할 수 있는 5가지 방법들](http://machinelearningmastery.com/techniques-to-understand-machine-learning-algorithms-without-the-background-in-mathematics/)
- [머신러닝은 어떻게 배워야 하나요?](https://www.quora.com/Machine-Learning/How-do-I-learn-machine-learning-1)

## 링크되어 있는 비디오 자료에 대하여

링크된 비디오 자료들 중 상당수는 코세라(Coursera) 수업 혹은 매사츄세츠 공대 EdX 강의에서 사용되는 자료들입니다. 이 수업들에 수강신청을 하는 건 비용이 들지 않습니다만, 강의 시기에 따라 제공이 되지 않는 케이스가 있을 수도 있습니다. 이런 경우엔 몇 주에서 길게는 몇 달을 기다려야 이 강의들이 다시 제공이 되는데, 이러한 이유 때문에 차차 이 수업에서 발췌된 링크들을 1년 내내 공개해주는 유튜브 같은 플랫폼에 올라와있는 링크들로 바꾸어 가려 합니다. 물론 대학교 수업 녹화본과 같은 신용성이 있는 비디오들을 링크하겠습니다.

## 필수 선행지식에 대하여

This short section were prerequisites/interesting info I wanted to learn before getting started on the daily plan.

- [ ] [What is the difference between Data Analytics, Data Analysis, Data Mining, Data Science, Machine Learning, and Big Data?](https://www.quora.com/What-is-the-difference-between-Data-Analytics-Data-Analysis-Data-Mining-Data-Science-Machine-Learning-and-Big-Data-1)
- [ ] [Learning How to Learn](https://www.coursera.org/learn/learning-how-to-learn)
- [ ] [Don’t Break The Chain](http://lifehacker.com/281626/jerry-seinfelds-productivity-secret)
- [ ] [How to learn on your own](https://metacademy.org/roadmaps/rgrosse/learn_on_your_own)

## The Daily Plan

Each subject does not require a whole day to be able to understand it fully, and you can do multiple of these in a day.

Each day I take one subject from the list below, read it cover to cover, take notes, do the exercises and write an implementation in Python or R.

# 동기부여가 필요할 것 같습니다
- [ ] [몽상가가 되어봅시다](https://www.youtube.com/watch?v=g-jwWYX7Jlo)

## 머신러닝에 대한 기초지식
- [ ] [A Visual Introduction to Machine Learning](http://www.r2d3.us/visual-intro-to-machine-learning-part-1/)
- [ ] [A Gentle Guide to Machine Learning](https://blog.monkeylearn.com/a-gentle-guide-to-machine-learning/)
- [ ] [Introduction to Machine Learning for Developers](http://blog.algorithmia.com/introduction-machine-learning-developers/)
- [ ] [Machine Learning basics for a newbie](https://www.analyticsvidhya.com/blog/2015/06/machine-learning-basics/)
- [ ] [How do you explain Machine Learning and Data Mining to non Computer Science people?](https://www.quora.com/How-do-you-explain-Machine-Learning-and-Data-Mining-to-non-Computer-Science-people)
- [ ] [Machine Learning: Under the hood. Blog post explains the principles of machine learning in layman terms. Simple and clear](https://georgemdallas.wordpress.com/2013/06/11/big-data-data-mining-and-machine-learning-under-the-hood/)
- [ ] [What is machine learning, and how does it work?](https://www.youtube.com/watch?v=elojMnjn4kk&list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A&index=1)
- [ ] [Deep Learning - A Non-Technical Introduction](http://www.slideshare.net/AlfredPong1/deep-learning-a-nontechnical-introduction-69385936)

## Machine learning mastery
- [ ] [The Machine Learning Mastery Method](http://machinelearningmastery.com/machine-learning-mastery-method/)
- [ ] [Machine Learning for Programmers](http://machinelearningmastery.com/machine-learning-for-programmers/)
- [ ] [Applied Machine Learning with Machine Learning Mastery](http://machinelearningmastery.com/start-here/)
- [ ] [Python Machine Learning Mini-Course](http://machinelearningmastery.com/python-machine-learning-mini-course/)
- [ ] [Machine Learning Algorithms Mini-Course](http://machinelearningmastery.com/machine-learning-algorithms-mini-course/)

## 쉽고 재미있는 머신러닝
- [ ] [Machine Learning is Fun!](https://medium.com/@ageitgey/machine-learning-is-fun-80ea3ec3c471#.37ue6caww)
- [ ] [Part 2: Using Machine Learning to generate Super Mario Maker levels](https://medium.com/@ageitgey/machine-learning-is-fun-part-2-a26a10b68df3#.kh7qgvp1b)
- [ ] [Part 3: Deep Learning and Convolutional Neural Networks](https://medium.com/@ageitgey/machine-learning-is-fun-part-3-deep-learning-and-convolutional-neural-networks-f40359318721#.44rhxy637)
- [ ] [Part 4: Modern Face Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-4-modern-face-recognition-with-deep-learning-c3cffc121d78#.3rwmq0ddc)
- [ ] [Part 5: Language Translation with Deep Learning and the Magic of Sequences](https://medium.com/@ageitgey/machine-learning-is-fun-part-5-language-translation-with-deep-learning-and-the-magic-of-sequences-2ace0acca0aa#.wyfthap4c)
- [ ] [Part 6: How to do Speech Recognition with Deep Learning](https://medium.com/@ageitgey/machine-learning-is-fun-part-6-how-to-do-speech-recognition-with-deep-learning-28293c162f7a#.lhr1nnpcy)

## [Inky Machine Learning](https://triskell.github.io/2016/11/15/Inky-Machine-Learning.html)
- [ ] [Part 1: What is Machine Learning ?](https://triskell.github.io/2016/10/23/What-is-Machine-Learning.html)
- [ ] [Part 2: Supervised Learning and Unsupervised Learning](https://triskell.github.io/2016/11/13/Supervised-Learning-and-Unsupervised-Learning.html)

## Machine learning: an in-depth, non-technical guide
- [ ] [Overview, goals, learning types, and algorithms](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide/)
- [ ] [Data selection, preparation, and modeling](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-2/)
- [ ] [Model evaluation, validation, complexity, and improvement](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-3/)
- [ ] [Model performance and error analysis](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-4/)
- [ ] [Unsupervised learning, related fields, and machine learning in practice](http://www.innoarchitech.com/machine-learning-an-in-depth-non-technical-guide-part-5/)

## Stories and experiences
- [ ] [Machine Learning in a Week](https://medium.com/learning-new-stuff/machine-learning-in-a-week-a0da25d59850#.tk6ft2kcg)
- [ ] [Machine Learning in a Year](https://medium.com/learning-new-stuff/machine-learning-in-a-year-cdb0b0ebd29c#.hhcb9fxk1)
- [ ] [How I wrote my first Machine Learning program in 3 days](http://blog.adnansiddiqi.me/how-i-wrote-my-first-machine-learning-program-in-3-days/)
- [ ] [Learning Path : Your mentor to become a machine learning expert](https://www.analyticsvidhya.com/learning-path-learn-machine-learning/)
- [ ] [You Too Can Become a Machine Learning Rock Star! No PhD](https://backchannel.com/you-too-can-become-a-machine-learning-rock-star-no-phd-necessary-107a1624d96b#.g9p16ldp7)
- [ ] How to become a Data Scientist in 6 months: A hacker’s approach to career planning
    - [Video](https://www.youtube.com/watch?v=rIofV14c0tc)
    - [Slide](http://www.slideshare.net/TetianaIvanova2/how-to-become-a-data-scientist-in-6-months)
- [ ] [5 Skills You Need to Become a Machine Learning Engineer](http://blog.udacity.com/2016/04/5-skills-you-need-to-become-a-machine-learning-engineer.html)
- [ ] [Are you a self-taught machine learning engineer? If yes, how did you do it & how long did it take you?](https://www.quora.com/Are-you-a-self-taught-machine-learning-engineer-If-yes-how-did-you-do-it-how-long-did-it-take-you)
- [ ] [How can one become a good machine learning engineer?](https://www.quora.com/How-can-one-become-a-good-machine-learning-engineer)
- [ ] [A Learning Sabbatical focused on Machine Learning](http://karlrosaen.com/ml/)

## 머신러닝 알고리즘들에 대하여
- [ ] [10 Machine Learning Algorithms Explained to an ‘Army Soldier’](https://www.analyticsvidhya.com/blog/2015/12/10-machine-learning-algorithms-explained-army-soldier/)
- [ ] [Top 10 data mining algorithms in plain English](https://rayli.net/blog/data/top-10-data-mining-algorithms-in-plain-english/)
- [ ] [10 Machine Learning Terms Explained in Simple English](http://blog.aylien.com/10-machine-learning-terms-explained-in-simple/)
- [ ] [A Tour of Machine Learning Algorithms](http://machinelearningmastery.com/a-tour-of-machine-learning-algorithms/)
- [ ] [The 10 Algorithms Machine Learning Engineers Need to Know](https://gab41.lab41.org/the-10-algorithms-machine-learning-engineers-need-to-know-f4bb63f5b2fa#.ofc7t2965)
- [ ] [Comparing supervised learning algorithms](http://www.dataschool.io/comparing-supervised-learning-algorithms/)
- [ ] [Machine Learning Algorithms: A collection of minimal and clean implementations of machine learning algorithms](https://github.com/rushter/MLAlgorithms)

## 초보자를 위한 서적
- [ ] [Data Smart: Using Data Science to Transform Information into Insight 1st Edition](https://www.amazon.com/Data-Smart-Science-Transform-Information/dp/111866146X)
- [ ] [Data Science for Business: What you need to know about data mining and data­ analytic-thinking](https://www.amazon.com/Data-Science-Business-Data-Analytic-Thinking/dp/1449361323/)
- [ ] [Predictive Analytics: The Power to Predict Who Will Click, Buy, Lie, or Die](https://www.amazon.com/Predictive-Analytics-Power-Predict-Click/dp/1118356853)

## 실용적인 전문서적
- [ ] [Machine Learning for Hackers](https://www.amazon.com/Machine-Learning-Hackers-Drew-Conway/dp/1449303714)
    - [GitHub repository(R)](https://github.com/johnmyleswhite/ML_for_Hackers)
    - [GitHub repository(Python)](https://github.com/carljv/Will_it_Python)
- [ ] [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka-ebook/dp/B00YSILNL0)
    - [GitHub repository](https://github.com/rasbt/python-machine-learning-book)
- [ ] [Programming Collective Intelligence: Building Smart Web 2.0 Applications](https://www.amazon.com/Programming-Collective-Intelligence-Building-Applications-ebook/dp/B00F8QDZWG)
- [ ] [Machine Learning: An Algorithmic Perspective, Second Edition](https://www.amazon.com/Machine-Learning-Algorithmic-Perspective-Recognition/dp/1466583282)
    - [GitHub repository](https://github.com/alexsosn/MarslandMLAlgo)
    - [Resource repository](http://seat.massey.ac.nz/personal/s.r.marsland/MLbook.html)
- [ ] [Introduction to Machine Learning with Python: A Guide for Data Scientists](http://shop.oreilly.com/product/0636920030515.do)
    - [GitHub repository](https://github.com/amueller/introduction_to_ml_with_python)
- [ ] [Data Mining: Practical Machine Learning Tools and Techniques, Third Edition](https://www.amazon.com/Data-Mining-Practical-Techniques-Management/dp/0123748569)
    - Teaching material
        - [Slides for Chapters 1-5 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch1-5.zip)
        - [Slides for Chapters 6-8 (zip)](http://www.cs.waikato.ac.nz/ml/weka/Slides3rdEd_Ch6-8.zip)
- [ ] [Machine Learning in Action](https://www.amazon.com/Machine-Learning-Action-Peter-Harrington/dp/1617290181/)
    - [GitHub repository](https://github.com/pbharrin/machinelearninginaction)
- [ ] [Reactive Machine Learning Systems(MEAP)](https://www.manning.com/books/reactive-machine-learning-systems)
    - [GitHub repository](https://github.com/jeffreyksmithjr/reactive-machine-learning-systems)
- [ ] [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/)
    - [GitHub repository(R)](http://www-bcf.usc.edu/~gareth/ISL/code.html)
    - [GitHub repository(Python)](https://github.com/JWarmenhoven/ISLR-python)
    - [Videos](http://www.dataschool.io/15-hours-of-expert-machine-learning-videos/)
- [ ] [Building Machine Learning Systems with Python](https://www.packtpub.com/big-data-and-business-intelligence/building-machine-learning-systems-python)
    - [GitHub repository](https://github.com/luispedro/BuildingMachineLearningSystemsWithPython)
- [ ] [Learning scikit-learn: Machine Learning in Python](https://www.packtpub.com/big-data-and-business-intelligence/learning-scikit-learn-machine-learning-python)
    - [GitHub repository](https://github.com/gmonce/scikit-learn-book)
- [ ] [Probabilistic Programming & Bayesian Methods for Hackers](https://camdavidsonpilon.github.io/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers/)
- [ ] [Probabilistic Graphical Models: Principles and Techniques](https://www.amazon.com/Probabilistic-Graphical-Models-Principles-Computation/dp/0262013193)
- [ ] [Machine Learning: Hands-On for Developers and Technical Professionals](https://www.amazon.com/Machine-Learning-Hands-Developers-Professionals/dp/1118889061)
    - [Machine Learning Hands-On for Developers and Technical Professionals review](https://blogs.msdn.microsoft.com/querysimon/2015/01/01/book-review-machine-learning-hands-on-for-developers-and-technical-professionals/)
    - [GitHub repository](https://github.com/jasebell/mlbook)
- [ ] [Learning from Data](https://www.amazon.com/Learning-Data-Yaser-S-Abu-Mostafa/dp/1600490069)
    - [Online tutorials](https://work.caltech.edu/telecourse.html)
- [ ] [Reinforcement Learning: An Introduction (2nd Edition)](https://webdocs.cs.ualberta.ca/~sutton/book/the-book-2nd.html)
    - [GitHub repository](https://github.com/ShangtongZhang/reinforcement-learning-an-introduction)
- [ ] [Machine Learning with TensorFlow(MEAP)](https://www.manning.com/books/machine-learning-with-tensorflow)
    - [GitHub repository](https://github.com/BinRoot/TensorFlow-Book)

## 캐글(Kaggle) 해결과제들 
- [ ] [Kaggle Competitions: How and where to begin?](https://www.analyticsvidhya.com/blog/2015/06/start-journey-kaggle/)
- [ ] [How a Beginner Used Small Projects To Get Started in Machine Learning and Compete on Kaggle](http://machinelearningmastery.com/how-a-beginner-used-small-projects-to-get-started-in-machine-learning-and-compete-on-kaggle)
- [ ] [Master Kaggle By Competing Consistently](http://machinelearningmastery.com/master-kaggle-by-competing-consistently/)

## Video Series
- [ ] [Machine Learning for Hackers](https://www.youtube.com/playlist?list=PL2-dafEMk2A4ut2pyv0fSIXqOzXtBGkLj)
- [ ] [Fresh Machine Learning](https://www.youtube.com/playlist?list=PL2-dafEMk2A6Kc7pV6gHH-apBFxwFjKeY)
- [ ] [Machine Learning Recipes with Josh Gordon](https://www.youtube.com/playlist?list=PLOU2XLYxmsIIuiBfYad6rFYQU_jL2ryal)
- [ ] [Everything You Need to know about Machine Learning in 30 Minutes or Less](https://vimeo.com/43547079)
- [ ] [A Friendly Introduction to Machine Learning](https://www.youtube.com/watch?v=IpGxLWOIZy4)
- [ ] [Nuts and Bolts of Applying Deep Learning - Andrew Ng](https://www.youtube.com/watch?v=F1ka6a13S9I)
- [ ] BigML Webinar
    - [Video](https://www.youtube.com/watch?list=PL1bKyu9GtNYHcjGa6ulrvRVcm1lAB8he3&v=W62ehrnOVqo)
    - [Resources](https://bigml.com/releases)
- [ ] [mathematicalmonk's Machine Learning tutorials](https://www.youtube.com/playlist?list=PLD0F06AA0D2E8FFBA)
- [ ] [Machine learning in Python with scikit-learn](https://www.youtube.com/playlist?list=PL5-da3qGB5ICeMbQuqbbCOQWcS6OYBr5A)
    - [GitHub repository](https://github.com/justmarkham/scikit-learn-videos)
    - [Blog](http://blog.kaggle.com/author/kevin-markham/)
- [ ] [My playlist – Top YouTube Videos on Machine Learning, Neural Network & Deep Learning](https://www.analyticsvidhya.com/blog/2015/07/top-youtube-videos-machine-learning-neural-network-deep-learning/)
- [ ] [16 New Must Watch Tutorials, Courses on Machine Learning](https://www.analyticsvidhya.com/blog/2016/10/16-new-must-watch-tutorials-courses-on-machine-learning/)
- [ ] [DeepLearning.TV](https://www.youtube.com/channel/UC9OeZkIwhzfv-_Cb7fCikLQ)
- [ ] [Learning To See](https://www.youtube.com/playlist?list=PLiaHhY2iBX9ihLasvE8BKnS2Xg8AhY6iV)
- [ ] [Neural networks class - Université de Sherbrooke](https://www.youtube.com/playlist?list=PL6Xpj9I5qXYEcOhn7TqghAJ6NAPrNmUBH)
- [ ] [21 Deep Learning Videos, Tutorials & Courses on Youtube from 2016](https://www.analyticsvidhya.com/blog/2016/12/21-deep-learning-videos-tutorials-courses-on-youtube-from-2016/)
- [ ] [30 Top Videos, Tutorials & Courses on Machine Learning & Artificial Intelligence from 2016](https://www.analyticsvidhya.com/blog/2016/12/30-top-videos-tutorials-courses-on-machine-learning-artificial-intelligence-from-2016/)
- [ ] [Practical Deep Learning For Coders](http://course.fast.ai/index.html)

## MOOC 온라인 공개수업
- [ ] [Udacity’s Intro to Machine Learning](https://www.udacity.com/course/intro-to-machine-learning--ud120)
    - [Udacity Intro to Machine Learning Review](http://hamelg.blogspot.com/2014/12/udacity-intro-to-machine-learning-review.html)
- [ ] [Udacity’s Supervised, Unsupervised & Reinforcement](https://www.udacity.com/course/machine-learning--ud262)
- [ ] [Machine Learning Foundations: A Case Study Approach](https://www.coursera.org/learn/ml-foundations)
- [ ] [Coursera’s Machine Learning](https://www.coursera.org/learn/machine-learning)
    - [Video only](https://www.youtube.com/playlist?list=PLZ9qNFMHZ-A4rycgrgOYma6zxF4BZGGPW)
    - [Coursera Machine Learning review](https://rayli.net/blog/data/coursera-machine-learning-review/)
    - [Coursera: Machine Learning Roadmap](https://metacademy.org/roadmaps/cjrd/coursera_ml_supplement)
- [ ] [Machine Learning Distilled](https://code.tutsplus.com/courses/machine-learning-distilled)
- [ ] [BigML training](https://bigml.com/training)
- [ ] [Coursera’s Neural Networks for Machine Learning](https://www.coursera.org/learn/neural-networks)
    - Taught by Geoffrey Hinton, a pioneer in the field of neural networks
- [ ] [Machine Learning - CS - Oxford University](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
- [ ] [Creative Applications of Deep Learning with TensorFlow](https://www.kadenze.com/courses/creative-applications-of-deep-learning-with-tensorflow/info)
- [ ] [Intro to Descriptive Statistics](https://www.udacity.com/course/intro-to-descriptive-statistics--ud827)
- [ ] [Intro to Inferential Statistics](https://www.udacity.com/course/intro-to-inferential-statistics--ud201)
- [ ] [6.S094: Deep Learning for Self-Driving Cars](http://selfdrivingcars.mit.edu/)
- [ ] [6.S191: Introduction to Deep Learning](http://introtodeeplearning.com/index.html)

## 기타 자료들
- [ ] [Learn Machine Learning in a Single Month](https://elitedatascience.com/machine-learning-masterclass)
- [ ] [The Non-Technical Guide to Machine Learning & Artificial Intelligence](https://medium.com/@samdebrule/a-humans-guide-to-machine-learning-e179f43b67a0#.cpzf3a5c0)
- [ ] [Best practices rule book for Machine Learning engineering from Google](http://martin.zinkevich.org/rules_of_ml/rules_of_ml.pdf)
- [ ] [Machine Learning for Software Engineers on Hacker News](https://news.ycombinator.com/item?id=12898718)
- [ ] [Machine Learning for Developers](https://xyclade.github.io/MachineLearning/)
- [ ] [Machine Learning Advice for Developers](https://dev.to/thealexlavin/machine-learning-advice-for-developers)
- [ ] [Machine Learning For Complete Beginners](http://pythonforengineers.com/machine-learning-for-complete-beginners/)
- [ ] [Getting Started with Machine Learning: For absolute beginners and fifth graders](https://medium.com/@suffiyanz/getting-started-with-machine-learning-f15df1c283ea#.yjtiy7ei9)
- [ ] [How to Learn Machine Learning: The Self-Starter Way](https://elitedatascience.com/learn-machine-learning)
- [ ] [Machine Learning Self-study Resources](https://ragle.sanukcode.net/articles/machine-learning-self-study-resources/)
- [ ] [Level-Up Your Machine Learning](https://metacademy.org/roadmaps/cjrd/level-up-your-ml)
- [ ] [An Honest Guide to Machine Learning](https://medium.com/axiomzenteam/an-honest-guide-to-machine-learning-2f6d7a6df60e#.ib12a1yw5)
- [ ] Enough Machine Learning to Make Hacker News Readable Again
    - [Video](https://www.youtube.com/watch?v=O7IezJT9uSI)
    - [Slide](https://speakerdeck.com/pycon2014/enough-machine-learning-to-make-hacker-news-readable-again-by-ned-jackson-lovely)
- [ ] [Dive into Machine Learning](https://github.com/hangtwenty/dive-into-machine-learning)
- [ ] [{Machine, Deep} Learning for software engineers](https://speakerdeck.com/pmigdal/machine-deep-learning-for-software-engineers)
- [ ] [Deep Learning For Beginners](https://deeplearning4j.org/deeplearningforbeginners.html)
- Machine Learning courses in Universities
    - [ ] [Stanford](http://ai.stanford.edu/courses/)
    - [ ] [Machine Learning Summer Schools](http://mlss.cc/)
    - [ ] [Oxford](https://www.cs.ox.ac.uk/people/nando.defreitas/machinelearning/)
    - [ ] [Cambridge](http://mlg.eng.cam.ac.uk/)
- Flipboard Topics
    - [Machine learning](https://flipboard.com/topic/machinelearning)
    - [Deep learning](https://flipboard.com/topic/deeplearning)
    - [Artificial Intelligence](https://flipboard.com/topic/artificialintelligence)
- Medium Topics
    - [Machine learning](https://medium.com/tag/machine-learning/latest)
    - [Deep learning](https://medium.com/tag/deep-learning)
    - [Artificial Intelligence](https://medium.com/tag/artificial-intelligence)
- Monthly top 10 articles
    - Machine Learning
        - [July 2016](https://medium.mybridge.co/top-ten-machine-learning-articles-for-the-past-month-9c1202351144#.lyycen64y)
        - [August 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-2f3cb815ffed#.i9ee7qkjz)
        - [September 2016](https://medium.mybridge.co/machine-learning-top-10-in-september-6838169e9ee7#.4jbjcibft)
        - [October 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-35c37825a943#.td5im1p5z)
        - [November 2016](https://medium.mybridge.co/machine-learning-top-10-articles-for-the-past-month-b499e4213a34#.7k39i08tv)
        - [Year 2016](https://medium.mybridge.co/machine-learning-top-10-of-the-year-v-2017-7552599935c0#.wtx2mchqn)
    - Algorithms
        - [September 2016](https://medium.mybridge.co/algorithm-top-10-articles-in-september-8a0e6afb0807#.hgjzuyxdb)
        - [October-November 2016](https://medium.mybridge.co/algorithm-top-10-articles-v-november-e73cba2fa87e#.kothimkhb)
- [Comprehensive list of data science resources](http://www.datasciencecentral.com/group/resources/forum/topics/comprehensive-list-of-data-science-resources)
- [DigitalMind's Artificial Intelligence resources](http://blog.digitalmind.io/post/artificial-intelligence-resources)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [CreativeAi's Machine Learning](http://www.creativeai.net/?cat%5B0%5D=machine-learning)

## 머신러닝 괸련 게임
- [Halite: A.I. Coding Game](https://halite.io/)
- [Vindinium: A.I. Programming Challenge](http://vindinium.org/)
- [General Video Game AI Competition](http://www.gvgai.net/)
- [Angry Birds AI Competition](https://aibirds.org/)
- [The AI Games](http://theaigames.com/)
- [Fighting Game AI Competition](http://www.ice.ci.ritsumei.ac.jp/~ftgaic/)
- [CodeCup](http://www.codecup.nl/intro.php)
- [Student StarCraft AI Tournament](http://sscaitournament.com/)
- [AIIDE StarCraft AI Competition](http://www.cs.mun.ca/~dchurchill/starcraftaicomp/)
- [CIG StarCraft AI Competition](https://sites.google.com/site/starcraftaic/)
- [CodinGame - AI Bot Games](https://www.codingame.com/training/machine-learning)

## Becoming an Open Source Contributor
- [ ] [tensorflow/magenta: Magenta: Music and Art Generation with Machine Intelligence](https://github.com/tensorflow/magenta)
- [ ] [tensorflow/tensorflow: Computation using data flow graphs for scalable machine learning](https://github.com/tensorflow/tensorflow)
- [ ] [cmusatyalab/openface: Face recognition with deep neural networks.](https://github.com/cmusatyalab/openface)
- [ ] [tensorflow/models/syntaxnet: Neural Models of Syntax.](https://github.com/tensorflow/models/tree/master/syntaxnet)

## 머신러닝 괸련 팟캐스트
- ### Podcasts for Beginners:
    - [Talking Machines](http://www.thetalkingmachines.com/)
    - [Linear Digressions](http://lineardigressions.com/)
    - [Data Skeptic](http://dataskeptic.com/)
    - [This Week in Machine Learning & AI](https://twimlai.com/)

- ### "More" advanced podcasts
    - [Partially Derivative](http://partiallyderivative.com/)
    - [O’Reilly Data Show](http://radar.oreilly.com/tag/oreilly-data-show-podcast)
    - [Not So Standard Deviation](https://soundcloud.com/nssd-podcast)

- ### Podcasts to think outside the box:
    - [Data Stories](http://datastori.es/)

## 머신러닝 괸련 커뮤니티
- Quora
    - [Machine Learning](https://www.quora.com/topic/Machine-Learning)
    - [Statistics](https://www.quora.com/topic/Statistics-academic-discipline)
    - [Data Mining](https://www.quora.com/topic/Data-Mining)

- Reddit
    - [Machine Learning](https://www.reddit.com/r/machinelearning)
    - [Computer Vision](https://www.reddit.com/r/computervision)
    - [Natural Language](https://www.reddit.com/r/languagetechnology)
    - [Data Science](https://www.reddit.com/r/datascience)
    - [Big Data](https://www.reddit.com/r/bigdata)
    - [Statistics](https://www.reddit.com/r/statistics)

- [Data Tau](http://www.datatau.com/)

- [Deep Learning News](http://news.startup.ml/)

- [KDnuggets](http://www.kdnuggets.com/)

## 머신러닝 괸련 학회
- Neural Information Processing Systems ([NIPS](https://nips.cc/))
- International Conference on Learning Representations ([ICLR](http://www.iclr.cc/doku.php?id=ICLR2017:main&redirect=1))
- Association for the Advancement of Artificial Intelligence ([AAAI](http://www.aaai.org/Conferences/AAAI/aaai17.php))
- IEEE Conference on Computational Intelligence and Games ([CIG](http://www.ieee-cig.org/))
- IEEE International Conference on Machine Learning and Applications ([ICMLA](http://www.icmla-conference.org/))
- International Conference on Machine Learning ([ICML](https://2017.icml.cc/))

## 머신러닝 면접 질문들
- [ ] [How To Prepare For A Machine Learning Interview](http://blog.udacity.com/2016/05/prepare-machine-learning-interview.html)
- [ ] [40 Interview Questions asked at Startups in Machine Learning / Data Science](https://www.analyticsvidhya.com/blog/2016/09/40-interview-questions-asked-at-startups-in-machine-learning-data-science)
- [ ] [21 Must-Know Data Science Interview Questions and Answers](http://www.kdnuggets.com/2016/02/21-data-science-interview-questions-answers.html)
- [ ] [Top 50 Machine learning Interview questions & Answers](http://career.guru99.com/top-50-interview-questions-on-machine-learning/)
- [ ] [Machine Learning Engineer interview questions](https://resources.workable.com/machine-learning-engineer-interview-questions)
- [ ] [Popular Machine Learning Interview Questions](http://www.learn4master.com/machine-learning/popular-machine-learning-interview-questions)
- [ ] [What are some common Machine Learning interview questions?](https://www.quora.com/What-are-some-common-Machine-Learning-interview-questions)
- [ ] [What are the best interview questions to evaluate a machine learning researcher?](https://www.quora.com/What-are-the-best-interview-questions-to-evaluate-a-machine-learning-researcher)
- [ ] [Collection of Machine Learning Interview Questions](http://analyticscosm.com/machine-learning-interview-questions-for-data-scientist-interview/)
- [ ] [121 Essential Machine Learning Questions & Answers](https://learn.elitedatascience.com/mlqa-welcome)


## My admired companies
- [ ] [ELSA - Your virtual pronunciation coach](https://www.elsanow.io/home)