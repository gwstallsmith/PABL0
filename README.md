# Discord Chat Analysis Bot

This repository contains code for a Discord chat analysis bot developed for Kent Hack Enough 2024 hackathon. The bot utilizes web scraping and machine learning sentiment analysis techniques to analyze users' messages on Discord servers.

## Features

- Analyzes users' messages on Discord servers.
- Utilizes web scraping to gather data from Discord.
- Implements a machine learning sentiment analysis model based on Naive Bayes algorithm.
- Provides analysis results categorizing messages into positive, neutral, or negative sentiment.

## How it Works

1. **Data Collection**: The bot collects messages from Discord servers using web scraping techniques.
2. **Sentiment Analysis**: It employs a Naive Bayes model trained on a dataset of 25000 social media messages to analyze the sentiment of each message.
3. **Result Generation**: After analysis, the bot categorizes messages as positive, neutral, or negative and provides the user with the count of each sentiment category.

## Requirements

- Python 3.x
- Discord API
- BeautifulSoup (for web scraping)
- NLTK (Natural Language Toolkit) for sentiment analysis

# Elysia with Bun runtime

## Getting Started
To get started with this template, simply paste this command into your terminal:
```bash
bun create elysia ./elysia-example
```

## Development
To start the development server run:
```bash
bun run dev
```

Open http://localhost:3000/ with your browser to see the result.

## Usage

- Invite PABL0 to your discord server via the web interface.
- Once PABL0 has joined, use the command */init*
- /init will scrape and analyze the content of the text channel.
- Once analyzed, navigate to the web interface to view the results.
