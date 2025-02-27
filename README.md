# Chatbot Web Application

This project contains a basic web application that uses web sockets to connect/communicate users to each other. A user must enter there username on entry and then will be placed into the chatbox space.

The user can then send messages to other users connected to the server (locally) for now because reasons explained later.

It also allows a user to query and receive a response from chatGPT.

## How this program works:

This program works by using web sockets to maintain connections and persist data. Functions execute "methods" on the socket and allow all people connect to the socket to receive data seemlessly.

Based on whether the response omitted is from a user or from the chat bot, an object property is set to true, which when rendering the HTML, provides a class to make ChatGPT text purple.

## Getting this to work locally

I believe it should be as simple as going to the following [repository link](https://github.com/Pela-A/WebApp)

1. Download the Zip file by clicking blue Code button and **Download Zip**

2. Unzip the files, and load in VS Code

3. Open a Terminal and run the command **npx nodemon** or **node app.js**

    1. Please note you may need to install dependencies including node, and nodemon.

4. Visit the following URL: [localhost](http://localhost:3000/)

See the following example below to query the chat bot. starting with @bot provides chatGPT response.

## Example Query to chat:

'''
@bot write me a recipe for chocolate chip cookies
'''

## Troubleshooting/extras

I attempted to upload this to Vercel however I ran into the following issue. Vercel actually does not support Web Sockets due to Vercel being a "serverless environment".

I had to pay for access to OpenAI's API. I don't really mind it was five dollars. If for some reason other people need a key I don't mind sharing mine but I will disable the key at the very end of this term.

Cool project overall pretty simple.




