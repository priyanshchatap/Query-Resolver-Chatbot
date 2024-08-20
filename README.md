# Query-Resolver-Chatbot
The primary objective of this project is to develop a chatbot capable of intelligently resolving user queries across various domains. To achieve this, we harness the capabilities of the Falcon 7B NLP model, renowned for its contextual understanding and language generation. By fine-tuning Falcon 7B on a custom dataset, we enhance its ability to comprehend and respond to domain-specific queries effectively.

The sharded model architecture employed in this project is designed to handle large volumes of data efficiently and scale seamlessly to accommodate evolving requirements. Sharding enables distributed processing of user queries, resulting in improved response times and enhanced scalability, making it suitable for real-world applications with varying workloads.

The outcomes of this project hold substantial implications for industries seeking to implement intelligent chatbot solutions for customer support, information retrieval, and task automation. The utilization of Falcon 7B and the sharded model architecture showcases a promising avenue for enhancing the capabilities of chatbots in handling complex and specialized queries, thereby advancing human-computer interaction in diverse domains.

The project was divided into the following phases:
1. Data Cleaning: The first step was to filter the data given by the company. The dataset of text conversations consisting of device name, device problem, problem type and respective remedies. This dataset was used to train the chatbot on how to respond to different prompts and questions.
  
2. Chatbot development: Once the dataset was collected and filtered, the next step was to develop the chatbot. This was done using Python and a variety of NLP libraries.
   
3. Chatbot testing: The chatbot was then tested to ensure that it worked correctly. This was done by running the chatbot on a variety of prompts and questions.
