# A Framework For Generating Explainable Recommendations Via Multitask Learning


## Abstract
Recommendation systems are intelligent information retrieval systems that predict desirable recommendations for 
users based on their past interactions with items. These systems face challenges such as data insufficiency and 
lack of transparency. To address these challenges, the use of user reviews has been proposed as a solution. Reviews 
can convey user preferences and provide textual explanations, helping to overcome data deficiency and improve 
transparency. Recently, due to the potential threats of AI, the concept of Responsible AI (RAI) has been introduced 
to address ethical and societal concerns. Transparency is one of the primary principles of RAI. Transparency is 
crucial for understanding the decision-making process and predicted results of AI models. Therefore, e-commerce 
platforms must make their AI solutions (e.g., recommender systems) transparent by providing users with 
explanations. Text is a prevalent style of explanation employed in a wide range of explainable recommendation 
systems. However, previous works often neglect the writing style of users, which can impact the effectiveness of 
explanations. The main objective of the paper is to develop a novel framework for generating explainable 
recommendations that incorporate user writing styles and preferences in the explanation generation process. We 
used a publicly available dataset for evaluating our research. Even though the proposed method could outperform 
some state-of-the-art methods in terms of the accuracy of recommendations, it could not enhance explainability 
at the writing style level.
<img width="653" alt="image" src="https://user-images.githubusercontent.com/103757072/233791305-44be5fa7-e794-411e-8863-c7709ec389ef.png">

The framework consists of a recommendation model and an explanation generation model, which are designed to provide the target user with explainable recommendations. The recommendation model utilizes ratings plus reviews to understand users' interests. Moreover, the explanation generation model uses user-generated reviews as a textual source to produce a couple of review-like sentences.
