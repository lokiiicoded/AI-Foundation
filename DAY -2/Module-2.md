# Module 2: In-Depth Study of Generative AI, LLMs, Transformers, Prompt Engineering, and Vector Search

## 🌐 What is Generative AI?

Generative AI refers to algorithms that can generate new content based on the patterns learned during training.  
It creates realistic outputs such as text, images, or even code.

### ✅ Popular Generative AI Examples
- **ChatGPT** – Text generation chatbot.
- **DALL·E** – Generates images from text prompts.
- **Codex** – Code generation AI.

---

## 📚 Large Language Models (LLMs)

### 🔧 How do LLMs Work?
- Trained on massive datasets (books, articles, web pages).
- Learn statistical patterns in language.
- Can perform tasks like:
  - Text generation
  - Summarization
  - Question answering

### ⚡ Characteristics of LLMs
- Billions of parameters
- Few-shot learning capability
- Zero-shot inference

### 🌟 Examples
| Model  | Parameters | Speciality |
|--------|------------|-----------|
| GPT-4  | 175B       | Text generation, translation |
| PaLM   | 540B       | Multilingual, multi-modal tasks |
| LLaMA  | 65B        | Open-source alternative |

---

## ⚙️ Transformer Architecture

Transformers are the backbone of LLMs.

### 🔧 Components
1. **Self-Attention Mechanism**
   - Each token attends to every other token.
   - Attention formula:
     ```
     Attention(Q, K, V) = softmax(QK^T / √d_k) V
     ```

2. **Positional Encoding**
   - Since transformers lack sequence order inherently, positional encodings inject order information.

3. **Encoder-Decoder Structure**
   - Encoder encodes input sequence.
   - Decoder generates output sequence (common in translation).

### ✅ Why Transformers?
- Parallelizable (better performance vs RNN).
- Handles long-range dependencies.

---

## 📝 Prompt Engineering

Prompt Engineering is the art of crafting inputs to guide model output.

### 💡 Example Scenarios
- Zero-shot Prompt:
    ```
    "Translate the following English sentence to French: 'I am learning AI.'"
    ```

- Few-shot Prompt:
    ```
    Q: What is the capital of France?
    A: Paris

    Q: What is the capital of Germany?
    A: 
    ```

### ✅ Best Practices
- Be specific and clear.
- Use examples for few-shot learning.
- Chain-of-thought prompts improve reasoning.

---

## 🔍 Vector Search Explained

### 🧱 Why Vector Search?
Traditional keyword search fails to capture semantics.

### ⚡ Process
1. Convert text/data into embeddings using models like BERT, Sentence Transformers.
2. Store embeddings in vector databases (FAISS, Pinecone).
3. Retrieve similar items using similarity metrics:
   - Cosine similarity
   - Euclidean distance

### 🏆 Real-World Use Cases
- Semantic Search Engines
- Product Recommendations
- Document Retrieval in Knowledge Bases

---

## ✅ Summary of Module 2

Generative AI and Large Language Models are revolutionizing content creation and information retrieval.  
Transformers are at the core of modern NLP, enabling efficient and effective modeling of long-range dependencies.  
Prompt Engineering improves LLM task performance, and Vector Search makes retrieval semantically powerful.

---

## 🚀 Further Reading
- [Attention Is All You Need (Vaswani et al., 2017)](https://arxiv.org/abs/1706.03762)
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/)
- [FAISS Library for Vector Search](https://github.com/facebookresearch/faiss)
