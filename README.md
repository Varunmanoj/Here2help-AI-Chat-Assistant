# Here2Help – Chat Assistant for College Students for Frequently Asked Questions.
## Project Background
When I joined Senior College, I found it difficult to get answers to simple questions in the online world as I was not familiar with the college website. I explored few other college websites and observed that most websites do not have a proper FAQ page. In today’s world there are new modes of user interaction aided by Artificial Intelligence that would help in addressing the various repeated questions that both current and prospective students have.
## Project Description 
A prospective student usually explores various colleges and institutes with a wide range of questions. “How can I register?”, “What courses are available?”, “Where is the college located?” and many other such queries. A student who is already enrolled in the college would also have different queries like “What is the syllabus?”, “What is the timetable?”, “Where is the holiday list?” etc.   
My AI Chatbot #Here2Help can answer these questions immediately, so students can avoid reading long FAQ documents or enquiring with multiple people or scrolling webpages in the college website. Students can simply ask their questions to the Chatbot and get an instant answer. This instant response improves student experience and makes life a lot easier for students and staff members.
A link to Assistant #Here2Help would be given on a demo college (ABC College) website. 

![# Here 2 Help Page with Chat bot](https://user-images.githubusercontent.com/66109641/146576732-141f193a-a16f-4a99-bbfd-467cb343b863.png)

## Features
This project is aimed to implement a Web Based ChatBot with the help of various Azure Services. This bot would help communicate in natural language with the users and help them answer the various frequent questions that students have automatically. 
Also, since I am a visually impaired person, I have focused on making the solution accessible to all users.
- Provide 24/7 assistance and satisfy the needs of existing students.
-	Provide an easy interface for prospective students for enquiry about courses and admission.
-	Provide instant answers to Frequently Asked Questions.
-	Take away the pressure from the human help desk representatives
-	Implemented Text to Speech on the website to make it accessible for all users.
-	Implemented a button to read aloud the website contents at relevant positions. 
![Speaker Icon](https://user-images.githubusercontent.com/66109641/146577007-808d9ba1-e51d-4ac7-8e44-170619bb068d.png)
---
## Technology Used
I have used various Azure Cognitive Services for building my project prototype. 
### Azure QnA maker and Azure bot Service
First, I have made a List of Question-and-Answer pairs of various Frequently Asked Questions (FAQ). This List is used to make the Knowledge base for the Assistant. 
Secondly, added some personality to the Assistant using the Azure QnA Maker’s Chit-Chat Feature so that the bot could answer general questions. 
Then I have trained the model with the help of Language Understanding so that the Assistant can understand the Natural Language inputted by the user. 
Then I have deployed the Assistant to a Web App using the provided REST Endpoint and the Secret Keys so that client applications can access and interact with the Assistant on a website. 
### A Focus on Accessibility
Since I am a visually impaired person, I feel the need for every website to be accessible for people with different abilities, so I have used the Bootstrap (CSS Framework) along with the various HTML 5 and ARIA (Accessible Rich internet Applications) to make the website accessible for people with different abilities.
### Azure Speech Service
I have also used the Azure Speech Service to implement Text to Speech on the Website for people with disabilities. 
I have used the Azure’s Neural text to speech voices which help in supplying high quality audio to the users on the website. 
## Other Technologies Used
### Bootstrap 5
Bootstrap 5 is one of the Leading CSS Framework used to create responsive Website using various pre-made components and libraries.
### HTML 5
HTML is the latest and most enhanced version of HTML.
### CSS
Cascading Style Sheets is a style sheet language used for describing the presentation of a document written in a markup language such as HTML. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript. 
## Architecture Diagram
![Architecture Diagram](https://user-images.githubusercontent.com/66109641/148674922-e4a3dc1d-a79f-4a55-b79a-6dd762b94b65.png)
## Project Demo
<iframe width="684" height="385" src="https://www.youtube.com/embed/V76UrW3z9e4" title="Project Demo Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
