# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

Free Forex API
> http://www.freeforexapi.com

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is providing real-time foreign exchange rates for the major currency pairs. No more, no less.

- What is the URL of the documentation?

> https://freeforexapi.com/Home/Api

- What is the full URL of one endpoint?

> https://www.freeforexapi.com/api/live

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{"message":"'pairs' parameter is
required","supportedPairs":["AUDUSD","EURGBP","EURUSD","GBPUSD","NZDUSD","USDAED","USDAFN","USDALL","USDAMD","USDANG","USDAOA","USDARS","USDATS","USDAUD","USDAWG","USDAZM","USDAZN","USDBAM","USDBBD","USDBDT","USDBEF","USDBGN","USDBHD","USDBIF","USDBMD","USDBND","USDBOB","USDBRL","USDBSD","USDBTN","USDBWP","USDBYN","USDBYR","USDBZD","USDCAD","USDCDF","USDCHF","USDCLP","USDCNH","USDCNY","USDCOP","USDCRC","USDCUC","USDCUP","USDCVE","USDCYP","USDCZK","USDDEM","USDDJF","USDDKK","USDDOP","USDDZD","USDEEK","USDEGP","USDERN","USDESP","USDETB","USDEUR","USDFIM","USDFJD","USDFKP","USDFRF","USDGBP","USDGEL","USDGGP","USDGHC","USDGHS","USDGIP","USDGMD","USDGNF","USDGRD","USDGTQ","USDGYD","USDHKD","USDHNL","USDHRK","USDHTG","USDHUF","USDIDR","USDIEP","USDILS","USDIMP","USDINR","USDIQD","USDIRR","USDISK","USDITL","USDJEP","USDJMD","USDJOD","USDJPY","USDKES","USDKGS","USDKHR","USDKMF","USDKPW","USDKRW","USDKWD","USDKYD","USDKZT","USDLAK","USDLBP","USDLKR","USDLRD","USDLSL","USDLTL","USDLUF","USDLVL","USDLYD","USDMAD","USDMDL","USDMGA","USDMGF","USDMKD","USDMMK","USDMNT","USDMOP","USDMRO","USDMRU","USDMTL","USDMUR","USDMVR","USDMWK","USDMXN","USDMYR","USDMZM","USDMZN","USDNAD","USDNGN","USDNIO","USDNLG","USDNOK","USDNPR","USDNZD","USDOMR","USDPAB","USDPEN","USDPGK","USDPHP","USDPKR","USDPLN","USDPTE","USDPYG","USDQAR","USDROL","USDRON","USDRSD","USDRUB","USDRWF","USDSAR","USDSBD","USDSCR","USDSDD","USDSDG","USDSEK","USDSGD","USDSHP","USDSIT","USDSKK","USDSLL","USDSOS","USDSPL","USDSRD","USDSRG","USDSTD","USDSTN","USDSVC","USDSYP","USDSZL","USDTHB","USDTJS","USDTMM","USDTMT","USDTND","USDTOP","USDTRL","USDTRY","USDTTD","USDTVD","USDTWD","USDTZS","USDUAH","USDUGX","USDUSD","USDUYU","USDUZS","USDVAL","USDVEB","USDVEF","USDVES","USDVND","USDVUV","USDWST","USDXAF","USDXAG","USDXAU","USDXBT","USDXCD","USDXDR","USDXOF","USDXPD","USDXPF","USDXPT","USDYER","USDZAR","USDZMK","USDZMW","USDZWD"],"code":1001}

```

- What status code did you get back?

> 1001

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`(text/html; charset=UTF-8)

> `Content-Length`(not applicable to current api, The Content-Length header indicates the size of the message body, in bytes, sent to the recipient. Doesn't show on Postman for this.)

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is ...
    the forex api returns back the names of all supported pairs parameters in the foreign exchange market.

- How could you use this data in an application?
    You can use this data for creating an exchange website for banks and/or firms alike.

> I could imagine integrating this API into an app that ...
    creates a foreign currency market exhange rate based on the pairs fed into the exchange.

- What did you like about the documentation?

> The documentation was ...
    clear, consice, and simple. The Free Forex API is a simple REST API providing real-time foreign exchange rates for the major currency pairs. No more, no less. And then it shows you how the code shows up with the exchange rate of different pairs.

- What did you find challenging about the documentation?

> I found the documentation ...
    not enough information on how or where to trade pairs.

- Did the quality of the documentation impact your decision to use it?

> No because... it is pretty simple and fairly easy to understand since it only has very basic information output.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up ...staying with the api because it didn't seem to cause any issues and I know a bit about finance so it made it easier to see the full picture clearer on what it would be used for.
    
- In your own words, summarize the request-response cycle.

> The request-response cycle ...when the first computer or person operating it sends a request to another computer on a network and the second user responds to the recognized request.

- In your own words, describe what an API is.

> An API is ...a code of software that allows communication between two, or maybe even more, desired participating parties.

- In your own words, describe the purpose of Postman.

> Postman is an application that ...an platform for apis that builds and uses them for websites in html, or other applications.
