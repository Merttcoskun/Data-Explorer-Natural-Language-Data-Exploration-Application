# Data-Explorer Natural Language Data Exploration Application

![{C9C11305-B171-4A83-B6A2-ADD4CEE7BF29}](https://github.com/user-attachments/assets/a520ea8b-3879-47be-84f9-ca26fd443d18)

Data Explorer is a Streamlit-based application that allows users to explore their datasets interactively, utilizing natural language models to provide insights and analyses. The app enables data summarization, variable exploration, and interactive Q&A through large language models, making it an intuitive data analysis tool for both technical and non-technical users.

Key Features:

- CSV File Upload
Users can upload their CSV files via the sidebar for exploration.

- Data Summarization
Once a file is uploaded, the app provides a detailed summary of the dataset, including initial data samples, column descriptions, missing data information, duplicate data, and essential metrics.

- Variable Exploration
Users can specify a variable of interest and receive visualizations (bar charts) and a trend analysis powered by AI models.

- Interactive Q&A
Users can ask freeform questions about the dataset in natural language, and the app returns AI-generated answers based on the data.

Technologies:
- Streamlit: The framework for building the interactive interface.
- LangChain: Used for integrating large language models and autonomous agents for data analysis.
- Pandas: For data handling and preprocessing.
- Google Gemini Pro, GPT-4, Claude 3: The models used for natural language processing and insights generation.
- dotenv: For securely loading API keys for the language models.


This app provides an intuitive, AI-powered data exploration experience, making it easier to interact with datasets and gain insights efficiently.
