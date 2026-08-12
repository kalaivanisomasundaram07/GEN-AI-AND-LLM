# CS4V48 - GENAI AND LLM LABORATORY

## **Experiment 1 - Text Generation Using Pre-Trained Foundation Models**

### **Sample Input**
`prompt = "Artificial Intelligence will transform the future of"`

### **Sample Output**
```text
--- Generated Text 1 ---
Artificial Intelligence will transform the future of healthcare, education,
and transportation by enabling smarter decision making and automating
repetitive tasks across industries.

--- Generated Text 2 ---
Artificial Intelligence will transform the future of work by creating new
job roles while automating routine processes in manufacturing and services.

---

## **Experiment 2 - Sentiment Analysis and Document Classification Using Foundation Models**

### **Sample Input**

`Two product reviews (sentiment) + one news sentence with candidate labels [Politics, Economy, Sports, Technology]`

### **Sample Output**

```text
Review: The new smartphone has an amazing camera and battery life!
-> POSITIVE (0.999)

Review: The delivery was late and the packaging was damaged.
-> NEGATIVE (0.998)

Document: The central bank raised interest rates to control rising inflation.
Economy: 0.94
Politics: 0.04
Technology: 0.01
Sports: 0.01
```
---

## **Experiment 3 - Conversational AI Chatbot Using Transformer-Based Language Models**

### **Sample Input**

```text
>> User: Hi, how are you? >> User: What can you help me with?
```

### **Sample Output**

```text
Bot: I'm doing great, thanks for asking! How about you?
Bot: I can chat with you about almost anything - just ask away!
```

---

## **Experiment 4 - Text Summarization and Question-Answering System Using Large Language Models**

### **Sample Input**

`Article about Generative AI and LLMs (see code) + Question: 'What are Large Language Models trained on?'`

### **Sample Output**

```text
Summary:
Generative AI models produce new content such as text, images, audio and video.
Large Language Models are trained on massive text corpora and perform many NLP tasks.
Question: What are Large Language Models trained on?
Answer: massive text corpora | Confidence: 0.87
```
---

## **Experiment 5 - Prompt Engineering Techniques for Content Generation, Reasoning and Task Automation**

### **Sample Input**

`Sentiment classification query and a two-step arithmetic word problem (see prompts above)`

### **Sample Output**

```text
=== Zero-shot ===
Sentiment: Positive

=== Few-shot ===
Review: 'The product quality is excellent!'
Sentiment: Positive

=== Chain-of-Thought ===
A: Let's think step by step. 120 - 45 = 75. 75 + 30 = 105. The answer is 105.
```

---

## **Experiment 6 - Retrieval-Augmented Generation (RAG) System Using Vector Databases**

### **Sample Input**

`query = "What is RAG in AI?"`

### **Sample Output**

```text
Retrieved Context: ['Retrieval-Augmented Generation combines document retrieval with
text generation.', 'Vector databases store embeddings and support fast similarity search.']
Answer: RAG combines document retrieval with text generation using vector databases.
```

---

## **Experiment 7 - AI-Powered Code Generation and Debugging Assistant**

### **Sample Input**

`Instruction: 'check if a number is prime' + buggy factorial() function initialised with result = 0`

### **Sample Output**

```text
Generated Function:
def is_prime(n):
    if n < 2:
        return False
    for i in range(2, int(n ** 0.5) + 1):
        if n % i == 0:
            return False
    return True

Debug Suggestion:
def factorial_fixed(n):
    result = 1
    for i in range(1, n+1):
        result = result * i
    return result
```

---

## **Experiment 8 - Image Generation Application Using Diffusion Models**

### **Sample Input**

`prompt = "A futuristic city skyline at sunset, digital art, highly detailed"`

### **Sample Output**

```text
Image generated and saved as generated_city.png
(A 512x512 PNG image showing a futuristic city skyline with warm sunset lighting is produced and saved to disk.)
```

---

## **Experiment 9 - Multimodal AI Application Integrating Text and Image Inputs**

### **Sample Input**

`Image of a dog in a field (URL) + Question: 'What animal is in the picture?'`

### **Sample Output**

```text
Generated Caption: a dog running through a grassy field
Question: What animal is in the picture?
Answer: dog
```

---

## **Experiment 10 - Fine-Tuning a Pre-Trained Language Model for a Domain-Specific Application**

### **Sample Input**

`IMDB movie review dataset (2000 training samples, 500 test samples), 2 epochs fine-tuning`

### **Sample Output**

```text
Epoch 1/2 - loss: 0.41 - accuracy: 0.83
Epoch 2/2 - loss: 0.24 - accuracy: 0.89
Evaluation metrics: {'eval_loss': 0.28, 'eval_accuracy': 0.887}
```

---

## **Experiment 11 - AI-Based Content Generation System for Text, Image and Multimedia Applications**

### **Sample Input**

`topic = "The benefits of renewable energy"`

### **Sample Output**

```text
Generated Text:
Renewable energy sources like solar and wind reduce carbon emissions,
lower energy costs over time, and help create a sustainable future for
generations to come.
Image saved as content_image.png
Audio saved as content_audio.mp3
```

---

## **Experiment 12 - Deployment and Evaluation of a Generative AI Application Using Cloud-Based APIs and AI Frameworks**

### **Sample Input**

`Long article text submitted via the Gradio web interface + one generated/reference summary pair for evaluation`

### **Sample Output**

```text
Running on local URL: http://127.0.0.1:7860
Running on public URL: https://xxxxx.gradio.live
ROUGE Evaluation Scores: {'rouge1': 0.78, 'rouge2': 0.55, 'rougeL': 0.74, 'rougeLsum': 0.74}
```
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ca19de77-1208-43af-b8b8-a1dae9c11b46" />
