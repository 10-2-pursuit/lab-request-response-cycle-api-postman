# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://picsum.photos/ and the website name is Lorem Picsum: The Lorem Ipsum for photos.

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for providing instructions and examples for using the Lorem Picsum service to generate placeholder images with various customization options.

- What is the URL of the documentation?

> https://winter-sunset-625862.postman.co/workspace/Post-Lab~7df7342c-75b9-4152-a2ff-a93fe64fdcb8/documentation/28288658-dd349ec7-2aad-476f-8399-6c3912cba0d4 (we were unable to get any documentation from the api)

- What is the full URL of one endpoint?

> https:\/\/a.nel.cloudflare.com\/report\/v3?s=rlR%2FTFGqgn94sjmbRm7sU5dK7ysFKgk3iytL1S7nnr99Ti3RJjwUm2E4jbIPhZyAvWOIl0%2BBjLECCsCi7pxZt8NF2GIr39%2BIDyGKFBOWAar6lmCc78QZyDfN5KB29kw%3D

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
        "id": "0",
        "author": "Alejandro Escamilla",
        "width": 5000,
        "height": 3333,
        "url": "https://unsplash.com/photos/yC-Yzbqy7PY",
        "download_url": "https://picsum.photos/id/0/5000/3333"
 }

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json

> `Content-Length` There is no content-length.

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is that in overall, this HTML document represents a webpage that provides instructions and examples for using the Lorem Picsum service to generate placeholder images with various customization options.

- How could you use this data in an application?

> I could imagine integrating this API into an app that create random photo for start-up websites that need a placeholder for visualization purposes.

- What did you like about the documentation?

> The documentation set-up of how the information was presented was understandable.

- What did you find challenging about the documentation?

> Finding the location of the documentation and understanding the information that it represents.

- Did the quality of the documentation impact your decision to use it?

> Yes.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes, we initially switched from https://imsea.herokuapp.com/ because there was essentially nothing built to the website.
- In your own words, summarize the request-response cycle.

> The request-response cycle is when your browser request inforamtion from the server which the server send back the needed information. Then once that information is filled out it is sent back to the server which is used as parameters to retrieve information from the database. To be sent back to the your browser.

- In your own words, describe what an API is.

> An API is required rules that are needed to gain access to data.

- In your own words, describe the purpose of Postman.

> Postman is an application that allow use to make request for data from server without build a front-end.