# Agentic System Builder – Travel Team

Build a team of AI agents from a CSV file. No coding needed.
Upload a CSV with two columns (`Role`, `Instructions`) and the app
creates a multi-agent system that works together on your request.

## Demo: Travel Team (12 agents)
Chief_Travel_Planner (supervisor), Destination_Research_Specialist,
Itinerary_Designer, Budget_Manager, Flight_and_Transport_Advisor,
Accommodation_Advisor, Local_Food_Guide, Activity_and_Experience_Curator,
Visa_and_Documents_Advisor, Safety_and_Tips_Advisor, Packing_Assistant,
Trip_Reviewer.

## Tech Stack
Streamlit, LangGraph, LangChain, OpenRouter, Pandas

## How to Run
1. Create and activate a virtual environment
2. `pip install -r requirements.txt`
3. `python -m streamlit run drl.py`
4. Enter your OpenRouter API key, upload a team CSV, click **Create System**
5. Select the system and type your request

## CSV Format
Role,Instructions
Chief_Travel_Planner,"You are the head of travel planning..."
