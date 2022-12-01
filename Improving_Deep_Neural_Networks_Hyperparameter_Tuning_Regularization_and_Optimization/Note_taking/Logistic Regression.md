202209291740
Status: #idea 
Tags: [[Data Science]], [[Algorithms]]

# Logistic Regression

Logistic Regression é um algoritmo de [[Machine Learning]] que pode ser usado para classificação binária. Ele tem como objetivo encontrar qual a probabilidade de uma predição y_hat acontecer dado que uma feature x seja escolhida (![[Pasted image 20220929174556.png]]).

Uma forma que poderia ser feito isso seria através de uma [[Linear Regression]], o que resultaria em uma equação de parâmetros de reta:
y_hat = w^T . x + b (![[Pasted image 20220929175035.png]])

Porém, isso faz com que a reta resultante apresente valores positivos e maiores que 1, algo que não faz sentido para uma classificação binária.

Assim, é possível utilizar uma [[Sigmoid Function]] para obter um resultado sempre entre zero e um para a distribuição probabilística Bernoulli ([[Bernoulli Distribution]])  apresentada (resultados apenas binários).

Com isso, teremos ![[Pasted image 20220929181548.png]]

Agora, basta achar os valores dos parâmetros w e b tal que a estimativa y_hat seja a mais precisa possível.



---
# References
https://www.coursera.org/learn/neural-networks-deep-learning/lecture/LoKih/logistic-regression
