LearnMate: Agentic AI for Personalized Course Pathways
🚀 Project Overview
LearnMate is a smart, adaptive AI coach built using IBM watsonx Agent Lab to guide students in discovering the right learning path. It interacts with users to understand their interests, assess their current skill levels, and generate a personalized course roadmap that evolves with their progress.

Problem Solved: Students often face confusion due to the vast number of online courses and lack of tailored guidance. LearnMate addresses this by providing structured, interest-based learning pathways.

🎯 Key Features
Understands student interests (e.g., Frontend, Cybersecurity, UI/UX)

Assesses skill levels (beginner to advanced)

Builds and updates personalized course roadmaps

Recommends free courses from platforms like Coursera, edX, etc.

Provides encouragement and adapts suggestions based on feedback

🛠️ Technology Stack
IBM watsonx Agent Lab

IBM Granite Language Models

LangGraph / ReAct Frameworks

IBM Cloud Lite (for hosting and deployment)

🧠 Agent Behavior (Design)
Friendly, clear, and helpful assistant tone

Asks questions before recommending anything

Prioritizes free, beginner-friendly resources

Gives short-term and long-term roadmap suggestions

Updates plans based on progress and user feedback

🔐 Prerequisites
IBM Cloud account (Lite plan is sufficient)

API key generated via IAM settings

watsonx Agent Lab access with deployable model (e.g., granite-3b-instruct)

✅ Example Use Cases
“I want to learn Frontend but I’m a beginner”

“Can you help me build a roadmap for Cybersecurity?”

“What should I learn after Python basics?”

“How do I get started with UI/UX?”

📌 Notes
Always ensure you’ve added a tool (like Search) in Agent Lab before deploying

Smaller Granite models (e.g., granite-3b) are more compatible with free-tier deployments

Save your API key securely when integrating IBM services# LearnMate
~Your personalized AI coach to discover, plan, and adapt learning paths based on your goals.
