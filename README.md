#구글 데이터 대학

> 아래의 내용은 나의 개인적인 공부 목표다.
> 그러다보니 부족한 부분도 상당할 것이지만 어느 정도 공부의 시작을 정해보고 싶어서 작성했다.
> 이후 영어 번역을 시도할 계획이다.


## 목차

- [전략적_취직준비기](#전략적_취직준비기)
- [소중한 리포들](#소중한-리포들)
- [공부스케줄](#공부스케줄)
- [데이터 과학](#데이터-과학)
    - [머신러닝](#머신러닝)
    - [딥러닝](#딥러닝)
    - [데이터 마이닝](#데이터-마이닝)
    - [통계모델링](#통계모델링)
    - [시각화](#시각화)
    - [분산컴퓨팅](#분산컴퓨팅)
    - [자연어 처리](#자연어-처리)
    - [소셜 네트워크](#소셜-네트워크)
    - [데이터과학논문](#데이터과학논문)
- [컴퓨터 과학](#컴퓨터-과학)
    - [서적](#서적)
    - [기초공부](#기초-공부)
    - [알고리즘](#알고리즘)
    - [자료구조](#자료구조)
    - [추가 지식](#추가-지식)
    - [Recrusion](#Recursion)
    - [동적프로그래밍](#동적프로그래밍)
    - [객체지향프로그래밍](#객체지향-프로그래밍)
    - [디자인 패턴](#디자인-패턴)
    - [Combinatorics](#Combinatorics-(n-choose-k)-&-Probability)
    - [NP](#NP)
    - [Cache](#Cache)
    - [Process and Thread](#Process-and-Thread)
    - [Testing](#Testing)
    - [논문](#논문)
- [기초 수학](#기초수학)
    - [선형대수](#선형대수)
    - [미적분](#미적분)
    - [통계](#통계)
    - [Convex Optimization](#Convex_Optimization)

## 전략적 취직 준비기

구글의 데이터 과학자로 취직 준비를 마음 먹은 이유는 구구절절하게 쓸 수 있다. 단적으로는 그 자체로 훌륭한 데이터 과학자로 철 발을 내딛는 공부가 되기 때문이다. 구글 취직 준비 자체를 한 명의 스승으로서 구글 취직 준비를 하려고 한다. 특히 8개월간 소프트웨어 엔지니어로 구글 취직 준비를 한 한 명의 깃헙 리포가 큰 자극이 되었다. 그는 자신이 구한 구글에서 필요로 하는 중요 지식의 토픽 노트를 기반으로 각 토픽 지식을 얻기 위해 필요한 자료를 정리해 올려 두었다.
그러나 데이터 과학은 유의미한 토픽 노트를 찾기도 어렵고, 형편없는 수준이다. 난이도가 이상하다기보다는 실제로 이 코스를 밟아서 공부한 사람이 있는지 의심스럽다. 유명한 Coursera의 데이터 과학 입문 코스에 프린스턴 통계 수업을 하나 추가해놓았다. 책은 데이터 과학 서적 중 Top5를 꼽아놓는 것이 전부다. 이런 자료들이 나의 공부 계획과 초기 공부에 도움이 되었던 것은 맞지만 누군가 자신의 커리어를 위해 온몸으로 견디어 낸 공부 과정을 찾기는 어렵다.
아래의 내용은 몇 가지 중요한 리포들을 참고해서 작성했다.
컴퓨터 과학은 8개월 구글 엔지니어 준비를 한 분의 토픽 리스트를 현실적으로 내가 남은 기간 할 수 있는 수준으로 줄였다. 데이터 과학은 범위나 종류가 다양하여 그 핵심 토픽을 꼽는 것이 어려웠다. 이를 크게 몇 가지 토픽으로 정리해 둔 깃헙 리포를 찾았다. 이 토픽을 전부 다루는 것은 사실 미친 짓에 가깝다. 공부 계획이 미친 수준이지만, 현실성이 필요해서 아래의 내용 중에는 머신러닝을 중점적으로 공부하고, 나머지는 최소한의 맛을 보는 정도로 한정했다. 수학은 최소한의 이해에 필요한 부분으로 공부를 한정했다. 이후 필요하면 늘릴 계획이다.

## 소중한 리포들

- [Coding-Inverview-University](https://github.com/jwasham/coding-interview-university)
  가장 중요한 시작이 되었던 것은 "내가 8개월간 풀타임으로 구글 인터뷰를 준비한 이유"의 저자가 작성한 CS 공부 리스트이다. 큰 동기 부여이기도 하고, 감을 잡을 수 있게 해주었다.

- [datasciencemasters](https://github.com/datasciencemasters/go)
  어떤 토픽들이 있는지, 무엇을 공부해야하는지 감을 잡게 되었다.

- [MIT Challenge](https://www.scotthyoung.com/blog/myprojects/mit-challenge-2/)
  데이터 과학과는 큰 상관이 없지만, 이 시기에 동기부여에 도움을 준 내용이다. 저자는 MIT의 4년 수업을 1년 안에 마무리하는 코스를 진행했다. 난 이렇게 공부하는 것이 도움이 되는지에 대해서 의심이 되지만, 시간이나 공부의 양과 방법을 자신이 정하고 몰아붙이는 모습을 보면서 아래의 공부계획을 짤 수 있었다.

## 공부 스케줄
8개월로 잡았다. 위의 8개월 공부한 케이스 때문은 아니고, 개인적인 사정 때문에 조금씩 길어졌기 때문이다.
첫 한 달과 마지막 한 달은 아래 서술할 공부 내용을 공부하지 않기로 했다.
첫 한 달간은 무조건 개발 또는 분석 프로젝트에 뛰어들어야 그 곳에서 답답함과 막막함을 느낄 수 있기 때문이다. 그 답답함의 끝에서 아래의 기본 지식을 공부하면 지치지 않고 빨아들일 수 있을 것이라고 계획했다. 그리고 실제로 그랬다. 마지막 한 달은 공부한 내용이 머리 속에서 무의미하게 쌓이지 않고 실제로 쓰이고 나의 커리어가 될 수 있게 하기 위함이다.


## 공부 원칙
- 재밌게 한다.
  블로그에도 적었지만, 사실 이 일이 재미있기 떄문에 시작한 것이다. 공부 계획이 과하게 스트레스가 된다면 무엇인가 잘 못되어있는 것이고 완주하기 어렵다. 그럴때에는 방법을 크게 수정하기로 했다.
- 하루에는 한 토픽만 한다.
  아래 내용은 나에게 굉장히 난이도가 높다. 따라서 한 가지 공부에 집중하고 다른 공부로 전환하는 것이 어렵다. 특히 기초 지식을 책으로 몇 회독씩 읽으며 이해할 때와 프로젝트를 진행할 때의 느낌은 다르다. 기초 지식을 익힐 때에는 책이 주는 답의 의미를 이해하려 하지만, 프로젝트 때에는 최고의 방법이 아니어도 내가 해낼 수 있는 것을 계속생각해야 하기 떄문이다.
- 버릴 건 버린다.
  아래 모든 공부의 주요 언어는 Python이다. 주요 회사의 코딩 인터뷰 주력 언어이기도 하고, 데이터 분석, 개발 프로젝트 등 모든 부분을 포괄할 수 있는 언어이기 때문이다. 부족한 부분을 Java와 같은 컴파일 언어로 공부하거나 하겠지만 되도록 저넌을 넓게 펴지 않으려 한다.
- 프로젝트 베이스로 공부한다.
  공부량이 많아도 한 주의 일부는 항상 프로젝트만 하는데 쓰려고 한다. 개발이 되었건 Kaggle이 되었건 간에 직접 코딩하면서 쓴 시간만큼만 성장할 수 있다. 동영상을 보는데에 지나친 시간을 낭비하지 않아야 한다.

## 팟캐스트
공부에서 핵심이 되지 않는데도 문제가 되는 것이 있다면 영어와 그 분야의 "감수성"이다. 이 것을 도와주었던 것이 팟캐스트로 평소에 듣고 있다.
- [Partially Derivative](http://partiallyderivative.com/)
  데이터 과학자 3명이 재미있는 관련 아티클을 소개. 전체적으로 가벼운 이야기들을 많이하고, 원년멤버인 남성 둘의 발음이 굉장히 좋아서 듣기 편함.
- [Linear Digressions](http://lineardigressions.com/)
  데이터 과학자 한 명이 소프트웨어 엔지니어 동료에게 데이터과학 주요 용어를 설명하는 방송. 조금 덜 재미있지만, 짧아서 듣기 편하고, 어려운 내용을 쉽게 설명함.

## 영상리스트
- [ ] [ted : making sense of too much data](https://www.ted.com/playlists/56/making_sense_of_too_much_data) : 데이터 과학으로 어떤 이야기들 많이 나오는지 가볍게 볼 수 있음, 시각화에 집중되어있는 경우가 많음
- [ ] [the life of data science](https://www.youtube.com/watch?v=h9vQIPfe2uU)
- [ ] [What data science is](https://www.youtube.com/watch?v=fZuDwiM1XBQ)

## 데이터 과학

### 머신러닝
머신러닝 공부는 서적이 잘 되어 있어서 서적을 중심으로 공부하고, 강의는 보조자료로 활용했다.
- 서적
    - [An Introduction to Statistical Learning](https://www.amazon.com/Introduction-Statistical-Learning-Applications-Statistics/dp/1461471370)
      크게 수학적이나 통계적인 지식이 없더라도, 기초적인 내용을 충분히 배울 수 있다. 한 번 읽은 상태로, 2회독 정도를 목표로 하고 있다. 책 뒤의 R 코드는 무시하면서 갔다.
    - [The Elements of Statistical Learning](https://www.amazon.com/Elements-Statistical-Learning-Prediction-Statistics/dp/0387848576)
      머신러닝의 바이블이라고 하는데, 난이도가 높지는 않은듯, ISL을 다 읽고 시작할 계획이다.
    - [Python Data Science Handbook: Essential Tools for Working with Data](https://www.amazon.com/Python-Data-Science-Handbook-Essential/dp/1491912057)
      파이썬으로 개발을 해봤어도 데이터 분석에서 막막한 것이, 각종 라이브러리 사용법을 익혀야 하기 때문이다. 데이터를 다루는데에 Numpy와 Pandas를 알아야 하고, 데이터의 모양이라도 보려면 Matplitlib을 알아야 한다. Scikit-learn은 물론이다. 그 순서대로 나와있는 책이다. ISL로 이론을 익히면서 이 책을 반복적으로 보며 연습했다.
    - [Python Machine Learning](https://www.amazon.com/Python-Machine-Learning-Sebastian-Raschka/dp/1783555130/)
      파이썬 머신러닝하면 가장 많이 언급된다. ESL과 병행하며 실습하려 한다.

- 강의
    - [Andrew Ng의 Coursera 강의](https://www.coursera.org/learn/machine-learning)
    - [Stanford matrial](http://cs229.stanford.edu/materials.html)

### 딥러닝
- 서적
    - [Deep Learning Book](https://www.amazon.com/Deep-Learning-Adaptive-Computation-Machine/dp/0262035618)
- 온라인 자료
    -[파이썬 딥러닝 워크쓰루](http://karpathy.github.io/neuralnets/)

### 데이터 마이닝
아래 내용은 Coursera Specialization으로 결제해야 하지만, 나눠서 들으면 공짜.
- [데이터 마이닝 스페셜](https://www.coursera.org/specializations/data-mining)

### 통계모델링
- [Probabilistic Programming and Bayesian Methods for Hackers](https://github.com/CamDavidsonPilon/Probabilistic-Programming-and-Bayesian-Methods-for-Hackers)
### 시각화
- [University of Washington / Slides & Resources](http://courses.cs.washington.edu/courses/cse512/14wi/)
- [D3 Libary](http://alignedleft.com/tutorials/)
### 분산컴퓨팅
- [Intro to Hadoop](https://www.udacity.com/course/intro-to-hadoop-and-mapreduce--ud617)
### 자연어 처리
- [From Languages to Information / Stanford CS147](http://bit.ly/nlpcs124)
- [한글 Konlpy Document](http://konlpy-ko.readthedocs.io/ko/v0.4.3/)
- [How to Write a Spelling Correcter/Norvig](http://norvig.com/spell-correct.html)
### 소셜 네트워크
- [Social and Economic Networks: Models and Analysis/Stanford/ Coursera](https://www.coursera.org/learn/networksonline)
### 데이터 분석
- [트위터 분석](http://blogs.ischool.berkeley.edu/i290-abdt-s12/)
### 데이터 베이스
- [생활코딩 Mysql](https://opentutorials.org/course/195)
- [Codecademy Mysql](https://www.codecademy.com)
- [스탠포드 데이터 베이스](https://lagunita.stanford.edu/courses/Engineering/db/2014_1/about)
### 데이터과학논문
- 랜덤 포레스트
    - [Random Forests](http://oz.berkeley.edu/~breiman/randomforest2001.pdf)
- Hadoop
    - [Map Reduce](https://research.google.com/archive/mapreduce.html) : 하둡의 등장을 이끈 소중한 논문
    - [Google File System](https://research.google.com/archive/gfs.html)
- NoSQL
    - [Amazon Dynamo](http://www.allthingsdistributed.com/2007/10/amazons_dynamo.html)
    - [Google Bigtable](https://research.google.com/archive/bigtable.html)
- 머신러닝
    - [A few useful things to know about Machine Learning](http://homes.cs.washington.edu/~pedrod/papers/cacm12.pdf)

## 컴퓨터 과학
컴퓨터 과학 부분은 위의 깃헙의 자료를 기반으로 했음.
아래 주요 토픽 별로는 동영상과 체크해야할 토픽들이 정리되어있는데, 모두 깃헙에 옮기는 것이 의미가 없어서, 원본 깃헙 기준으로 보면 좋을듯
### 서적
#### 인터뷰 기초
- [Programming Interviews Exposed: Secrets to Landing Your Next Job, 2nd Edition](http://www.wiley.com/WileyCDA/WileyTitle/productCd-047012167X.html)
    - answers in C++ and Java
    - this is a good warm-up for Cracking the Coding Interview
    - not too difficult, most problems may be easier than what you'll see in an interview (from what I've read)
- [Cracking the Coding Interview, 6th Edition](http://www.amazon.com/Cracking-Coding-Interview-6th-Programming/dp/0984782850/)
    - answers in Java
#### 컴퓨터 구조
- [Write Great Code: Volume 1: Understanding the Machine](https://www.amazon.com/Write-Great-Code-Understanding-Machine/dp/1593270038)
#### 파이썬
- [Data Structures and Algorithms in Python](https://www.amazon.com/Structures-Algorithms-Python-Michael-Goodrich/dp/1118290275/)
    - by Goodrich, Tamassia, Goldwasser
    - I loved this book. It covered everything and more.
    - Pythonic code
    - 존경하는 깃헙 주인의 책 평가: https://startupnextdoor.com/book-report-data-structures-and-algorithms-in-python/

### 기초 공부
#### C
- 서적
    - [C Programming Language, Vol 2](https://www.amazon.com/Programming-Language-Brian-W-Kernighan/dp/0131103628)
        - This is a short book, but it will give you a great handle on the C language and if you practice it a little
            you'll quickly get proficient. Understanding C helps you understand how programs and memory work.
        - [answers to questions](https://github.com/lekkas/c-algorithms)
    -[C 언어 공부법과 책 추천 (한글)](http://sunyzero.tistory.com/225)
#### 컴퓨터가 어떻게 프로그램을 작동시키는가
    - [How does CPU execute program (video)](https://www.youtube.com/watch?v=42KTvGYQYnA)
    - [Machine Code Instructions (video)](https://www.youtube.com/watch?v=Mv2XQgpbTNE)

### 알고리즘
    - [ ] [Harvard CS50 - Asymptotic Notation (video)](https://www.youtube.com/watch?v=iOq5kSKqeR4)
    - [ ] [Big O Notations (general quick tutorial) (video)](https://www.youtube.com/watch?v=V6mKVRU1evU)
    - [ ] [Big O Notation (and Omega and Theta) - best mathematical explanation (video)](https://www.youtube.com/watch?v=ei-A_wy5Yxw&index=2&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
    - [ ] Skiena:
        - [video](https://www.youtube.com/watch?v=gSyDMtdPNpU&index=2&list=PLOtl7M3yp-DV69F32zdK7YJcNXpTunF2b)
        - [slides](http://www3.cs.stonybrook.edu/~algorith/video-lectures/2007/lecture2.pdf)
    - [ ] [A Gentle Introduction to Algorithm Complexity Analysis](http://discrete.gr/complexity/)
    - [ ] [Orders of Growth (video)](https://class.coursera.org/algorithmicthink1-004/lecture/59)
    - [ ] [Asymptotics (video)](https://class.coursera.org/algorithmicthink1-004/lecture/61)
    - [ ] [UC Berkeley Big O (video)](https://youtu.be/VIS4YDpuP98)
    - [ ] [UC Berkeley Big Omega (video)](https://youtu.be/ca3e7UVmeUc)
    - [ ] [Amortized Analysis (video)](https://www.youtube.com/watch?v=B3SpQZaAZP4&index=10&list=PL1BaGV1cIH4UhkL8a9bJGG356covJ76qN)
    - [ ] [Illustrating "Big O" (video)](https://class.coursera.org/algorithmicthink1-004/lecture/63)
    - [ ] TopCoder (includes recurrence relations and master theorem):
        - [Computational Complexity: Section 1](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-1/)
        - [Computational Complexity: Section 2](https://www.topcoder.com/community/data-science/data-science-tutorials/computational-complexity-section-2/)
    - [ ] [Cheat sheet](http://bigocheatsheet.com/)


### 자료구조
- #### Arrays
- #### Linked Lists
- #### Stack
- #### Queue
- #### Hash table

### 추가 지식
#### Binary&Bitwise
- ##### Binary search
- ##### Bitwise operations
- ##### Heap / Priority Queue / Binary Heap
#### Trees
- ##### Trees
- ##### Binary search trees: BSTs
#### Sorting
#### Graphs

### Recursion
### 동적프로그래밍
### 객체지향 프로그래밍
### 디자인 패턴
### Combinatorics (n choose k) & Probability
### NP
### Cache
### Process and Thread
### Testing

### 논문
- [Love classic papers?](https://www.cs.cmu.edu/~crary/819-f09/)
- [ ] [1978: Communicating Sequential Processes](http://spinroot.com/courses/summer/Papers/hoare_1978.pdf)
    - [implemented in Go](https://godoc.org/github.com/thomas11/csp)
- [ ] [An Inside Look at Google BigQuery](https://cloud.google.com/files/BigQueryTechnicalWP.pdf)
- [ ] [2006: The Chubby Lock Service for Loosely-Coupled Distributed Systems](https://research.google.com/archive/chubby-osdi06.pdf)
- [ ] [2007: What Every Programmer Should Know About Memory (very long, and the author encourages skipping of some sections)](http://s3.amazonaws.com/AllThingsDistributed/sosp/amazon-dynamo-sosp2007.pdf)
- [ ] [2010: Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://research.google.com/pubs/archive/36356.pdf)
- [ ] [2010: Dremel: Interactive Analysis of Web-Scale Datasets](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36632.pdf)
- [ ] [2012: Google's Colossus](https://www.wired.com/2012/07/google-colossus/)
    - paper not available
- [ ] 2012: AddressSanitizer: A Fast Address Sanity Checker:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/37752.pdf)
    - [video](https://www.usenix.org/conference/atc12/technical-sessions/presentation/serebryany)
- [ ] 2013: Spanner: Google’s Globally-Distributed Database:
    - [paper](http://static.googleusercontent.com/media/research.google.com/en//archive/spanner-osdi2012.pdf)
    - [video](https://www.usenix.org/node/170855)
- [ ] [2014: Machine Learning: The High-Interest Credit Card of Technical Debt](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43146.pdf)
- [ ] [2015: Continuous Pipelines at Google](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43790.pdf)
- [ ] [2015: High-Availability at Massive Scale: Building Google’s Data Infrastructure for Ads](https://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44686.pdf)
- [ ] [2015: TensorFlow: Large-Scale Machine Learning on Heterogeneous Distributed Systems](http://download.tensorflow.org/paper/whitepaper2015.pdf )
- [ ] [2015: How Developers Search for Code: A Case Study](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/43835.pdf)
- [ ] [2016: Borg, Omega, and Kubernetes](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/44843.pdf)


## 기초 수학
### 선형대수
- 서적
  - [코딩 더 매트릭스]()
- 참고자료
  -[Linear Programming (Math 407)](http://bit.ly/course-uw-linearprogramming)
- 강의
  - [칸아카데미](https://www.khanacademy.org/math/linear-algebra)
### 미적분
- 강의
  - [칸아카데미-기초미적](https://www.khanacademy.org/math/precalculus)
  - [칸아카데미-미분](https://www.khanacademy.org/math/differential-calculus)
  - [칸아카데미-적분](https://www.khanacademy.org/math/integral-calculus)
  - [칸아카데미-다변수미적](https://www.khanacademy.org/math/multivariable-calculus)
  - [칸아카데미-미분방정식](https://www.khanacademy.org/math/differential-equations)
### 통계
- 강의
  - [칸아카데미-통계](https://www.khanacademy.org/math/statistics-probability)
  - [프린스턴 통계](https://www.youtube.com/watch?v=VJlpQs4a5LI&list=PLgIPpm6tJZoTlY4A-xikgjXmlscqduP5k)
### Convex Optimization
- 강의
  - [스탠포드](http://stanford.edu/class/ee364a/index.html)
