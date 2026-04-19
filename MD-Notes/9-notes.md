# Affective Computing - Week 9

# Empathetic Agents - Key Points (Simple Explanation)

## 1. What is Empathy?
- Empathy = understanding what another person is feeling or going through.
- Example: If someone is sad, you can sense it and respond kindly.

## 2. Why Add Empathy to AI?
- When AI (robots, chatbots, virtual assistants) show empathy:
  - Interactions feel more natural
  - Users feel more comfortable
  - Communication becomes more effective
- Simple idea: People respond better when they feel understood.

## 3. Basic Assumption
- Humans prefer interacting with machines like they interact with other humans.
- So, making AI behave more human-like improves user experience.

## 4. Anthropomorphism (Important Concept)
- Meaning: Giving human-like qualities to non-human things.
- Word breakdown:
  - "Anthropos" = human
  - "Morphe" = form/shape

- Example:
  - Talking to a chatbot like it's a person
  - Naming robots or giving them emotions

## 5. Why Anthropomorphism Matters
- It helps make machines:
  - More familiar → easier to relate to
  - More understandable → easier to trust
  - More predictable → users feel in control

## 6. Where Anthropomorphism Affects AI

### a) Form
- How the AI looks
- Example: humanoid robots, avatars

### b) Behavior
- How the AI acts
- Example: showing emotions, polite responses

### c) Interaction
- How the AI communicates
- Example: conversational tone, empathy in replies

## 7. Overall Idea
- Empathetic + human-like AI = better user interaction
- People naturally treat machines like humans, so designing AI this way improves experience

# Uncanny Valley - Key Points (Simple Explanation)

## 1. What is Uncanny Valley?
- It describes how humans react to robots/AI as they become more human-like.
- As similarity increases → comfort increases (initially)
- But at a certain point → slight imperfections make them feel creepy or unsettling

## 2. Graph Explanation
- X-axis: Human likeness (how human-like the robot looks)
- Y-axis: Familiarity (how comfortable we feel)

### Trend:
- Low human likeness → low familiarity (e.g., simple robots like R2-D2)
- Moderate likeness → higher comfort (e.g., WALL-E, C-3PO)
- Very high but imperfect likeness → sudden drop (uncanny valley)
- Perfect human-like → familiarity rises again

## 3. Why It Happens
- Small imperfections in near-human robots feel unnatural
- Humans are very sensitive to:
  - Facial expressions
  - Eye movement
  - Skin texture
- Even tiny errors → discomfort

## 4. Design Insight
- Avoid making robots “almost human but not quite”
- Either:
  - Keep them clearly non-human
  - Or make them extremely realistic

# Types of Empathetic Agents - Key Points

## 1. Type 1: Emotion-Responsive Agents
- These agents respond based on the user’s emotions

### Example Flow:
- User experiences something → expresses emotion
- Agent observes → understands emotion
- Agent gives an empathetic response

### Key Elements:
1. Observer → the agent
2. Target → the user (or another agent)
3. Event → what happened
4. Emotion → feeling caused by the event
5. Situation/Context → background info
6. Mediating factors → past experiences, personality, etc.

## 2. Type 2: Emotion-Inducing Agents
- These agents influence how users feel

### How it works:
- Agent shows emotion → user reacts emotionally
- The agent’s behavior shapes user response

### Key Idea:
- Instead of reacting → they lead the emotional interaction

# Design Principle (Appearance vs Function)

## 1. Appearance Matters
- How a product looks affects:
  - User perception
  - Interaction quality
  - Long-term relationship

## 2. Match Appearance with Capability
- A robot should look as capable as it actually is

### Example:
- If it looks very intelligent → users expect advanced behavior
- If it fails → users lose trust

## 3. User Expectation Alignment
- Design should match what users expect:
  - Simple look → simple behavior
  - Advanced look → advanced functionality

## 4. Overall Idea
- Good design = balance between:
  - Appearance
  - Functionality
  - User expectations
- Mismatch → confusion, frustration, or distrust

