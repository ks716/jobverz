## Project Description

**Jobverz** is a product of [Multiverz](https://www.multiverz.com/)

## Problem statement

Job hunting, job seeking, or job searching is the act of looking for employment, due to unemployment, underemployment, discontent with a current position, or a desire for a better position. JobVerz is a web application designed for job seekers to identify their skills and skills to be known to get a job in their chosen career path. <br>
As a part of the Integration Team, our job is to extract skills from the given job description. We started to work on a mapper API which will act as a bridge between skills and job postings to provide a list of skills present in the posting. Additionally, by keeping track of all the retrieved skills, we can come up with insights into the present job market to predict trending skills.


## Technologies used

* **Frontend :** React JS
* **Backend :** Python, Spacy, AWS
* **Code Versioning Systems:** Git and GitHub  
  

## Sprint 1:

Naive approach to identify the skills in a given job description which are present in the given list of various skills. Any spelling mistakes that were present in the job description were taken care using spellchecker library in python. We were able to attain an accuracy of close to 50% using this approach and measures were taken to improve this in further sprints.


## Sprint 2:

To further improve the accuracy of the initial version of the algorithm, NLP techniques like lemmatization, stemming, word2vec, bag of words approaches were studied and applied. Also, data of job postings and skills were scraped from the pdf files from skillsfuture website.

## Sprint 3:

The data of all the job postings that were present in the top-3 fortune companies (Walmart, Amazon, Exonmobil) careers site were collected. Manually identified the skills present in some of the job descriptions to test the accuracy of the existing model. Research was done to develop a machine learning algorithm to extract skills from the job posting.


## Sprint 4:

Developed an algorithm using fuzzywuzzy library of python to match the skills from job description to those present in the EMSI skills list. Using this algorithm we were able to extract the skills with an accuracy of 63%.


## Sprint 5:
Improved the previous algorithm to match the partially matched skills which improved the accuracy to 66%. Researched on other algorithms that could potentially improve the accuracy further. Tried to employ BERT similarity to further extract the partial matches as well.

## Sprint 6:
Researched on GPT-3 (Generative Pretrained Transformer 3) model and NER(Named Entity Recognition) model to extract skills from a job posting. We weren’t able to use the GPT-3 model due to some limitations. We started training the NER model by manually annotating some job postings. Also experimented with stemming and lemmatization to format the skills taxonomy.
Impediments : 
Manually annotating the data was very difficult and needed to find a way to automate the process.
Prevent noise and format the retrieved skills.

## Sprint 7:
Used the fuzzywuzzy algorithm to extract the skills from a job posting and used that as training data. Trained the NER model with 300 job postings. Extracted skills from 2.54 lakhs job postings from 59 fortune companies. Performed error analysis and observed  that the NER model is working with an accuracy of 74%. The retrieved skills were sent to EMSI mapper to further format the skills.

## Sprint 8:
Cleaned and modularized the code to form a sort of API endpoint which is then deployed on AWS Lambda. Beacuse of storage restrictions had to use EC2 instance to deploy the package. Had our project demo infront if MSIT panel and worked on the [documentation](https://docs.google.com/document/d/11RWac0FnvHcHOYZuptnNKRxajd_XFk5-9DHOZkDmPrY/edit?usp=sharing).
