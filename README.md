# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## SCENARIO:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## OUTPUT
Ai tools used are:
-Chat gpt
-Microsoft Copilot
-Claud
-Perplexity
-Gemini

Prompting Techniques in AI
1. Direct Prompting

This is the simplest form of prompting where the user gives a straightforward instruction to the AI. The AI responds based only on that single command, without any extra guidance or examples.
Example: “Summarize the blockchain article.”

2. Role-Based Prompting

In this technique, the user assigns a role or identity to the AI, such as a teacher, researcher, or student. This helps shape the tone, depth, and style of the response.
Example: “Act as a professor and explain blockchain to undergraduates.”

3. Structured Prompting

Structured prompting asks the AI to organize the response using headings, bullet points, or a fixed format. It improves clarity and logical flow.
Example: “Summarize the article under headings like Definition, Working, and Applications.”

4. Constraint-Based Prompting

This technique sets limits or rules for the output, such as word count, language simplicity, or formatting restrictions. It helps control the length and complexity of the response.
Example: “Summarize in 100 words using simple language.”

5. Chain-of-Thought Prompting

Here, the AI is encouraged to think step by step before giving the final answer. This improves reasoning and accuracy, especially for complex topics.
Example: “Identify the main ideas first, then write a clear summary.”

6. Few-Shot Prompting

Few-shot prompting provides one or more examples before asking the AI to perform the task. The AI learns the expected style or structure from those examples.
Example: “Here is a sample summary. Write a similar summary for blockchain.”

7. Zero-Shot Prompting

In zero-shot prompting, the AI is asked to perform a task without any examples or prior context. It relies entirely on its general knowledge.
Example: “Explain blockchain technology.”

8. Iterative Prompting

This involves refining the output through multiple prompts. The user gradually improves the response by asking for changes or clarifications.
Example: “Simplify the summary further” → “Make it more student-friendly.”

9. Audience-Focused Prompting

The user clearly specifies the target audience. The AI then adjusts vocabulary, depth, and explanation style accordingly.
Example: “Explain blockchain for non-technical undergraduate students.”

10. Comparative Prompting

This technique asks the AI to generate multiple versions or compare different outputs. It is useful for evaluation and selection of the best response.
Example: “Give both a technical and a simplified summary of blockchain.”

11. Evaluation-Driven Prompting

The AI is asked to review or self-check its own response for accuracy, clarity, or completeness. This improves output quality.
Example: “Create a summary and check whether all key points are included.”

12. Multi-Step Prompting

In this approach, the task is broken into clear stages, with each step handled separately. It helps manage complex tasks effectively.
Example: “First list key points, then simplify them, and finally write a summary.”

Key Observations
1. Accuracy

ChatGPT and Claude consistently preserved core blockchain concepts such as decentralization, blocks, cryptographic hashes, and immutability. Microsoft Copilot also demonstrated strong accuracy, especially when summarizing well-structured technical content, as it closely adhered to the original article’s key points. Perplexity occasionally introduced additional contextual or background information that was not explicitly present in the source article.

2. Coherence

Structured prompting significantly improved the logical flow and organization of summaries across all platforms. Claude performed particularly well in maintaining smooth transitions between ideas, producing summaries with a clear academic structure. Microsoft Copilot generated coherent summaries but sometimes followed a more rigid, document-style format compared to conversational models like ChatGPT.

3. Simplicity

ChatGPT was most effective at reducing technical jargon while preserving the original meaning, making its summaries highly suitable for undergraduate students. Gemini produced simple explanations but at times oversimplified certain technical aspects. Microsoft Copilot maintained clarity but occasionally used more formal or technical language, which may require minor simplification for beginner-level learners.

4. Speed

Gemini and Perplexity delivered the fastest responses, making them efficient for rapid content generation. Microsoft Copilot and ChatGPT showed moderate response times, while Claude was slightly slower. However, all platforms performed within acceptable time limits for educational content curation.

5. User Experience

ChatGPT offered the best overall user experience due to its clear formatting, adaptability to different prompting styles, and student-friendly tone. Microsoft Copilot provided a smooth experience, particularly in academic and document-based workflows, but felt less conversational. Claude’s responses were polished and detailed but appeared more academic, which may be slightly less engaging for undergraduate audiences.

