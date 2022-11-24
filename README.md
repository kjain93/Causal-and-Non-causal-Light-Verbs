# Identifying Causal and Non-causal verb alternations in Hindi

Provides a framework to identify causative (causal) and anticausatives (non-causal) for Light Verb Constructions (LVC) found in Hindi.

For the analysis the focus was on finding nouns occuring with both /kar/ 'do' and /ho/ 'be' verbs in Hindi. The occurence of nouns with /kar/ in a LVC is taken as causative and with /ho/ as anticausative as suugested in [2].

Data: HDTB corpus is used and can be downloaded from here: https://github.com/UniversalDependencies/UD_Hindi-HDTB

Python library: UDAPI can be downloaded from here: https://github.com/udapi/udapi-python

### Python Notebook
* calculates the C/A ratio for the nouns alternating as causal and non-causal and gives a spontenity scale
* calculates the probability of a noun to occur as causative noun
* calculates the probability of a noun to occur as causative noun when not occurring with highly frequent verbs. For our purpose the verbs 'do', 'give', and 'take' have been selected


### Selected References
1. Haspelmath, M. (1993). More on the typology of inchoative/causative verb alternations. *Causatives and transitivity*, 23, 87-121.
2. Vaidya, A., Rambow, O., & Palmer, M. (2014, August). Light verb constructions with ‘do’and ‘be’in Hindi: A TAG analysis. In *Proceedings of Workshop on Lexical and            Grammatical Resources for Language Processing* (pp. 127-136).
