#  AI Agent for Medical Diagnosis report upload any medical report .txt file

An AI agent interactive Streamlit-based medical assistant powered by domain-specific AI agents. This tool allows healthcare professionals and researchers to analyze medical reports using specialists (Cardiologist, Psychologist, Pulmonologist) and generate comprehensive diagnostic insights. It runs locally using the Mistral LLM via the Ollama backend.

##  Features

- 🔬 **Specialist Simulations**: Analyze reports from the perspective of a cardiologist, psychologist, or pulmonologist using dedicated prompts.
- 🎛️ **Manual Agent Selection**: Choose a specialist or run a full multidisciplinary analysis via the frontend interface.
- 🧠 **Multidisciplinary Team Analysis**: Combines all three specialist reports to suggest three possible diagnoses with reasoning.
- 📤 **File Upload & Analysis**: Upload `.txt` medical reports for instant processing and evaluation.
- 💾 **Report Export**: Final diagnosis is saved to `results/final_diagnosis.txt` for record-keeping.
- 🛠️ **Local LLM Integration**: Uses `mistral-nemo:latest` model via `langchain_ollama` for privacy-respecting, offline AI inference.

##  Getting Started

### 1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/Medical-AI
cd Medical-AI
2. Install Requirements
Create a virtual environment and install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Make sure you have Ollama installed and running with the mistral-nemo model:

bash
Copy
Edit
ollama pull mistral-nemo
3. Run the App
bash
Copy
Edit
streamlit run app.py

📄 How to Use
Upload a .txt file containing the medical report will be ready.

Choose one of the following specialists from the dropdown:

Cardiologist

Psychologist

Pulmonologist

All Specialists (for a full diagnosis)

Click "🔍 Analyze Report" to run the selected analysis.

Review detailed results and multidisciplinary diagnosis (if selected).

Final diagnosis will be saved locally in results/final_diagnosis.txt.

📁 Project Structure
bash
Copy
Edit
AI-Agents-to-assist-for-Medical-Diagnosis/
│
├── app.py                  # Streamlit application code
├── requirements.txt        # Python dependencies
├── results/
│   └── final_diagnosis.txt # Output file (auto-generated)
└── README.md               # Project documentation

🧠 Tech Stack
Streamlit

LangChain

Ollama

Mistral (via mistral-nemo:latest)

Python 3.8+

🧪 Disclaimer
This tool is a prototype for research and educational use only. It is not approved for clinical diagnosis or treatment planning. Always consult a licensed healthcare professional for actual medical decisions.

🙌 Acknowledgments
Special thanks to the open-source communities of:

LangChain

Ollama

Mistral


owner by viraj 