GIVEN PROMPT AND OUTPUT TAKEN (Chat GPT):
1. Direct Prompting – Summary

Prompt used: “Summarize the article on blockchain technology.”

Summary:
Blockchain is a digital technology that records data in a secure and decentralized way. It stores information in blocks that are linked together to form a chain. Each block contains transaction data and a unique code called a hash. Because the data is distributed across many computers, it is difficult to change or hack. Blockchain is widely used in cryptocurrencies like Bitcoin and is also applied in areas such as supply chain management, healthcare, and finance.

2. Role-Based Prompting – Summary

Prompt used: “Act as a teacher and explain blockchain technology to undergraduate students.”

Summary:
Blockchain is a system used to store digital records safely without depending on a central authority. Information is grouped into blocks, and each block is connected to the previous one, forming a chain. Once data is added, it cannot be easily altered, which makes blockchain secure and trustworthy. This technology is best known for powering cryptocurrencies, but it is also useful in banking, voting systems, and tracking goods.

3. Structured Prompting – Summary

Prompt used: “Summarize the article under clear headings.”

Summary:

Definition:
Blockchain is a decentralized digital ledger used to record transactions securely.

How It Works:
Data is stored in blocks, and each block is linked using cryptographic hashes.

Key Features:
Transparency, security, decentralization, and immutability.

Applications:
Cryptocurrency, supply chain tracking, healthcare records, and finance.

4. Constraint-Based Prompting – Summary

Prompt used: “Summarize the article in 100 words using simple language.”

Summary:
Blockchain is a technology used to store information securely. It keeps data in blocks that are connected in a chain. Each block contains transaction details and cannot be easily changed. Blockchain does not rely on a single authority, making it more transparent and safe. It is mainly used in cryptocurrencies like Bitcoin but is also helpful in banking, healthcare, and supply chain management. This technology increases trust and reduces the risk of fraud.

5. Audience-Focused Prompting – Summary

Prompt used: “Explain blockchain for non-technical undergraduate students.”

Summary:
Blockchain is like a shared digital notebook that many people can see and trust. Once something is written in it, no one can easily erase or change it. This makes blockchain very secure. Instead of being controlled by one organization, it is shared among many computers. Blockchain is famous for supporting digital money, but it is also useful for keeping records safe in many industries.

6. Chain-of-Thought Prompting – Summary

Prompt used: “Identify key ideas step by step, then summarize.”

Summary:
Blockchain works by collecting transactions into blocks. These blocks are connected using cryptographic methods, making the data secure. Since the data is stored across many systems, it cannot be easily altered. This ensures trust and transparency. Blockchain is most commonly used in cryptocurrencies but is now expanding into fields like finance, healthcare, and logistics due to its reliability.

GIVEN PROMPT AND OUTPUT TAKEN (Copilot):

1. 🔹 Direct Prompting
Blockchain is a decentralized ledger that records transactions in blocks linked together by cryptographic hashes. Each block contains transaction data, a timestamp, and a hash of the previous block, ensuring immutability. The system relies on consensus mechanisms like Proof of Work or Proof of Stake to validate entries. Applications include cryptocurrencies, smart contracts, supply chain management, healthcare, and voting systems. Challenges include scalability, energy consumption, and regulatory uncertainty.

2. 🎭 Role-Based Prompting (Explained as a Teacher)
Imagine I’m your professor in class:
“Think of blockchain as a shared notebook where every student writes their transactions. Once a page is filled, it’s sealed with a unique code and attached to the previous page. No one can secretly change past entries because the codes won’t match. This makes blockchain trustworthy, transparent, and secure. Beyond Bitcoin, it’s used in logistics, healthcare, and even elections.”

3. 📑 Structured Prompting
Definition: Immutable, decentralized ledger.
Core Features:
- Decentralization
- Transparency
- Security
- Consensus
Process:
- Transaction initiated
- Verified by nodes
- Added to block
- Block hashed & linked
- Consensus achieved
- Ledger updated
Applications: Cryptocurrency, smart contracts, supply chain, healthcare, voting.
Challenges: Energy use, scalability, regulation.
Conclusion: Blockchain is a transformative technology with potential beyond finance.

