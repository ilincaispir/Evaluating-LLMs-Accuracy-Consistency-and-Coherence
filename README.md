# Evaluating-LLMs-Accuracy-Consistency-and-Coherence

Natural Language Processing Group Coursework

All rights reserved


Datasets:


Saxena, S. (2021). ‘food nutrition dataset.’ [online]. Provenance: https://ndb.nal.usda.gov/. Available at: https://www.kaggle.com/datasets/shrutisaxena/food-nutrition-dataset/data (Accessed: 10 March 2024)



We utilise a curated dataset from the USDA containing information on 7,413 food samples and their corresponding nutritional values (Saxena, 2021). A subset of this data was chosen, encompassing 47 nutrients and 102 randomly selected foods, including both brand-specific products and generic food types. This randomization minimises potential bias in the evaluation.



To improve Gemini's understanding and question-answering capabilities in the domain of human nutrition, we employed fine-tuning on Vertex AI platform. A curated dataset containing 100 question-and-answer pairs specific to nutrition served as the fine-tuning resource. The dataset covers various nutrition topics, including essential nutrients, dietary recommendations, and common food properties. The pre-trained Gemini model text-bison@001 was chosen as the base model due to its suitability for text-based tasks like question answering and its robustness in conversational turns (Zhang et al., 2024). The fine-tuning process on the platform provided automated evaluation metrics to assess the effectiveness of the fine-tuning, ensuring successful training. The fine-tuned “Nutri” model was deployed within Vertex AI for further use and evaluation.
