# My CS Degree - Full-Stack ML Engineering (2020)

Being a machine learning software engineer with a background in Physics, I felt the lack of a CS degree had been a limiting factor in my long-term growth. To tackle it head-on, I designed this curriculum for myself with the best resources I found online, focusing on CS basics as well as full-stack development, deep learning and natural language processing.

There are general knowledge courses and project courses.

**General knowledge courses** are for indexing knowledge in the brain into an organized system. When facing a new problem, at least you know what relevant info to look for.

**Project courses** are the real learning process. Learning by doing is the only way to learn.

If you are interested in the philosophy of the creation of this curriculum, I wrote an article about it:

[How I Designed My Own Full-Stack ML Engineering Degree](https://towardsdatascience.com/how-i-designed-my-own-full-stack-ml-engineering-degree-297a31e3a3b2?sk=fe0ac0cc081b3e4734734a0e4f85f637)


## General knowledge courses

#### CS101. Computer architectures: general intro
- Coursera: [From NAND to Tetris part I](https://www.coursera.org/learn/build-a-computer/home/welcome)

#### CS102. Networking: general intro
- Coursera [computer networking](https://www.coursera.org/learn/computer-networking/home/welcome)
- Stanford course [youtube playlist](https://www.youtube.com/playlist?list=PLvFG2xYBrYAQCyz4Wx3NPoYJOFjvU7g2Z)
- parrt cs601 [Sockets](https://github.com/parrt/cs601/blob/master/lectures/sockets.md)
- parrt cs601 [Network programming](https://github.com/parrt/cs601)
- [Socket programming in Python, 5 videos](https://pythonprogramming.net/sockets-tutorial-python-3/)

#### CS103. Operating systems: general intro
- **[Udacity course](https://classroom.udacity.com/courses/ud923)**
- Coursera: [From NAND to Tetris part II](https://www.coursera.org/learn/nand2tetris2)

#### CS201. Database: general intro
- Architecture of a Database System [Paper](https://dsf.berkeley.edu/papers/fntdb07-architecture.pdf)
- Berkeley [Course Playlist](https://www.youtube.com/user/CS186Berkeley/playlists)

#### CS401. System Design
- **Book: Designing Data Intensive Applications**
- **[Course: MIT course playlist](https://www.youtube.com/playlist?list=PLrw6a1wE39_tb2fErI4-WkMbsvGQk9_UB)**
- Grokking the System Design Interview
- [Gaurav Sen Playlist](https://www.youtube.com/playlist?list=PLMCXHnjXnTnvo6alSjVkgxV-VH6EPyvoX)
- [Uber engineering blog series](https://eng.uber.com/tech-stack-part-one-foundation/)


#### CS403. Design Patterns
- Python Factory pattern and Message Queue
- Book: Design Patterns by Gamma et al

#### CS405. Software Engineering Fundamentals
- **Course**: [Software Development Process](https://classroom.udacity.com/courses/ud805)
- [Prof. Terence Parr, USF **CS601**](https://github.com/parrt/cs601)
- [Gaurav Sen](https://www.youtube.com/playlist?list=PLMCXHnjXnTntYbKsUs6Pj8_BO_8ou4y07)

#### CS406 DevOps with Docker
- [Udemy Docker course](https://www.udemy.com/course/learn-docker/)
- [Deploy ML/DL using Docker](https://youtu.be/0qG_0CPQhpg)

#### **CS501 Deep Learning with PyTorch by Yann LeCun & Alfredo Canziani: knowledge**
- **Highly recommended deep learning course!!**
- [Course site](https://atcold.github.io/pytorch-Deep-Learning/)
- [Youtube playlist](https://www.youtube.com/playlist?list=PLLHTzKZzVU9eaEyErdV26ikyolxOsz6mq)

#### CS503 [fastai: Computation Linear Algebra by Rachel Thomas](https://github.com/fastai/numerical-linear-algebra/blob/master/README.md)


#### CS504. Overview of Production Machine Learning and MLOps
- **Book: Building ML Powered Applications**
- **Suggestion: take project course CS512 for hands-on practice after this course**
- Other readings:
  - [MLOps overview by Huyen Chip](https://huyenchip.com/2020/06/22/mlops.html)
  - [TDS Article: Big picture architecture of ML system](https://towardsdatascience.com/architecting-a-machine-learning-pipeline-a847f094d1c7)
  - [Challenges](https://eugeneyan.com/writing/challenges-after-deploying-machine-learning/) and [practical guide to maintaining machine learning](https://eugeneyan.com/writing/practical-guide-to-maintaining-machine-learning/) by Eugene Yan

#### CS505 Natural Language Understanding Stanford
- [Course page](https://web.stanford.edu/class/cs224u/2019/index.html)
- [Playlist](https://www.youtube.com/playlist?list=PLoROMvodv4rObpMCir6rNNUlFAn56Js20)


#### CS506 [Natural Language Processing using Deep Learning CMU](https://www.youtube.com/playlist?list=PL8PYTP1V4I8CJ7nMxMC8aXv8WqKYwj-aJ)

#### CS507 [Full Stack Deep Learning](https://course.fullstackdeeplearning.com/)
- [Project template](https://github.com/DanielhCarranza/ml-production-template)

#### CS508 [Deep Learning for Computer Vision](https://www.youtube.com/playlist?list=PL5-TkQAfAZFbzxjBHtzdVCWE0Zbhomg7r)


#### CS509 [Yannic Kilcher Youtube series](https://www.youtube.com/c/YannicKilcher/playlists)

#### CS510 [Luigi SageMaker course](https://mlinproduction.teachable.com/p/build-deploy-and-monitor-ml-models-with-amazon-sagemaker)
- Great blog for prodML: [mlinproduction.com](http://mlinproduction.com/)

#### CS511 MLOps with GitHub Action
- [MLOps youtube playlist](https://www.youtube.com/playlist?list=PL7WG7YrwYcnDBDuCkFbcyjnZQrdskFsBz)
- MLOps: Setup Github Actions CI/CD for NLP project
    - [Weights & Biases Youtube video with Hamel Husain](https://youtu.be/S-kn4mmlxFU)
    - [Blog post](https://github.blog/2020-06-17-using-github-actions-for-mlops-data-science/)

## Project courses

#### CS301. Coding Interview
- EPI book

#### CS302 Python 3
- Basics: [Practical Python course](https://dabeaz-course.github.io/practical-python/Notes/Contents)
- [Eugene Yan's Python project setup](https://eugeneyan.com/writing/setting-up-python-project-for-automation-and-collaboration/)
- RestAPI with [FastAPI guide](https://fastapi.tiangolo.com/tutorial/first-steps/)
    - FastAPI MadeWithML example
- Project: DoverChat, poetry, Docker, deployed on Heroku and AWS EB

#### CS303 Nature of Code youtube series

- [JS Prototype](https://youtu.be/hS_WqkyUah8)
- [Topics of ES6-ES8, promise, async await (20 vids)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YgpA3Oht-7B4NBQwFVe3pr)
- Nature of Code
    - [Physics Engine, matter.js simulation project (10 vids)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6akvoNKE4GAxf6ZeBYoJ4uh)
    - [Autonomous Agents (10 vids)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YHt0dtyf4uiw8tKOxQLvlW)
    - [Cellular Automata (4 vids)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6YrWXvEQFOGbCt6cX83Xunm)
    - [Fractals (10 vids)](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bXUJvjnMWGU5SmjhI-OXef)
        - Fractal trees, space colonization project


#### CS304 Weather Comparison App
- Build API using **FastAPI** to get daily and hourly weather for cities
- Frontend based on **Streamlit**, a Python framework for building UI for prototype projects
    - [Streamlit get started](https://docs.streamlit.io/en/stable/)


#### CS402 Full-Stack Web Development, ReactJS
- **Udemy [the complete junior to senior web developer roadmap](https://www.udemy.com/course/the-complete-junior-to-senior-web-developer-roadmap/)**

#### CS404 AWS Services
- Book: **The Good Parts of AWS** by Daniel Vassallo

#### CS407 iOS Development with Swift and SpriteKit
- Optional course for mobile game development
- youtube video: https://youtu.be/467Doas5J6I
- Project: A sound game for instruments

#### CS500 Deep Learning with FastAI & Pytorch: projects
- **Course v4: [https://course.fast.ai/](https://course.fast.ai/)**
- **[fastbook](https://github.com/fastai/fastbook)**
  - **Document all answers to questionnaires**
- [FastAI2 design paper](https://arxiv.org/abs/2002.04688)
- [Deep Tutorials for PyTorch](https://github.com/sgrvinod/Deep-Tutorials-for-PyTorch)
- Official PyTorch book: Deep Learning with PyTorch

#### CS502 NLP: projects
- **[fastai NLP course](https://www.fast.ai/2019/07/08/fastai-nlp/)**
- **[Awesome visual course](https://lena-voita.github.io/nlp_course.html#main_page_content)**
- **Book: [Practical NLP](https://github.com/practical-nlp/practical-nlp)**
- Survey
    - [Eugene Yan: NLP Survey](https://eugeneyan.com/writing/nlp-supervised-learning-survey/)
    - [Pratik Bhavsar: Pytorch for NLP](https://medium.com/modern-nlp/get-pro-in-pytorch-for-nlp-60352b51fa1e)
- Other resources
  - [Fast AI course v4 NLP lecture](https://course.fast.ai/videos/?lesson=8)
  - [@amitness: How to Learn Transformers](https://twitter.com/amitness/status/1297471740012982273)
  - [Advanced course](https://www.coursera.org/learn/language-processing/home/welcome)
  - [NLP Masterclass: Modeling Fallacies in NLP](https://youtu.be/f2m6Mon0VE8?t=316)
  - [NLP Datasets](https://datasets.quantumstat.com)
  - Book: NLP with Pytorch
  - MadewithML and [dair.ai](http://dair.ai) chatbot materials
      - [Survey paper](https://arxiv.org/abs/2004.03705)
      - [MadeWithML topic curation](https://madewithml.com/topics/conversational-ai/)
      - [Future of NLP](https://youtu.be/G5lmya6eKtc)
      - [Level 3 AI Conference 2020](https://www.youtube.com/playlist?list=PL75e0qA87dlGP51yZ0dyNup-vwu0Rlv86)
  - Full stack ML prototype stack: FastAPI, Streamlit, Docker, Heroku
      - [Project example 1: streamlit + fastapi](https://github.com/davidefiocco/streamlit-fastapi-model-serving/)
      - [Project example 2](https://github.com/abhimishra91/insight)

#### CS512 Applied ML in Production by MadeWithML
- Quote the course description: "This course isn't just about ML. In fact, it's mostly about clean software engineering! We'll cover important concepts like versioning, testing, logging, etc. that really makes this a production-grade product."
- [course page](https://madewithml.com/courses/applied-ml-in-production/)
- [MadeWithML youtube channel](https://www.youtube.com/c/MadeWithML/)

#### CS602 Open Source Contributions of Your Choosing
