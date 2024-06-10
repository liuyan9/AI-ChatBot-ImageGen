# AI-ChatBot-ImageGen Web App

[App hosted on fly.io](https://nolimitgpt.fly.dev/)

## Introduction

The AI-ChatBot-ImageGen web app is a straightforward and extensible SAAS web app template designed for developers who are taking a stab at creating AI-based web apps. Taking advantage of cutting-edge technologies such as OpenAI, MongoDB, and Stripe, the project aims to simplify the process of SAAS web app development.

## Features

- Node.js, Express, and EJS for web app framework
- Utilizes the OpenAI API for AI-centric text interactions and image generation
- Stripe integrated for subscription management
- Google OAuth provisioned for user authentication
- MongoDB for addressing user administration
- Responsive front-end facilitated by Webflow CSS and JavaScript

## Getting Started

To get the project up and running locally, follow these instructions:

1. Clone the repository from GitHub.
2. Ensure Node.js and npm (Node Package Manager) are installed. If not, please install.
3. Navigate to the project directory and run `npm install` to install the necessary dependencies.
4. Rename the `example.env` file to `.env` and replace the placeholders with your specific keys and credentials. To obtain the required API keys, follow the instructions below:
 - For the OpenAI API key, create an account at [OpenAI](https://beta.openai.com/signup/) and adhere to their instructions to generate an API key.
   - For the Stripe secret key, set up an account at [Stripe](https://dashboard.stripe.com/register) and head over to the API section in the dashboard to fetch your secret key. Set up three monthly subscription plans in Stripe and note their price IDs. Don't forget to get your Stripe public key.
   - To get the Google Client ID and Google Client Secret, access [Google Developers Console](https://console.developers.google.com/), create a new project, enable the necessary Google APIs (such as Google+ API, Google OAuth2 API) and create an OAuth 2.0 client ID. You'll be provided with the client ID and secret.
   - For the MongoDB URI, create an account at [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/regist