🚀 Project Overview

This application allows multiple users to join a game as players or audience members, where they can:

Suggest prompts

Submit answers

Vote on the best responses

Track scores over multiple rounds

The project is divided into three main components:

Server: Built with NodeJS and deployed on Google App Engine. Handles WebSocket communication, state management, and integration with Azure functions.

Interactive Client: A VueJS-based frontend where users register, log in, and participate in the game.

Display Client: A spectator view that shows game progress and results (accessible at /display).

🧱 Tech Stack

NodeJS: WebSocket server and cloud deployment

VueJS: Client-side interactive interfaces

Socket.IO: Real-time communication

Azure Functions: Backend APIs for authentication and prompt storage

Google App Engine: Server deployment

🧩 Features

✅ Authentication

User registration and login using username and password

Players and audience members distinguished automatically

🧠 Game Flow

Joining phase: Players join until the host starts the game

Prompt submission: Players and audience submit creative prompts

Answering phase: Players answer prompts (each prompt shared between 2 players)

Voting phase: Audience and players (except the submitters) vote on answers

Scoring phase: Scores are tallied per round and cumulatively

Final leaderboard: Total scores displayed when the game ends

📺 Display Client

A dedicated display view for shared screens, showing:

Game status and instructions

Prompt and answer updates

Live voting results and final scores
