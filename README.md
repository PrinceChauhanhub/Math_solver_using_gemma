Text to Math Problem Solver using Google Gemma 2
================================================

Web-App Link -> https://mathsolverusinggemma.streamlit.app/

This is a Streamlit-based web application that uses the **Gemma 2 LLM** (via Groq API) to solve math problems, perform logical reasoning, and fetch relevant information from Wikipedia.

🧮 Features
-----------
- Math problem-solving using LangChain's `LLMMathChain`.
- Logical reasoning explained step-by-step using custom prompts.
- Wikipedia-based fact lookup for context-related queries.
- Interactive chat-style interface with memory.
- Built with Google's `Gemma2-9b-It` model via Groq.

🚀 Live Interaction
-------------------
- Ask any math-related or logic-based question.
- Get point-wise explanations and computations.
- Supports general knowledge queries via Wikipedia.

🔧 Tech Stack
-------------
- Python
- Streamlit
- LangChain
- Groq (Gemma 2 model)
- Wikipedia API Wrapper (LangChain Community)
- HuggingFace Transformers

📦 Installation
---------------

1. **Clone the repository**
git clone https://github.com/PrinceChauhanhub/Math_solver_using_gemma.git
cd Math_solver_using_gemma

2. **Install the dependencies**
pip install -r requirements.txt

3. **Set up environment variables**  
Create a `.env` file in the root directory and add your Groq API key:
GROQ_API_KEY=your_groq_api_key_here

Or enter it manually in the Streamlit sidebar at runtime.
4. **Run the application**
streamlit run app.py

🔐 API Key Requirement
----------------------
You must have a **Groq API Key** to use the application.  
Sign up and generate a key from: [https://console.groq.com](https://console.groq.com)

💡 Example Use Case
-------------------
_Question_:  
"I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. Then I buy a dozen apples and 2 packs of blueberries. Each pack of blueberries contains 25 berries. How many total pieces of fruit do I have at the end?"

💬 The app will provide:
- Logical breakdown of the problem
- Step-by-step calculation
- Final answer in a human-readable format

🤝 Contributing
---------------
Feel free to contribute!  
Whether it's fixing bugs, improving logic, optimizing prompts, or enhancing UI—contributions are always welcome.

1. Fork the repo
2. Create a new branch (`git checkout -b feature-xyz`)
3. Commit your changes (`git commit -m 'Add feature xyz'`)
4. Push to the branch (`git push origin feature-xyz`)
5. Open a Pull Request

🙋 Author
---------
👨‍💻 Prince Chauhan  
🔗 GitHub: https://github.com/PrinceChauhanhub
