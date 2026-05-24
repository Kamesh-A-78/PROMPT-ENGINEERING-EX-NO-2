# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.
# zero shot:
 # chatgpt:
 Zero-shot learning is a technique where an AI model performs a task without prior examples or training for that specific task.It uses its existing knowledge and understanding of patterns to make predictions or generate responses. For example, a chatbot answering a completely new type of question without being trained on similar examples.It helps AI systems generalize and work efficiently on unseen tasks.
 # Gemini:
 Zero-shot learning is an AI's ability to complete tasks it has never specifically practiced by leveraging its
existing conceptual knowledge. Instead of relying on a library of labeled examples, the model uses semantic reasoning to connect a new request to the vast patterns it observed during its initial training.
# grok:
Zero-shot prompting is a technique where you ask an AI model to perform a task without providing any examples or prior demonstrations. The model relies entirely on its pretrained knowledge to understand and generate the desired output. This approach is efficient and fast because it requires minimal input tokens.

# few shot:
# chatgpt:
 Few-shot learning is a technique where an AI model learns a task using only a small number of examples. The model uses these examples as guidance to understand the pattern and generate accurate results. For example, giving a chatbot 2–3 sample question-answer pairs before asking a new question. It improves performance when large training data is not
available.
# Gemini:
Few-shot learning is a technique where an AI is provided with a small number of specific examples (usually between two and five) to help it understand a pattern or format before performing a task. Unlike zero-shot, which relies purely on pre-existing knowledge, this method uses "in-context learning" to narrow down exactly how the user wants a problem solved. 
# grok:
Few-shot prompting involves giving the model a small number of examples (usually 1–5) within the prompt before asking it to complete a similar task. These examples help the model identify the pattern, format, and reasoning style required. It significantly improves consistency and accuracy compared to zeroshot, especially for tasks with specific output formats.

# chain of thought:
# chatgpt:
Chain-of-thought prompting is a technique where an AI model solves a problem by explaining the reasoning step by step. Instead of giving only the final answer, the model shows the intermediate thinking process.
This method improves accuracy in complex tasks like mathematics, logic, and problemsolving.For example, the AI explains each calculation step before giving the final result.

# Gemini:
Chain-of-Thought (CoT) prompting is a technique that encourages an AI to break down complex problems into a series of intermediate reasoning steps before arriving at a final answer. By explicitly "thinking out
loud," the model mimics human problem-solving, which significantly improves its performance on tasks involving math, logic, or multi-step common sense reasoning.

# grok:
Chain-of-Thought prompting encourages the model to break down complex problems into intermediate reasoning steps before arriving at the final answer. By adding phrases like “Let’s think step by step,” the model generates explicit reasoning chains that mimic human problem-solving. 

# role based:

# chatgpt:
Role-based prompting is a technique where the AI is assigned a specific role or personality before performing a task. The role helps the model generate responses in a suitable style, tone, and expertise level. For example, telling the AI “Act as a teacher” or “Act as a career advisor.”.
# Gemini:
Role-based prompting is a technique where you assign a specific persona, profession, or identity to an AI to frame its perspective and tone before it answers a query. By telling the model to "Act as a Senior Software Engineer" or "Speak like a 17th-century pirate," you narrow its focus to a specific domain of knowledge and a particular style of communication.

# grok:
Role-based prompting assigns a specific persona, expertise level, or character to the AI before giving it instructions. For example, “You are a world-class cardiologist with 20 years of experience” or
“Act as a friendly high-school physics teacher.” This framing helps the model adopt the right tone, depth, and perspective for the response.

Here are the overall average scores for all 12 combinations:
## OUTPUT:

<img width="903" height="652" alt="Screenshot 2026-05-24 100828" src="https://github.com/user-attachments/assets/c1e57a25-2882-48d8-af9b-d55b76fa22c6" />

## RESULT: 
hence evaluated and compared the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.
