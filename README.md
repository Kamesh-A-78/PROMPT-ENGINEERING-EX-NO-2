# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.
# zero shot:
# Prompt
Summarize the following 500-word technical article on "The Basics of Blockchain Technology" for undergraduate students in approximately 150 words. Use simple language and focus on the key concepts.

# chatgpt:
Blockchain is a decentralized digital ledger that records transactions across multiple computers. Instead of relying on a central authority, blockchain uses a distributed network where each participant maintains a copy of the ledger. Transactions are grouped into blocks, which are linked together using cryptographic hashes to form a secure chain. Once data is added, it becomes difficult to alter, ensuring transparency and security. Consensus mechanisms such as Proof of Work and Proof of Stake help network participants agree on the validity of transactions. Blockchain technology is widely used in cryptocurrencies like Bitcoin but also has applications in supply chain management, healthcare, voting systems, and finance. Its key benefits include security, transparency, traceability, and reduced dependence on intermediaries. However, challenges such as scalability, energy consumption, and regulatory concerns remain barriers to widespread adoption.

 # Gemini:
 **Blockchain technology** is a decentralized, digital ledger that securely records transactions across a network of computers. Unlike traditional databases managed by a single institution, like a bank, blockchain operates on a peer-to-peer network, meaning no single entity has control.
Every transaction is grouped into a "block." Once verified by network participants through a process called consensus, this block is permanently linked to the previous one, forming a chronological "chain."
Three core principles make blockchain unique:
1. **Decentralization:** Data is shared across the entire network, eliminating a single point of failure.
2. **Transparency:** All participants can view the transaction history, which builds trust.
3. **Immutability:** Once data is written into a block, it is nearly impossible to alter or delete.
Ultimately, blockchain acts as a highly secure, tamper-proof system for exchanging value and data without relying on a middleman.

# grok:
**Blockchain Basics: A Simple Summary**
Blockchain is a revolutionary technology that works like a secure, shared digital notebook. Instead of one person or company controlling the records, it is **decentralized**—thousands of computers (called nodes) around the world keep identical copies of the ledger.
Information is stored in "blocks." Each block contains a list of transactions (like sending money or recording data). Once a block is full, it is linked to the previous block using advanced cryptography, forming a permanent **chain**. This linking makes the data nearly impossible to change or delete—hence the term **immutable**.
Security comes from **consensus mechanisms** (e.g., Proof of Work in Bitcoin), where participants must agree on which transactions are valid before adding them. This eliminates the need for trusted middlemen like banks.
Key benefits include **transparency** (everyone can see the ledger), **security** through encryption, and **trust** without central authority. 
Blockchain powers cryptocurrencies like Bitcoin, but also enables smart contracts (self-executing agreements), supply chain tracking, voting systems, and more. For beginners, remember: blockchain is essentially a tamper-proof, distributed database that builds trust in a digital world.

# few shot:
# Prompt
Example 1:
Article Topic: Cloud Computing
Summary: Cloud computing allows users to access computing resources such as storage, servers, and software over the internet. It offers scalability, flexibility, and cost savings.
Example 2:
Article Topic: Internet of Things (IoT)
Summary: IoT connects physical devices through the internet, enabling data collection, communication, and automation. It improves efficiency in homes, industries, and healthcare.
Now summarize the following article on "The Basics of Blockchain Technology" in a similar style and length.

# chatgpt:
Blockchain technology is a distributed digital ledger that securely records transactions across a network of computers. Transactions are stored in blocks, which are linked together using cryptographic techniques to maintain data integrity. Since the ledger is decentralized, no single organization controls the network, improving transparency and trust. Consensus algorithms ensure that all participants agree on transaction validity before new blocks are added. Blockchain is most commonly associated with cryptocurrencies such as Bitcoin, but it is also used in banking, healthcare, logistics, and digital identity systems. The technology offers benefits including enhanced security, transparency, and reduced reliance on intermediaries. Despite these advantages, challenges such as high energy consumption, limited scalability, and regulatory issues continue to affect its adoption.

# Gemini:
Blockchain technology is a decentralized digital ledger that securely records transactions across a network of computers. It offers transparency, enhanced security, and data immutability by eliminating the need for a central authority or middleman.

