202212061256
Status: #idea 
Tags: [[Machine Learning]]

# Momentum em Gradient Descent

[[Gradient Descent]] com Momentum é um tipo de otimização de algoritmo que faz com que haja uma convergência mais rápida para um mínimo local/global. 

A otimização funciona com a utilização de [[Exponential Weighted Average]] para um determinado conjunto de valores. 

Quando se relaliza um [[Gradient Descent]], pode-se dizer que existe a movimentação do erro em duas coordenadas, uma vertical e uma horizontal. Se tomarmos o seguinte desenho como base:

![[Pasted image 20221206130025.png]]

A movientação horizontal não contribui de nenhuma forma ao percurso até o ponto optimum. Dessa forma, é possível realizar a adição de uma computação de [[Exponential Weighted Average]] durante a atualização pelas derivadas dos parâmetros. De forma que os novos cálculos de gradient descent possuam a seguinte estrutura:

![[Pasted image 20221206130258.png]]

Sendo que b (beta) se torna um novo Hyperparameter, normalmente assumindo o valor de 0,9.

Uma outra forma parecida de otimização de Gradient Descent é o [[RMSprop]]

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/y0m1f/gradient-descent-with-momentum