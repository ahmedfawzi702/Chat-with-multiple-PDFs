git clone https://github.com/ahmedfawzi702/pdf-chatbot.git
cd pdf-chatbot

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run use.py
# Download model (optional if already downloaded)
ollama pull qwen:7b

# Start Ollama server
ollama run qwen:7b
