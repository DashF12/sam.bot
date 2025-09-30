
# sam.bot

Discord is a chatting social platform that allows users to interact with each other.
“sam.bot”
is an AI companion using Sarvam-M AI that allows users to directly prompt their questions in
the chatting platform removing time complexity and provides opportunities for creative implementation of its use-cases.

##### The code for this project is not published for safety concerns, if you wish to learn more, DM on linkedIn or Discord. You can, ofcourse, add the application in your discord server by following the link below.

## How to use?

Add the application or bot in your server -> [link](https://discord.com/api/oauth2/authorize?client_id=1316024749649952778&permissions=8&scope=bot%20applications.commands)
## Screenshots

![App Screenshot](https://github.com/DashF12/sam.bot/blob/main/assets/example_demo.png)


## API Reference

| From | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `Sarvam-M` | `Chat` | returns a string |

| From | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `Gemini`      | `GenImage` | returns a file(png) |

## Tech Stack

**Client:** Discord Interface

**Server:** AWS, NoSQL

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`Sarvam-M API` -> [Sarvam-M](https://dashboard.sarvam.ai/chat)

`Gemini API` -> [Gemini API](https://aistudio.google.com/app/)


## Roadmap

- Additional customization via an easy to access interface

- Implementation of Context to read chats before and after a prompt to give better responses

- Implementation of problem solving models such as a Claude Sonnet 4.5

## Authors

- [DashF12](https://www.github.com/DashF12)
