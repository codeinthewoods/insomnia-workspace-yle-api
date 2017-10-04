# Insomnia Workspace for YLE API

This is a ready-made Insomnia workspace for [YLE API](http://developer.yle.fi/api_docs.html).

## Installation

In case you do not have API keys yet, register yourself a YLE account and fetch the keys [here](https://tunnus.yle.fi/api-avaimet).

Once you have the keys, add them to your Insomnia environment as follows:

* appId: The application ID (as generated to you when registering)
* appKey: The application key (as generated to you when registering)

## Usage

After configuring the keys, everything should be set. Execute the queries from top to down, and everything should work out of box.

The YLE Endpoints have been configured with all available parameters, but only some of them have been activated. Please also note that some of the API calls are interlinked 
(the request parameters of an API link to responses of a previous API). Such cases should be easy to notice, as the failing linkages are painted in red.

## Notes

The interlinking between the API calls is done with [JSONPath](http://goessner.net/articles/JsonPath/) - a rich expression language for mining JSON datasets. This should 
also foreshorten in applying then in practice, as you already know what to pick into your UI from the responses.
