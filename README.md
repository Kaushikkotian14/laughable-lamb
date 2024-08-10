**YatraGuru** is a travel assistant chatbot designed to help users with various travel-related tasks. The application leverages natural language processing to interact with users and provide useful information or services related to travel, including booking flights, hotels, rental cars, and providing local attractions and travel tips.

**Key Features**:
**1.Chatbot Functionality:**
Assists users with booking flights, hotels, rental cars, and providing destination information.
Provides weather updates, local attractions, and customer service support.
**2.Language Support:**
Offers responses in multiple languages using Google Translate for translation.
**3.Voice Input**:
Allows users to input queries via voice commands and stops voice input if needed.
Supports text-to-speech to read out responses.

**Technical Stack:**
Backend Framework: Flask
Natural Language Processing: LangChain, Hugging Face (text generation)
Translation: Google Translate (via googletrans library)

**Endpoints:**
Home (/): Renders the main HTML page (index.html).
Ask (/ask): Accepts user queries via POST request and returns responses from the chatbot.

