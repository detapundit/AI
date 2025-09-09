Transparent and trustworthy

Fairness
explain
Privacy security

high transparency-high interpretability-poor performance

human centered design amplified decision making, unbiased, human and AI learning


FMs use unlabeled training data sets for self-supervised learning

In supervised learning, you train the model with a set of input data and a corresponding set of paired labeled output data. Unsupervised machine learning is when you give the algorithm input data without any labeled output data. Then, on its own, the algorithm identifies patterns and relationships in and between the data. Self-supervised learning is a machine learning approach that applies unsupervised learning methods to tasks usually requiring supervised learning. Instead of using labeled datasets for guidance, self-supervised models create implicit labels from unstructured data.

Foundation models use self-supervised learning to create labels from input data. This means no one has instructed or trained the model with labeled training data sets.



Correct option:

Underfit models experience high bias, whereas, overfit models experience high variance

Your model is underfitting the training data when the model performs poorly on the training data. This is because the model is unable to capture the relationship between the input examples (often called X) and the target values (often called Y). Your model is overfitting your training data when you see that the model performs well on the training data but does not perform well on the evaluation data. This is because the model is memorizing the data it has seen and is unable to generalize to unseen examples.


Underfit models experience high bias — they give inaccurate results for both the training data and test set. On the other hand, overfit models experience high variance - they give accurate results for the training set but not for the test set.

You cannot use continued pretraining to implement RAG workflow in Amazon Bedrock.

You can use a customized model only in the Provisioned Throughput mode
Smaller models are cheaper to use than larger models

Correct options:

With Amazon Bedrock, you will be charged for model inference and customization. You have a choice of two pricing plans for inference: 1. On-Demand and Batch: This mode allows you to use FMs on a pay-as-you-go basis without having to make any time-based term commitments. 2. Provisioned Throughput: This mode allows you to provision sufficient throughput to meet your application's performance requirements in exchange for a time-based term commitment.

You can use the On-Demand mode only with time-based term commitments - With the On-Demand mode, you only pay for what you use, with no time-based term commitments. So, this option is incorrect.

You can use a customized model in the Provisioned Throughput or On-Demand mode - Custom models can only be accessed using Provisioned Throughput. So, this option is incorrect.


Large Language Model (LLM)

Large language models (LLMs) are a class of Foundation Models (FMs). For example, OpenAI's generative pre-trained transformer (GPT) models are LLMs. LLMs are specifically focused on language-based tasks such as such as summarization, text generation, classification, open-ended conversation, and information extraction.

Retrieval-Augmented Generation (RAG)

Retrieval-Augmented Generation (RAG) is the process of optimizing the output of a large language model, so it references an authoritative knowledge base outside of its training data sources before generating a response. Large Language Models (LLMs) are trained on vast volumes of data and use billions of parameters to generate original output for tasks like answering questions, translating languages, and completing sentences. RAG extends the already powerful capabilities of LLMs to specific domains or an organization's internal knowledge base, all without the need to retrain the model. It is a cost-effective approach to improving LLM output so it remains relevant, accurate, and useful in various contexts.

Depending on the configuration, Amazon Q Business web application workflow can use LLM/RAG or both.

Diffusion Model - Diffusion models create new data by iteratively making controlled random changes to an initial data sample. They start with the original data and add subtle changes (noise), progressively making it less similar to the original.

Generative adversarial network (GAN) - GANs work by training two neural networks in a competitive manner. The first network, known as the generator, generates fake data samples by adding random noise. The second network, called the discriminator, tries to distinguish between real data and the fake data produced by the generator. During training, the generator continually improves its ability to create realistic data while the discriminator becomes better at telling real from fake. This adversarial process continues until the generator produces data that is so convincing that the discriminator can't differentiate it from real data.

Variational autoencoders (VAE) - VAEs use two neural networks—the encoder and the decoder. The encoder neural network maps the input data to a mean and variance for each dimension of the latent space. It generates a random sample from a Gaussian (normal) distribution. This sample is a point in the latent space and represents a compressed, simplified version of the input data. The decoder neural network takes this sampled point from the latent space and reconstructs it back into data that resembles the original input.

This process is called inference, where the model uses its trained parameters to generate a prediction or output based on new input data provided by the user
This process is known as training, which involves using labeled data to adjust the model's parameters so it can generate a prediction or output based on new input data provided by the user  



Self-supervised learning

It works when models are provided vast amounts of raw, almost entirely, or completely unlabeled data and then generate the labels themselves.

Foundation models use self-supervised learning to create labels from input data. In self-supervised learning, models are provided vast amounts of raw completely unlabeled data and then the models generate the labels themselves. This means no one has instructed or trained the model with labeled training data sets.

Reinforcement learning - Reinforcement learning is a method with reward values attached to the different steps that the algorithm must go through. So the model’s goal is to accumulate as many reward points as possible and eventually reach an end goal.

Supervised learning - In supervised learning, models are supplied with labeled and defined training data to assess for correlations. The sample data specifies both the input and the output for the model. For example, images of handwritten figures are annotated to indicate which number they correspond to. A supervised learning system could recognize the clusters of pixels and shapes associated with each number, given sufficient examples.

Data labeling is the process of categorizing input data with its corresponding defined output values. Labeled training data is required for supervised learning. For example, millions of apple and banana images would need to be tagged with the words “apple” or “banana.” Then machine learning applications could use this training data to guess the name of the fruit when given a fruit image.

Unsupervised learning - Unsupervised learning algorithms train on unlabeled data. They scan through new data, trying to establish meaningful connections between the inputs and predetermined outputs. They can spot patterns and categorize data. For example, unsupervised algorithms could group news articles from different news sites into common categories like sports, crime, etc. They can use natural language processing to comprehend meaning and emotion in the article.

