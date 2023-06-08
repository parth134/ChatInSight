## WhatsApp Chat Analyzer

# Overview
The WhatsApp Chat Analyzer is a machine learning project that processes WhatsApp chat data and provides valuable insights and analysis. The project is implemented using Python and the Streamlit library for the user interface.

# Features
Import WhatsApp chat text files (.txt format)
Display chat statistics (total messages, number of participants, etc.)
Perform sentiment analysis to determine the overall sentiment of the chat
Identify and highlight named entities (people, locations, organizations) in the chat
Perform topic modeling to discover the main topics discussed in the chat
Visualize chat data with interactive charts and graphs
Export analysis results to a downloadable file

# Installation
Clone the repository: git clone https://github.com/your_username/whatsapp-chat-analyzer.git
Navigate to the project directory: cd whatsapp-chat-analyzer
Install the required dependencies: pip install -r requirements.txt

# Usage
Place your WhatsApp chat text file (in .txt format) in the project directory.
Run the Streamlit application: streamlit run app.py
Open the provided URL in your web browser to access the application.
Select the WhatsApp chat file from the dropdown menu.
Choose the analysis options (sentiment analysis, named entity recognition, topic modeling).
Click the "Analyze" button to start the analysis.
Explore the visualizations and analysis results on the Streamlit web interface.
Use the provided options to download the analysis results as needed.

# Data Format
The WhatsApp chat data should be in the following format:

[dd/mm/yy, hh:mm:ss] Sender: Message
[dd/mm/yy, hh:mm:ss] Sender: Message
...
Each message should be on a separate line, starting with the timestamp in the square brackets, followed by the sender's name and the message content.

# Dependencies
 Python 3.7+,
 Streamlit,
 scikit-learn,
 matplotlib

# License
This project is licensed under the MIT License.

# Contributing
Contributions are welcome! If you have any suggestions or improvements, please submit a pull request or open an issue.

# Acknowledgments
This project was inspired by the need to analyze WhatsApp chat data and gain insights from it.
