# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> [Animechan]http://localhost:8000/api/comments/6397736a3a914c87e029c0f6

- What purpose is this API for (education/fun and games/information/etc.)?

 The purpose of this API is to provide anime quotes.

- What is the URL of the documentation?

> https://github.com/RocktimSaikia/anime-chan

- What is the full URL of one endpoint?

> https://animechan.vercel.app/api/random

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```
{
  "anime": "One Piece",
  "character": "Tony Tony Chopper",
  "quote": "I'm sorry! I'm sorry! I'm sorry I was born!"
}


```

- What status code did you get back?

 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

Content-Type: application/json; charset=utf-8

Content-Length: 23

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

 The summary of the data is the name of the anime, the name of a character who said the quote and the actual quote.

- How could you use this data in an application?

Produce random anime quotes or create a collection of favorite quotes.

- What did you like about the documentation?

 The documentation gave clear instructions on how to use the api. There were adequate examples to understand how to make a request.

- What did you find challenging about the documentation?

I did not find any significant issues with the documentation.

- Did the quality of the documentation impact your decision to use it?

No, I choose it for my affinity for anime and it fell in the search parameters.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

Yes I switched, the initial the url was giving me errors about public downloads and forking the data. It was very unclear how to proceed.

- In your own words, summarize the request-response cycle.

The request-response cycle is the communication between a client and a server.
 First, the client sends a request to the server, asking for a specific action or resource. Second, the server processes the request and generates a response, which is sent back to the client. Finally, the client receives the response and can then translate and use the data.

- In your own words, describe what an API is.

An API (Application Programming Interface) is a set of rules and protocols that allows different software applications to communicate and interact with each other.

- In your own words, describe the purpose of Postman.

 Postman is an application that allows developers to make HTTP requests to APIs and receive responses, making it easier to experiment with different endpoints, parameters, and headers. Postman provides a friendly UI that can make request inspect responses and organize workflows.
