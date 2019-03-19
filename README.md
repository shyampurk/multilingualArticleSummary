# Multilingual Article Summary Generator

An app to generate summary text from webpages

This app is based on 

* [node.js](https://nodejs.org/en/) - The Javascript Runtime
* [Express](https://expressjs.com/) - fast node.js network app framework

## Installation

Download the code and run the command from root directory.

    npm install
    
This will install all dependencies

## Configuration

Update the API keys in the code with your keys obtained from [Rakuten website](https://english.api.rakuten.net) for the following APIs

1. [Text Analysis API](https://english.api.rakuten.net/aylien/api/text-analysis) 

2. [Translation API](https://english.api.rakuten.net/hongson890/api/translate-api)

You MUST update the API key in [index.js](/index.js#L14) . Look for <RAKUTEN_API_KEY> and replace with your API key.

## Execution

To run the app

    node index.js

Open your browser and point to http://localhost:3000 to launch the app.
