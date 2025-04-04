#Overview

This project contains the development files for Z-Bot, an intelligent AI chatbot tailored for Z Hotels Holborn. Z-Bot provides assistance by referencing information stored in Google Sheets and leveraging AI to handle general inquiries. Currently, the bot is in an active developmental stage and offers foundational interaction capabilities.

Current Features

AI-Powered Chat Interface: Utilizes the OpenAI GPT model (gpt-4o-mini) to generate dynamic, contextually relevant responses.

Google Sheets Integration:

Automatically retrieves data to answer user queries.

Appends new queries and responses to the FAQs Google Sheets document for continuous improvement.

Memory Buffer: Maintains conversational context to provide coherent interactions.

Polite and Customer-Friendly Responses: Programmed to ensure excellent customer service through friendly and engaging interactions.

Workflow

On receiving a chat message, Z-Bot attempts to provide an answer by first consulting Google Sheets.

If the query is new, Z-Bot generates an answer using its AI capabilities, and the query-answer pair is recorded in the Google Sheets document along with relevant keywords.

For unresolved questions, Z-Bot clearly communicates and escalates the interaction to a human agent.

Technical Stack

Framework: n8n Workflow Automation

AI Integration: OpenAI GPT-4o Mini

Data Management: Google Sheets (via OAuth2 authentication)

Chat Memory Management: Window Buffer Memory Node in n8n

Future Development

The following enhancements are planned:

Human-Agent Integration: Direct connectivity with human agents to seamlessly transfer conversations when necessary.

Improved Query Handling: Enhanced logic for determining when a human agent intervention is required.

Data Logging and Analytics: Automatic logging of chat interactions into a CSV file for analytics and performance improvement.

Expanded Automation: Deeper integration with hotel operational systems to handle complex queries.

Usage

To interact with Z-Bot, simply initiate a chat. Z-Bot is designed to offer quick, reliable, and friendly assistance tailored specifically to guests and queries related to Z Hotels Holborn.

Contributions

Currently, contributions are managed internally by the development team. Further details on collaboration and contribution will be available in upcoming releases.

Support

For any immediate technical support, please contact the development team or the IT department directly.

Author

Rafique Mohammad

