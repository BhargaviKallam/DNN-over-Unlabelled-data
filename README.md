# DNN-over-Unlabelled-data
CODE EXECUTION 

For successful execution of the code, the following libraries should be installed in addition to all the statistical libraries:

  1. YAKE (https://github.com/LIAAD/yake)
  2. RAKE (https://pypi.org/project/rake-nltk/)
  3. KeyBert (https://github.com/MaartenGr/KeyBERT)
  4. PositionRank (https://pypi.org/project/pytextrank/)
  5. Scikit-learn for LDA and TF-IDF (https://scikit-learn.org/stable/install.html)



Execution pattern of files;

  - Index 1 : HULTH2003 dataset; Index 2 : SemEval2017 dataset; Index 3 : WWW dataset
  - Run the 1.1.---- next 1.2.------ next 1.3.----- and 1.4. ---
  - Similarly for the 2 and 3 indexed files.


FOLDERS DESCRIPTION:

- dataset : this folder contains all the original data for all the datasets which are in text files.
- Data : this folder contains the converted text files to pandas data frame stored in a pickle file
- hulth_results : this folder contains all the pickle file outputs for each algorithm on the HULTH dataset
- semeval_results : this folder contains all the pickle file outputs for each algorithm on the semeval dataset
- www_results : this folder contains all the pickle file outputs for each algorithm on the www dataset

