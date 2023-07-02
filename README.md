# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL

>The name of the API we chose was Cat Facts, its base URL is https://cat-fact.herokuapp.com;

- What purpose is this API for (education/fun and games/information/etc.)?

> This API is for education/fun, given it is for Cat facts, which are both informative and fun.

- What is the URL of the documentation?

> https://alexwohlbruck.github.io/cat-facts/docs/

- What is the full URL of one endpoint?

> https://cat-fact.herokuapp.com/facts;

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json

[
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e00b5f0aac31001185ed24",
        "user": "58e007480aac31001185ecef",
        "text": "When asked if her husband had any hobbies, Mary Todd Lincoln is said to have replied \"cats.\"",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-02-19T21:20:03.434Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "feedback": "",
            "sentCount": 1
        },
        "_id": "5887e1d85c873e0011036889",
        "user": "5a9ac18c7478810ea6c06381",
        "text": "Cats make about 100 different sounds. Dogs make only about 10.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-09-03T16:39:39.578Z",
        "type": "cat",
        "createdAt": "2018-01-15T21:20:00.003Z",
        "deleted": false,
        "used": true
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e008780aac31001185ed05",
        "user": "58e007480aac31001185ecef",
        "text": "Owning a cat can reduce the risk of stroke and heart attack by a third.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-03-29T20:20:03.844Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e009390aac31001185ed10",
        "user": "58e007480aac31001185ecef",
        "text": "Most cats are lactose intolerant, and milk can cause painful stomach cramps and diarrhea. It's best to forego the milk and just give your cat the standard: clean, cool drinking water.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-08-23T20:20:01.611Z",
        "type": "cat",
        "createdAt": "2018-03-04T21:20:02.979Z",
        "deleted": false,
        "used": false
    },
    {
        "status": {
            "verified": true,
            "sentCount": 1
        },
        "_id": "58e00af60aac31001185ed1d",
        "user": "58e007480aac31001185ecef",
        "text": "It was illegal to slay cats in ancient Egypt, in large part because they provided the great service of controlling the rat population.",
        "__v": 0,
        "source": "user",
        "updatedAt": "2020-09-16T20:20:04.164Z",
        "type": "cat",
        "createdAt": "2018-01-15T21:20:02.945Z",
        "deleted": false,
        "used": true
    }
]
```

- What status code did you get back?

>200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 1877

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ...
>The data we are getting back is a json object. We're obtaining data on the cats (cat facts) also when these cat facts were created, who they were created by(user/id), when the fact was updated, the status of the cat fact, and if the cat fact is still active and to make sure it can not be deleted.

- How could you use this data in an application? 
>We could use the data in this application to show the benefits of cats in the world we live in.
>Use the information to build a catgologue type of apps based on cat facts.
>Perhaps even just use this data as the data for our application.


I could imagine integrating this API into an app that ...
>App ideas: Cats & Health(using information from the data we obtained to illustrate how cats are helpful to humans and their wellbeing).

- What did you like about the documentation?

> The documentation was informative, something we had seen before and were comfortable with (arrays/objects)

- What did you find challenging about the documentation?

> I found the documentation challenging when it came to some of the keys in the data of objects we obtained that we had not seen before.

- Did the quality of the documentation impact your decision to use it?

> Yes because the first API we chose was simply just an image, therefore it isnt very useful as data for an application. Theerefore, we switched to an API that held more information.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes because the first API we chose was simply just an image, therefore it isnt very useful as data for an application. Therefore, we switched to an API that held more information.

- In your own words, summarize the request-response cycle.

> The request-response cycle is a client(computer) sends a request to a server, the server then uses that request to build its response with the requested information. Once built, the response is sent back to the client, to be rendered to the user.

- In your own words, describe what an API is.

> An API is a list of rules needed in order to interact with the data.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows a user to obtain data from an API or see if an API is worth using or usable at all(status code).
