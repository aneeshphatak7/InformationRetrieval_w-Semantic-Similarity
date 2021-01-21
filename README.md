# InformationRetrieval_w-Semantic-Similarity


When a new virus is discovered and causes a pandemic, it is important for scientists to get information coming from all scientific sources that may help them combat the pandemic. The challenge, however, is that the number of scientific papers created is large and the papers are published very rapidly, making it nearly impossible for scientists to digest and understand what’s important in this mass of data. We have developed and discussed a cosine similarity model, a deep learning model and a corpus specific scientific literature understanding system that can take in common terms and analyze a very large corpus of scientific papers and return highly relevant text excerpts from papers containing topical data relating to the common text inputted, allowing a single researcher to gather targeted information and quickly answer important questions about the new virus. We have developed and discussed an evaluation metric to identify the best performing IR algorithm in this paper.

1  Introduction 
The COVID-19 pandemic has brought in a need for international efforts to understand, track and mitigate the disease, yielding a significant corpus of biomedical related publications for scientific research. The health practitioners and medical researchers will require specialized tools to keep 
up with the literature. COVID-19 has also resulted in an explosion of online questions related to the pandemic. While there is a rich collection of content on the web in the form of publications and articles, medical researchers would like to hone in on the most relevant pieces of text in conjunction with their scope of research. Traditional search engines do a limited job in this context but generating a set of most relevant outputs through pieces of texts and the publications they come from as answers to queries would even further speed up the process of gathering data most pertinent to the interests of the researcher. In this paper, the technical goal is to create an Information Retrieval system and rapidly search through a corpus to find relevant information to address a particular information needed.

2  Research Questions
We aim to investigate the following research questions:
RQ1. How to identify the semantically relevant documents to a given query using NLP techniques?
For this, we have designed an automated query pipeline to search for relevant findings in the reference corpus. This would possibly speed up the search process and make an efficient retrieval-based system. This would also help doctors and medical professionals to arrive at highly relevant text excerpts by analyzing a large corpus of scientific papers. 
RQ2. How to evaluate inter-model performances and assess important feature differences?
For this, we have implemented three machine learning models: 1) Feature engineering using TF-IDF weights with Cosine Similarity metric; 2) Transformer based BERT model with contextual BERT Embeddings; 3) Clinical Bert Model Pre-Trained on the MED_STS Database.
RQ3. What are the major annotation rules while annotating the relevancy? What are the major methods the models use to compute the similarity?
