
# (Re) Re-visiting the false consensus bias in the interpretation of legal text 
This experiment is an extension of a recent study investigating variation in the interpretation of vague or underspecified terms in legal documents (Waldon, Brodsky, Ma, and Degen 2023). The abstract from this original study is as follows: 

_We present a large-scale conceptual replication of an experiment that provided evidence of false consensus biases in legal interpretation: when reading a legal contract, individuals are prone to over-estimate the extent to which others would agree with their interpretation of that contract (Solan 2008). The results of our replication affirm this previous finding, but they also suggest that there is substantial unexplained item-level variation in the extent to which individuals agree on contract interpretation, in addition to unexplained variation in the extent to which the false consensus bias holds across interpretive contexts._

_In a first step towards understanding the source(s) of this variability, we show that a state-of-the-art large language model (LLM) with zero-shot prompting does not robustly predict the degree to which interpreters will exhibit consensus in a given context. However, performance improves when the model is exposed to data of the form collected in our experiment, suggesting a path forward for modeling and predicting variability in the interpretation of legally-relevant natural language._


The current (pilot) experiment aims to replicate the human-experimental portion of the original study, with additional conditions manipulating the synactic form of the insurance definition. The four versions of the insurance definitions contain difficult-to-process syntactic features that are known to be extraordinarily prevalent in legal contracts (Martinez & Gibson 2020), namely center-embedded clauses and passive voice. In so far as our original study demonstrated that humans are bad reporters of how others will interpret text, and to the extent that 1) it is important for legal language to be interpreted as intended and 2), legal documents are ridden with interpretive difficulties, it will be valuable to investigate what, if any, systematic relationship exists between these interpretive difficulities and measures of interpretive consensus. 

This repository that contains the following sub-directories:

The directory `experiments` contains stimuli and code used to run the experiment. 

The directory `data` contains the (anonymized) data from the experiment. 

The directory `analyses` contains the R scripts used for analysis and visualization. 
