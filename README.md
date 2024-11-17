# PEFT-Based Fine-Tuning of Mental Health Chatbot using Bloomz-560m with LoRA and QLoRA
This project explores the fine-tuning and optimization of the Bloomz-560m model, specifically adapted for mental health chatbot applications. Leveraging the PEFT (Parameter-Efficient Fine-Tuning) techniques, we enhance the model's performance by applying LoRA (Low-Rank Adaptation) and QLoRA (Quantized Low-Rank Adaptation) methods. These techniques allow for efficient fine-tuning with a smaller set of parameters, improving the model's ability to handle specialized tasks while minimizing computational overhead.

The Bloomz-560m model, originally trained on a diverse range of tasks, is fine-tuned here on a mental health chatbot dataset, enabling the model to engage in thoughtful, empathetic conversations surrounding mental health topics. The fine-tuned model can be accessed via the Hugging Face hub at: bloomz-560m-mentalhealthchatbot.

In this GitHub repository, we demonstrate the use of PEFT techniques, focusing on LoRA and QLoRA through the integration of BitsAndBytes for optimized quantization. This makes the fine-tuning process both resource-efficient and scalable, ideal for deploying mental health AI solutions.

Key Features:
- Fine-tuned Bloomz-560m model for mental health chatbot tasks.
- Application of PEFT techniques: LoRA and QLoRA.
- Utilization of BitsAndBytes library for efficient quantization.
- Detailed Colab notebook for model exploration and experimentation.

This repository serves as a comprehensive guide to experimenting with large language models in the context of mental health applications, while ensuring that they are computationally efficient and optimized for various hardware environments. Feel free to explore, run the provided Colab notebooks, and adapt the model to your own mental health chatbot projects. The fine tuned model can be accessed here: https://huggingface.co/hezronling/bloomz-560m-mentalhealthchatbot 
