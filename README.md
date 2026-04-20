  # Language-Model
LLM project used with Python, and C++ to speed up my model, The goal is to understand how AI models process and generate human language by building a simplified version from scratch.

# Phase 1 - Overview
For phase 1 the chatbot uses a rule-based approach to simulate basic Natural Language Processing (NLP). This system is to detect basic emotions in user input, such as sadness, stress, or lack of motivation. It does this through keyword matching, then selects a response from organized response lists. The Python random module is used to add some variation so responses don’t feel completely repetitive. I also added a response bank to categorize the responses to keep it organized and easier to add onto while I continue the rest of my phases. 

Though a reflection function was added to acknowledge and lightly rephrase user input, future phases will focus on making the chatbot feel more natural and less robotic, with improved emotional understanding and more attentive responses.

# Phase 2 - Overview
In Phase 2, I focused on improving my model by making it feel more conversational rather than just responding with one-off messages. I introduced a basic memory system and added follow-up questions to help the AI continue conversations instead of stopping after a single response. I also began separating parts of the logic into functions (Such as response generation), to make the code more organized and easier to expand on.

However, this phase also revealed several challenges. Even with memory and follow-up questions added, the AI still felt repetitive and somewhat robotic. The conversation often followed the same pattern each time, response, follow-up, repeat. This phase was important because it helped highlight the limitations of my initial approach and showed me what needed to be improved. It directly led to the development of Phase 2.5 where I could truly begin working on the issue of "How do I make these sentences flow better."

# Phase 2.5 - Overview
In Phase 2.5, I focused on fixing the main issues I found in Phase 2, especially how repetitive and robotic the chatbot felt during longer conversations. Instead of trying to add more structure, I simplified the system to make responses feel more natural and more like a real conversation.

One of the biggest changes was removing the reflection system that repeated user input, since it made the chatbot feel unnatural. I replaced it with more direct and supportive responses that respond to the user’s emotion without echoing what they said. I also improved the response system by writing more thoughtful replies for each emotion, including new categories like anger and happiness, so the chatbot can handle a wider range of situations.

The follow-up questions were also improved to match each emotion more clearly, helping the conversation continue in a more natural way instead of following the same pattern every time. This makes the chatbot feel more like it’s listening and responding, rather than just reacting.

Compared to Phase 2, this version focuses less on structure and more on how the conversation feels. While Phase 2 introduced ideas like memory and follow-ups, it still struggled with flow and repetition. In Phase 2.5, I focused on making the interaction smoother, more natural, and easier to talk to.

This phase shows my progress in understanding not just how to build a system, but how to improve the user experience. It reflects a shift from just adding features to actually thinking about how the chatbot feels to use.

# Phase 3/3.5 - Overview
Phase 3.5 represents a significant improvement over Phase 3, shifting the chatbot from a primarily rule-based emotional response system into a more context-aware conversational model. While Phase 3 introduced foundational features such as basic emotion detection, simple memory tracking (turn count and last emotion), and randomized response variation, the interaction remained largely static and often felt repetitive. Responses were generated based on isolated emotional states without considering the actual content or context of the user’s message.

In Phase 3.5, the system was refined to improve conversational depth and continuity. Instead of only reacting to detected emotions, the chatbot now incorporates contextual understanding by identifying elements such as situations related to school, work, interpersonal conflict, or achievements. This allows responses to become more relevant to what the user is actually describing, rather than relying solely on predefined emotional templates.Additionally, Phase 3.5 introduces emotional progression tracking, enabling the system to recognize when a user’s emotional state changes over time.
