# 🤖 Promptfoo LLM Testing Demo

<img width="415" height="121" alt="image" src="https://github.com/user-attachments/assets/bd1ac7f3-a50e-4558-be5a-89f503225bad" />


<img width="225" height="225" alt="image" src="https://github.com/user-attachments/assets/dcceefef-d61b-4a2a-af1e-2b61046f2f33" />



# 🤖 Promptfoo LLM Testing Demo

A complete demo framework for **testing, benchmarking, and evaluating Large Language Models (LLMs)** using **Promptfoo**, **Python**, and **LM Studio**, fully integrated with **Visual Studio Code** and **GitHub CI/CD**.

---

## 🚀 Features

✅ **Promptfoo Integration** – Create structured prompt tests and visualize results in an interactive dashboard.  
✅ **Python Evaluators** – Add custom metrics, scoring, or text comparison logic.  
✅ **Local LLM Studio Support** – Compare OpenAI vs local Llama/Mistral models side-by-side.  
✅ **VS Code Ready** – Includes dev container, linting, and extensions for productivity.  
✅ **GitHub Actions CI/CD** – Automatically runs evaluations on every push or PR.  
✅ **Environment Isolation** – Works with `.env` secrets and per-branch testing.

---

## 🧩 Tech Stack

| Component | Purpose |
|------------|----------|
| **Promptfoo** | LLM evaluation and benchmarking |
| **Python** | Custom evaluators, logic, and metrics |
| **Node.js** | CLI and test orchestration |
| **LM Studio** | Local inference server for offline testing |
| **GitHub Actions** | CI/CD automation pipeline |
| **VS Code** | IDE and debugging support |

---

## 🧱 Project Structure

ai-llm-eval/
├── prompts/
│ └── test_prompt.txt
├── evaluators/
│ └── compare_model.py
├── promptfooconfig.yaml
├── .github/workflows/promptfoo.yml
├── requirements.txt
├── package.json
└── README.md

yaml
Copy code

---

## ⚙️ Installation

### 1. Clone the repo
```bash
git clone https://github.com/<your-username>/ai-llm-eval.git
cd ai-llm-eval
2. Install dependencies
bash
Copy code
brew install node python
npm install
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt
3. Add your API key
bash
Copy code
export OPENAI_API_KEY="sk-xxxx"
4. Run evaluations
bash
Copy code
promptfoo eval
promptfoo view


<img width="1457" height="1202" alt="image" src="https://github.com/user-attachments/assets/f1234a59-257b-4690-b376-b6f6ef25a9ed" />
