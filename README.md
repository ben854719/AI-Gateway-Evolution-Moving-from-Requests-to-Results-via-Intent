# AI Gateway Evolution: Moving from Requests to Results via Intent

## Objective:

The application aims to develop an intent-driven AI assistant that seamlessly supports the users with daily tasks by acting as a reminder, contextual helper, and agentic AI. It will translate reports into English, French, Spanish, and Chinese based on the user requests, without any issues of prompting. The backend utilizes Node.js (Express), BullMQ, and python sheduler for task orchestration, while PyTorch predicts the user’s intent and Matplotlib visualizes a task trigger to optimize the engagement from the user. The frontend features an interactive UI that previews NLP interpretation. The Key metrics includes an achieving at least 90% intent accuracy, less than 500ms latency, 60% daily engagement, and 95% translation precision.

## Video of the project:

## Key Features: 

## Multilingual Report Translation:

- Translates reports into English, French, Spanish, and Chinese on demand with high precision (≥95%).

## Intent Recognition via Deep Learning:

- Uses PyTorch to accurately predict user intent with a target accuracy of ≥90%.
  
## Agentic AI:

- The Agentic AI will acts autonomously to support daily tasks serving as a reminder, contextual helper, and proactive assistant.

## Task Orchestration System:
  
- The Backend powered by Node.js (Express), BullMQ, and python scheduler to manage and schedule tasks efficiently.

## Visual Engagement Triggers
  
- It will employ Matplotlib to visualize task triggers, enhancing user interaction and engagement.

## Interactive NLP UI: 

- The Frontend displays real-time previews of natural language interpretation to improve transparency and usability.

## Performance-Optimized Architecture:
  
- The designed for low latency (<500ms) and high daily engagement (≥60%).

## Installation:

## Prerequistes:

- Python
- Node.JS (Express)
- JSON
- BullMQ
- Redis Cloud Console
- Pytorch
- Numpy
- Matplotlib
- Gradio
- Agentic AI
- LangGraph
- Gemini
- MCP Server

## Agentic AI Configuration (with MCP Server Installation):

## API Credentials:

- Register and obtain your Gemini API key from Google AI Studio.
- Store the key securely in a .env file to protect sensitive credentials.

## LangGraph Flow Setup:

- Design a multi-step processing graph to handle translation, reporting, assistance, and reminder.
- Node Configuration.
- Input Normalization – Preprocess incoming text for consistency and clarity.
- Gemini Translation Output – Use Gemini API to translate report in English, French, Spanish, and Chinese.
- Language Detection – Automatically identify the source language for routing and fallback handling.
  
## Normalize:

- Clean and standardize the input text.

## Detect:

- Use NLP to detect the user's intent and identify the input language.

## Translate:

- If the input is in English, translate it into French, Spanish, and Chinese.
  
- Translation is triggered only when English is the source language.


## Fallback:

- Translation fails or the input is ambiguous.
  
- Retry with alternate models or heuristics.
  
- Notify the user with a graceful message or ask for clarification.

## Output:

- Display the translated results in French, Spanish, and Chinese.
  
- Include metadata such as confidence scores, detected intent, and original input preview.



