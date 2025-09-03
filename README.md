# Ex. No. 3 – Scenario-Based Report Development Utilizing Diverse Prompting Techniques

 Register Number: 212222040128

### Aim

To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries.
The chatbot should handle queries efficiently while maintaining a conversational, friendly, and user-focused tone.
This experiment demonstrates how different prompting techniques can shape the chatbot’s interaction style.

### Algorithm & Prompting Techniques
#### 1. Direct Instruction Prompting

Objective: Provide concise responses to customer queries.
Prompt Pattern:
"When a customer asks for the status of their order, reply with:
‘Your order is currently being processed and will be delivered by [date].’"

Example Interaction:

Customer: What is the status of my order?

Chatbot: Your order is currently being processed and will be delivered by [date].

#### 2. Contextual Prompting

Objective: Use customer’s previous interactions for more relevant replies.
Prompt Pattern:
"If the customer mentioned they haven’t received their order, reply:
‘I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.’"

Example Interaction:

Customer: I haven't received my order yet.

Chatbot: I see that you mentioned your order hasn't arrived yet. Let me check the details for you and get back shortly.

#### 3. Persona-Based Prompting

Objective: Make the chatbot sound engaging by adopting a persona.
Prompt Pattern:
"Pretend you are a friendly customer service representative. Use a conversational tone."

Example Interaction:

Customer: I'm having trouble with my new product.

Chatbot: Hey there! I’m here to help with any questions you might have. Let’s get your issue sorted! What seems to be the problem?

#### 4. Few-Shot Prompting

Objective: Teach the AI with examples for better generalization.
Prompt Pattern:
"Here are some examples of handling technical issues… Now respond to: ‘My app keeps crashing.’"

Example Interaction:

Customer: My app keeps crashing.

Chatbot: It sounds like the app is unstable. Have you tried closing other apps? If it continues, try restarting your device or reinstalling the app.

#### 5. Chain-of-Thought Prompting

Objective: Solve complex issues step by step.
Prompt Pattern:
"When a customer reports overheating, guide them step by step… Now solve: ‘My laptop fan is making a loud noise.’"

Example Interaction:

Customer: My laptop fan is making a loud noise.

Chatbot: I understand your laptop fan is making noise. Could you tell me if you’re using it on a soft surface? Also, have you cleaned the vents recently? Dust buildup can often cause this issue.

#### 6. Instruction with Constraints

Objective: Respond under specific rules (length, tone, no jargon).
Prompt Pattern:
"Respond to order inquiries in no more than 50 words."

Example Interaction:

Customer: When will my order arrive?

Chatbot: Your order is on the way and should arrive by [date]. Feel free to reach out if you need anything else.

#### 7. Reflective Prompting

Objective: Confirm customer’s query before answering → reduces confusion.
Prompt Pattern:
"Reflect the query back to the user before answering."

Example Interaction:

Customer: How do I track my order?

Chatbot: You're asking how to track your order, correct? You can find your tracking info in the confirmation email or by logging into your account.

### Result

The various prompting strategies were executed successfully.

Each technique produced distinct chatbot behaviors, from concise replies to step-by-step guidance.

Direct prompts gave short, accurate answers.

Persona-based prompts made interactions engaging.

Chain-of-thought and reflective prompts ensured clarity and problem-solving depth.
