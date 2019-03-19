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

1. [Text Anaalysis API](https://english.api.rakuten.net/aylien/api/text-analysis) 

	Update the API key in index.js in line 26 & 33 

2. [Translation API](https://english.api.rakuten.net/hongson890/api/translate-api)

	Update the API key in index.js in line 39 & 47	

## Execution

To run the app

    node index.js

Open your browser and point to http://localhost:3000 to launch the app.