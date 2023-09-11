#**League of Legends Summary Tracker using Riot Games API**

##**Riot Games Logo**

This project provides a League of Legends summary tracker using the Riot Games API. You can use this tool to retrieve various information about players, what the biggest factors are for their previous wins, and summary statistics on their gameplay.

##**Table of Contents**
Introduction
Prerequisites
Usage
API Key
Endpoints
Contributing
License
##**Introduction**
League of Legends is a popular online multiplayer game developed and published by Riot Games. The Riot Games API provides developers with access to various game data, including player stats, match history, and more. This project aims to create a League of Legends summary tracker using this API.

##**Prerequisites**
Before you begin, make sure you have the following prerequisites:

Python 3.x installed on your system.
Riot Games API Key: You need to sign up for a Riot Games API key to access the API.

Start the application as mentioned in the Getting Started section.

Open a web browser and navigate to http://localhost:5000.

Enter a summoner name and select the region you want to track.

Click the "Search" button to retrieve the summary information for the specified summoner.

##**API Key**
To access the Riot Games API, you need to obtain an API key. Follow these steps to get your API key:

Visit the Riot Games Developer Portal and sign in with your Riot Games account.

Create a new application and obtain an API key.

Store your API key in a secure manner and configure it in the config.py file in this project.

##**Endpoints**
This project currently supports the following API endpoints:

/summoner: Get summoner information by summoner name and region.
/champion-mastery: Get champion mastery information for a summoner by summoner ID.
/match-history: Get recent match history for a summoner by account ID.

##**Contributing**
Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please submit a pull request.

##**License**
This project is licensed under the MIT License - see the LICENSE file for details.