# Artificial Empathy - Key Points (Simple Explanation)

## 1. What is Artificial Empathy?
- It is how AI systems understand and respond to human emotions.
- Built using three main processes.

## 2. Three Core Subprocesses

### a) Emotional Simulation
- AI mimics or shares the user’s emotional state
- Example: If user is sad → AI responds in a comforting tone

### b) Perspective Taking
- AI understands what the user is thinking or feeling internally
- It tries to “put itself in the user’s shoes”

### c) Emotion Regulation
- AI controls its response to avoid negative impact
- Ensures responses are helpful, calm, and supportive

# Example: AI-Powered Chatbot

## 1. Emotional Simulation
- Detects emotional triggers (like stress or anxiety) from user data

## 2. Perspective Taking
- Responds in a calm, supportive, and understanding way
- Uses empathetic language

## 3. Emotion Regulation
- Filters harmful or negative responses
- Ensures user feels safe and understood

# Empathy Analysis - Key Points

## 1. Behavioral Studies
- Humans observe interactions to identify empathy
- Includes:
  - Physiological signals (heart rate, etc.)
  - Behavioral cues (speech, actions)

## 2. Computational Analysis
- AI models analyze empathy using data

### Modalities:
- Language (text analysis)
- Facial expressions
- Other behavioral signals

## 3. Key Insight
- Language-based models (like N-grams) can detect empathy patterns

# Empathy Analysis (EA): Vocal Cues

## 1. Importance
- Voice reflects internal emotional state

## 2. Features Used
- Pitch (tone)
- Energy (loudness)
- Jitter (voice variation)
- Speech duration

## 3. Outcome
- These features help predict empathy levels (high vs low)

# EA: Facial Expressions

## 1. Types of Expressions
- Neutral, smile, laughter, thinking, etc.

## 2. Gaze Patterns
- Mutual gaze (eye contact)
- One-way gaze
- Looking away

## 3. Emotional Categories
- Empathy
- Unconcern
- Antipathy

## 4. Key Insight
- Facial expressions are strong indicators of empathy

# Empathy Simulation - Key Points

## 1. What it Means
- AI displays behaviors that humans perceive as empathetic

## 2. Two Approaches
- Theory-driven → based on psychology models
- Data-driven → based on real user data

## 3. Important Note
- Human-like behavior must actually evoke empathy, not just imitate it

# Empathy Simulation: Computational Model

## 3 Main Steps:

### 1. Empathy Mechanism
- AI internally imitates user emotion
- Generates emotional feedback

### 2. Empathy Modulation
- Adjusts response based on:
  - Context
  - Familiarity
  - User state

### 3. Expression of Empathy
- Outputs empathy via:
  - Facial expressions
  - Voice
  - Text

# AI Chatbot (Computational Model Example)

## 1. Empathy Mechanism
- Detects anxiety/stress from user messages

## 2. Empathy Modulation
- Adjusts tone based on:
  - User history
  - Severity of issue
  - Personal factors

## 3. Expression
- Uses supportive language:
  - Kind words
  - Validation
  - Understanding tone

# Application: User & Context Modeling

## 1. What it Does
- Learns how humans express empathy using data

## 2. Example Framework
- CARE framework:
  - Observes behavior
  - Models user context
  - Generates empathetic responses

# Data-Driven Approach: Affective AutoTutor

## 1. What is it?
- AI tutor that interacts empathetically with students

## 2. Features
- Detects:
  - Facial expressions
  - Voice
  - Conversation cues
  - Body posture

## 3. How it Responds
- Uses rules to choose best response
- Example:
  - “I know this is hard, but you can do it”

## 4. Key Result
- Students with less prior knowledge performed better with empathetic tutor

# Overall Idea

- Artificial empathy = understanding + adapting + expressing emotion
- Uses:
  - Text
  - Voice
  - Facial cues
- Goal:
  - Make AI interactions more human-like, supportive, and effective

# Limitations of Empathy Computation - Key Points (Simple Explanation)

