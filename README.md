EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

1. Zero-Shot Prompt

Prompt:
“Summarize the article ‘Basics of Blockchain Technology’ in about 100 words for undergraduate students.”

ChatGPT Output

Blockchain is a decentralized digital ledger used to record transactions across multiple computers. Each transaction is stored in a block, and blocks are connected in chronological order to form a chain. Cryptographic techniques ensure the data is secure and cannot easily be changed. Blockchain is best known for supporting cryptocurrencies like Bitcoin, but it also has applications in areas such as finance, supply chain management, healthcare, and digital identity. The technology improves transparency and trust, although challenges such as energy consumption and scalability still limit widespread adoption.

Gemini Output

Blockchain technology is a distributed system used to securely record digital transactions. Instead of storing data in a central database, it shares information across many computers in a network. Each transaction is verified by participants and stored in blocks linked together as a chain. This structure ensures transparency and reduces the risk of data manipulation. Blockchain is widely used in cryptocurrencies like Bitcoin and is increasingly applied in industries such as banking, healthcare, and logistics to improve data security and traceability.

Claude Output

Blockchain is a decentralized ledger that records transactions across a network of computers. Data is stored in blocks that are cryptographically linked, creating a secure and tamper-resistant chain. Consensus mechanisms such as Proof of Work help validate transactions before they are added to the ledger. While blockchain gained popularity through cryptocurrencies like Bitcoin, it also supports applications in supply chain tracking, financial services, and secure data sharing.

2. Few-Shot Prompt

Prompt:
Example: “Artificial Intelligence helps doctors analyze medical data quickly.”
Now summarize the blockchain article in the same simple style.

ChatGPT Output

Blockchain helps store digital transactions safely. It keeps records across many computers instead of one central system. Each record is stored in a block and connected to others to form a chain. This system increases security and transparency. Blockchain is used in cryptocurrencies and also helps industries like finance and supply chains track information reliably.

Gemini Output

Blockchain is a technology that records transactions across multiple computers. Instead of relying on a central authority, the system shares data across a network. Each transaction becomes part of a secure chain of blocks. This improves trust and transparency in digital systems. It is commonly used in cryptocurrency and data tracking applications.

Claude Output

Blockchain is a secure digital record system shared across many computers. Transactions are grouped into blocks and connected to form a chain. This design prevents easy tampering and builds trust in the data. Blockchain is used for cryptocurrencies and also helps businesses track products and manage digital records.

3. Chain-of-Thought Prompt

Prompt:
Step 1: Identify key blockchain concepts.
Step 2: Extract important ideas.
Step 3: Write a clear 100-word summary.

ChatGPT Output

Blockchain technology is a decentralized system that records transactions securely across a network of computers. Each transaction is grouped into a block, and blocks are linked using cryptographic hashes. This design ensures transparency and prevents data from being easily modified. Transactions are validated using consensus mechanisms such as Proof of Work or Proof of Stake. Blockchain is widely used in cryptocurrencies but also supports applications in finance, supply chain tracking, and healthcare data management. Although the technology provides security and trust, issues like energy consumption and scalability remain challenges for global adoption.

Gemini Output

Blockchain works by storing transaction records in blocks connected through cryptographic hashes. These blocks are distributed across a network where participants verify transactions using consensus mechanisms. Because all nodes maintain copies of the ledger, the system becomes transparent and resistant to tampering. Blockchain technology powers cryptocurrencies but also supports applications such as product tracking in supply chains and secure medical data storage. Despite its advantages, challenges including high computational costs and limited scalability must be addressed.

Claude Output

Blockchain technology records digital transactions using a distributed network of computers rather than a centralized system. Each verified transaction is placed in a block and connected to the previous block through cryptographic hashing. Consensus algorithms ensure that network participants agree on the transaction’s validity. This architecture makes blockchain secure and transparent. While it became popular through cryptocurrencies, it is also used in industries like logistics, finance, and healthcare to improve traceability and trust in digital records.

4. Role-Based Prompt

Prompt:
“You are a university professor explaining blockchain technology to first-year students. Write a simple summary.”

ChatGPT Output

Blockchain is a digital system used to record transactions in a secure and transparent way. Instead of being controlled by a single organization, it is maintained by many computers working together. Transactions are stored in blocks that are linked together like a chain. This structure prevents data from being easily changed and helps build trust. Blockchain is best known for powering cryptocurrencies but is also used in fields like healthcare, finance, and supply chain management.

Gemini Output

Imagine a shared digital notebook that many computers maintain together. That is similar to how blockchain works. Every transaction is written into a block and linked to earlier blocks, forming a chain. Because many computers verify the information, it becomes difficult to alter the records. Blockchain is widely used in cryptocurrency systems and is also applied in industries that require secure and transparent data tracking.

Claude Output

Blockchain can be understood as a shared record book that is maintained by many computers across a network. Every transaction is recorded in a block, and blocks are connected sequentially to form a secure chain. This system prevents unauthorized changes and improves transparency. Although blockchain is most famous for cryptocurrencies, it is also useful in areas such as finance, supply chain monitoring, and digital identity systems.

Summary Table :
| Platform | Accuracy | Coherence | Simplicity | Speed | User Experience |
| -------- | -------- | --------- | ---------- | ----- | --------------- |
| ChatGPT  | 5        | 5         | 5          | 5     | 5               |
| Gemini   | 4        | 4         | 4          | 4     | 4               |
| Claude   | 5        | 5         | 4          | 3     | 4               |


RESULT:
The experiment compared summarization outputs from ChatGPT, Google Gemini, and Claude using different prompting techniques (Zero-shot, Few-shot, Chain-of-thought, and Role-based).

From the evaluation based on accuracy, coherence, simplicity, speed, and user experience, ChatGPT produced the best overall summaries with high clarity and faster response time. Claude generated highly accurate and detailed summaries, but its response speed was slightly slower. Gemini provided balanced performance, delivering clear and simple summaries with moderate accuracy and speed.

Therefore, ChatGPT with role-based prompting was found to be the most effective combination for generating student-friendly summaries of technical content.
