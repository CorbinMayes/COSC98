# Dartmouth Watson Advisor

## Files

- DartmouthAdvisorCSS.css
- DartmouthAdvisorWebpage.html
- skill-Advisor-Skill.json
- AssistantImage.png

## Build

To run this project, open the html file in google chrome. It will open as a website and from there you will be able to interact with the 
Dartmouth Watson Advisor.

## Project

This project simply implements Watson's chatbot feature. I trained it to recognize keywords related to Dartmouth features like say "What is an NRO?" and it will tell you what it is and how it works. The skill-advisor-Skill.json is the json file that shows the examples used to train Watson on certain intents so that it can make out the purpose of each question asked to it as well as synonyms and entities and also contains its responses. The html and css files build a simple webpage that can show as an example for how the chatbot can be dropped onto. 

## Testing

To test this just open the .html file in chrome and click on the green chat button in the bottom right corner. It will pop up a chat function that you can type your questions into.
Examples: "What is an NRO?" "Who is my dean?" "How does the meal plan work?" 
Themes can be picked from the intents in the .json if you wish to know what options are available for questions.