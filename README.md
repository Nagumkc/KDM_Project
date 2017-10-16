# KDM_Project on Dynamic Intelligent Q/A system

Designed Question and Answer system to retrieve correct responses to the questions asked by human in natural language. The techniques we used are NLP, Information extraction, Machine learning and Knowledge Graph Construction.

-> Used K-Means(Clustering technique) to cluster the dataset into K number of clusters, where K is the predefined value.

-> We applied TF-IDF for labelling the cluster.

-> Processed the data of each cluster through NLP techniques(Parsing,Tokenization,Lemmatization,Named Entity Recognition(NER)) to identify classes, Individuals for Ontology construction.

-> Implemented OpenIE technique to extract triplets(realtions in the form of RDF) and a combination of NER result to identify Object properties,Data properties,Predicates

-> Built the seperate ontology for every cluster.

-> Used the DLQuery for querying the ontology.

-> When a question is being asked identify the cluster to which the question belongs to and query the corresponding Ontology and obtain the answer.

-> If the system is not able to find the answer, query the other corresponding ontology and if the answer is still not found, the system says 'Answer Not Found'.


KDM Project Presenation link:

https://drive.google.com/file/d/0B3uNuUS7xRYaVXJvdmZLMUJ1Q2M/view?usp=sharing

KDM Project video:

https://www.youtube.com/watch?v=DE8qVM5XMXA&feature=youtu.be

