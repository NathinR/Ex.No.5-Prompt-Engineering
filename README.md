# EXP 5: Comparative Analysis of Different Types of Prompting Patterns

## Aim
To test and compare how different prompting patterns respond to broad/unstructured prompts versus clear and refined prompts across multiple scenarios. Analyze the quality, accuracy, and depth of the generated responses.

---

## AI Tools Required
- ChatGPT (OpenAI) or any equivalent AI model capable of processing text prompts.

---

## Explanation

### Define the Two Prompt Types
1. **Naïve Prompt:**  
   - Broad or unstructured prompt with minimal guidance.  
   - May lack details or context.  
   
2. **Basic Prompt:**  
   - Clear, detailed, and structured prompt.  
   - Provides explicit instructions and context to guide the model effectively.

---

## Test Scenario

**Scenario:** Generating a customer support response for a retail chatbot.  

- **Naïve Prompt:**  
*"Help a customer with their order problem."*

- **Basic Prompt:**  
*"You are a friendly retail customer support chatbot. A customer writes: 'I ordered a laptop last week, but it hasn’t arrived yet. Can you help me?' Respond politely, provide a solution, and mention the expected delivery timeframe if available."*

---

## Output

### Naïve Prompt Output
*"Sure, I can help you with your order. Please provide more details."*

### Basic Prompt Output
*"Hello! I see that you ordered a laptop last week. Could you please confirm your order ID? Based on that, I can check the shipping status. Generally, deliveries take 5–7 business days, so it might be arriving soon. Thank you for your patience!"*

---

## Result
- Both prompts executed successfully.  
- Naïve prompt generates a **generic response** that requires further clarification from the user.  
- Basic prompt generates a **polite, structured, and actionable response** with clear guidance, saving time for both the customer and support agent.

---

## Analysis

| Metric              | Naïve Prompt Result                    | Basic Prompt Result                                             |
|--------------------|--------------------------------------|----------------------------------------------------------------|
| **Quality**         | Generic, incomplete                  | High-quality, professional, and user-friendly                  |
| **Accuracy**        | Needs additional information         | Accurate response with clear solution and context              |
| **Depth**           | Shallow, minimal guidance            | Deep, detailed, actionable, anticipates user needs            |

**Observations:**  
- Clear and refined prompts consistently provide **better quality, accuracy, and depth**.  
- Naïve prompts may work for simple tasks but are less effective for structured problem-solving or customer interactions.  
- Effective prompt design is key for optimal AI performance, especially in customer support and technical guidance.

---

**Conclusion:**  
Refined and structured prompts allow AI models to produce **more reliable, accurate, and helpful responses**, minimizing the need for follow-up clarification and improving overall user experience. This experiment demonstrates the importance of prompt clarity in achieving optimal AI output.

