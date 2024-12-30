# Healio - Your Personal Wellness Assistant 💪💚

Healio is an advanced health and wellness bot built on Zoho SalesIQ using the Deluge scripting language. It offers personalized health guidance, appointment management, mental wellness support, organic product recommendations, and access to healthcare services. Healio helps individuals live a healthier and more balanced lifestyle by integrating multiple third-party APIs for a seamless user experience.

## 🚀 Overview

Healio acts as your personal wellness assistant, providing users with access to health and wellness services, such as:

- **Personalized Dietary Guidance**: Powered by the Spoonacular API, Healio generates meal plans based on user preferences, goals, and dietary restrictions.
- **Mental Wellness Support**: Motivational quotes from ZenQuotes, jokes for stress relief, and book recommendations using the Google Books API.
- **Appointment Management**: Users can book, reschedule, and cancel appointments, integrated with Calendly for easy scheduling.
- **Healthcare Services**: Find nearby hospitals via the Overpass API and order medicines directly from the bot with a database in Google Sheets.
- **User Authentication**: Secure OTP verification through Twilio ensures the safety of all interactions.

## 🌟 Features

- **Book Appointment**: Easily book consultations with healthcare professionals across various fields (general health, dermatology, cardiology, etc.).
- **My Appointment**: View, reschedule, or cancel your appointments with simple steps.
- **Health & Wellness**: Tailored meal plans, stress-relief activities, and organic product recommendations.
- **Healthcare Services**: Find hospitals nearby and buy medicines online.
- **Multi-language Support**: Designed for a diverse audience, supporting users in English, Spanish, and Japanese.

## 🔧 Technologies Used

- **Zoho SalesIQ**: Platform for bot development.
- **Deluge**: Scripting language used to write the business logic.
- **Calendly API**: For scheduling appointments.
- **Spoonacular API**: For meal planning and dietary recommendations.
- **Twilio API**: For OTP verification.
- **Overpass API**: For location-based services to find hospitals.
- **ZenQuotes API**: For motivational quotes.
- **Joke API**: For providing humor.
- **Google Books API**: For book recommendations.
- **Google Sheets**: For storing medicines and user transactions.

## 🌐 Hosted Demo

You can access a hosted demo of Healio here:

👉 [Link to Hosted Demo](#)

## 📥 Installation

To get started with Healio, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/healio.git
    cd healio
    ```

2. Set up Zoho SalesIQ:

    - Create a Zoho SalesIQ account and configure your bot there.
    - Use the Deluge scripting language to implement the logic shared in the repository.

3. API Integration:

    - Register for APIs (Spoonacular, Calendly, Twilio, Overpass, ZenQuotes, Joke API, Google Books).
    - Add your API keys and set up the necessary integrations in Zoho SalesIQ.

4. Google Sheets Integration:

    - Create Google Sheets for storing medicine products and user transactions.
    - Set up Google Sheets API in Zoho SalesIQ to connect and interact with the data.

## ⚙️ Configuration

In Zoho SalesIQ, create the necessary workflows and rules for the bot to perform the actions described. This involves:

- Setting up user flow (from Main Menu to sub-options).
- Implementing OTP verification via Twilio.
- Integrating API responses (meal plans, health recommendations, hospital locator, etc.).
- Setting up Calendar scheduling for appointment booking.

## 🖼️ Screenshots & GIFs

Here are some visuals demonstrating Healio's key features:

- **Book Appointment**: ![Book Appointment](#)
- **Buy Medicine**: ![Buy Medicine](#)
- **Dietary Plan**: ![Dietary Plan](#)

## 🤝 Contribution

Feel free to fork this project and contribute! Whether it's fixing bugs, adding features, or improving documentation, all contributions are welcome. 😄
