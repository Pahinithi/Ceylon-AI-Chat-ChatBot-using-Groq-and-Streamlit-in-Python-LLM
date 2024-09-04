# 💬 🇱🇰 Ceylon AI Chat

**Ceylon AI Chat** is an AI-powered chatbot application built using Streamlit and the Groq API. It leverages the powerful "llama-3.1-8b-instant" model to provide intelligent and contextual responses to user queries. This chatbot blends advanced AI capabilities with a touch of Sri Lankan identity.

## Features

- **Real-time AI Conversations:** Engage in seamless and natural conversations with the AI.
- **Session History:** Chat history is maintained throughout the session for continuity.
- **Easy Setup:** Simple configuration and deployment with Streamlit.
- **Customizable Interface:** Personalize the interface to match your style.

## Demo

[Click here to see the demo](https://drive.google.com/file/d/1UMjMCLcIz_Ltqwb-sHjuTl1ZdKsHLQwj/view?usp=sharing)  

## Screenshots

<img width="1728" alt="LLM05" src="https://github.com/user-attachments/assets/510f4e7b-6f75-4823-b267-72b3f70d8c58">


## Installation

### Prerequisites

- Python 3.7 or higher
- pip (Python package installer)

### Steps

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Pahinithi/Ceylon-AI-Chat-ChatBot-using-Groq-and-Streamlit-in-Python-LLM
   cd Ceylon-AI-Chat
   ```

2. **Install the Required Packages:**

   Use the following command to install all dependencies from the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

   **Dependencies:**
   - `groq==0.9.0`
   - `streamlit==1.37.0`

3. **Configure the API Key:**

   - Open the `config.json` file and replace the placeholder API key with your own Groq API key.

     ```json
     {
       "GROQ_API_KEY": "your_groq_api_key_here"
     }
     ```

4. **Run the Application:**

   Start the Streamlit application with the following command:

   ```bash
   streamlit run main.py
   ```

5. **Access the Application:**

   - Open your web browser and go to `http://localhost:8501`.
   - Start chatting with the AI by entering your queries in the input field.

## Usage

- **Chat Interaction:** Type your message in the input box at the bottom of the page and press Enter. The AI will respond, and the conversation will be displayed on the screen.
- **Session History:** Your conversation history is maintained throughout the session, so you can refer back to previous exchanges.

## Project Structure

- **`main.py`:** The main Python script that runs the Streamlit application.
- **`config.json`:** Contains the configuration details, including the Groq API key.
- **`requirements.txt`:** Lists all the dependencies required to run the application.

## Configuration

- **Groq API Key:** Ensure that your `config.json` file contains your correct Groq API key. The application reads this key to authenticate API requests.

## Contributing

Contributions are welcome! If you have suggestions, find bugs, or want to enhance the application, feel free to fork the repository and create a pull request. You can also open issues for any bugs or feature requests.

## License

This project is licensed under the MIT License.

## Contact

For any questions or support, please contact:

- **Name**: Pahirathan Nithilan
- **Email**: [nithilan32@gmail.com](mailto:nithilan32@gmail.com)
- **GitHub**: [Pahinithi](https://github.com/Pahinithi)

