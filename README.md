# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE:30/04/2025                                                                         
### REGISTER NUMBER : 212222040042
### Aim: To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

Here's a comprehensive breakdown of how to design an AI-powered chatbot for product troubleshooting, order tracking, and general inquiries, using the following prompting techniques:

## 🎯 Project Aim
Design a conversational AI chatbot that:

Assists users with product troubleshooting, order tracking, and general inquiries.

Uses Straightforward Prompts, Tabular Format Prompting, and Preceding Question Prompting.

Delivers responses in a clear, concise, and friendly tone.

## 📌 Prompting Techniques Explained

Prompting Technique	Description	Application in Chatbot
Straightforward Prompts	Directly ask the user for information or guide them to the next step.	Gather order number, ask for product details, etc.
Tabular Format Prompting	Use a table to present options, FAQs, or troubleshooting steps clearly.	Display product issues and fixes, delivery stages, etc.
Preceding Question Prompting	Use the previous question to guide or refine the next one.	Follow up based on previous user input (e.g., ask for model number after selecting a product).
🛠️ Chatbot Workflow Design (with Prompt Techniques)
1. Welcome Message
“Hi there! 👋 I'm your virtual assistant. I can help you with order tracking, troubleshooting, or any general questions. How can I help you today?”

2. Identify User Intent – Straightforward Prompt
“Please choose one of the following:
1️⃣ Order Tracking
2️⃣ Product Troubleshooting
3️⃣ General Inquiry”

3. Order Tracking – Tabular Format Prompting
If the user selects Order Tracking:

“Great! Please enter your Order ID to proceed.”

➡️ Once Order ID is entered:

## Chatbot Response:


📦 Order ID	🕒 Status	🚚 Estimated Delivery	🔁 Next Step
123456789	Shipped	May 3, 2025	Track via courier →
“Would you like to contact support for any delivery delay?”

4. Product Troubleshooting – Preceding + Tabular Format
If the user selects Product Troubleshooting:

“What product are you having trouble with?”
(Use Preceding Prompting based on answer.)

➡️ If user says "Bluetooth speaker":

“What issue are you facing with your Bluetooth speaker?”

## Then show a table:


🔧 Issue	✅ Possible Solution
Speaker not turning on	Charge for 30 min and hold power for 5 sec
Bluetooth not connecting	Reset device and retry pairing
Poor sound quality	Check volume settings or device range
“Did this solve your issue? (Yes/No)”
If "No", escalate to human agent.

5. General Inquiries – Straightforward Prompts
“Sure, I can help! Please type your question or select a category below:
🛍️ Return Policy | 💳 Payment Options | 📦 Shipping | 📄 Warranty”

➡️ Based on selection, provide concise answers.
## Example:

“Our return policy allows you to return items within 15 days of delivery.”

🧠 Chatbot Memory + Flow Example (Prompt Chaining)
plaintext
Copy
Edit
User: I need help with my speaker.
Bot: Is it a Bluetooth speaker or wired?
User: Bluetooth.
Bot: Got it! What issue are you facing with your Bluetooth speaker?
User: It’s not turning on.
Bot: Please try charging it for 30 minutes and hold the power button for 5 seconds. Did that work?
User: No.
Bot: Sorry to hear that. Would you like me to connect you to a customer support agent? 👨‍💼
✅ Best Practices
Keep language friendly and simple.

Use emojis for tone (optional).

Offer options when possible to reduce typing.

Always give users a way to escalate to a human agent.

Would you like a sample implementation in Python (with a conversational flow using dictionaries or a framework like Rasa or Flask)?




# Result: 
Thus the Prompts were exected succcessfully .

