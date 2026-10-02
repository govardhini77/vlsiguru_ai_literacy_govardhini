## Q1 - AI → ML → Deep Learning → Generative AI → Agents

### A - Answer

AI (Artificial Intelligence) means making computers or machines do tasks that normally need human intelligence. For example, recognizing a face, understanding speech, or making a decision.

Machine Learning (ML) is a part of AI where the computer learns patterns from data. Instead of giving the computer every rule, we give it data and it learns from it.

Deep Learning is a type of Machine Learning that uses neural networks with many layers. It is useful for things like image recognition, speech recognition and understanding complex patterns.

Generative AI is AI that can create new content such as text, images, audio, video or code. ChatGPT is one example of a Generative AI application.

An AI Agent is a system that can take a goal, decide what steps are needed, use tools and perform actions to complete the task. It is more than just giving an answer to a question.

### Simple relationship

```text
Artificial Intelligence (AI)
│
└── Machine Learning (ML)
    │
    └── Deep Learning
        │
        └── Generative AI

AI Agent
└── AI model + tools + actions → completes tasks
```

### Everyday examples

- AI: Face unlock on a smartphone can recognize a person's face.
- Machine Learning: YouTube can learn what videos a person watches and recommend similar videos.
- Deep Learning: A phone camera can use deep learning to recognize objects and improve photos.
- Generative AI: ChatGPT can generate text, answers or code from a prompt.
- AI Agent: An AI agent could take a travel request, search for suitable options using tools and complete several steps for the user.

### Generative AI vs AI Agents

Generative AI mainly focuses on creating new content from a user's prompt. For example, it can write an email, create an image or generate code. An AI agent can use an AI model together with tools and take actions to achieve a goal. So, Generative AI is mainly about generating content, while an AI agent is about using AI to complete a task or workflow.

### E - Evidence

I checked the basic definitions and relationships using reliable sources. The sources explain that Machine Learning is a part of AI, Deep Learning is a type of Machine Learning, and Generative AI can create new content. They also explain that AI agents can use models and tools to perform tasks.

Sources:
- [IBM Think - What is Artificial Intelligence?] (https://www.ibm.com/think/topics/artificial-intelligence)
- [IBM Think - What Are AI Agents?] (https://www.ibm.com/think/topics/ai-agents)


### V - Verification

I compared the information from the sources with my own understanding. I verified that AI is the broader field, while Machine Learning is a part of AI and Deep Learning is a part of Machine Learning. I also verified that Generative AI is mainly used for creating content, while an AI agent can use tools and perform actions to complete a goal.

### R - Reflection

Before learning this, I thought AI, Machine Learning and Generative AI were almost the same thing. Now I understand that they are connected but have different roles. I also understood that an AI agent is different from a normal Generative AI chatbot because an agent can use tools and perform multiple actions to complete a task.



## Q2 - Is Everything That Looks Intelligent Actually AI?

### A - Answer

Not everything that looks intelligent is actually AI. Some programs just follow fixed instructions written by a programmer, while AI systems can learn patterns from data or generate new content.

| Example | Classification | Why |
|---|---|---|
| A. Calculator produces 25 × 16 = 400 | Traditional software | The calculator follows a fixed mathematical operation. It does not learn from data. |
| B. Program says If temperature > 80°C, display WARNING | Traditional software | This is a fixed rule written by a programmer. The program only checks the condition and gives the defined output. |
| C. Email system identifies spam using patterns learned from previous email data | Machine-learning-based AI | The system learns patterns from previous email data and uses them to identify spam. |
| D. AI assistant writes a summary of a document | Generative AI | The AI generates new text based on the information in the document and the user's request. |
| E. Navigation app predicts estimated arrival time using traffic and historical data | Machine-learning-based AI | The system can use traffic and historical data to predict the estimated arrival time. |

### Why these classifications are different

The calculator and the temperature warning program mainly follow instructions that were already defined. They do not learn from data.

The spam detection example uses patterns learned from data, so it is a machine-learning-based AI system. The navigation example also uses data to make a prediction.

The AI assistant is different because it generates new content, such as a summary, based on the input it receives.

### What makes AI different from a program that simply follows explicit instructions?

A traditional program usually follows rules that are directly written by the programmer. It gives an output based on those instructions. An AI system can learn patterns from data or generate an output based on what it has learned or been trained on. So, an automated program is not automatically AI just because it looks intelligent.

### E - Evidence

I checked the classification and reasoning using the Week 1 assignment requirements and reviewed the difference between traditional rule-based software, machine learning, and generative AI.

### V - Verification

I checked each example separately instead of assuming that every automated system is AI. I verified that the calculator and temperature warning use fixed instructions, while spam detection and ETA prediction use data-based patterns or predictions. I also checked that generating a document summary fits the idea of Generative AI.

### R - Reflection

Before this question, I sometimes thought that any smart-looking software was AI. Now I understand that some programs are just following fixed rules. The important difference is whether the system is using learned patterns or generating content instead of only following predefined instructions.



## Q3 - What Happens When You Ask an LLM a Question?

### A - Answer

When a user sends a question to an LLM, the model processes the prompt and generates a response step by step. It uses patterns learned during training to predict what text should come next.

### Simple flow

```text
Prompt
  ↓
Tokens
  ↓
Model processing
  ↓
Probability distribution
  ↓
Next-token selection
  ↓
Generated response
```

### What each stage means

- Prompt: The prompt is the input given by the user. It can be a question, instruction, or request.

- Tokens: The model breaks the input into smaller pieces called tokens. A token can be a word, part of a word, or a symbol.

- Context: Context is the information available to the model while generating the response. It helps the model understand the question and the information already given in the conversation.

- Model processing: The language model processes the tokens and uses patterns learned during training to determine what should come next.

- Probability: The model gives different possible next tokens different probabilities. Some tokens are more likely than others based on the context.

- Next-token prediction: The model predicts a likely next token and continues this process to build the response.

- Generated response: The selected tokens are combined to produce the response shown to the user.

### Training vs Inference

Training is the stage where the model learns patterns from large amounts of data.

Inference is when the trained model is used to process a user's prompt and generate a response.

### Why can an LLM give a fluent but incorrect answer?

An LLM can produce a response that sounds clear and confident even when the information is wrong or unsupported. This is because the model predicts likely text based on patterns learned during training. It does not automatically verify every statement against a reliable source. Because of this, an answer can sound correct while still containing mistakes.

### E - Evidence

I checked my explanation using a reliable educational source about large language models and how they generate text.

Source:
- [IBM Think - What are Large Language Models (LLMs)?](https://www.ibm.com/think/topics/large-language-models)

### V - Verification

I checked that my explanation includes all the main stages given in the assignment: prompt, tokens, model processing, probability distribution, next-token prediction, and generated response. I also checked the difference between training and inference and verified why an LLM can produce fluent but incorrect information.

### R - Reflection

Before this question, I thought an AI chatbot mainly searches for an answer and gives it to me. Now I understand that an LLM processes the input and predicts the next tokens to build a response. I also learned that a fluent answer is not always a correct answer, so I should verify important information instead of trusting the response immediately.
