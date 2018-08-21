# StackOverflow-API


[![Build Status](https://travis-ci.org/mozzy11/StackOverflow-API.png)](https://travis-ci.org/mozzy11/StackOverflow-API)
[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.png)](https://codeclimate.com/github/mozzy11/StackOverflow-API)
https://coveralls.io/repos/github/mozzy11/StackOverflow-API/badge.svg(Coverage Status)!:https://coveralls.io/github/mozzy11/StackOverflow-API

Project Overview
StackOverflow-lite is a platform where people can ask questions and provide answers.

 Features:
1. Users can create an account and log in.
2. Users can post questions.
3. Users can delete the questions they post.
4. Users can post answers.
5. Users can view the answers to questions.

Optional Features:
- Users can upvote or downvote an answer.
- Users can comment on an answer.
- Users can fetch all questions he/she has ever asked on - the platform
- Users can search for questions on the platform
- Users can view questions with the most answers.

END POINT 
the app s hosted on HEROKU here https://stackoveflow.herokuapp.com and u can use that as the Base url with the followng end ponts

1.GET api/v1/questions  gets all questons

2.GET api/v1/questions/<questionId>  gets a specific Question
 
3.POST api/v1/questions  adds a question

4.POST api/v1/questions/<questionId>/answers  Adds an answer



