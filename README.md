# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API that has no auth and no CORS from the following list: [public APIs](https://github.com/public-apis/public-apis)
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.

## Instructions

Do your best to answer the questions with specific details when required fully. Writing about code clearly and thoroughly is a critical skill to practice. 

- Which one did you choose? Provide the name and base URL

> http://developers.steem.io STEEM

- What purpose is this API for (education/fun and games/information/etc.)?

> The purpose of this API is Blockchain-based blogging and social media website

- What is the URL of the documentation?

> http://developers.steem.io/quickstart/#quickstart-choose-library

- What is the full URL of one endpoint?

> http://steemit.com/@curie.json

- What is a sample of the data from the endpoint (copy and paste results from Postman, ok to shorten if it’s over 100 lines)? Be sure to wrap your answer in the correct formatting for code/JSON.

```json
{
    "user": {
        "id": 81544,
        "name": "curie",
        "owner": {
            "weight_threshold": 1,
            "account_auths": [],
            "key_auths": [
                [
                    "STM69WGR1yhUdKrnzwQLDPnXrW9kaAERwHze8Uvtw2ecgRqCEjWxT",
                    1
                ]
            ]
        },
        "active": {
            "weight_threshold": 1,
            "account_auths": [],
            "key_auths": [
                [
                    "STM5GAbbS84ViMEouJL3LKcM8VZzPejn68AfPaYaLZZDdmy98kwU5",
                    1
                ]
            ]
        },
        "posting": {
            "weight_threshold": 1,
            "account_auths": [
                [
                    "buildteam",
                    1
                ],
                [
                    "busy.app",
                    1
                ],
                [
                    "dpoll.xyz",
                    1
                ],
                [
                    "steemauto",
                    1
                ],
                [
                    "steempeak.app",
                    1
                ]
            ],
            "key_auths": [
                [
                    "STM5cmuKw6EPkZWeVNXcZorKtattZTX5wSopcRb4xNe6VhRKjETgv",
                    1
                ]
            ]
        },
        "memo_key": "STM7ZBi61xYz1b9STE1PHcAraPXJbvafzge3AcPjcfeq4XkKtM2At",
        "json_metadata": {
            "profile": {
                "profile_image": "https://i.imgur.com/Mjewc66.jpg",
                "name": "Curie",
                "about": "Discovering exceptional content. ",
                "location": "Worldwide",
                "website": "http://curiesteem.com",
                "trail": "true",
                "trail_threshold": "20"
            }
        },
        "posting_json_metadata": "{\"profile\":{\"profile_image\":\"https://i.imgur.com/Mjewc66.jpg\",\"name\":\"Curie\",\"about\":\"Discovering exceptional content. \",\"location\":\"Worldwide\",\"website\":\"http://curiesteem.com\",\"trail\":\"true\",\"trail_threshold\":\"20\"}}",
        "proxy": "",
        "last_owner_update": "1970-01-01T00:00:00",
        "last_account_update": "2020-03-26T14:05:48",
        "created": "2016-09-02T10:44:24",
        "mined": false,
        "recovery_account": "anonsteem",
        "last_account_recovery": "1970-01-01T00:00:00",
        "reset_account": "null",
        "comment_count": 0,
        "lifetime_vote_count": 0,
        "post_count": 9518,
        "can_vote": true,
        "voting_manabar": {
            "current_mana": "4382095255775",
            "last_update_time": 1678579659
        },
        "downvote_manabar": {
            "current_mana": "1095523813944",
            "last_update_time": 1678579659
        },
    }
}

```

- What status code did you get back?

> 200 OK

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type` application/json; charset=utf-8

> `Content-Length` 139

- Summarize the most salient parts of the data you are getting back (for example, Cat facts returns JSON that identifies the source of the cat fact, the cat fact, information about when the fact was created and updated, and the fact itself).

> The summary of the data is getting a particular user profile.

- How could you use this data in an application?

> I could imagine integrating this API into an app that works with criptocurrency.

- What did you like about the documentation?

> The documentation was clear in describing how we should use the link to specifically target user profile or any other specific data.

- What did you find challenging about the documentation?

> I found the documentation a littler bit difficult to read because the structure.

- Did the quality of the documentation impact your decision to use it?

> No because we continued on after we read through we found exacly what we need it to target the endpoint.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

>No I ended up staying with my first choice.

- In your own words, summarize the request-response cycle.

> The request-response cycle  refers to the interaction between a client and server in a networked system such as a web application.

- In your own words, describe what an API is.

> An API is Application Programing Interface it is a set of rule needed to interact .

- In your own words, describe the purpose of Postman.

> Postman is an application that allows user to request, desing ,test, document and share API.
