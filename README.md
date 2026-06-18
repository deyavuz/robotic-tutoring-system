# Robotic Tutoring System

### 🛸 Captain's Log
#### 18/06/2026
Looking through the Hugging Face Reachy Mini library and making notes on apps with features that could be relevant to my project. I will be going through their code to see how I could take inspiration from and build on what's already out there.
Currently, I'm most interested in the [Baby Reachy Mini Companion](https://huggingface.co/spaces/ravediamond/baby-reachy-mini-companion) - for its in-built safety features, danger detection (which, for my uses, could be used to analyse sentiment), and interactive teaching - and the [Reachy Mini Conversation App](https://huggingface.co/spaces/pollen-robotics/reachy_mini_conversation_app) - once again for its visual awareness and natural conversational capabilities.

As in a real-life setting this robot would be deployed to help students (most likely including children and teens), it is crucial to me that I implement the necessary AI safeguards. I believe doing a thorough analysis of the pre-existing apps' code will help me fill in the gaps of what I found in my literature review and what I thought would be appropriate/necessary to implement.

#### 17/06/2026
Working on setting up the virtual simulation environment today. Dividing my day into two parts: 
1) Writing some demo code to see how the virtual simulation robot behaves, testing key behaviours
2) Researching social robot behaviours that have had positive or conducive (to learning) results, in literature

Once I manage to get the behaviours down and complete a demo Jupyter notebook, my main goal is to create a roadmap for the user app. This app has to be informed by previous social robotics literature that have looked into human-robot interaction in a learning environment, especially focusing on differences between different robot behaviour conditions. Due to the pre-determined nature of the study, the robot is expected to be taking the role of a tutee (as protégé effect hypothesises that students learn better when they take on the role of teacher). However, the robot's "personality" and mannerisms is fully up to me. So, today's research will create a basis for this.
##### End of Day Report:
- Set up virtual simulation - this proved to be a lot more difficult than I expected, due to many compatibility and requirement clashes. I had to forgo using the Control app and launched MuJoCo directly from the terminal.
- Wrote a launch script to make the sim setup process more seamless/efficient.
