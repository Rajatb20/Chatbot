# Hotel Booking Chatbot 🏨🤖

A simple and intelligent chatbot designed to facilitate conversations between hotels and customers for booking rooms and finding information about various hotel services.

## 📋 Project Overview

This Telegram-based chatbot serves as a virtual hotel assistant that helps customers:
- Book hotel rooms
- Inquire about room availability
- Get information about different room types
- Learn about hotel services and amenities
- Answer frequently asked questions

## 🗂️ Repository Structure

Chatbot/ │ ├── Telegram Chatbot.ipynb # Main Jupyter notebook with chatbot implementation ├── credentials.yml # Configuration file for connecting to Telegram ├── domain.yml # Defines intents, entities, slots, and responses ├── nlu.md # Natural Language Understanding training data ├── stories.md # Conversation flows and dialogue management └── README.md # Project documentation


## 🛠️ Technologies Used

- **Rasa**: Open-source conversational AI framework
- **Python**: Primary programming language
- **Telegram Bot API**: Platform for chatbot deployment
- **Jupyter Notebook**: Development environment

## ✨ Features

- 🔍 **Room Inquiry**: Ask about available rooms and their features
- 📅 **Booking Assistance**: Help customers book rooms
- 💰 **Pricing Information**: Provide room rates and packages
- 🏊 **Amenities Information**: Share details about hotel facilities
- 📞 **24/7 Availability**: Automated responses anytime
- 💬 **Natural Language Processing**: Understands customer queries in natural language

## 🚀 Getting Started

### Prerequisites

```bash
Python 3.7+
Rasa 2.x or higher
Telegram Bot Token
Jupyter Notebook
Installation
Clone the repository:
Copygit clone https://github.com/Rajatb20/Chatbot.git
cd Chatbot
Install Rasa:
Copypip install rasa
Install required dependencies:
Copypip install rasa[full]
pip install jupyter
Set up Telegram Bot:
Create a bot using @BotFather on Telegram
Copy the API token
Update credentials.yml with your bot token
Configuration
Update credentials.yml:
Copytelegram:
  access_token: "YOUR_TELEGRAM_BOT_TOKEN"
  verify: "YOUR_BOT_NAME"
  webhook_url: "YOUR_WEBHOOK_URL"
Train the model:
Copyrasa train
Run the chatbot:
Copyrasa run
Connect to Telegram:
Copyrasa run --credentials credentials.yml --enable-api
📊 Project Components
Domain.yml
Defines the chatbot's universe:

Intents: User intentions (e.g., greet, book_room, ask_price)
Entities: Important information extracted from user messages
Slots: Variables to store information
Responses: Bot's replies to users
Actions: Custom actions the bot can perform
NLU.md
Contains training examples for:

Greeting intents
Room booking requests
Price inquiries
Service questions
General hotel information requests
Stories.md
Defines conversation flows:

Greeting → Room inquiry → Booking
Price check → Room features → Decision
Service inquiry → Information → Thanks
💡 Usage Examples
Customer: Hi, I need a room for tonight

Bot: Hello! I'd be happy to help you book a room. What type of room are you looking for?

Customer: Do you have any deluxe rooms available?

Bot: Yes, we have deluxe rooms available. They feature king-size beds, city views, and premium amenities. Would you like to proceed with the booking?

Customer: What's the price?

Bot: Our deluxe rooms are priced at $150 per night. Would you like to book one?

🔧 Customization
To customize the chatbot for your hotel:

Update NLU data (nlu.md):

Add your hotel-specific terminology
Include more training examples
Add new intents for specific services
Modify Domain (domain.yml):

Define your room types
Add your hotel's amenities
Customize response messages
Create Stories (stories.md):

Design conversation flows
Handle edge cases
Add fallback scenarios
🧪 Testing
Test the chatbot locally:

Copyrasa shell
Test with Telegram:

Copyrasa run --credentials credentials.yml
📈 Future Enhancements
 Integration with hotel booking system
 Payment processing
 Multi-language support
 Image sharing for room types
 Calendar integration for availability
 Customer review system
 Special offers and promotions
 Room service ordering
🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository
Create a feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request
👨‍💻 About the Author
@Rajatb20

🎓 MTech Data Science Student
🌱 Passionate about AI and conversational interfaces
💞️ Open to collaborating on Python and AI projects
📫 Feel free to reach out for collaboration!
📄 License
This project is open source and available for educational and commercial purposes.

🙏 Acknowledgments
Rasa for the amazing conversational AI framework
Telegram for the bot platform
The open-source community for continuous support
📞 Support
For questions or issues:

Open an issue on GitHub
Contact through GitHub profile
Check Rasa Documentation
🔐 Security Note
Never commit your credentials.yml with real tokens to GitHub
Use environment variables for sensitive data
Keep your Telegram bot token secure
⭐ If you find this project useful, please consider giving it a star!

Made with ❤️ for better hotel customer service


This complete README file includes:

✅ **Professional Structure**: Well-organized sections with emojis  
✅ **Comprehensive Documentation**: Installation, setup, and usage instructions  
✅ **Technical Details**: All file explanations and Rasa framework details  
✅ **Usage Examples**: Real conversation flow examples  
✅ **Customization Guide**: How to adapt for different hotels  
✅ **Future Enhancements**: Roadmap for improvements  
✅ **Security Best Practices**: Warnings about credentials  
✅ **Author Information**: Your personal details included 
