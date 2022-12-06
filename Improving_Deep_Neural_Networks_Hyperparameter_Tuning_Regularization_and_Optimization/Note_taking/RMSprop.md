202212061327
Status: #idea 
Tags: [[Machine Learning]]

# RMSprop

Root Mean Square propagation (RMSprop) é um tipo de otimizador de [[Gradient Descent]] Bem parecido com [[Momentum em Gradient Descent]]. Também utiliza [[Exponential Weighted Average]] para reduzir a disperção do erro em direções que não se aproximem do mínimo local/global. A diferença é a computação utilizada:

![[Pasted image 20221206132953.png]]

O Epsilon somado na raiz serve para que não haja problemas de computação com [[Underflow]].

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/BhJlm/rmsprop