# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://swapi.dev/
Magic the Gathering Information

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is fun.

- What is the URL of the documentation?

> https://swapi.dev/documentation

- What is the full URL of one endpoint?

> https://swapi.dev/api/people/1

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json

{
    "name": "Luke Skywalker",
    "height": "172",
    "mass": "77",
    "hair_color": "blond",
    "skin_color": "fair",
    "eye_color": "blue",
    "birth_year": "19BBY",
    "gender": "male",
    "homeworld": "https://swapi.dev/api/planets/1/",
    "films": [
        "https://swapi.dev/api/films/1/",
        "https://swapi.dev/api/films/2/",
        "https://swapi.dev/api/films/3/",
        "https://swapi.dev/api/films/6/"
    ],
    "species": [],
    "vehicles": [
        "https://swapi.dev/api/vehicles/14/",
        "https://swapi.dev/api/vehicles/30/"
    ],
    "starships": [
        "https://swapi.dev/api/starships/12/",
        "https://swapi.dev/api/starships/22/"
    ],
    "created": "2014-12-09T13:50:51.644000Z",
    "edited": "2014-12-20T21:17:56.891000Z",
    "url": "https://swapi.dev/api/people/1/"
}
```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` apllication/json

> `Content-Length` 974Bytes

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ... probably the links for the related data.

- How could you use this data in an application?

> I could imagine integrating this API into an app that ... an encyclopedia for the starwars fans.  

- What did you like about the documentation?

> The documentation was ... good for giving some easy examples to pull data.

- What did you find challenging about the documentation?

> I found the documentation ... has really slow response to pull the information.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...yes, b/c some other APIs does not give enough info to pull data.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up ... Yes, my parter's and my initial choice was The Magic the Gethering API, but had bunch of 403 errors so, we choose to change the api.

- In your own words, summarize the request-response cycle.

> The request-response cycle ... asking the server for specific info by sending a query through HTTP request. If the server says ok (by 200 status code), sendback the info by HTTP response.

- In your own words, describe what an API is.

> An API is ... a layer to ask to pull database from the server.

- In your own words, describe the purpose of Postman.

> Postman is an application that ... sneaking packets to analyze
