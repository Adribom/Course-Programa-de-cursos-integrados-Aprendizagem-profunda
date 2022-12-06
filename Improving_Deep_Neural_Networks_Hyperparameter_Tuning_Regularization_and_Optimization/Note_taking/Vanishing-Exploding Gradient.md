202212021129
Status: #idea 
Tags: [[Machine Learning]]

# Vanishing-Exploding Gradient

![[Pasted image 20221202113007.png]]

O termo marcado serve para reduzir o vanishing/exploding gradients. Ao computar uma rede com muitas camadas, é bem provavel que o valor de w gere um valor para a função de ativação que exploda (quando inicializado com valor > 1) ou desapareça (quando inicializado com valor < 1). Assim, é benéfico usar o termo para que, quanto maior o número de camadas, menor a soma total de w.

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/RwqYe/weight-initialization-for-deep-networks