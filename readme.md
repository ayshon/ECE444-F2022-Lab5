# CARTE Education Pathways

## Note:
The following students are working on this repo:

Sean Llera

Ali Meshkat

Shaibal Muhtadee

This repo is a clone of 
https://github.com/nelaturuk/education_pathways.  


## Activity 1
![activity1](assignment_imgs/activity1.png)

## Activity 2-5
![homepage](assignment_imgs/homepage-s.jpg)

![form](assignment_imgs/form-ss.jpg)

![results](assignment_imgs/results-ss.jpg)

## Activity 6


User Stories 1 & 2 & 3: Course Page - its minors, career paths and Student Reviews

<img width="719" alt="image" src="https://user-images.githubusercontent.com/29826854/198181016-2a21901f-eef8-4fce-a789-42bd10f97f21.png">


User Story 4 (Bonus): Minors Dropdowwn

<img width="721" alt="image" src="https://user-images.githubusercontent.com/29826854/198181158-9b63f6d7-bec5-4b8c-8742-4e78b164686a.png">


## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker


## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
