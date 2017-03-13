#WDI_PROJECT_3
This is my third project for the Web Development Immersive boot camp at General Assembly. This was a group project.

#GA WDI Project 3

##Code Fund - Group Project MEAN Stack App

A group project inspired by Stack Overflow, incorporating a charity element. Users can sign up choosing a charity via the integrated JustGiving API and ask programming questions. Other users can post answers in response to the question and the poster of the question then donates the set bounty to their answerers chosen charity.

Home
![](http://i.imgur.com/l8P6QnJ.png)

Users Page
![](http://i.imgur.com/0SM08kK.png)

Choose your technology
![](http://i.imgur.com/rgr8w9V.png)

Questions List - JavaScript
![](http://i.imgur.com/H4oIUCn.png)

Example question
![](http://i.imgur.com/Uhi5JPa.png)



###Technology

It was built using an Express/Node Backend accessing a MongoDB, with Angular on the Frontend. I was responsible for building out the Angular JS on the front end, including authentication and building the user index and user profile pages. We integrated the JustGiving API for selecting charities. I also contributed to the styling and branding.

###Approach to the build of Code Fund: 

The app was built over the course of 4 days with a team of 5, this consisted of planning, collaboration and delegation of tasks. We used Balsamiq for wireframes, Trello for organisation and the delegation of tasks and git for version and collaboration control.
We also often pair programmed on more complicated tasks and brainstormed as a team for branding/design ideas.

One of the most complex tasks we collaborated on was designing the models for this project. As we decided to filter the questions by coding language, we decided we would require four models - user, language, question, and answer. The user model would store the basic authentication information, along with the charity selected by the user, and the questions he asked. The language model stored the languages, which were seeded in, and the questions associated with each language. The question models stored the obvious information, plus the monetary value the question asker would donate in return for a solution. Finally, the answer model stored the response, the owner, the question and whether it was the chosen solution by the question asker, as a Boolean value set to default false.


###The completed Mean Stack app is deployed on Heroku:
https://codefund.herokuapp.com

###Wins

It was my first experience working in a team and on a full MEAN stack application. 

Working in a team proved very efficient but also provided a large learning curve in communication both in person and digitally via Slack and Trello.

Also a first working with Angular JS, I was very enthusiastic about learning a new JavaScript framework. It was a fairly simple way of learning about two-way data binding and provided an alternative method of implementing the front end authentication for users.


###Future Improvements: 

Currently a user can select a charity, however, there isn't an actual payment method involved. As an improvement it would be essential to implement a payment method using PayPal linking it to the charities. 

