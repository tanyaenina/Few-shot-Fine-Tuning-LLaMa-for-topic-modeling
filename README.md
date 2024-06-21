# SummAI NLP Challenge

The objective of this project is to fine-tune the LLaMA-2 model using a few-shot prompting strategy for topic modeling. 

## Technical Prerequisites

Given the computational constraints, I utilized Google Colab with a T4 GPU.

## Challenges and Limitations

Due to some technical problems that I encountered while implementing a solution and lack of time, unfortunately I didn't manage to try other ideas suggested in related literature. So I uploaded just the simplest solution that I found. 

Approaches described in the following papers I found quite promising and applicable for the defined objective:

- Wang, Han & Prakash, Nirmalendu & Hoang, Nguyen & Hee, Ming Shan & Naseem, Usman & Lee, Roy Ka-Wei. (2023). Prompting Large Language Models for Topic Modeling. (the system prompt was taken from this article and adjusted for only one topic-output)
  
- Houlsby, Neil & Giurgiu, Andrei & Jastrzebski, Stanislaw & Morrone, Bruna & Laroussilhe, Quentin & Gesmundo, Andrea & Attariyan, Mona & Gelly, Sylvain. (2019). Parameter-Efficient Transfer Learning for NLP.
and in particular
- Hu, E. J., Shen, Y., Wallis, P., Allen-Zhu, Z., Li, Y., Wang, S., ... & Chen, W. (2021). Lora: Low-rank adaptation of large language models.
