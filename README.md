# HMM_Based_POS_Tagging
HMM+-based+POS+tagging-+Assignment from Upgrad
MM-based POS tagger and implement the Viterbi algorithm using the Penn Treebank training corpus. The vanilla Viterbi algorithm we had written had resulted in ~87% accuracy. The approx. 13% loss of accuracy was majorly due to the fact that when the algorithm encountered an unknown word (i.e. not present in the training set, such as 'Twitter'), it assigned an incorrect tag arbitrarily. This is because, for unknown words, the emission probabilities for all candidate tags are 0, so the algorithm arbitrarily chooses (the first) tag.

 

In this assignment, you need to modify the Viterbi algorithm to solve the problem of unknown words using at least two techniques.
