User journey

1) homepage
Information
Splash image
Register/Login

2) profile page
Photo
username
coding language
charity
questions/answers posted

3) question list page
list of questions
categories

4) question page
headline of question
description
responses
  code framework for submitting answers

5) question submission page
headline
description
deadline
reward

Models
1)User model
email
github name
icon (optional)
language
charity
description

2)Question model
Language (reference)
Owner
Title
Reward
Deadline
Answers

3)Answers model
title
owner
description

4)Language model
name

 [
  email: sdfsdf@hotmail.com,
  githubName: sdsdfd,
  charity: blah
    question: { JavaScrip, javascript: {title, answers: {fdsf, dfsdf, fsdf}}}
      ]
    ]

user {
  email:
  username:
  githubLink:
  number
  language: { language Schema }
}

language {
  name
  question: { questionSchema }
}

Question {
  user
  title
  description
  answers { answer schema }
}

Answer {
  title
  owner
  winner default false
  description
}
