202212061334
Status: #idea 
Tags:

# Adam Optimization Algorithm

Adaptive Moment Estimation (Adam) É um algoritmo de otimização muito famoso que ajuda na convergência do [[Gradient Descent]] em vários casos. Consiste na união do [[Momentum em Gradient Descent]] com [[RMSprop]].

![[Pasted image 20221206135208.png]]

Com a união, é necessário a utilização de dois Betas diferentes, B1 e B2. Além da utilização do Epsilon. Os autores do paper de introdução ao Adam recomendam os seguintes valores:
- B1: 0,9
- B2: 0,999
- E: 10^-8

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/w9VCZ/adam-optimization-algorithm