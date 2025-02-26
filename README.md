# -Building-a-Support-Agent-Chatbot-for-CDPs

# Building a Support Agent Chatbot for CDPs

This project involves building a chatbot capable of answering "how-to" questions related to four Customer Data Platforms (CDPs): Segment, mParticle, Lytics, and Zeotap. The chatbot retrieves relevant information from the official documentation of each platform to provide accurate answers to user questions.

## Features

### 1. **Answer "How-to" Questions:**
- The chatbot can understand and respond to user questions about performing specific tasks within each CDP.
- Example questions it can handle:
  - **"How do I set up a new source in Segment?"**
  - **"How can I create a user profile in mParticle?"**
  - **"How do I build an audience segment in Lytics?"**
  - **"How can I integrate my data with Zeotap?"**

### 2. **Extract Information from Documentation:**
- The chatbot extracts relevant steps and information from the official documentation of the four CDPs.
- It can navigate through the documentation, identify the relevant sections, and pull out the necessary instructions or steps.

### 3. **Handle Variations in Question Phrasing:**
- The chatbot is designed to handle different ways of asking similar questions, ensuring it doesn't break down for various question formats.
- It also handles irrelevant questions gracefully (e.g., questions about movies or other non-CDP topics).

### 4. **Cross-CDP Comparisons (Bonus Feature):**
- The chatbot can compare different CDPs' features and processes.
  - **Example question**: "How does Segment's audience creation process compare to Lytics'?"

### 5. **Advanced "How-to" Questions (Bonus Feature):**
- The chatbot is capable of answering more complex or platform-specific questions about advanced configurations, integrations, or use cases within each CDP.

## Technologies Used
- **Python**: The core language for building the chatbot.
- **Natural Language Processing (NLP)** libraries (e.g., `spaCy`, `nltk`): Used for processing and understanding user queries.
- **Requests/BeautifulSoup (if needed)**: For extracting data from the official documentation.
- **Flask/Django**: To create a simple web server and interact with the chatbot via HTTP requests (if building a web app).

## How to Run the Chatbot

1. Clone the repository to your local machine using the following command:
   ```bash
   git clone https://github.com/Pall-avi-r/-Building-a-Support-Agent-Chatbot-for-CDPs.git

2. Navigate into the project directory:
cd Building-a-Support-Agent-Chatbot-for-CDPs

3. Install the necessary dependencies (if you have a requirements.txt file):
   pip install -r requirements.txt
4. Run the chatbot:
   python chatbot.py
5. For a web-based chatbot (using Flask/Django), use:
   python app.py
Then, open your browser and go to http://127.0.0.1:5000 (or the appropriate URL if using a different port).

