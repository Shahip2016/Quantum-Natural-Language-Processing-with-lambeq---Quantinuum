# Quantum-Natural-Language-Processing-with-lambeq---Quantinuum
Womanium Quantum Hackathon 2022

Implement a new reader
So far you’ve seen the DisCoCat model based on grammar parsing, the cups reader, the
spider reader and the tree reader. Can you come up with your own (simple) compositional
model? Maybe you can come up with a variation of the cups reader that simplifies
the computational graph and uses fewer qubits.


Implement a rewrite rule
Part of a successful QNLP experiment is to simplify the diagrams as much as possible and
cut out words that may not contribute in the meaning of a sentence. A simple example is
the article “the”. Articles are generally of type (n, n.l), i.e expect a noun to their right-hand
side. However, in most cases, articles do not come with a specific distributional meaning
(since they appear in almost every possible context) and can be left out. Hence, the following
diagram
