# Annual_Report_NLP
Financial Page Document Classification

Pre-processed of text files followed by using tdidf to extract features from the training text pages.
Fed this to several ML models-
1. Naive Bayes
2. Random Forest
3. XGB (best accuracy)

Pre-process the input pdf annual report unstuctured data using pdfminer. Feed it to the classifier to classify as all the pages of the pdf file as financial notes, financial statement or junk.
