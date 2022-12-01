202211271747
Status: #idea 
Tags: [[Machine Learning]]

# Regularization ou Weight Decay

Pensando em reduzir overfitting produzido por uma variância alta. Para uma logistic regression, podemos adicionar na cost function uma L2 regularization. Equanto que em uma rede neural, podemos adicionar uma Norma de Frobenius (Praticamente o L2 aplicado para redes neurais).

De forma intuitiva, a regularization estará reduzindo a complexidade que a função final de cada ativação pode ter. Vários parâmetros de W chegaram a valores próximos de zero. 
![[Pasted image 20221127180013.png]]

Dessa forma, acontecerá uma simplificação da rede neural. Como se estivesse tentendo mais a um caso de High Bias.

![[Pasted image 20221127180056.png]]

## **Logistic regression:**
![[Pasted image 20221127174839.png]]

## **Neural Network:**
![[Pasted image 20221127174922.png]]


---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/Srsrc/regularization