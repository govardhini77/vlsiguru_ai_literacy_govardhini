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



## Q4 - Hallucination Experiment: Can AI Sound Confident and Still Be Wrong?

### A - Answer

For this experiment, I asked the same factual question to two different AI assistants and then checked their answers using an independent reference source.

Question asked:

What is the SI unit of electrical resistance?

### Experiment results

| AI Assistant | Response summary | Verified claim | Evidence | Result |
|---|---|---|---|---|
| ChatGPT | The SI unit of electrical resistance is the ohm (Ω). | The SI unit of electrical resistance is the ohm. | NIST SI Units | Correct |
| Gemini | The SI unit of electrical resistance is the ohm (Ω). It also explained the relationship as 1 Ω = 1 V / 1 A. | The SI unit of electrical resistance is the ohm. | NIST SI Units | Correct |

### E - Evidence

I checked the answer using the National Institute of Standards and Technology (NIST). NIST identifies the ohm (Ω) as the SI unit of electrical resistance.

Source:
- [NIST - SI Units](https://www.nist.gov/pml/owm/metric-si/si-units)

### V - Verification

Both AI assistants gave the same answer, and the answer matched the information from the NIST reference. Gemini also gave the relationship between resistance, voltage, and current, which is consistent with the definition of the ohm.

No incorrect or unsupported claim was found in this particular test.

### R - Reflection

This experiment showed me that an AI response can sound clear and confident, but it is still important to check factual information with a reliable source. In this test, both AI assistants gave a correct answer, so the experiment did not expose a hallucination. However, checking the answer against an independent source helped confirm that the information was accurate.



## Q5 - AI Assistant vs Search vs Authoritative Reference

### A - Answer

Question:

What is the difference between SRAM and DRAM?

I investigated the same question using an AI assistant, a web search, and an authoritative technical reference.

### Comparison

| Method | Answer / Findings | Accuracy | Explanation | Traceability | Ease of verification |
|---|---|---|---|---|---|
| Gemini | SRAM uses flip-flops and does not need refreshing. DRAM uses a transistor and capacitor and needs periodic refreshing. SRAM is faster and more expensive, while DRAM is cheaper and has higher density. | Good | Detailed comparison with a table | Moderate | Easy |
| Google Search | The search results showed that SRAM is faster and more expensive and does not need refreshing. DRAM is slower, cheaper, and needs refreshing. | Good | Clear summary and comparison table | Good | Easy |
| Intel technical reference | Intel explains that a typical SRAM cell uses six transistors and does not need refreshing, while a typical DRAM cell uses one transistor and one capacitor and requires periodic refreshing. Intel also compares speed, cost, capacity, and typical use. | High | Technical and detailed | High | Easy |

### E - Evidence

The Google search results were useful for quickly finding the main differences between SRAM and DRAM.

For the authoritative reference, I used Intel technical documentation. It explains the structure and operation of SRAM and DRAM and compares their speed, cost, capacity, and typical applications.

Source:
- [Intel - External Memory Interface Handbook](https://cdrdv2-public.intel.com/737517/emi-16.1-710283-737517.pdf)

### V - Verification

I compared the important claims from the AI answer and Google search with the Intel reference. The main points matched: SRAM does not require periodic refresh and is generally faster and more expensive, while DRAM requires refresh and is generally denser and lower cost.

The authoritative reference was more useful for verification because it provides technical details and explains the memory cell structures.

### R - Reflection

This comparison showed me that AI is useful for getting a quick explanation, while search is useful for finding different sources and information. An authoritative reference is more useful when I need to confirm an important technical claim. I would use AI for understanding a topic, search for finding information, and a primary or authoritative source before making an important engineering decision.



## Q6 - What Is an AI Agent?

### A - Answer

An AI agent is a system that can use an AI model along with tools and actions to complete a task. A simple chatbot mainly responds to a user's message, while an agent can take additional steps and use tools when needed.

### Five important ideas

LLM:

A Large Language Model is an AI model that understands and generates text. It can answer questions, explain concepts, and generate different types of text.

LLM application:

An LLM application is a software application that uses an LLM to provide a specific function. For example, a customer support application can use an LLM to answer customer questions.

RAG system:

RAG stands for Retrieval-Augmented Generation. It retrieves relevant information from a knowledge source and provides that information to the LLM so that it can generate a response using the retrieved context.

Tool-using assistant:

A tool-using assistant is an AI system that can use external tools to perform tasks or get information. For example, it may use a calculator, database, or search tool.

AI agent:

An AI agent is a system that can use a model, tools, and a workflow to work toward a goal. It can decide what step to take next based on the task and the results it receives.

### Comparison

| System | Main purpose | Uses external information or tools? | Can work through multiple steps? |
|---|---|---|---|
| LLM | Understands and generates text | Not by itself | No |
| LLM application | Uses an LLM for a specific function | Depends on the application | Depends on the application |
| RAG system | Retrieves information and uses it to generate a response | Yes | Limited to the retrieval and response process |
| Tool-using assistant | Uses external tools to get information or perform tasks | Yes | Yes, depending on the workflow |
| AI agent | Works toward a goal using a model, tools, and multiple steps | Yes | Yes |

### Simple architecture

```text
User request
     ↓
AI model
     ↓
Decide whether a tool is needed
     ↓
Tool call
     ↓
Tool result
     ↓
Decision / next step
     ↓
Final response
```

### Agent vs simple chatbot

A simple chatbot mainly generates a response to a user's message. An AI agent can do more than generate text. It can use tools, receive the results, decide what to do next, and continue through multiple steps to complete a task.

### Non-VLSI example

A travel planning agent is one simple example. A user can ask it to plan a trip. The agent can search for travel information, check hotel availability, compare options, and prepare a final travel plan based on the information it finds.

### E - Evidence

I checked this explanation using a reliable reference about AI agents and how they use models, tools, and actions.

Source:
- [IBM Think - What Are AI Agents?](https://www.ibm.com/think/topics/ai-agents)

### V - Verification

I checked that the explanation includes all five concepts required in the question. I also checked that the architecture shows the flow from the user request to the AI model, tool call, tool result, decision, and final response. The comparison also shows how an AI agent differs from an LLM, LLM application, RAG system, and tool-using assistant.

### R - Reflection

I learned that an AI agent is more than a chatbot that generates text. An agent can use tools and work through multiple steps to complete a task. This helped me understand why agents can be useful for more complex workflows.




## Q7 - Where Should Humans Still Make the Decision?

### A - Answer

AI can be useful for reading documents, answering questions, summarizing information, generating text, and suggesting actions. However, there are situations where a human should still check and approve the result before taking action.

### Situations requiring human verification

| Situation | Possible failure | Required verification | Who/what approves the result |
|---|---|---|---|
| Medical information or health advice | The AI may give incorrect or incomplete information. | Check with a qualified medical professional or reliable medical source. | Medical professional |
| Financial decision | The AI may misunderstand financial information or give an unsuitable suggestion. | Check the information with official financial sources and relevant records. | Person making the decision or qualified financial professional |
| Engineering calculation or design | A wrong calculation or assumption could cause a technical failure. | Recalculate and test the result using reliable technical references or engineering tools. | Engineer |
| Important legal or official document | The AI may misunderstand requirements or include incorrect information. | Check the document against official requirements or legal sources. | Responsible person or qualified professional |
| Safety-related instruction | Incorrect information could create a safety risk. | Check the instruction against official safety procedures and reliable documentation. | Responsible safety authority or qualified person |

### E - Evidence

I checked this explanation using the National Institute of Standards and Technology (NIST) AI Risk Management Framework. NIST explains that trustworthy AI requires attention to risks, reliability, safety, accountability, and human oversight.

Source:
- [NIST - AI Risk Management Framework](https://www.nist.gov/itl/ai-risk-management-framework)


### V - Verification

I checked that each situation includes a possible failure, a way to verify the information, and a person or source responsible for approving the final result. I also made sure the examples cover different types of decisions where an incorrect AI response could have important consequences.

### R - Reflection

I learned that using AI does not remove human responsibility. AI can help with information and suggestions, but a person should verify important results before acting on them. The level of verification should depend on how serious the possible consequences are.

### Responsible AI rule

I will use AI to assist with important decisions, but I will verify the evidence and keep the final decision with a responsible human when the consequences of an error are significant.



## Q8 - Find AI Around You

### A - Answer

AI and machine learning are already used in many applications that I use in everyday life. I checked some common examples and looked for public information about how they work.

### Examples

| System / Application | AI involvement | Task type | Evidence / Source | My conclusion |
|---|---|---|---|---|
| Google Maps | Yes, machine learning is used | Prediction | Google explains that Maps uses machine learning to predict traffic and travel times. | AI/ML is involved in predicting travel time and traffic conditions. |
| Gmail spam filter | Yes, machine learning is used | Classification | Google explains that Gmail uses machine learning to identify emails that are likely to be spam. | AI/ML is involved in classifying emails as spam or not spam. |
| Spotify recommendations | Yes, machine learning is used | Recommendation | Spotify explains that machine learning is used to personalize music and podcast recommendations. | AI/ML is involved in recommending content based on user activity and preferences. |
| iPhone Face ID | Yes, machine learning is used | Recognition | Apple explains that Face ID uses machine learning for face recognition. | AI/ML is involved in recognizing and matching the user's face. |
| Apple Photos people recognition | Yes, machine learning is used | Recognition | Apple explains that Photos uses machine learning to recognize people in photos. | AI/ML is involved in identifying people in images. |

### A simpler rule-based example

Gmail spam filtering is an example where a simpler rule-based approach could also be used. For example, a basic system could mark an email as spam if it contains certain words or comes from a blocked sender.

However, Google explains that machine learning can learn patterns from email data and adapt to new spam patterns. This makes it different from only using a fixed list of rules.

### E - Evidence

I checked the examples using information published by the companies that provide these services.

Sources:

- [Google - How AI helps Google Maps predict traffic and determine routes](https://blog.google/products-and-platforms/products/maps/google-maps-101-how-ai-helps-predict-traffic-and-determine-routes/)

- [Google - How machine learning in Gmail helps identify spam](https://blog.google/products-and-platforms/products/workspace/how-machine-learning-g-suite-makes-people-more-productive/)

- [Spotify Engineering - How Spotify uses ML for personalization](https://www.engineering.atspotify.com/2021/12/how-spotify-uses-ml-to-create-the-future-of-personalization)

- [Apple Support - About Face ID advanced technology](https://support.apple.com/en-in/102381)

- [Apple Machine Learning Research - Recognizing People in Photos](https://machinelearning.apple.com/research/recognizing-people-photos)

### V - Verification

I checked the public information from Google, Spotify, and Apple before deciding that these examples use AI or machine learning. I did not assume that a feature is AI just because it looks smart. The sources specifically mention machine learning or AI being used for these features.

### R - Reflection

I learned that AI is already part of many applications I use every day. Before this question, I did not think much about things like spam filtering, map predictions, music recommendations, and face recognition as AI systems. I also learned that not every automated feature needs AI because some simple tasks can be done using fixed rules.



## Q9 - Prediction, Classification, and Generation

### A - Answer

The three task types are Prediction, Classification, and Generation. Some real AI systems can use more than one type, but here I classified each example based on its main task.

### Classification

| Example | Task type | Reason |
|---|---|---|
| A. Predicting house prices | Prediction | The system estimates a future or unknown house price using available information such as location, size, and other features. |
| B. Detecting whether an image contains a cat | Classification | The system decides which category the image belongs to, such as cat or not cat. |
| C. Writing an email from a short instruction | Generation | The system creates new text based on the instruction given by the user. |
| D. Predicting whether a customer will cancel a subscription | Prediction | The system estimates whether the customer is likely to cancel based on available data. |
| E. Summarizing a research paper | Generation | The system creates a shorter version of the original text while keeping the main points. |
| F. Identifying whether a transaction is fraudulent | Classification | The system classifies the transaction as fraudulent or not fraudulent. |
| G. Generating an image from a text description | Generation | The system creates a new image based on the text description. |
| H. Predicting the next word/token in a sentence | Prediction | The model predicts which token is likely to come next based on the previous context. |

### Why is next-token prediction important?

Next-token prediction is a basic part of how modern language models generate text. The model looks at the tokens that came before and predicts what token should come next.

The model repeats this process one token at a time. This can produce longer outputs such as emails, summaries, answers, and code. So even though the final application may look like writing or question answering, the model is still generating the response by predicting the next token step by step.

### E - Evidence

I checked the explanation of next-token prediction using a technical educational source about large language models.

Source:
- [IBM Think - What are Large Language Models (LLMs)?](https://www.ibm.com/think/topics/large-language-models)

### V - Verification

I checked each example based on its main task. Prediction is used when the system estimates an unknown or future value, classification is used when it selects a category, and generation is used when it creates new content.

I also checked that the explanation of next-token prediction matches the basic working idea of a language model.

### R - Reflection

This question helped me understand the difference between prediction, classification, and generation. I also understood that many things that look different, such as writing an email and answering a question, can use the same basic next-token prediction process.



## Q10 - Design Your Personal AI Verification Protocol

### A - Answer

If I use an AI assistant for engineering work, I will not directly trust the result. I will check it step by step before using it.

### My AI Verification Flow

```text
AI-generated result
        ↓
1. Define the problem
        ↓
2. Inspect the AI output
        ↓
3. Check assumptions
        ↓
4. Check evidence / source
        ↓
5. Test the result
        ↓
6. Compare and recheck
        ↓
7. Accept / Reject / Revise
        ↓
Use the verified result
```

### 7-step verification process

| Step | What I will do | Why I will do it | Failure it can catch |
|---|---|---|---|
| 1. Define the problem | Clearly understand what I need to solve and what result I need. | To make sure I am solving the correct problem. | Wrong or unclear problem |
| 2. Inspect the AI output | Read the answer carefully and check what the AI has given me. | An AI answer can look correct even when it has mistakes. | Accepting the answer without checking |
| 3. Check assumptions | Look at the assumptions made by the AI and see if they are suitable for my problem. | Wrong assumptions can lead to a wrong answer. | Hidden or incorrect assumptions |
| 4. Check evidence / source | Check important facts using reliable sources such as official documentation, standards, or trusted technical references. | AI can give information that is unsupported or incorrect. | False or unsupported information |
| 5. Test the result | Test calculations, examples, code, or other results when possible. | Testing helps check whether the result actually works. | Calculation errors, wrong logic, or incorrect results |
| 6. Compare and recheck | Compare the AI result with the information I verified and check any differences. | This helps me find mistakes before making a final decision. | Missing differences or mistakes |
| 7. Accept / Reject / Revise | Decide whether to accept the result, reject it, or revise it before using it. | The final decision should be based on verification, not only on the AI answer. | Using an unverified result |

### Worked example

Suppose I ask an AI assistant:

"Five notebooks cost ₹60 each. What is the total cost?"

The AI answers ₹300.

First, I check the problem and the given price. Then I calculate it myself:

5 × ₹60 = ₹300

The result matches, so I can accept the answer.

If the AI had given ₹350, I would reject that result, check the calculation again, and use the corrected answer of ₹300.

### E - Evidence

I followed the Week 1 assessment guidance for creating a verification process. The assessment says the process should include defining the problem, inspecting assumptions, checking evidence or sources, testing the result, and deciding whether to accept, reject, or revise the output.

### V - Verification

I checked my seven steps against the requirements in the assignment. The process includes all the required parts: defining the problem, checking assumptions, checking evidence, testing the result, and making a final accept, reject, or revise decision.

### R - Reflection

I learned that an AI answer should not be treated as the final answer immediately. Checking the problem, assumptions, sources, and result can help me find mistakes before using the information. I can use this process for my future engineering work as well.
