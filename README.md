# WhatsApp Automation Bot with n8n and Google Gemini

<img width="1240" height="597" alt="Screenshot 2025-09-18 001354" src="https://github.com/user-attachments/assets/e8711d90-51ed-4622-8729-70d433497eca" />

![wp3](https://github.com/user-attachments/assets/7a090c35-4b74-45e0-bd19-6ef8ac2ec45b)




## Project Overview
This project demonstrates building a WhatsApp automation chatbot using n8n workflow automation combined with Google Gemini LLM. The bot handles customer queries, processes orders, checks inventory, and sends confirmations—all directly on WhatsApp. It’s designed for small businesses like restaurants to automate order management, reduce errors, and provide instant responses 24/7.

## Features
- AI-driven conversational chatbot powered by Google Gemini LLM.
- Seamless WhatsApp Business Cloud integration via n8n.
- Inventory management backed by Google Sheets as a database.
- Automated order processing with real-time confirmation.
- Memory feature to remember user context for personalized interactions.
- Multi-language support configuration.
- Easy no-code setup with detailed workflow steps.

## Technologies Used
- n8n workflow automation platform
- Google Gemini language model (LLM)
- WhatsApp Business Cloud API
- Google Sheets for data storage
- JavaScript expressions for dynamic data handling

## Installation and Setup
1. Create an account on n8n.io and set up your workspace.
2. Obtain Google Gemini API credentials and connect them in n8n.
3. Integrate WhatsApp Business Cloud API credentials with n8n.
4. Prepare Google Sheets for inventory, orders, and FAQs.
5. Import the workflow JSON (provided in this repo) into your n8n instance.
6. Configure authentication and access tokens as described in the workflow.
7. Test the chatbot by sending messages on your connected WhatsApp number.

## How to Use
- Customers can place orders by sending a WhatsApp message.
- The bot confirms inventory availability and collects order details.
- Orders are recorded in Google Sheets automatically.
- FAQs and business info can be queried via chat.
- Admins can update inventory and FAQs through Google Sheets.

## Challenges & Learnings
This project involved integrating multiple platforms like n8n, WhatsApp Business Cloud, and Google APIs. Key learnings include managing API credentials securely, handling conversational AI context, and designing a user-friendly no-code automation flow.

## Future Work
- Add payment gateway integration for a complete order-to-payment workflow.
- Enhance multi-language support.
- Expand to support other messaging platforms.
- Implement advanced analytics on order data.

## Contributing
Contributions are welcome! Feel free to fork the repository, work on improvements or new features, and submit a pull request.

## License
This project is licensed under the MIT License.


