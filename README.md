# Evaluating-LLMs-Accuracy-Consistency-and-Coherence

NLP Group Work

All rights reserved


Datasets:


Saxena, S. (2021). ‘food nutrition dataset.’ [online]. Provenance: https://ndb.nal.usda.gov/. Available at: https://www.kaggle.com/datasets/shrutisaxena/food-nutrition-dataset/data (Accessed: 10 March 2024)



We use a USDA curated dataset that includes information on 7,413 food items and their nutritional values (Saxena, 2021). A subset of this data was chosen, consisting of 47 nutrients and 102 randomly selected foods, comprising both brand-specific goods and generic food kinds. This randomisation reduces the possibility for assessment bias.



We fine-tuned Gemini's comprehension and question-answering skills in the domain of human nutrition using the Vertex AI platform. A curated dataset of 100 nutrition-specific question-and-answer pairs was used as the fine-tuning resource. The collection contains a variety of nutrition subjects, such as vital nutrients, dietary advice, and common food features. The pre-trained Gemini model text-bison@001 was chosen as the base model due to its suitability for text-based tasks like question answering and its robustness in conversational turns (Zhang et al., 2024). The fine-tuning process on the platform provided automated evaluation metrics to assess the effectiveness of the fine-tuning, ensuring successful training. The fine-tuned “Nutri” model was deployed within Vertex AI for further use and evaluation.
