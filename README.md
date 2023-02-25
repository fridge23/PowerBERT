# PowerBERT
#Code for paper: Detecting Cyber Attacks in Smart Grid Systems with Massive Unlabeled Sensing Data

Abstract:Modern power grids are undergoing significant changes driven by information and communication technologies (ICTs), and evolving into smart grids with higher efficiency and lower operation cost. Using ICTs, however, comes with an inevitable side effect that makes the power system more vulnerable to cyber attacks. In this paper, we propose a self-supervised learning-based framework to detect and identify various types of cyber attacks. Different from existing approaches, the proposed framework does not rely on large amounts of well-curated labeled data but makes use of the massive unlabeled data in the wild which are easily accessible. Specifically, the proposed framework adopts the BERT model from the natural language processing domain and learns generalizable and effective representations from the unlabeled sensing data, which capture the distinctive patterns of different attacks. Using the learned representations, together with a very small amount of labeled data, we can train a task-specific classifier to detect various types of cyber attacks. Experiment results in a 3-area power grid system with 37 buses demonstrate the superior performance of our framework over existing approaches, especially when a very limited amount of labeled data are available. We believe such a framework can be easily adopted to detect a variety of cyber attacks in other power grid scenarios.

model structure:![image](https://user-images.githubusercontent.com/79786784/190063806-377abf78-d0f9-4b5d-bee2-1c8a9233fd20.png)

Update 2023/2/25:
We propose a new loss function to solve the problem of imbalance dataset in unsupervised learning.
The code will be updated soonly after our new paper accepted.
