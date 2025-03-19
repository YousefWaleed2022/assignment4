# assignment4  
# assignment4  
**Conversational Assistant with Weather and Calculator Tools**

## Overview  
This project demonstrates a Python-powered assistant that can retrieve real-time weather data, perform mathematical calculations, and mimic web search functionality. By integrating external APIs for weather information and employing reasoning strategies, it delivers context-aware and informative responses.

## Features  
- Fetch current weather data for a specified location  
- Retrieve weather forecasts for upcoming days  
- Perform mathematical calculations  
- Simulate web searches for general knowledge  

## Setup Instructions  

### Prerequisites  
Make sure you have:  
- Python 3.x  
- pip (Python package manager)

### Step 1: Clone the Repository  
git clone https://github.com/YousefWaleed2022/assignment4.git  
cd assignment4  

### Step 2: Install Dependencies  
pip install -r requirements.txt  

Make sure requirements.txt includes:  
requests  
dotenv  
openai  

### Step 3: Set Up Environment Variables  
Create a .env file in the project directory and add the following lines:  
API_KEY=your_openai_api_key  
WEATHER_API_KEY=your_weather_api_key  
BASE_URL=https://api.openai.com/v1  
LLM_MODEL=gpt-4  

Replace your_openai_api_key and your_weather_api_key with valid API keys.

### Step 4: Run the Application  
python conversational_agent.py  

## Usage  
You can call functions within the script as follows:  

print(get_current_weather("New York"))  
print(get_weather_forecast("London", days=5))  
print(calculator("5 + 3 * 2"))  
print(web_search("climate change"))  

## License  
This project is intended for educational purposes only.
