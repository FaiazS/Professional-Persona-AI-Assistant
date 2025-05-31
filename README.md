# Professional-Persona-AI-Assistant
---
A fully functioning AI chatbot built that represents **me**, as if a recruiter or hiring manager is personally interacting with.

This project is a **multi-agent LLM system** that reads my professional background, understands my experiences, and speaks on my behalf in a professional and engaging way — exactly how I would, when applying for a job or being interviewed.

Apart from being just a chatbot, it is a **real-time evaluator-backed agent loop** that refines its responses until they meet professional standards, ideal for showcasing how LLMs can be grounded, self-evaluated, and deployed for real-world interaction.

---

## 🎯 Use Case

**Recruiters and hiring managers** often visit a candidate's portfolio or LinkedIn and wonder:

> _“Can I get a quick, clear sense of who this person is without manual inspection and much time consumption?”_

So instead of going through and reading text, they can now **talk to me directly via my AI agent**. This agent:

- Is grounded on my professional summary and LinkedIn profile
  
- Understands how to speak in a way that's appropriate
  
- Can answer questions like:
  
  - "What are your core strengths?"
    
  - "What’s your work history?"
    
  - "Do you own any startups?"
    
  - "Are you open to relocation?"
    
- Knows when it doesn't know something — and admits it professionally
---

## 💡 Project Highlights

| Feature                             | Description                                                                 |
|-------------------------------------|-----------------------------------------------------------------------------|
| 🧠 LLM Simulation                   | Uses **LLaMA 3 (Groq)** to simulate my responses from professional context |
| 🕵️‍♂️ Evaluator Layer                  | Uses **GPT-4o (OpenAI)** to review, critique, and flag weak answers        |
| 🔁 Self-Correction Loop             | If rejected, the agent re-generates the answer with feedback               |
| 📄 Context Grounding                | Reads my **LinkedIn profile PDF** and **professional summary**             |
| 🎛️ Gradio UI                        | Clean interface for live interaction                                       |
| 🧱 Built from scratch               | Every component — prompt design, logic, flow, retry loop — is engineered   |

---

## 🔧 Tech Stack

- [x] **Python 3.10+**
      
- [x] **Groq API (LLaMA 3.3 70B)**
      
- [x] **OpenAI GPT-4o**
      
- [x] **Gradio (Chat UI)**
      
- [x] **PyPDF2** for PDF parsing
      
- [x] **Pydantic** for response evaluation schema
      
- [x] **Multi-agent loop**: chatbot + evaluator + self-correction

---

## 🚀 How It Works

1. **Grounding**  
   The chatbot reads my LinkedIn profile PDF and a manually written summary.

2. **Conversation**  
   The user interacts with the chatbot through a Gradio interface.

3. **Evaluation**  
   Each response is evaluated by GPT-4o for professionalism, clarity, and helpfulness.

4. **Correction**  
   If the evaluator rejects a reply, the chatbot regenerates it using the feedback.

5. **Final Output**  
   The user gets a refined, professionally acceptable response — as if talking to the physical professional me.
   
---

## 🧠 Objective

- To go beyond a traditional portfolio and **showcase real AI Engineering**

- To demonstrate how LLMs can simulate humans professionally
  
- To stand out as a candidate who doesn't just talk about AI — but also build them

---

## 💬 What Recruiters and Hiring Managers Can Ask My Chatbot

- “What are your core technical skills?”
  
- “Tell me about your experience with Spring Boot”
  
- “Have you worked on AI projects?”
  
- “What are your career goals?"
  
- “Are you open to relocation or remote work?”

> You’ll get answers based on my real experience — and evaluated for professionalism.

---

## 🧠 Key skills involved 

- Prompt Engineering (System prompts, evaluation prompts, regeneration prompts)
  
- Retrieval-Augmented Generation (RAG-style grounding from PDF & text)
  
- Multi-agent LLM flow (chatbot + evaluator + retry)
  
- Chain of Thought (regeneration with reasoned feedback)
  
- Safe fallback behavior (refuses when unsure)
  
---
