# Plagiarism-Detection-Study

### Objective
The objective of the project is to explore natural language processing (NLP) & Machine Learning (ML) techniques to improve plagiarism detection and to overcome the hurdles of plagiarism detection in paraphrased text. We aim at exploring the scope and limitation of existing word embeddings in literature and identifying the best method for detecting plagiarism in text.

### Purpose
Ethical issues of the authenticity of one’s work have become a matter of concern. In this project, we explore natural language processing and machine learning techniques to improve plagiarism detection. The main issues focused on this project is the issue of plagiarism detection in paraphrased text and that degrades the academic and research integrity. The current systems only enable students to paraphrase texts to avoid detection rather than giving claim to the sources where the citation has taken place. Similar words don’t mean similar implications. Different words don’t imply different meanings to sentences. A context-based plagiarism detection tool is needed to look beyond words. We inculcated the idea of Word embeddings in the Machine Learning models so that paraphrasing can also be detected.

Unlike the traditional plagiarism detection method that uses text-matching, we attempt to focus on the context of the text. Plagiarised text need not be copy pasted, it can also be adoption of ideas without giving credit. The project tries to overcome the hurdles of plagiarism detection in paraphrased text. 
We look forward to understanding the scope and limitation of currently existing word embeddings in literature, suggest methods for plagiarism detection according to user requirements, evaluate effectiveness of different word embeddings in identifying different types of plagiarism in the text. We aim to identify the best word embedding method for detecting plagiarism in the text and develop an automated model for plagiarism detection in text. We hope this study will benefit not only developers interested in plagiarism detection software but also researchers working in NLP to advance the domain of inter-textual similarity detection.

### Summary
Plagiarism is claiming another’s work as one’s own. The issue is about not crediting the original author. 
This digital crime has become a frequent practice in the academic industry and can raise many legal and monetary issues with copyright claims. 
There are many readily available platforms for plagiarism detection. Some use string matching and pattern matching, whereas the others use a variety of techniques
like LSA, LDA, and other ML techniques. Most of these techniques are based on Bag of Words and do not give word order into consideration. This is when the appearance 
of a word in the vocabulary is given higher priority than the meaning or context of the word. Adoption of ideas from one without giving credit is also a form of 
plagiarism. We introduced the idea of incorporating Word Embeddings within a Machine Learning to weigh the semantics of the word. This would enable us to detect if 
the text is paraphrase. We adopted features like 1-7 n-gram containment, sumo-metric adapted blue-score, along with Bert-similarity to build three Machine Learning 
classifiers. Random Forest, Support Vector Model and Logistic Regession classifiers were build. 

Our Study happened in two stages.
#### Stage1
	
In the first part of the project, we conduct a comparative study with different word embeddings to determine its efficiency to detect plagiarism or paraphrasing of text.
To conduct this, we need

	--> Data to train the embeddings
	
	--> An organized Corpus with labelled data to check the performance of the embeddings

The word embeddings we used are:

		a)	Word2vec

		b)	Glove

		c)	Bert

		d)	FastText
	
The Corpus to evaluate the performance of the embeddings is developed by Paul Clough and the team of Computer Science Department in Sheffield University.
It is commonly referred as the ‘Wikipedia Rewrite Corpus’ and was created with the intention to ease research in the domain of intertextuality.
The corpus containing 100 documents were built by a team of 19 students consisted of 95 answers and 5 source documents.
It aimed at showcasing different degrees of rewrite in the plagiarized documents to enable the evaluation of different plagiarism detection algorithms.

In the first stage we used our pretrained word embeddings to analyze how effectively the word embeddings detect if the text is plagiarized. 
The measures used to calculate similarity between the source text and generated text was 

		(a) Cosine Similarity
		
		(b) Word Mover's Distance
	
A pictorial representation can help to understand better. Here is the stage 1 workflow.
	
![asd-Page-1](https://user-images.githubusercontent.com/68504809/211213457-d0c097fa-dcb2-4606-a300-6835e0e9714d.jpg)

#### Stage2

The “Webis Crowd Paraphrase Corpus-2011” (Webis-CPC-11) was used in the second stage, which is a part of the PAN 2010, the international plagiarism-detection competition. 
This corpus contains passage-level paraphrases with 4067 positive samples and 3792 negative samples that failed our criteria, using Amazon’s 
Mechanical Turk, a commercial tool for crowdsourcing that has gathered considerable interest in research and practice; 
it has also been demonstrated to be useful for proofreading, writing, and translating texts. The whole corpus has text files with
the original text files, paraphrased text files, metadata files.

A 


	


