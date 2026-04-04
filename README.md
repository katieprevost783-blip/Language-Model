# Language-Model
LLM project used with Python, and C++ to speed up my model, The goal is to understand how AI models process and generate human language by building a simplified version from scratch.

# Phase 1 - Overview
For phase 1 the chatbot uses a rule-based approach to simulate basic Natural Language Processing (NLP). This system is to detect basic emotions in user input, such as sadness, stress, or lack of motivation. It does this through keyword matching, then selects a response from organized response lists. The Python random module is used to add some variation so responses don’t feel completely repetitive. I also added a response bank to categorize the responses to keep it organized and easier to add onto while I continue the rest of my phases. 

Though a reflection function was added to acknowledge and lightly rephrase user input, future phases will focus on making the chatbot feel more natural and less robotic, with improved emotional understanding and more attentive responses.

# Phase 2 - Overview
In Phase 2, I focused on improving my model by making it feel more conversational rather than just responding with one-off messages. I introduced a basic memory system and added follow-up questions to help the AI continue conversations instead of stopping after a single response. I also began separating parts of the logic into functions (Such as response generation), to make the code more organized and easier to expand on.

However, this phase also revealed several challenges. Even with memory and follow-up questions added, the AI still felt repetitive and somewhat robotic. The conversation often followed the same pattern each time, response, follow-up, repeat. This phase was important because it helped highlight the limitations of my initial approach and showed me what needed to be improved. It directly led to the development of Phase 2.5 where I could truly begin working on the issue of "How do I make these sentences flow better."
