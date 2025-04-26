# 📂 Case Status Voice Assistant

This project is a simple voice and chatbot assistant that helps users check their case status by speaking or typing.

It uses:
- **Dialogflow** (for natural language processing)
- **Make.com** (for automation and webhooks)
- **Airtable** (for storing case data)

---

## 🛠️ Stack Used
- **Dialogflow**: Handles user queries and understands intent.
- **Make.com**: Connects Dialogflow to Airtable and formats the response.
- **Airtable**: Stores Case ID, Status, Assigned Lawyer, Hearing Date, etc.

---

## 🚀 How It Works
1. The user asks, "What is the status of case CASE-0001?"
2. Dialogflow extracts the case ID from the query.
3. Make.com receives a webhook from Dialogflow, queries Airtable for the case.
4. The case status and other details are fetched.
5. Make.com sends a response back to Dialogflow.
6. Dialogflow replies to the user with the case status.

---


## 📈 Future Improvements
- Handle voice input more flexibly.
- Add authentication for users (e.g., OTP verification).
- Deploy to WhatsApp or a Website using Dialogflow integrations.
- Error Handling Improvements (e.g., case not found, multiple cases).

---

## 💬 Contact
If you want to collaborate or ask questions, feel free to reach out!
