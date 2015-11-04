# Week-3-Day-3


Challenge - Word Count
----------------------

Count the number of appearances for each word in the gettysburg.txt speech. It should output something like (fake results):

```
pizza: 20
dude: 15
perish: 10
```

```c#
Regex.Split(someText, @"\W+") 

var excluded_words = new []{ "that", "the", "to", "a", "and", "can", "of", "here", "have", "it", "in", "is", "not" };

```
Rules:

-	Ignore common words

Hint: use a dictionary for each word, or use linq's groupby

Today
--------
1. Regex
1. Groupby
1. Web  API 


Homework
----------
Create a web aspi app that allows a client to list all Posts via an API.

GET /posts to return all posts
GET /posts/:id gives details of a post
POST /posts creates a post
PUT /posts/:id updates a post
DELETE /posts/:id deletes a post

Test your apps using [Postman](https://www.getpostman.com/)