4. ⚖️ Constraint-Based Prompting (Limited to 100 Words)
Blockchain is a decentralized ledger storing transactions in linked blocks. Each block has data, a timestamp, and a hash, making tampering nearly impossible. Consensus mechanisms like Proof of Work validate entries. Applications include cryptocurrency, smart contracts, supply chain tracking, healthcare, and voting. Advantages: transparency, security, reduced costs. Challenges: energy consumption, scalability, regulation. In short, blockchain is a secure, transparent, and decentralized system reshaping industries.

5. 🎯 Audience-Focused Prompting (For Undergraduates)
As students, you’ve probably heard of Bitcoin, but blockchain is much bigger. It’s like a group project where everyone keeps the same record, and no one can cheat. Each “page” of records is locked with a digital fingerprint and added to the chain. This technology ensures fairness and trust. Beyond crypto, it’s used to track products, secure medical records, and even run elections. The catch? It’s energy-hungry and hard to scale. But if solved, blockchain could revolutionize how we share and secure information.

6. 🔗 Chain-of-Thought Prompting
- Problem: Centralized systems are vulnerable to fraud and hacking.
- Idea: Distribute records across many computers.
- Mechanism: Store transactions in blocks, link them with hashes.
- Safeguard: Use consensus algorithms to ensure validity.
- Result: Immutable, transparent ledger.
- Applications: Finance, supply chain, healthcare, governance.
- Limitation: Energy use, scalability, regulation.
- Conclusion: Blockchain solves trust issues in digital systems but needs refinement for mass adoption.

GIVEN PROMPT AND OUTPUT TAKEN:(Claud)

Zero-Shot Prompting
Prompt:
Summarize this article about blockchain technology for undergraduate students in 3-4 sentences.

Output:
Blockchain is a distributed digital ledger that records transactions across multiple computers instead of a single server. Each transaction is grouped into blocks that are cryptographically linked together, creating an immutable chain that cannot be altered without network consensus. This decentralized approach makes blockchain more secure and transparent than traditional databases. While originally developed for cryptocurrencies like Bitcoin, blockchain now has applications in finance, supply chains, healthcare, and digital identity systems.

When to use: Simple, straightforward tasks where the desired output is clear.

Few-Shot Prompting
Prompt:
Here are examples of good article summaries for undergraduate students

Output:
Blockchain is a distributed ledger system where transactions are recorded across multiple computers rather than a single server. Each transaction is grouped into cryptographically-linked blocks forming an immutable chain that prevents tampering. Originally created for Bitcoin, blockchain now supports applications in banking, supply chain tracking, and secure data management. The technology's decentralized nature eliminates the need for central authorities while maintaining transparency and security.

When to use: When you want a specific format, tone, or style that's best shown through examples.

Chain-of-Thought Prompting
Prompt:

Summarize this blockchain article for undergraduates. Think through this step-by-step:
1. First, identify the main concept
2. Then, explain how it works technically
3. Next, note why it matters
4. Finally, give real-world applications

Show your thinking for each step, then provide the final summary.

Output:

Blockchain is a decentralized ledger technology that records transactions across multiple computers in cryptographically-linked blocks, creating a tamper-proof chain. Unlike traditional databases controlled by single entities, blockchain distributes data across a network, eliminating central points of failure while maintaining transparency and security. Originally developed for Bitcoin, the technology now enables applications in finance, supply chain management, healthcare, and digital identity systems.

When to use:Complex topics where showing reasoning improves understanding and accuracy.

Role-Based Prompting:
Prompt:
Assigning the AI a specific role or persona with domain expertise.

You are a computer science professor teaching Introduction to Emerging Technologies. Summarize this blockchain article for your undergraduate students who have basic programming knowledge but no prior blockchain experience. Make it educational and engaging.

Output:
Think of blockchain as a shared spreadsheet that no single person controls. In traditional systems, banks or companies manage databases on their servers—they're the single source of truth. Blockchain flips this: instead of one central database, identical copies exist on thousands of computers worldwide (called nodes). 

When you make a transaction, it's grouped with others into a "block." Each block gets a unique cryptographic fingerprint (hash) that depends on all the data inside it AND the previous block's fingerprint. This creates a chain where changing any historical data would break all the subsequent links—like trying to edit one page in a book without changing all the page numbers that follow. The network would immediately detect the mismatch.

