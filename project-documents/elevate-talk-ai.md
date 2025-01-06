# Elevate Talk AI

Elevate Talk AI is a dynamic web application that integrates ChatGPT for creating and managing conversational chatbots. This platform allows users to build customizable chatbots and embed them as widgets, iframes, or standalone pages in their projects.

## Features

### 1. Dashboard
The dashboard provides users with a concise summary of their chatbot and usage statistics, displayed in both card and table views. The reports include:
- **Total number of chatbots**: Displays the overall number of chatbots created by the user, with a breakdown of active chatbots.
- **Total conversations**: Shows the total interactions recorded for all chatbots.
- **Total unique conversations**: Counts distinct conversations based on unique users or sessions.
- **Total leads collected**: Displays the total number of leads extracted from chatbot interactions.
- **User limits**: Indicates feature limits based on the user's subscription plan.

Logs/print statements:
```plaintext
- Log: Fetching dashboard data for user ID: {user_id}
- Log: Rendering dashboard cards and table views.
- Log: Calculating total unique conversations for all chatbots.
```

### 2. Chatbot Management
Users can create and maintain chatbots with a variety of customization options:
- **UI customization**:
  - Customize chatbot appearance, including title, background color, icon, logo, header, and description. 
  - Examples:
    - **Title**: Up to 50 characters.
    - **Background color**: Any valid HEX, RGB, or named color value.
    - **Icon**: Upload PNG or JPEG (max size: 2 MB).
    - **Placeholder text**: Up to 100 characters.
  - Provide predefined suggestions for quicker interaction (e.g., "How can I help you?", "What services do you offer?").
- **Training data**: Users can train each chatbot by providing domain-specific or custom data that improves the quality of conversations.
- **Integrations**: Connect chatbots with automation platforms like Zapier and Pabbly for streamlined workflows.
- **Sharing options**:
  - Generate shareable links that allow others to interact with the chatbot directly.
  - Create embeddable widgets or iframes for seamless integration into other projects or websites.

Logs/print statements:
```plaintext
- Log: Creating a new chatbot with title: {chatbot_title}
- Log: Updating chatbot UI for chatbot ID: {chatbot_id}
- Log: Training chatbot with new data set for chatbot ID: {chatbot_id}
- Log: Generating shareable link for chatbot ID: {chatbot_id}
```

### 3. Conversation Management
This module allows users to:
- **View all chatbot conversations**: A comprehensive list of conversations across all chatbots.
- **Filter unique conversations**: Separate recurring interactions from new or unique users.
- **Access detailed conversation histories**: Review past interactions for insights or debugging.
- **Cookie-based previewing**: Cookies are used to preserve and display previous interactions for returning users in the widget or embedded chatbot. Cookie usage complies with relevant data privacy regulations, including GDPR, ensuring transparency and user consent.

Logs/print statements:
```plaintext
- Log: Fetching conversation data for chatbot ID: {chatbot_id}
- Log: Filtering unique conversations from total conversations.
- Log: Loading conversation details for conversation ID: {conversation_id}
- Log: Retrieving previous conversation using cookie for user session ID: {session_id}
```

### 4. Lead Management
Users can view all leads collected through chatbot interactions. A Python script processes conversations to extract and present valuable leads:
- **Lead extraction**: The script analyzes conversation data to identify potential leads by extracting contact details, identifying patterns, and scoring interactions for lead relevance.
- **Lead storage**: Collected leads are securely stored in a database with encryption, ensuring user privacy and data security. The data is presented in an easy-to-read format for user convenience.

Logs/print statements:
```plaintext
- Log: Extracting leads from conversation data for chatbot ID: {chatbot_id}
- Log: Storing lead information in the database.
- Log: Displaying total collected leads for user ID: {user_id}
```

### 5. Credit Management
Users can manage their credits and packages through this module:
- **Purchase credits and packages**: Enables users to buy resources required for chatbot operation.
- **Credit card management**: Add, update, or remove credit card details securely.
- **Invoice history**: View transaction records for credit and package purchases.
- **Credit usage tracking**: Monitor how credits are consumed over time.

Logs/print statements:
```plaintext
- Log: Initiating credit purchase for user ID: {user_id}
- Log: Fetching invoice history for user ID: {user_id}
- Log: Displaying credit usage details for user ID: {user_id}
```

### 6. Authentication
- **Login and Registration**: Users must register an account and log in to access the platform.
- **Package restriction**: Users must purchase a package to unlock all features of the application.

Logs/print statements:
```plaintext
- Log: User registration attempted with email: {email}
- Log: User login successful for user ID: {user_id}
- Log: Restricting feature access due to no active package for user ID: {user_id}
```

## Getting Started

### Prerequisites
- A modern web browser (Google Chrome, Mozilla Firefox, Safari, or Microsoft Edge).
- Active internet connection.
- A valid user account.

### Installation
Elevate Talk AI is a web application and does not require local installation. Simply navigate to the application's URL, register an account, and log in.

Logs/print statements:
```plaintext
- Log: Application accessed via URL: {app_url}
- Log: User redirected to login page.
```

### Usage
1. Log in to your account.
2. Navigate through the various features using the menu:
   - **Dashboard**: View usage statistics and chatbot summaries.
   - **Chatbot**: Create, customize, and train your chatbot.
   - **Conversation**: Manage and review chatbot interactions.
   - **Lead**: Access leads extracted from conversations.
   - **Credit**: Purchase credits, manage transactions, and view usage history.
3. Embed or share your chatbot using generated links or widgets.

Logs/print statements:
```plaintext
- Log: Menu navigation to feature: {feature_name}
- Log: Embedding chatbot widget for chatbot ID: {chatbot_id}
```

## Key Technologies
- **ChatGPT Integration**: Powers dynamic conversational capabilities.
- **Python Scripts**: Extract valuable leads from conversations.
- **Third-Party Integrations**: Zapier and Pabbly for enhanced automation.

![Simple Accounting Dashboard](https://softwareelevate.com/svg/projects/chatbot/1.jpeg)

<div style="text-align: center; margin-top: 20px;">
  <img src="https://softwareelevate.com/svg/projects/chatbot/2.png" alt="Chat bot" style="width: 50%; height: 300px;">
</div>

## License
Elevate Talk AI is proprietary software. All rights reserved.

---

For more information or support, contact the development team or refer to the official documentation.
