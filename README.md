# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> https://openwhyd.github.io/openwhyd/API

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is free and open-source music curation service that allows users to create playlists of music tracks from various streaming platforms

- What is the URL of the documentation?

> https://openwhyd.github.io/openwhyd/API

- What is the full URL of one endpoint?

> https://openwhyd.org/adrien/playlist/61

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
<!DOCTYPE html>
<html lang="en">
  <head prefix="og: http://ogp.me/ns# fb: http://ogp.me/ns/fb# whydapp: http://ogp.me/ns/fb/whydapp#">
    <meta charset="utf-8" />
<meta name="google-site-verification" content="mmqzgEU1bjTfJ__nW6zioi7O9vuur1SyYfW44DH6ozg" />
<meta name="apple-itunes-app" content="app-id=874380201, app-argument=whyd://app?href=http://openwhyd.org/u/4d94501d1f78ac091dbc9b4d/playlist/61">
<link rel="image_src" href="https://openwhyd.org/img/playlist/4d94501d1f78ac091dbc9b4d_61"/>
<meta name="description" content="Discover and collect music gems from Youtube, Soundcloud, Deezer and more" />
<meta name="keywords" content="discover, music, curation, streaming, tracks, youtube, soundcloud, bandcamp, playlists, play, free" />
<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@open_whyd" />
<meta property="og:image" content="https://openwhyd.org/img/playlist/4d94501d1f78ac091dbc9b4d_61" />
<meta property="og:description" content="Discover and collect music gems from Youtube, Soundcloud, Deezer and more" />
<meta property="fb:app_id" content="169250156435902" />
<meta property="fb:admins" content="510739408" />
<meta property="og:type" content="website" />
<meta property="og:title" content="🎺 Jazz meets World by Adrien Joly" />
<meta property="og:url" content="https://openwhyd.org/u/4d94501d1f78ac091dbc9b4d/playlist/61" />
    <link href="/favicon.ico" rel="shortcut icon" type="image/x-icon" />
    <link href="/favicon.png" rel="icon" type="image/png" />
    <link href=' //fonts.googleapis.com/css?family=Varela+Round' rel='stylesheet' type='text/css'>
    <link href=' //fonts.googleapis.com/css?family=Varela' rel='stylesheet' type='text/css'>
    <link rel="search" type="application/opensearchdescription+xml" title="Whyd" href="https://openwhyd.org/html/opensearch.xml">
    <link rel="chrome-webstore-item" href="https://chrome.google.com/webstore/detail/foohaghobcolamikniehcnnijdjehfjk">

> 
```

- What status code did you get back?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`

> `Content-Length`

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is customizing playlists 

- How could you use this data in an application?

> I could imagine integrating this API into an app that if I was promoting a website that can be used for people who need help creating their own playlist

- What did you like about the documentation?

> The documentation was 

- What did you find challenging about the documentation?

> I found the documentation ...

- Did the quality of the documentation impact your decision to use it?

> Yes/No because...

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes/No I ended up choosing the same one 

- In your own words, summarize the request-response cycle.

> The request-response cycle is that you make a request and get a response

- In your own words, describe what an API is.

> An API is the middle man between requests and respones 

- In your own words, describe the purpose of Postman.

> Postman is an application that lets you know if your endpoint works and you are able to troubleshoot, fix it so that you are able to use the functionality in your website 
