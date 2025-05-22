# Social Media Content Generator

Generates social media content based on YouTube video transcripts using OpenAI's GPT Agent SDK

Features

Extract transcripts from YouTube videos using the video ID
Generate content for multiple social media platforms (LinkedIn, Instagram, Twitter)
Customize your content generation query
Download generated content for each platform


Installation steps

Clone this repository:

git clone https://github.com/arcinsights-io/Agentic-AI.git
cd Social-Media-Agent
Create a virtual environment and activate it:

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
Install the required dependencies:

pip install -r requirements.txt

Create a .env file in the root directory with your OpenAI API key:

OPENAI_API_KEY=your_openai_api_key_here

#Run the below command to execute the code
python3 social_media_agent.py