# LegalChatbot
A Streamlit-based Legal Chatbot powered by Google's Gemini API to answer legal queries. It detects greetings, farewells, and legal keywords, and can generate responses using stories.yml intent mappings or Gemini AI for additional queries.

-------------------------------------------------------


🛠️ Installation & Setup
1. Clone the repository :
   git clone https://github.com/your-username/legal-chatbot.git
   cd legal-chatbot
2. Create .env file and paste your apikey
3. Create a virtual environment venv :
   python -m venv venv
4. Activate the virtual environment:
   venv\Scripts\activate
5. Install dependencies :
   pip install -r requirements.txt
6. Update stories.yml path:
   Inside main.py, change the stories_file_path to your correct path:
   stories_file_path = "path/to/your/stories.yml"
7. Run the chatbot:
   streamlit run main.py

