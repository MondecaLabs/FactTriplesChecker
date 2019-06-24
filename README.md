# FactTriplesChecker
Fact triples validator work made for the ISWC 2019 challenge - Task 1 

processing.ipynb : process the data and create ampligraph [1] embedding models  
classificationDEV.ipynb : classification of the development dataset  
classificationTEST.ipynb : classification of the officialy released dataset

The RDF2VEC models are located in the test and dev folders, and have been generated from the source of the original paper : https://madoc.bib.uni-mannheim.de/41307/1/Ristoski_RDF2Vec.pdf

The file Results_MLPbest_rdf2vec_300_10_8.nt is the submitted result of the classification in the GERBIL platfrom for the task 1 ISWC 2019 challenge

[1] https://github.com/Accenture/AmpliGraph
