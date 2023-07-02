# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> http://www.randomfox.ca/  RandomFox

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is for information. It seeks to users input a link to a picture of a fox and in turn returns a random f0x picture with every click.

- What is the URL of the documentation?

> https://github.com/xinitrc-dev/randomfox.ca

- What is the full URL of one endpoint?

> www.randomfox.ca/floof
- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "image": "https://randomfox.ca/images/19.jpg",
    "link": "https://randomfox.ca/?i=19"
}

```

- What status code did you get back?

> 200 ok

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`
application/JSON
> `Content-Length`
0
- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is available to the public. There is an html link for those who want to send a link of pictures of foxes and email in a picture of a fox. The information of the person making the addition is saved on a server on discord while the actual pictures and their addition timestamps is accessible on github.

- How could you use this data in an application?

> I could imagine integrating this API into an app that are for feline lovers, maybe one that shows random foxes or felines as a screensaver or one that shows the different species of foxes and the locations they frequent.

- What did you like about the documentation?

I liked that it was public access information. Also it had very clear names to make the need for a description obsolete and its representation as a JSON file nto only makes it easily understood but easily transferable into various forms so that various data manipulation programs can make use of it.
- What did you find challenging about the documentation?

> I found the documentation in full to the most accessible only because it is spread over different domains ir github, discord and a personal website.

- Did the quality of the documentation impact your decision to use it?

> Yes/No because the quality was top notch.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up with the one I initially chose because I stuck with it.

- In your own words, summarize the request-response cycle.

> The request-response cycle starts with a http request sent from a website. The request is received by the server which then runs a program to decipher the request and another to compile a response that contains the requested information. At http response is then sent by the server and recieved by the html client that requested it.

- In your own words, describe what an API is.

> An API is the mechanism involved in actualizing the communication between two or more computers or rather their programs.  Applications are programs that carry out specific tasks and by a means of requests and responses are able to do this with the use of other computers with other apps that aide in the completion of these tasks.

- In your own words, describe the purpose of Postman.

Postman tests apis and their ability to create, update, read and delete data the api works with and the speed with which they do so.