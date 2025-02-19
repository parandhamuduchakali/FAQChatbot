# FAQ Chatbot

A simple rule-based chatbot for customer service queries built with Streamlit.

## Features
- Answers questions about company services
- Handles greetings, product info, pricing, and support queries
- Responds to multiple phrasings for each intent
- Chat interface with message history

## How It Works
1. **Intent Matching**: Uses keyword patterns to detect user intent
2. **Response Selection**: Randomly picks from predefined responses
3. **Conversation History**: Maintains chat context using Streamlit's session state

## Supported Intents
| Intent Category | Example Phrases | Sample Responses |
|-----------------|-----------------|------------------|
| Greeting        | "Hello", "Hi"   | "Hi there!", "Greetings!" |
| Product Info    | "What services?", "What do you offer?" | "We offer AI solutions..." |
| Pricing         | "How much?", "Cost?" | "Pricing starts at $99..." |
| Support         | "Contact support", "Help" | "Reach us at support@company.com..." |

## Installation
1. Clone this repository
2. Install requirements:

```bash
pip install streamlit

Usage
Run the chatbot:
```bash
streamlit run chatbot_app.py
