# ChatGPTravel

## SI 568 Mini Project
### Use Case
This program utilizes the OpenAI API to provide tailored travel recommendations to users based on their preferences, including recommended destinations, hotels, restaurants, and activities. As a replacement to travel agents or hours spent combing the internet, ChatGPTravel offers customized recommendations quickly and at no cost. Upon receiving their recommendations, users can save the results to a file. ChatGPTravel accomodates both those with destinations in mind and those who are interested in learning about places to explore. If you already know where you want to go, ChatGPTravel is a great tool for learning more about things to do and places to see near your destination. If you don't have a destination in mind, ChatGPTravel is the perfect resource for providing recommendations for destinations based on your preferences.

## Set up
### Dependencies
- `Python3`
- OpenAI API key and organization code
  - You will need to generate your own API key from OpenAI. Instructions for generating your own API key can be found [here](https://platform.openai.com/account/api-keys).

 ### Installations
 `pip install openai`
 
 ## Running the program
 - First, you will need to download the `main.py` file. Next, ensure the openai package is installed by running the pip install.
 - Then you will need to replace apiInfo['ORGANIZATION'] with your organization code and apiInfo['APIKEY'] with your personal API key. 
 - From there, run`main.py`. You will be prompted to respond to a set of questions in the command line. These questions will help the program return a set of recommendations that are based on user specifications. 
 - Once you have gone through all of the questions, the program will ask you if you would like to save the recommendations. If you choose to have your recommendations saved, the information will be stored in a file called `TripInfo.txt`. The file will be saved to the same location as your `main.py` file. 
 - If you choose to exit the program, the program can be started again by re-running the `main.py` file.

## Disclaimer
While ChatGPT is a powerful tool, recommendations are sourced from a natural language processing tool driven by AI technology. The tool can only work as well as the quality of the prompts it receives. This means that the more concise and clear the user's responses are, the better the tool will work. Please use the information provided at your own risk as some of the information provided may be inaccurate or out of date. 
