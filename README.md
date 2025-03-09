
# HeartHealer AI  

**Empathetic, Science-Backed Emotional Wellness Companion**  

Open WebUI Link - https://openwebui.com/m/anjali1/hearthealer-ai

![WhatsApp Image 2025-03-09 at 4 30 53 PM](https://github.com/user-attachments/assets/45726269-5d3b-4f39-b68a-5ee4913d2c9b)

---

## Objective  
HeartHealer AI is an AI-powered emotional wellness assistant developed as part of my college project. Designed to provide judgment-free, actionable support, it blends psychological research with empathetic conversational design to help users navigate stress, anxiety, and emotional challenges. Inspired by evidence-based therapeutic practices, HeartHealer AI offers personalized guidance, coping strategies, and a safe space for reflection.  

---

## Technology Stack Used  
HeartHealer AI leverages modern AI frameworks and deployment tools to ensure accessibility and reliability:  

1. **Large Language Model (LLM) – Llama 3.2: Latest**  
   - Trained for empathetic dialogue and psychological support.  
   - Delivers context-aware responses grounded in cognitive-behavioral principles.  
   - Optimized for natural, non-judgmental interactions.  

2. **Web OpenAI via Docker**  
   - Deployed using Docker for isolated, scalable execution.  
   - Integrated with Ollama for efficient model serving.  

---

## Installation & Deployment Process  

### Step 1: Install Ollama  
Ollama simplifies running the LLM locally:  
```bash  
curl -fsSL https://ollama.ai/install.sh | sh  
ollama pull llama3.2:latest  # Download the latest Llama 3.2 model (~2GB)  
```  

### Step 2: Deploy Web OpenAI on Docker  
Run Open WebUI in a Docker container to interact with HeartHealer AI:  
```bash  
docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart always ghcr.io/open-webui/open-webui:main  
```  
- Access the interface at `http://localhost:3000` after deployment.  

---
### Images
![WhatsApp Image 2025-03-09 at 4 30 53 PM (1)](https://github.com/user-attachments/assets/15fbfdfe-5470-4933-96d7-4ab1742097be)

### Video



## Results: HeartHealer AI in Action  

### Example 1:  
**User Input**:  
```  
Hello!  
```  

**HeartHealer AI Response**:  
```  
Hello! It takes courage to reach out and talk about your feelings, so I want to start by saying thank you for trusting me with this conversation. How are you doing today? Is there something specific that's been on your mind or in your heart lately that you'd like to talk about? I'm here to listen and offer support in any way I can.
```


### Example 1:  
**User Input**:  
```  
How do I stop missing my ex so much?  
```  

**HeartHealer AI Response**:  
```  
It's completely normal to still feel a strong connection with someone after a breakup, especially if the relationship was meaningful or lasted for an extended period.

For many people, it takes time and effort to adjust to life without their partner. The good news is that with patience, self-reflection, and support, you can learn to reduce those feelings of missing your ex.

Let's explore some strategies together:

Allow yourself to grieve: It's essential to acknowledge the emotions you're experiencing and give yourself permission to process them. Acknowledge the pain, but also remind yourself that it's temporary.
Practice self-care: Focus on nurturing your physical, emotional, and mental well-being. Engage in activities that bring you joy, like exercise, hobbies, or spending time with loved ones.
Rebuild your daily routine: Breakups can disrupt our routines, so try to get back into a regular schedule. This might help you feel more grounded and less dependent on thoughts of your ex.
Create new connections: Meet new people, join clubs or groups that align with your interests, or volunteer. Expanding your social circle can help shift your focus away from missing someone else.
Reflect on the relationship: Take time to think about what you learned from the relationship and how it's impacted you as a person. This can help you gain closure and perspective.
Remind yourself of your worth: You are more than this one relationship, and your ex doesn't define your self-worth. Repeat positive affirmations to yourself, like "I am enough," or "I am worthy of love and happiness."
Create distance (physically): If you feel the need to limit contact with your ex, that's okay too! Take a break from social media, avoid mutual friends who might be in touch with each other, or simply give yourself space.
Remember, healing is not linear, and it's okay if you still think about your ex sometimes. The key is to learn to manage those feelings so they don't consume you.

Which of these strategies resonates with you the most? Or do you have any specific thoughts or emotions that are making this process more challenging for you?  
```  

---

### Example 3:   
**User Input**:  
```  
How do I stop overthinking?  
```  

**HeartHealer AI Response**:  
```  
Overthinking often stems from trying to control uncertainty. Here’s a science-backed approach:  

1. **Grounding Exercise**: Name 5 things you see, 4 you feel, 3 you hear, 2 you smell, 1 you taste.  
2. **Reframe Thoughts**: Write down worries and label them as “helpful” or “unhelpful.”  
3. **Mindfulness**: Practice 10 minutes of guided meditation (I can share a link!).  

A 2023 study found mindfulness reduces anxiety by 40% in 8 weeks. Let’s start small! 🌱  
```  

---

## Key Learnings from the Project  

1. **AI for Mental Health Requires Nuance**  
   - Balancing empathy with evidence-based strategies is critical.  
   - Context-aware responses build trust and engagement.  

2. **Deployment Efficiency**  
   - Ollama + Docker ensures low-latency performance, even on modest hardware.  

3. **Academic Insights**  
   - **User-Centric Design**: Privacy and non-judgment are paramount in emotional wellness tools.  
   - **Bridging Theory & Practice**: Implementing psychological principles in AI interactions deepens their impact.  
