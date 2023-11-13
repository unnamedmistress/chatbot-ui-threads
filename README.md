# Chatbot UI with Threads/GPT Assistant
## News
This is a early implimentation to use threads in a simple chatbot UI. Use your custom 'assistant' outside of OpenAI by using this. Requires an API key and an Assistant ID.  You will need to create your assistant inside the GPT playground to get the Id you need. 

## About

Chatbot UI is an open source chat UI for AI models.

See a [demo](https://twitter.com/mckaywrigley/status/1640380021423603713?s=46&t=AowqkodyK6B4JccSOxSPew).

![Chatbot UI](./public/screenshots/screenshot-0402023.jpg)

## Updates

Chatbot UI will be updated over time.

Expect frequent improvements.

**Next up:**

- [ ] Sharing
- [ ] "Bots"

## Deploy

**Docker**

Build locally:

```shell
docker build -t chatgpt-ui .
docker run -e OPENAI_API_KEY=xxxxxxxx -p 3000:3000 chatgpt-ui

docker run -e OPENAI_API_KEY=xxxxxxxx -p 3000:3000 ghcr.io/mckaywrigley/chatbot-ui:main
Running Locally
1. Clone Repo


git clone https://github.com/mckaywrigley/chatbot-ui.git
2. Install Dependencies


npm i
3. Provide OpenAI API Key and Assistant ID

Create a .env.local file in the root of the repo and include your OpenAI API Key and Assistant ID:

OPENAI_API_KEY=YOUR_KEY
ASSISTANT_ID=YOUR_ASSISTANT_ID
Make sure to replace YOUR_KEY with your actual OpenAI API Key and YOUR_ASSISTANT_ID with the ID of your Assistant. This fork of Chat-UI with threads (Custom GPT Assistant) is built so you can use your bot directly outside of OpenAI.

You can set OPENAI_API_HOST where access to the official OpenAI host is restricted or unavailable, allowing users to configure an alternative host for their specific needs.

Additionally, if you have multiple OpenAI Organizations, you can set OPENAI_ORGANIZATION to specify one.

4. Run App


npm run dev
5. Use It

You should be able to start chatting.

Configuration

If you do not provide an OpenAI API key and Assistant ID with OPENAI_API_KEY and ASSISTANT_ID, users will have to provide their own key.

If you don't have an OpenAI API key or an Assistant, you can get them at OpenAI.

Contact
If you have any questions, feel free to reach out to Mckay on Twitter.


This addition includes instructions for users on how to add both the OpenAI API Key 