# P4-_Implementation_of_ChatBot_using_NLP

This project focuses on the development of an interactive chatbot that leverages Natural Language Processing (NLP) and machine learning techniques to streamline user interactions. Designed to classify user inputs into predefined intents such as greetings, farewells, and questions, the chatbot provides accurate, contextually relevant responses. Built using Python, the system employs libraries like NLTK for text preprocessing and Scikit-learn for intent classification. A JSON-based intents file facilitates easy customization and scalability, while a conversation logging feature records user interactions in a CSV file for future reference. The chatbot is deployed using Streamlit, offering a user-friendly web interface for seamless communication. Although the system primarily handles basic interactions and predefined patterns, it serves as a scalable and modular foundation for more advanced functionalities, such as deep learning models, sentiment analysis, and multilingual support. This project demonstrates the practical application of NLP and machine learning in automating conversations, highlighting its adaptability to diverse use cases across industries like customer support, education, and healthcare.

Technologies Used
-  Python
- NLTK
- Scikit-learn
- Streamlit
- JSON for intents

## Installation

1. Clone the Repository
```bash
git clone <repository-url>
cd <repository-directory>
```
2. Create a Virtual Environment (Optional but Recommended)
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```
3. Install Required Packages
```bash
pip install -r requirements.txt
```
4. Download NLTK Data
```python
import nltk
nltk.download('punkt')
```
Usage
To run the chatbot application, execute the following command:
```bash
streamlit run app.py
```
Once the application is running, you can interact with the chatbot through the web interface. Type your message in the input box and press Enter to see the chatbot's response.

Intents Data
The chatbot's behavior is defined by the `intents.json` file, which contains various tags, patterns, and responses. You can modify this file to add new intents or change existing ones.

Conversation History
The chatbot saves the conversation history in a CSV file (`chat_log.csv`). You can view past interactions by selecting the "Conversation History" option in the sidebar.

Contributing
Contributions to this project are welcome! If you have suggestions for improvements or features, feel free to open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

Acknowledgments
- NLTK for natural language processing.
- Scikit-learn for machine learning algorithms.
- Streamlit for building the web interface.
