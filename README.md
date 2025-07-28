ShuleGPT: AI for Education, Healthcare, and Financial Empowerment in Tanzania.

ShuleGPT is a multilingual AI assistant built to help in making informed decisions about education, healthcare, and finance — using the power of LLMs, Retrieval-Augmented Generation (RAG), and fine-tuning.

MISSION: Democratize access to expert-level guidance for every Tanzanian youth — no matter their location, language, or background.

ShuleGPT is built for;
Secondary school and university students
Youth looking for carrier, health and academic guidance
Educators and organizations looking to extend access to reliable AI advice in local language
Anyone in Tanzania wanting localized AI tools

Why ShuleGPT?

Every year, thousands of students across Tanzania face challenges like:
- Choosing the right university or course
- Accessing trusted healthcare information
- Making smart financial decisions
- Lack of mentorship or guidance
- Lack of personalized learning platform for students

ShuleGPT is built to bridge this gap, offering:
- Academic advising based on local university and TCU data
- Basic medical Q&A fine-tuned from medical datasets
- Swahili-first financial literacy support
- Multilingual support via WhatsApp and Web
- RAG pipeline with real Tanzanian documents especially for students who will be able to learn anywhere at any time.


Core Technologies

LLM Backbone | Gemma 2B (Fine-tuned) |
Fine-tuning | QLoRA + HuggingFace PEFT |
Retrieval | LangChain + FAISS |
Data Sources | TCU Handbook, University Prospectuses, MedAlpaca, MedMCQA |
Interface | Streamlit + Flask + Twilio (WhatsApp) |
Deployment | Hugging Face Spaces, Localhost, Ngrok |

📊 Project Architecture

```text
           ┌─────────────┐
           │   User      │
           └────┬────────┘
                │ (Question)
        ┌───────▼────────┐
        │ Streamlit UI / │
        │ WhatsApp Bot   │
        └───────┬────────┘
                │
        ┌───────▼────────────┐
        │   RAG Pipeline     │
        │ (LangChain + FAISS)│
        └───────┬────────────┘
                │
        ┌───────▼────────────┐
        │  Fine-Tuned LLM    │
        │   (Gemma 2B + QLoRA)│
        └───────┬────────────┘
                │
        ┌───────▼────────────┐
        │    Answer with     │
        │   Citations + Link │
        └────────────────────┘
⭐ Support or Collaborate
If you believe in the mission of localizing AI for Africa, feel free to:

⭐ Star this repo

🤝 Collaborate or sponsor

📢 Share with others

“At the end of the day, people care about results, not effort.” — Show them what you built.