This architecture makes blockchain incredibly secure and transparent. While Bitcoin made it famous, today's applications include tracking pharmaceutical supply chains to prevent counterfeits, managing medical records across hospitals, and enabling instant international payments without banks as intermediaries.

When to use:When targeting a specific audience or requiring domain-specific expertise.

Structured Output Prompting:
Prompt:
Summarize this blockchain article in the following structure

Output:
What it is: Blockchain is a distributed digital ledger that records transactions across multiple computers without a central authority.

How it works: Data is grouped into cryptographically-linked blocks that form a chronological chain. Each block contains a unique hash connecting it to the previous block, making historical records immutable. Changes require consensus from the network, preventing unauthorized tampering.

Key benefits:
• Decentralization – No single point of control or failure
• Immutability – Once recorded, data cannot be altered retroactively
• Transparency – All participants can verify transactions independently

Applications:
• Finance – Cryptocurrency transactions (Bitcoin), cross-border payments, trade settlements
• Supply Chain – Tracking goods from manufacture to delivery, preventing counterfeits
• Healthcare – Secure medical record sharing across providers while maintaining privacy

Bottom line: Blockchain removes the need for trusted intermediaries by using mathematics and distributed consensus to create secure, transparent, tamper-proof records.

When to use: When consistency and organization are critical, or when integrating with other systems.


Constraint-Based Prompting:
Prompt:
Summarize this blockchain article for undergraduates with these constraints:
- Maximum 100 words
- Avoid jargon like "cryptographic," "immutable," "consensus"
- Use analogies where helpful
- 8th-grade reading level

Output:
Blockchain is like a shared notebook that many people have copies of instead of one person controlling it. When someone makes a transaction, it gets written into a new page (called a block) that links to the previous page. Because everyone has a copy, no one can secretly change old entries—others would notice the mismatch. This makes blockchain very secure without needing banks or companies to verify everything. While Bitcoin made it famous, today it's used to track products, share medical records safely, and handle payments across countries.

When to use:When writing for specific audiences or meeting strict requirements (word count, reading level, compliance).

PROMPT GIVEN AND OUTPUT GIVEN:(Perplexity)

Direct Prompting
Simple instruction: "Summarize the basics of blockchain technology.

"Blockchain is a distributed ledger technology (DLT) that records transactions in blocks linked chronologically via cryptography. It operates without a central authority, using consensus mechanisms like proof-of-work to validate and add data immutably across a peer-to-peer network.Key elements include blocks (data + hash), chains (linked blocks), and nodes (computers maintaining copies). Applications span cryptocurrencies, supply chain tracking, and secure voting.

Structured Prompting
Uses headings and sections for organization.DefinitionBlockchain: Decentralized, immutable digital ledger for transaction records.
Core ComponentsBlocks: Contain transactions, timestamp, previous hash.Chain: Sequential links via hashes.Consensus: Network agreement (e.g., proof-of-work/stake).
BenefitsTransparency, security, no intermediaries; used in finance and logistics.

Constraint-Based Prompting
Limits to 150 words, 5 bullets, undergrad level, no jargon without definition.Blockchain = shared digital notebook for transactions, spread across computers (nodes), no boss in charge.Each page (block) lists deals + unique code (hash) matching last page.New pages added only if most computers agree (consensus, like voting).Can't fake changes: alters code, breaks chain, everyone notices.Why cool? Safe money (Bitcoin), track shipments honestly (under 150 words total).

Chain-of-Thought Prompting
Step-by-step reasoning before summary.First, identify core concept: blockchain as distributed ledger. Key traits? Decentralized (no central server), immutable (cryptographic chaining), transparent (public view). 
Next, explain mechanics: transactions → validation → block creation with hash → append to chain via consensus. 
Avoid errors: not just crypto, but any secure records. Simplify for undergrads: compare to tamper-proof receipt chain.
Benefits: trustless systems. 
Example: Bitcoin ledger.�
Now synthesize: Start with what/why, then how, end with uses.
Final Summary: Blockchain enables secure, shared record-keeping without middlemen by linking transaction "blocks" with unbreakable hash codes across a network. Nodes validate additions collectively, preventing fraud—perfect for digital currencies or supply tracking.

