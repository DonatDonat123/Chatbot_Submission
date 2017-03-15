# Chatbot_Submission

LASTMINUTE HELPER

Description: Lastminute Helper is a Telegram-Chatbot that helps to pick a destination for a city trip. Why don't you try it out and add him on Telegram under "GeoMaster" and have a chat ? In the state of submission it comprises the following functions:

	- Introduction of it's function by entering "/start"
	- Basic rule-based chit-chat
	- Giving more information (weather and distance(in time)) about 1 city.
	- Comparing 2 cities by either weather or distance
	- Giving a blindshot suggestion to the user, covered by weather info
	- Setting the origin (departure)
	

Methods: Live Weather data is received by the openweathermap.org API and Distance Matrix via Google Maps API.
	If the user is entering just chit-chat or important keywords like cities is analyzed by Spacy Tokenization
	
Outlook: Within the scope of the project the Chat-bot has different limitations: Firstly he is feeded by only 2APIs, it would be beneficial to have more data like famous attractions and activities per destination. Secondly the processing of Input, for instance comparing 2 cities by weather is rather simple. In later versions we want to give weights to the e.g different weather parameters and also let the user decide on a continous scale what's most important for him.
