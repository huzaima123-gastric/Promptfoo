---

# 🚀 Promptfoo – LLM Prompt Testing & Evaluation Tool

**Promptfoo** is an open-source framework for evaluating, comparing, and optimizing prompts for **Large Language Models (LLMs)** like GPT, Gemini, and LLaMA.
It helps developers build **reliable, consistent, and high-quality AI prompts** through automated testing and data-driven insights. 🤖

---

## ⚙️ Installation

1. Make sure **Node.js (v20+)** and **npm** are installed.
   Verify using:
   **`node --version`**
   **`npm --version`**

2. Create a new folder for your project:
   **`mkdir promptfoo-demo`**
   **`cd promptfoo-demo`**

3. Initialize a sample project:
   **`npx promptfoo@latest init --example getting-started`**

---

## 🧠 Running Evaluations

1. Navigate to the project directory:
   **`cd getting-started`**

2. Start the evaluation process:
   **`npx promptfoo@latest eval`**

3. If you see an API key error, set your provider key (example for OpenAI):
   **`setx OPENAI_API_KEY "sk-your-api-key-here"`**
   *(Restart your terminal after setting it.)*

---

## 🌐 Viewing Results in Dashboard

Launch the local web dashboard to visualize results:
**`npx promptfoo@latest view`**

It will open the Promptfoo UI in your browser at:
👉 [http://localhost:15500](http://localhost:15500)

---

## 📊 Exporting Reports

Export evaluation results for sharing or documentation:

* JSON format → **`npx promptfoo export eval <evalId> --output results.json`**
* Logs (ZIP) → **`npx promptfoo export logs --output logs.zip`**

---

## 🧩 Supported Models

Promptfoo integrates seamlessly with:

* 🦙 **LLaMA (via Groq API)**
* 🌟 **Gemini (via Google AI Studio)**
* 🤖 **OpenAI GPT models**
* And more custom/local models

---

## 💡 Example Use Cases

* Comparing multiple LLMs for the same prompt
* Measuring response accuracy, coherence, and tone
* Automating LLM regression testing
* Tracking improvements during prompt engineering

---

## 🏁 Conclusion

Promptfoo is a must-have tool for anyone working with LLMs — from prompt engineers to AI researchers.
It turns **prompt testing into measurable, repeatable science** 🧪✨

---

Would you like me to tailor this README to match your **LLaMA & Gemini project setup** (so it includes both API setup instructions and example config)?