Zero-Shot Prompt
SummaryThis basic technique uses a simple instruction without examples.Blockchain is an advanced database that stores data in linked "blocks," forming a tamper-proof chain for tracking transactions like payments or orders. Unlike traditional databases controlled by one entity, it spreads data across a network of computers (nodes), requiring most nodes to agree (consensus) before adding a block—often via methods like proof-of-work where computers solve puzzles. Each block includes transaction details, a timestamp, and a unique hash linking it to the previous one; altering any data changes the hash, breaking the chain and alerting the network. This makes it immutable and ideal for uses like finance (secure payments), supply chains (tracking goods), and cryptocurrencies (Bitcoin). Key benefits include decentralization (no single failure point), transparency, and efficiency in audits.

Rubric-Driven Prompt
Summary This structures output around predefined criteria for clarity.1. What is Blockchain?A shared, append-only ledger distributed across nodes, storing transactions in chronological blocks linked by cryptographic hashes.
2. How Blocks Are AddedTransactions are recorded, validated by network consensus (e.g., majority approval), bundled into a block with a hash of the prior block, then shared across all nodes.
3. Why Tamper-Resistant?Hashes create an unbreakable chain; changing one block alters its hash and all following ones, requiring impossible network-wide consensus to approve.This ensures immutability, security via public-private keys, and trust without central authorities.

Role-Prompted 
Summary Imagine explaining to undergrads new to tech: as a friendly prof simplifying for a lecture.Hey students—blockchain is like a giant shared Google Doc that no one person controls, where every edit (transaction) gets stamped with a unique code (hash) and locked into a chain of pages (blocks). Picture buying coffee: your payment gets broadcast to café computers worldwide; they check it's legit via puzzles or votes, add it to the newest page, and everyone updates their copy instantly—no bank needed! It's super secure because messing with one page breaks the chain's codes, and transparent since all see the history. Real-world? Bitcoin for digital cash, or Walmart tracking food from farm to store to avoid outbreaks.

PROMPT GIVEN AND OUTPUT TAKEN:(Gemini ):
​1. Zero-Shot Prompt
​Purpose: Generating a broad, unbiased overview without providing examples.
​Summary: Blockchain is a decentralized, distributed ledger technology that records transactions across many computers so that the record cannot be altered retroactively. It relies on three pillars: decentralization, transparency, and immutability. By using cryptographic hashing to link "blocks" of data, it creates a secure chain that removes the need for third-party intermediaries like banks or government clearinghouses.

​2. Chain-of-Thought (CoT) Prompt
​Purpose: Breaking down the "why" and "how" for students who need to understand the logic.
​Step-by-Step Logic:
​The Problem: Traditional digital records are easy to copy or fake (the "double-spend" problem).
​The Solution: Create a ledger that everyone can see but no one can edit.
​The Connection: To ensure security, each block of data is assigned a unique digital fingerprint (hash).
​The Chain: Because Block B contains the hash of Block A, they become mathematically linked.
​The Result: Therefore, if you try to change Block A, Block B’s link breaks, alerting the entire network to the fraud.

​3. Structured Prompt
​Purpose: High scannability for students cramming or reviewing notes.
​## Blockchain 101
​Definition: A peer-to-peer shared database.
​Key Components:
​Node: A computer on the network.
​Consensus: The process by which nodes agree a transaction is valid.
​Mining: The act of adding new blocks (in specific networks).
​Primary Benefits: * Eliminates "Single Point of Failure."
​Reduces transaction costs by removing middlemen.

​4. Constraint-Based Prompt
​Purpose: Strict adherence to specific formats (e.g., word counts or reading levels).
​The "3-3-3" Summary:
​3 Keywords: Decentralized, Immutable, Cryptographic.
​3 Sentences: Blockchain is a shared digital record-keeper that no single person controls. It uses complex math to "lock" data into a chronological chain. This ensures that every transaction is permanent and visible to all members.
​3 Syllables or Less (Core Concept): "Trust the code."

​5. Direct Prompt
​Purpose: Getting straight to the point with zero fluff.
​Definition: Blockchain is a secure, decentralized record of transactions.
Function: It groups data into blocks, hashes them, and chains them together.
Impact: It enables trustless peer-to-peer exchanges of value or information.


## RESULT
The prompting techniques from various AI tools such as Chat gpt, Perplexity ,claud, Gemini and Copilot are analysed and verified.
