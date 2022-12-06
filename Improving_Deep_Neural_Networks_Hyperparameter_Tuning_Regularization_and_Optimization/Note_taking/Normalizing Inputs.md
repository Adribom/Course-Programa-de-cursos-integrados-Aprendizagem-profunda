202212021053
Status: #idea 
Tags: [[Machine Learning]]

# Normalizing Inputs

Uma forma de acelerar o processo de treinamento de um rede neural é normalizar os dados, de modo a normalizar a média, para que fique próxima de zero, e normalizar a variância, para que vá de 0 a 1 em todos os eixos do dataset.

![[Pasted image 20221202105533.png]]

Com isso, a Cost Function terá um formato mais simétrico, e uma [[Gradient Descent]] terá um caminho mais direto para prosseguir, aumentando a velocidade de otimização do modelo.

![[Pasted image 20221202110219.png]]

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/lXv6U/normalizing-inputs