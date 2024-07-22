# AI Food & Travel Assistant 🍔 ✈️ 🤖
This project is a travel and food guide chatbot for Chicago, leveraging a Large Language Model (LLM) to process both text and image inputs. The system integrates with various tools to fetch real-time data, ensuring accurate and relevant recommendations. Current features include suggesting food and travel options based on user location and preferences. For example, a user can input, "I'm at 401 East, 32nd Street, Chicago. Give me burger places within 1200 metres," and receive relevant suggestions. Future features will include itinerary planning for both formal and impromptu occasions.

## Agentic Branch Description 🔍
The implementation follows the basic principles of a conversable agent modeling with tool use:
1. **Tool Creation** - The functions that are used to search for relevant places as per users' queries. 
2. **Agent Creation** - (1) User Proxy Agent: Intiates the chat and takes user input, (2) Travel Agent: An LLM-powered agent that suggests which tool to use and gives back the final output.
3. **Workflow** - The chat is initiated with the query. If there is more data required to complete the query, the travel agent prompts the user agent for the inputs. The travel agent generates the final response in natural language. A chat feature cap

## Technology Stack:
- Programming Language - Python
- Integration Framework - Autogen
- LLMs - OpenAI GPT-4o-mini

## Environment Setup 🛠️
The needed installation packages for the various libraries are in the requirements.txt file. Use the following command to install the requirements ```pip install -r ./requirements.txt```

## How to RUN 🕹️
1. Download the notebook file & the dotenv template locally in your project directory.
2. Fill in your API keys in the dotenv file using a text editor (such as Notepad).
3. Run the chat_result cell with the required query

## References 🙌
1. https://microsoft.github.io/autogen
2. https://github.com/areed1192/sigma_coding_youtube/blob/master/python/python-api/yelp-api/Yelp%20API%20-%20Business%20Search.py