# grok:**Blockchain Technology**
Blockchain is a decentralized digital ledger that securely records transactions across a network of computers. Each transaction is grouped into blocks that are cryptographically linked in a chain, making the data transparent, immutable, and resistant to tampering. It eliminates the need for trusted intermediaries, enabling secure applications such as cryptocurrencies, smart contracts, and supply chain tracking.

# chain of thought:
Prompt

Read the article on "The Basics of Blockchain Technology."

Step 1: Identify the main concepts.

Step 2: Determine the purpose and applications of blockchain.

Step 3: Extract advantages and challenges.

Step 4: Create a concise summary for undergraduate students using the information gathered.

# chatgpt:
Main Concepts Identified:
Decentralized ledger
Blocks and cryptographic hashing
Consensus mechanisms
Security and transparency
Purpose and Applications:
Secure transaction recording
Cryptocurrency systems
Supply chain tracking
Healthcare records
Voting systems
Advantages:
High security
Transparency
Immutability
Reduced intermediaries
Challenges:
Scalability issues
Energy consumption
Regulatory uncertainty
Final Summary:
Blockchain technology is a decentralized system for recording and verifying transactions without requiring a central authority. Information is stored in blocks connected through cryptographic hashes, creating a secure and tamper-resistant chain. Consensus mechanisms ensure agreement among network participants before transactions are validated. While blockchain gained popularity through cryptocurrencies like Bitcoin, it is also used in industries such as healthcare, finance, and supply chain management. The technology provides enhanced security, transparency, and trust, but faces challenges related to scalability, energy usage, and regulations.

# Gemini:
Here is the breakdown of the foundational elements of blockchain technology based on your requested steps, designed specifically for undergraduate students.

### Step 1: Main Concepts

* **Distributed Ledger:** A shared database spread across multiple computers (nodes) globally, rather than a single central server.
* **Blocks and Chains:** Transactions are bundled into "blocks," which are permanently linked in a chronological "chain" using cryptography.
* **Consensus Mechanism:** Rules ensuring all nodes agree on the validity of new transactions before adding them to the chain.

### Step 2: Purpose and Applications

* **Purpose:** To enable secure, transparent, and direct peer-to-peer data or value transfer without requiring a trusted intermediary (like a bank or government).
* **Applications:** Cryptocurrency (Bitcoin, Ethereum), supply chain tracking, digital identity verification, secure medical records management, and automated legal agreements (smart contracts).

### Step 3: Advantages and Challenges

| Advantages | Challenges |
| --- | --- |
| **Immutability:** Data cannot be secretly altered once written. | **Scalability:** Transaction speeds can slow down significantly as the network grows larger. |
| **Transparency:** High auditability as every node holds an identical copy. | **Energy Consumption:** Certain consensus models (like Proof-of-Work) demand immense computational power. |
| **Security:** No single point of failure protects it from centralized hacks. | **Regulation & Adoption:** Unclear global legal frameworks slow down widespread corporate use. |

---

### Step 4: Concise Summary

Blockchain is a decentralized digital ledger that securely records transactions across a peer-to-peer computer network. By organizing data into chronologically linked blocks secured by cryptography, it guarantees data immutability and high transparency. Its primary purpose is to eliminate central middlemen, enabling direct trust between parties. While it offers groundbreaking security advantages for applications like finance and supply chains, the technology still faces significant technical challenges in network scalability and high computational energy demands.

# grok:
**Blockchain Technology**

Blockchain is a decentralized digital ledger that records transactions across a network of computers in a secure and transparent way. It organizes data into blocks that are cryptographically linked to form an immutable chain, making it extremely difficult to alter past records without network consensus.

**Main Concepts**: Key elements include decentralization (no single controlling authority), cryptographic hashing for security, consensus mechanisms (like Proof of Work) for validating transactions, and distributed copies maintained by nodes.

**Purpose and Applications**: Its primary purpose is to enable trustless, tamper-proof record-keeping. It powers cryptocurrencies like Bitcoin, smart contracts (self-executing agreements), supply chain tracking, identity management, secure voting, and more.