## 1. Empathy is Complex
- Empathy is not simple - it involves:
  - Multiple signals (voice, face, text, behavior)
  - At least two people interacting

## 2. What One Empathy Process Requires
Even a single empathy interaction needs:

1. Behavior Stimuli  
   → What triggered the emotion (event/situation)

2. Behavior Perception  
   → Understanding what the other person is expressing

3. Empathic Resonance  
   → Internally feeling or aligning with that emotion

4. Empathic Expression  
   → Showing an appropriate response

## 3. Research Challenge
- Empathy is hard to define clearly
- Depends heavily on:
  - Context
  - Situation
  - Type of interaction
- Researchers must carefully decide:
  - What kind of empathy they are modeling

# Limitations of Data-Driven Approach

## 1. Data is the Biggest Problem
- Limited in:
  - Quantity (not enough data)
  - Variety (not diverse enough)

## 2. Current Datasets Issues
- Mostly based on:
  - Audio recordings
  - Large psychotherapy sessions
- But:
  - Only a small part is properly labeled (annotated)

## 3. Annotation Problem
- Requires:
  - Psychological understanding
  - Behavioral analysis
- Hard and expensive to label data accurately

## 4. Limited Modalities
- Often only audio is used
- Missing:
  - Facial expressions
  - Physiological signals

## 5. Domain Limitations
- Important real-world areas lack data:
  - Education
  - Customer service
  - Healthcare

# Unified View: Behavioral Signal Processing (BSP)

## 1. Problem Identified
- Gap between:
  - Theory-based empathy models
  - Practical AI applications

## 2. Key Insight
- Knowledge from empathy analysis is not fully used in building systems

## 3. BSP Approach
- Uses behavioral signals to model empathy

### Signals include:
- Speech
- Facial expressions
- Actions
- Context

# Key Components in BSP

## 1. Expression & Perception
- Every interaction has:
  - Expression → what one person shows
  - Perception → how the other interprets it

## 2. Observer Role
- A third person (evaluator) may:
  - Analyze interaction
  - Provide feedback
- Example: Therapist evaluating a conversation

## 3. Computational Modeling
- AI models should include:
  - Behavioral characteristics
  - Context understanding
- Used for:
  - Empathy analysis
  - Empathy simulation

# Overall Idea

- Empathy in AI is difficult because:
  - It is complex and multi-layered
  - Data is limited and hard to annotate
- BSP provides a structured way to:
  - Analyze
  - Model
  - Simulate empathy effectively

# Evoking Empathy - Key Points (Simple Explanation)

## 1. What Needs to Be Designed in AI?
To make AI evoke empathy, we must decide:

1. What behaviors should the agent show?  
   → e.g., caring tone, supportive responses  

2. What appearance/features trigger empathy?  
   → human-like face, voice, gestures  

3. How context affects empathy?  
   → same action can feel different depending on situation  

4. Mediating factors  
   → user personality, culture, past experience  

5. How to measure impact?  
   → does the user feel understood or supported?  

# Empathy in Virtual Agents (VAs)

## 1. Social Identity Matters
- People respond differently based on:
  - In-group (similar people)
  - Out-group (different people)

## 2. Key Insight
- Users are more likely to help or empathize when:
  - They feel connected to the agent

## 3. Limitation
- Hard to study experimentally due to ethical concerns

# Empathy in Robots

## 1. Example: Kismet Robot
- Had:
  - Human-like facial features
  - Expressive emotions

## 2. Key Idea
- Physical appearance + expressions → stronger emotional connection

# Empathic Companion (Interview Systems)

## 1. What It Does
- Detects user emotions in real-time using:
  - Physiological data (e.g., skin conductance)
  - Voice signals

## 2. Response
- Uses virtual characters to respond empathetically

## 3. Result
- Reduces stress in users during interactions

# Shimi (Emotion-Based Robot)

## 1. How It Detects Emotion

### a) Valence (Positive/Negative)
- Uses language analysis to detect:
  - Positive words → happy
  - Negative words → sad/angry

