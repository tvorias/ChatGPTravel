# ChatGPTravel

## SI 568 Mini Project
### Use Case
This program utilizes the OpenAI API to provide tailored travel recommendations to users based on their preferences, including recommended destinations, hotels, restaurants, and activities. As a replacement to travel agents or hours spent combing the internet, ChatGPTravel offers customized recommendations quickly and at no cost. Upon receiving their recommendations, users can save the results to a file. 

## Set up
### Dependencies
- `Python3`
- `OpenAI API key` (which is imported from a file called 'apikeys.py')
  - Though we provide the API key, instructions for generating your own API key can be found [here](https://platform.openai.com/account/api-keys).\
  :exclamation: For the purposes of submitting this project, we provide the API key. However, the API key is private and should not be published, shared, or used outside of testing this submission. Use of our private key is not authorized outside of the 568 teaching team. 
 ### Installations
 `pip install openai`
 
 ## Running the program
 - First, you will need to download the `main.py` and `apikeys.py` files and store them in the same location because the program is dependent on imports from the apikey.py file. Next, ensure the openai package is installed by running the pip install.
 - From there, run`main.py`. You will be prompted to respond to a set of questions in the command line. These questions will help the program return a set of recommendations that are based on user specifications. 
 - Once you have gone through all of the questions, the program will ask you if you would like to save the recommendations. If you choose to have your recommendations saved, the information will be stored in a file called `TripInfo.txt`. The file will be saved to the same location as the other two files. 
 - If you choose to exit the program, the program can be started again by re-running the `main.py` file. 
