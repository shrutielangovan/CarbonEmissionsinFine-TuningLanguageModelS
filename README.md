# Quantifying the Environmental Cost of AI: Carbon Emissions in Language Model Fine-Tuning for Question Answering 

## Project Description 

As language models continue to play a larger role in natural language processing, their environmental impact has become an important issue to consider. While much of the research in this area focuses on improving model accuracy, the energy use and carbon footprint involved in training these systems are often overlooked or poorly documented. This project aims to explore that imbalance by studying how improvements in model performance relate to the environmental costs of fine-tuning. 

We will fine-tune several small-sized language models(ranging from 66 million to 124 million parameters) on a Question Answer(QA) task. We aim to provide evidence of the environmental trade-offs inherent in different modeling choices. Our goal is to systematically analyze and compare emissions across three key dimensions: model architecture, dataset size, and training methodology. 

Our project will evaluate three distinct model architectures: { DistilBERT, BERT-base, and GPT-2} to understand how architectural choices influence both performance and emissions. We will vary dataset sizes to examine whether training on more data yields proportional accuracy improvements or follows a pattern of diminishing returns relative to carbon output. Additionally, we will compare traditional full fine-tuning against parameter-efficient methods like Low-Rank Adaptation (LoRA) and few-shot learning approaches. 

Beyond raw emissions data, we will calculate efficiency metrics that combine model performance with environmental impact. We wish this project to contribute to the growing body of research advocating for responsible AI development. By making the environmental costs of model training visible and quantifiable, we aim to encourage more mindful practices in the NLP community. 

## Dataset 

For this project, we will use the Stanford Question Answering Dataset (SQuAD), a widely used benchmark for machine reading comprehension. The dataset consists of questions written by crowd workers based on a collection of Wikipedia articles. Each example includes a question, a corresponding passage of text, and an answer span within that passage.  

Source: https://huggingface.co/datasets/squad (SQuAD 2.0) 

Size: ~100,000 question-answer pairs on 500+ articles 
