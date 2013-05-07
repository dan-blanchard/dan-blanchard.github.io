---
title: Word Segmentation
---

How do infants come to identify words in the speech stream? As adults, we break up speech into words with such ease that we often think that there are audible pauses between words in the same sentence. However, unlike some written languages, speech does not have any completely reliable markers for the breaks between words (Cole and Jakimik, 1980). In fact, languages vary on how they signal the ends of words (Cutler and Carter, 1987), which makes the task even more daunting. Adults at least have a lexicon they can use to recognize familiar words, but when an infant is ﬁrst born, they do not have a pre-existing lexicon to consult. In spite of these challenges, by the age of six months infants can begin to segment words out of speech (Bortfeld et al., 2005). The goal of my research is to use evidence from infant language acquisition research to build an efficient unsupervised word segmentation system.  
  
### PHOCUS  ###
Since the publication of our JCL article, we have discovered an error in how the phoneme trigram probabilities were calculated. Essentially, only the trigrams probabilities were being multiplied together, whereas the word-initial bigram probability should also have been included to properly follow the [chain rule](http://en.wikipedia.org/wiki/Chain_rule_(probability)). The updated implementation of PHOCUS is available [here](http://www.eecis.udel.edu/~blanchar/research/phocus-jcl/download_files/phocus-r310.tar.bz2).  
  
### Publications ###

- Blanchard, Daniel (2011). [Unsupervised Word Segmentation: An Investigation of Sub-word Features](http://www.eecis.udel.edu/~blanchar/research/files/proposal.pdf). University of Delaware PhD Thesis Proposal. 
- Blanchard, Daniel, Jeffrey Heinz, and Roberta Golinkoff (2010). [Modeling the contribution of phonotactic cues to the problem of word segmentation](http://journals.cambridge.org/repo_A76oKjVI). Journal of Child Language vol. 37 (3) pp. 487-511. _[Full results and segmenter code as it was at time of paper submission.](http://www.eecis.udel.edu/~blanchar/research/phocus-jcl/)_ 
- Blanchard, Daniel and Jeffrey Heinz (2008). [Improving Word Segmentation by Simultaneously Learning Phonotactics](http://www.eecis.udel.edu/~blanchar/research/files/improving-word-segmentation-by-simultaneously-learning-phonotactics.pdf). CoNLL 2008: Proceedings of the 12th Conference on Computational Natural Language Learning, pp. 65–72. 
Related Work 

- Goldwater, Sharon, Thomas Griffiths, and Mark Johnson (2009). [A Bayesian Framework for Word Segmentation: Exploring the Effects of Context.](http://homepages.inf.ed.ac.uk/sgwater/papers/cognition-hdp.pdf) Cognition. 
- Fleck, Margaret (2008). [Lexicalized phonotactic word segmentation.](http://www.cs.uiuc.edu/homes/mfleck/my-papers/wordseg-final.pdf) Proceedings of ACL-08: HLT, pp. 130–138. 
- Johnson, Mark (2008). [Using adaptor grammars to identify synergies in the unsupervised acquisition of linguistic structure.](http://www.aclweb.org/anthology/P/P08/P08-1046.pdf) Proceedings of ACL-08: HLT, pp. 398–406. 
- Johson, Mark (2008). [Unsupervised word segmentation for Sesotho using Adaptor Grammars.](http://www.aclweb.org/anthology/W/W08/W08-0704.pdf) SIGMORPHON 2008: Proceedings of the Tenth Meeting of the ACL Special Interest Group on Computational Morphology and Phonology, pp. 20–27. 
- Swingley, Daniel (2005). [Statistical clustering and the contents of the infant vocabulary.](http://linkinghub.elsevier.com/retrieve/pii/S0010028504000398) Cognitive Psychology vol. 50 (1) pp. 86–132. 
- Batchelder, Eleanor (2002). [Bootstrapping the lexicon: a computational model of infant speech segmentation.](http://linkinghub.elsevier.com/retrieve/pii/S0010027702000021)Cognition vol. 83 (2) pp. 167–206. 
- Venkataraman, Anand (2001). [A statistical model for word discovery in transcribed speech.](http://portal.acm.org/citation.cfm?id=972657) Computational Linguistics vol. 27 (3) pp. 352–372. 
- Brent, Michael (1999). [An Efficient, Probabilistically Sound Algorithm for Segmentation and Word Discovery.](http://www.springerlink.com/content/g840p555100429vj/fulltext.pdf)Machine Learning vol. 34 pp. 71–105.
