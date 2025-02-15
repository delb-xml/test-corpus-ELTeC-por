# ELTeC-por, level 2
Here are the Portuguese files parsed with the PALAVRAS parser v. 14008, from which we used tokenization, morphological tagging and named entity recognition.
Conversion to the specific COST level 2 encoding was done partially using the **visl2malt** xml converter included in the PALAVRAS distribution, and a set of COST specific scripts available in the script folder here.

Please use the following references to PALAVRAS and PALAVRAS-NER if you use the material:
* Bick, Eckhard. 2014. PALAVRAS, a Constraint Grammar-based Parsing System for Portuguese. In: Tony Berber Sardinha & Thelma de Lurdes São Bento Ferreira (eds.): *Working with Portuguese Corpora*, pp 279-302. London/New York: Bloomsbury Academic.
* Bick, Eckhard. 2006. Functional Aspects in Portuguese NER.  In Renata Vieira, Paulo Quaresma, M. da Graça Volpe Nunes, Nuno J. Mamede, Cláudia Oliveira, and Carmelita M. Dias, editors, *Computational Processing of the Portuguese Language: 7th International Workshop*, PROPOR 2006. Itatiaia, Brazil, May 2006 (PROPOR'2006), pages 80–89. Springer Verlag. 

We thank Eckhard Bick for support and further development of the visl2malt xml converter for the purposes of ELTeC.

As for the POS tags, we used the simple (and possibly error-inducing) conversion to UD names as follows: 
PROP -> PROPN;
V marked as aux -> AUX;
V -> VERB;
IN -> INTJ;
N -> NOUN;
PERS -> PRON;
KC -> CCONJ;
KS -> SCONJ;
PRP -> ADP;
SPEC -> PRON

However, it is important to indicate that the works were parsed by the PALAVRAS parser and differ significantly in the underlying linguistic dependency options.