**Advantages and Challenges**: Advantages include enhanced transparency, security, reduced intermediaries, and efficiency. Challenges involve scalability issues, high energy consumption (in some systems), regulatory hurdles, and complexity for beginners.

In summary, blockchain revolutionizes how we handle data and trust in the digital world by providing a shared, unchangeable record without needing central authorities.
# role based:
# Prompt

You are a university professor teaching introductory computer science courses. Summarize the article "The Basics of Blockchain Technology" for first-year undergraduate students. Use clear explanations, simple terminology, and educational language.
# chatgpt:
Imagine a digital notebook that is shared among thousands of computers and cannot easily be changed. This is the basic idea behind blockchain technology. Blockchain is a decentralized digital ledger that stores records of transactions in blocks. Each block is connected to the previous one using cryptographic methods, creating a secure chain of information. Because many computers maintain copies of the ledger, no single organization controls it, making the system transparent and reliable. To ensure accuracy, blockchain networks use consensus mechanisms that allow participants to agree on valid transactions. Although blockchain is best known for supporting cryptocurrencies such as Bitcoin, it is also used in banking, healthcare, logistics, and voting systems. Its main advantages include security, transparency, and trust, while its major challenges involve scalability, energy consumption, and legal regulations.

# Gemini:

1. How the "Chain" Forms
When people make transactions, that data is bundled together into a digital container called a block. Once a block is full of data, it gets tightly locked using advanced math and is linked to the block that came right before it. This creates a chronological chain of blocks. Because each block is mathematically glued to the previous one, you cannot alter an old block without breaking the entire chain.

2. Decentralization (No Single Boss)
In a traditional system, like a bank, one central authority controls the ledger. If the bank's servers crash or get hacked, the system fails. Blockchain is decentralized, meaning an identical copy of this notebook is shared across a global network of thousands of computers (called nodes) simultaneously.

3. The Rules of Trust
If there is no boss, how do we know someone isn't cheating? Blockchain relies on two main pillars:

Consensus: Before any new block is added to the chain, the computers on the network must follow strict rules to agree that the transactions are valid.

Immutability: Once the network agrees and a block is added, the data becomes permanent. It cannot be edited, deleted, or forged.

Ultimately, blockchain's biggest achievement is that it allows two people who don't know each other to securely exchange value or data directly over the internet, completely eliminating the need for a middleman.

# grok:
**Blockchain Technology: A Simple Introduction for First-Year Students**

Hello everyone! Today, let's explore one of the most exciting technologies in computer science—**blockchain**. Imagine a shared digital notebook that everyone can see but no single person can secretly change. That's blockchain in a nutshell.

At its core, a **blockchain** is a decentralized digital ledger—a secure record-keeping system spread across many computers (called **nodes**) instead of being stored on one central server. Data is organized into **blocks**, each containing a list of transactions (such as sending money or recording information). These blocks are linked together using **cryptography** (advanced math-based security), forming an unbreakable **chain**. Once a block is added and verified by the network, it becomes nearly impossible to alter—making the record **immutable** (unchangeable).

How does it stay secure and trustworthy? Through **consensus mechanisms**, like Proof of Work, where computers in the network agree on which transactions are valid before adding them. This eliminates the need for middlemen like banks.

**Why does this matter?** Blockchain powers cryptocurrencies like Bitcoin, but its uses go far beyond that. It enables **smart contracts** (automatic digital agreements), transparent supply chains, secure voting systems, and more.

**Key benefits**: High transparency, strong security, and trust without a central authority. Like any new technology, it also faces challenges such as energy use and scalability.

Blockchain represents a fundamental shift in how we can build trustworthy systems in our digital world. As you continue in computer science, you'll see how it combines cryptography, distributed systems, and game theory in brilliant ways. Questions? Let's discuss!
Here are the overall average scores for all 12 combinations:
## OUTPUT:

<img width="903" height="652" alt="Screenshot 2026-05-24 100828" src="https://github.com/user-attachments/assets/c1e57a25-2882-48d8-af9b-d55b76fa22c6" />

## RESULT: 
hence evaluated and compared the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.
