# Multi-modal AI Workflow

![Workflow Screenshot](image_b40186.png)

This project is an intelligent workflow built in n8n that analyzes and routes user inputs based on their data type. It can distinguish between text messages, images, and documents, processing each accordingly.

## Key Features

- **Multi-modal Input:** Handles different data types, including text, images, and documents.
- **Conditional Logic:** Uses an `If` node to intelligently route the input to the correct processing path.
- **AI-Powered Analysis:** Leverages Google Gemini for analyzing images and documents.
- **Conversational Memory:** Includes a fallback to a conversational agent with persistent memory for standard text chats.

## Technologies Used

- **n8n** for workflow automation
- **Google Gemini Pro** as the core LLM
- **APIs** for document and image analysis

## How to Use

1.  Download the `multi-modal-workflow.json` file from this repository.
2.  Import the JSON file into your n8n instance.
3.  Add your own credentials for the Google Gemini node.
