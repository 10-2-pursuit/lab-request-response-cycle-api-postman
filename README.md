# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://meowfacts.herokuapp.com/ Meowfacts

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is education & fun.

- What is the URL of the documentation?

> https://app.swaggerhub.com/apis-docs/wh-iterabb-it/meowfacts/1.0.0 & https://rapidapi.com/wh-iterabb-it-wh-iterabb-it-default/api/meowfacts/ & https://meow-facts.netlify.app/

- What is the full URL of one endpoint?

> http://https://meowfacts.herokuapp.com/?blah=cat

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
  "data": {
    "fact": "Cats can rotate their ears 180 degrees."
  }
}

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: application/json; charset=utf-8

> `Content-Length`: 62

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is meow facts returns JSON that identifies the source of the meow fact, the meow fact, information about when the fact was created and updated, and the fact itself

- How could you use this data in an application?

> I could imagine integrating this API into an app that sells cat food and provides trivia when is purchased

- What did you like about the documentation?

> The documentation was straight forward, easy to read data.

- What did you find challenging about the documentation?

> I found the documentation challenging when its spread across 3 different sources

- Did the quality of the documentation impact your decision to use it?

> No because the API was straight forward

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I changed from OpenLibrary because it offered an overwhelming amount of APIs

- In your own words, summarize the request-response cycle.

> The request-response cycle pulls JSON upon refresh 

- In your own words, describe what an API is.

> An API is a way for 2 computers to talk to each other and exchange large amounts of data.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows user to test the functionality of APIs in various ways.
