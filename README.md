By MH Gencer


Go to 'code.py' above for the Python script (requires Python 3.9 or higher). See below for a short explanation. 


![Figure_1](https://user-images.githubusercontent.com/97817068/205480104-cc36b21f-eeb7-42e5-87db-816342ee811b.png)


## Integrated Information Theory of Consciousness (IITC)
IITC is a relatively new theory of consciousness proposed by Giulio Tononi (2008, 2014, 2016). The theory's main goal is to establish the foundations for a mathematical framework with which we can answer the question of why we are conscious. In the framework IITC offers, consciousness results from highly integrated informational processes that can be specified by using a set of well-defined mathematical concepts. The hope is to open new avenues for both empirical and purely mathematical research on necessary and sufficient conditions for having conscious experience.


## Kullback-Leibler Divergence (KLD)
KLD is one of the statistical concepts used in IITC. In particular, IITC uses KLD to conceptualize the difference between what the conscious entity generates as output (i.e., conscious experience) and what its brain (or any other physical substrate of consciousness) takes as input (e.g., sense-data), both construed as probability distributions. Here, KLD proves helpful because it quantifies how much one probability distribution "differs" from another probability distribution. More specifically, from an information-theoretic perspective, KLD calculates how many bits of information (nats) are lost in the process where the probabilistic input a system receives turns into the system's actual output (in a way contingent upon the randomly actualized value of the input). This is what makes KLD a handy tool in the IITC framework. For related reasons, KLD has been argued to be the best measure of 'integrated information', the key concept used in the definition of consciousness in IITC (Amari 2016, Griffith 2014).


In the interactive plot generated by 'code.py', KLD is stated using the standard notation KL(P || Q), which returns the value of the statistical distance from the distribution P to the distribution Q, measured in terms of nats. Users can toggle between possible μ and σ values for Blue (P) and Red (Q) normal probability distributions, and see KLD at work.

## References
Amari, S. I. (2016). Information Geometry and Its Applications (Vol. 194). Springer.


Griffith, V. (2014). A principled infotheoretic\phi-like measure. arXiv preprint arXiv:1401.0978.


Oizumi, M., Albantakis, L., & Tononi, G. (2014). From the phenomenology to the mechanisms of consciousness: integrated information theory 3.0. PLoS computational biology, 10(5), e1003588.


Tononi, G. (2008). Consciousness as integrated information: a provisional manifesto. The Biological Bulletin, 215(3), 216-242.


Tononi, G., Boly, M., Massimini, M., & Koch, C. (2016). Integrated information theory: from consciousness to its physical substrate. Nature Reviews Neuroscience, 17(7), 450-461.

