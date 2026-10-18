# Multi-Class Cyberbullying Classification for Platform Safety Operations

# Project Overview & Problem Definition

Most existing platforms' trust and safety moderation systems are primarily focused on solving a binary problem of toxicity identification. However, in the context of live moderation, the following two issues arise:
False positives: Informal non-abusive language, profanity and slang, not targeted at an individual, are often categorized as toxic, which leads to unjustified account suspensions and user churn.
Slow incident escalation: The most severe cases of identity-based harassment are grouped along with the common profanity, which hinders automation of triage and routing of severe incidents to the appropriate team.
This project creates a multi-class classification model which classifies the social media text into six categories: age, ethnicity, gender, religion, other_cyberbullying, and not_cyberbullying. The project compares the performance of classical models (scikit-learn) and deep learning architectures (TensorFlow/Keras) over 10 experiments using wandb for offline monitoring.

# Set Up Instructions

**1. Clone the repository** 

git clone https://github.com/k-bridget/Intro-to_ML_Summative.git

**2. Set up and activate a virtual environment**

python -m venv venv

 source venv/bin/activate 
 
**3. Install dependencies**

pip install -r requirements.txt
