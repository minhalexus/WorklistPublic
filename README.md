# WorklistPublic
Worklist is a project that aims to automate the job searching process to make everyone's life easier.

# Demo
Demo can be accessed at https://worklistui.herokuapp.com
Click "Skip to demo" to see a quick preview of the work accomplished.

# Source Code
The source code for Worklist is currently in a private repository, as I may later want to monetize some of the ideas. 
If an employer wants proof of the source code, please contact me on mashanje@uwaterloo.ca, and it proofs can be arranged.

# Worklist Guide

Welcome to Worklist! This page will guide you through the features presently implemented on this Web Application, as discuss the development road map ahead and the ultimate goal we are working towards.

### The Vision

*Automating the Job Searching Process*

The job searching process is an incredibly stressful task for most people. In the process of facing many job application rejections, people lose enthusiasm and motivation to continue their efforts in finding a job. They stop customizing their resumes, get burnt out from creating new cover letters, and even looking up new job postings due to demoralization from rejections.

Worklist aims to solve this problem by not just creating a smart resume developing library that utilizes *natural language processing* libraries to create highly optimized resumes based on a job description, but also creating a job posting website that can utilize this ability to automatically apply for jobs with a user's consent.

### Road Map

1. Created a backend REST API with Python+Flask with Postgresql. (completed)
2. Developed a customized resume generating library, that allows new resume designs from HTML + CSS. (completed)
3.  Developed a front-end dashboard with ReactJS that provides a GUI for all the REST API functions. (completed)
4. Create guides, demoes, documentation and iron-out bugs so that the project is more polished to get more people on board. **(in progress)**
5. Integrating Spacy library with the REST API and linking it with the frontend. **(in progress)**
6. Re-design of front-end dashboard to utilize a more user-friendly and animated UX that is a lot more intuitive to use. (Est. December 2020)

## Guide

**The project requires an account to test all features, although we have made all pages viewable without authentication for demo purposes.**

Currently, the project is more so aimed at software related resumes, as that is our area of expertise. But we will later be customizing Worklist to cater to more professions. So far, a resume consists of the following entities:

1. Projects
2. Experiences
3. Skills
4. Qualifications
5. And Personal Info (in the User Profile)

Once a user has filled out these forms, they are ready to generate resumes for themselves. On the "Resume" tab, a use may select specific projects and experiences to generate a resume. 

Once they create a resume, they may then download the resume by clicking on the download icon.



The "Generate Smart Resume" tab (still a bit buggy) will ask you to enter a job description, and will utilize the **Spacy** library (an NLP library) to determine the most similar words to your ***Skills***, and select your **Projects** and **Experiences** accordingly.



## About Me

#### Minhal Shanjer

I am a 4th year Computer Science student at the University of Waterloo. I am interested in data analysis and big data, and that is one of the reasons why I am interested in developing Worklist which has the potential to encapsulate both of these fields.

https://minhalshanjer.ca


