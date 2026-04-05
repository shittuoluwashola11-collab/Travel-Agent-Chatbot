# Travel-Agent-Chatbot
A Python-based AI travel assistant using OpenAI's GPT-4o-mini to provide optimized, conversational navigation and route recommendations specifically for destinations within Nigeria.
## NaijaRoute AI: Nigeria Travel Assistant

NaijaRoute AI is a specialized conversational agent built to help users navigate the complex road networks, bus stops, and local government areas of Nigeria. Leveraging the power of OpenAI's `gpt-4o-mini`, this assistant provides tailored, multi-path directions with a focus on speed and local accuracy.

## 🇳🇬 Features
* **Niche Expertise**: Specifically trained to act as a knowledgeable Nigeria Travel Agent familiar with local landmarks, states, and "street-smart" navigation.
* **Intelligent Routing**: Recommends multiple paths to a destination, prioritizing the fastest route from the user's current location to the least.
* **Context Awareness**: Automatically prompts users for their current location if it is missing from the query to ensure accurate directions.
* **Strict Geofencing**: Programmed to maintain focus on Nigerian geography, politely declining queries for routes outside the country.

## 🛠️ Technical Implementation
The system uses a structured prompt engineering approach:
* **Base Role**: Defines the assistant as a specialized Nigerian travel expert.
* **Behavior Guidelines**: Ensures the assistant handles missing user data (like starting point) gracefully.
* **Response Guidelines**: Enforces a conversational tone and specific formatting for route recommendations.

## 🚀 Getting Started

### Prerequisites
* Python 3.12+
* OpenAI API Key