### b) Arousal (Intensity)
- Uses voice features:
  - Loudness
  - Pitch
  - Energy

## 2. Output
- Classifies emotions into:
  - Happy
  - Sad
  - Angry
  - Calm

# Creating Synthetic Emotions

## 1. Limitations
- AI struggles to fully understand:
  - Beliefs
  - Desires
  - Intentions

## 2. Practical Approach
- Focus on basic emotions:
  - Simple
  - Short-lived
  - Clearly defined (e.g., Ekman emotions)

## 3. Other Factors
- Mood
- Personality
- Emotional intelligence

# Theory of Mind (ToM)

## 1. Definition
- Ability to understand others’ mental states:
  - Beliefs
  - Desires
  - Intentions
  - Emotions

## 2. Importance
- Helps AI:
  - Predict user behavior
  - Understand intentions

## 3. False Belief Test
- Used to check if someone can:
  - Understand that others can have incorrect beliefs

# Mind Reading by Affective Agents

## 1. What It Means
- AI tries to infer what the user is thinking

## 2. Capabilities
- Detect:
  - Beliefs
  - Misconceptions
  - Intentions

## 3. Goal
- Help user achieve their objective effectively

# Shared Mental Attention

## 1. Concept
- AI tries to see things from the user’s perspective

## 2. How It Works
- Uses user’s viewpoint to:
  - Predict beliefs
  - Understand actions

## 3. Key Benefit
- Even if AI and user think differently:
  - AI can still understand the user

# Overall Idea

- Evoking empathy requires:
  - Behavior + appearance + context
- Advanced empathy involves:
  - Understanding thoughts (ToM)
  - Predicting intentions
  - Adapting responses
- Goal:
  - Make AI socially intelligent and emotionally aware

# Evaluation of Empathetic Agents - Key Points (Simple Explanation)

## 1. How Do We Measure Success?
- No clear standard exists yet
- Hard to define what “good empathy” means in AI

## 2. Challenges in Evaluation
- In real interactions:
  - Difficult to measure actual impact on users
- Empathy is subjective → varies from person to person

## 3. During Testing
- Key question:
  → How well does the system imitate human behavior?

# Psychological Benchmarks

## 1. Autonomy
- Are robots acting independently?
- Or just following programmed rules?

## 2. Imitation
- Do humans imitate robots?
- How does this compare to human-human imitation?

# Ethical & Social Evaluation Factors

## 1. Intrinsic Moral Value
- Do people believe robots have moral worth?

## 2. Moral Accountability
- Can robots be blamed for harmful actions?
- Do people treat them as responsible?

## 3. Privacy
- Does interacting with robots affect user privacy?
- Are users comfortable sharing personal data?

## 4. Reciprocity
- Do humans form mutual relationships with robots?
- Example:
  - If robot shows care → does user respond similarly?

# Methodological Metrics

## 1. Human Ratings
- People evaluate:
  - Behavior
  - Empathy level
  - Interaction quality

## 2. Questionnaires & Analysis
- Surveys used to measure:
  - User feelings
  - Satisfaction
  - Perceived empathy

# Conclusion - Key Takeaways

## 1. Importance of Empathy in AI
- Empathetic AI leads to:
  - Better interactions
  - More natural communication
  - Positive user experience

## 2. Evoking Empathy
- Requires:
  - Proper behavior
  - Suitable appearance
  - Context awareness

## 3. Virtual & Robotic Agents
- Design must balance:
  - Appearance
  - Functionality
- This affects long-term user trust

## 4. Beyond Basic Emotions
- AI still struggles to fully understand:
  - Beliefs
  - Desires
  - Intentions

## 5. Evaluation Methods
- Psychological benchmarks are important
- No perfect system yet → ongoing research area

# Overall Idea

- Evaluating empathy in AI is difficult because:
  - It involves human emotions
  - It lacks standard metrics
- Future work focuses on:
  - Better measurement methods
  - More human-like understanding in AI
