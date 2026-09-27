
AI vs ML vs DL vs GenAI Fundamentals

<img width="1312" height="1199" alt="AIML" src="https://github.com/user-attachments/assets/08dc46d6-80ac-4c61-9ccb-fedb109c577f" />

Agentic AI

<img width="1312" height="1199" alt="Agentic AI" src="https://github.com/user-attachments/assets/810d2f0c-207b-48f4-956f-85b16ba5eeeb" />

Types of Machine Learning :

The three primary types of Machine Learning (ML) are Supervised Learning, Unsupervised Learning, and Reinforcement Learning. Depending on the data structure and how the model learns, two hybrid categories—Semi-Supervised Learning and Self-Supervised Learning—are also widely recognized.

Machine Learning
│
├── 1. Supervised Learning
│   │
│   ├── Classification
│   │   └── Predict a category
│   │       Example: Spam / Not Spam
│   │
│   └── Regression
│       └── Predict a number
│           Example: House price = ₹75 lakh
│
├── 2. Unsupervised Learning
│   │
│   ├── Clustering
│   │   └── Find natural groups
│   │       Example: Customer segmentation
│   │
│   └── Dimensionality Reduction
│       └── Reduce number of features
│           Example: PCA
│
├── 3. Semi-Supervised Learning
│
├── 4. Self-Supervised Learning
│
└── 5. Reinforcement Learning

 1. Supervised Learning

The model learns from labelled examples.

Input → Correct answer → Model learns

Daily examples:

📧 Spam detection: Email → Spam / Not Spam
💳 Fraud detection: Transaction → Fraud / Genuine
🏠 House price prediction: House features → Price
📱 Face recognition: Face image → Person identity
🏥 Disease prediction: Patient data → Disease / No disease

There are two major types:

Classification → predicts a category.
Gmail → Spam

Regression → predicts a numerical value.
House features → ₹75 lakh


Common Algorithms
Linear & Logistic Regression
Decision Trees & Random Forests
Support Vector Machines (SVM)
K-Nearest Neighbors (KNN)


2. Unsupervised Learning

The model receives unlabelled data and tries to discover patterns or groups.

Daily examples:

YouTube/Netflix customer grouping

Millions of users
       ↓
ML finds behavior patterns
       ↓
Group A → watches action movies
Group B → watches documentaries
Group C → watches children's content

Other examples:

Customer segmentation
Finding unusual transaction patterns
Grouping similar news/articles
Product recommendation
Market segmentation

The most common technique is clustering.

Common Algorithms
K-Means
K-Medoids
Hierarchical Clustering
PCA
t-SNE
UMAP
Autoencoders

3. Reinforcement Learning

The model learns through actions, rewards and penalties.


Daily/real-world examples:

🎮 Game-playing AI
🤖 Robot navigation
🚗 Autonomous driving research
📦 Warehouse robot movement
🧠 Recommendation/ad optimization
Traffic signal optimization

Example:

Robot chooses Route A → reaches destination quickly → positive reward
Robot chooses Route B → gets blocked → negative reward

Over time, it learns better decisions.

4. Semi-Supervised Learning

Uses a small amount of labelled data + a large amount of unlabelled data.


Example: A company has 100,000 images but humans have labelled only 5,000. ML can use both labelled and unlabelled images.

Common in:

Image classification
Speech recognition
Document classification
5. Self-Supervised Learning

The model creates a learning signal from the data itself, rather than requiring humans to label every example.

This is extremely important for modern AI/LLMs.

Example:

"The server failed because the _____
was unavailable."

The original text provides the learning signal.

Used heavily in:
LLMs
NLP
Computer vision
Speech models










