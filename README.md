

# 🤖 AI Agent for Digital Financial Literacy – Powered by IBM Watsonx

This project is an AI-powered virtual assistant developed using **IBM Watsonx Assistant**, designed to enhance digital financial literacy. It helps users understand key financial topics such as UPI, online scams, interest rates, savings, budgeting, and personal finance—especially useful for first-time digital users and students.

---

## 🌟 Features

- 💬 Conversational agent built with **Watsonx Assistant**
- 🌐 Answers questions on financial topics: UPI, fraud prevention, interest rates, etc.
- 📚 Retrieves information from trusted government and banking sources
- 🌍 Multilingual support via IBM Watson Language Translator (optional)
- 📈 Potential for future integration with RAG, Watson Discovery, and live data sources

---

## 🛠️ Built With

- [IBM Watsonx Assistant](https://www.ibm.com/products/watsonx-assistant)
- [IBM Cloud](https://cloud.ibm.com/)
- 
- [Cloud Object Storage (COS)] – For storing documents/knowledge base
- [Watson NLP (Optional)] – For enhanced text analysis
- [Watson Discovery (Optional)] – For future document search and retrieval
- - **Watsonx Assistant** – Chatbot interface

---

## 🧑‍💻 How to Set Up and Run

> 📌 **No local code or installation needed**. Everything is built and deployed on **IBM Cloud**.

### Step-by-Step Instructions:

1. **Create IBM Cloud Account**  
   Sign up at https://cloud.ibm.com/ (use Lite plan – free tier).

2. **Create a Project**  
   - Go to ☰ (menu) → **Projects** → `Create Project`  
   - Name: `FinanceAgent`  
   - Region: `Dallas` (or any other)  
   - Add **Cloud Object Storage** when prompted  

3. **Create Watsonx Assistant**  
   - Go to ☰ → **Services & APIs** → Search for "Watsonx Assistant"  
   - Click **Create**  
   - Choose Lite Plan  
   - Go to the assistant dashboard and create a **new assistant**

4. **Build Your Assistant**  
   - Add **intents** (e.g., `#UPI_Explanation`, `#Avoid_Scams`, `#Interest_Rates`)  
   - Add **dialog nodes** to respond to each intent  
   - Train the model using Watsonx's interface  
   - Optionally integrate Watsonx Discovery for document-based answers

5. **Test & Deploy**  
   - Use the built-in chat window for testing  
   - Deploy using the **Web Chat Integration** or generate an embeddable code for websites

---

## 📦 Optional Services for Enhancement

- **Watsonx Discovery** – Add smart document search via PDF/HTML ingestion  
- **Watson Language Translator** – Enable multilingual support  
- **Cloud Functions** – Add custom logic or external API calls  
- **Watson Studio** – For integrating ML or trend prediction models in the future

---

## 📈 Future Scope

- Multilingual Financial Guidance  
- Integration with live RBI or SEBI APIs  
- RAG Pipeline for document-level retrieval  
- Personalized dashboards with user history  
- Financial goal tracking or budget planning suggestions

---

## 🚀 How to Run

1. Open `chatbot.html` in your browser.

## ✅ Conclusion

This AI Agent makes digital financial education accessible, user-friendly, and interactive. Built entirely on **IBM Watsonx**, it empowers users to understand financial systems securely and confidently—without needing to write a single line of code.

---

## 🙌 Acknowledgements

- IBM Watsonx Assistant & IBM Cloud  
- Government Financial Resources (RBI, SEBI, NPCI)  
- Project guided by [Your College/Team/Org Name]  

