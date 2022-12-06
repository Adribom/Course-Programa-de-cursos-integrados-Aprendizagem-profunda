202212031234
Status: #idea 
Tags: [[Machine Learning]]

# Mini-batch Gradient Descent

Quando treinamos um modelo, devemos nos preocupar com diversas coisas, como [[Overfitting]] ou [[Underfitting]]. Porém, quando entramos na situação em que há diversos exemplos de treino, o modelo terá que realizar diversas computações antes que possa dar um único passo de [[Gradient Descent]] para todo o "*Batch*".

Dessa forma, podemos utilizar a técnica de dividir os exemplos de treino em conjuntos, chamadas de Mini-batches. Para cada Mini-batch, é feito um pequeno passo com o Gradient Descent.
![[Pasted image 20221203123744.png]]

Cada iteração de Foward Prop e Back Prop em um Mini-batch é chamado de *epoch*.

Quanto ao número de mini-batches, é mais vantagioso escolher um valor entre 1 e o número de exemplos. Porém, isso só vale para muitos exemplos, vale a pena deixar de usa-ló quando esse não é o caso. Como forma de referência:
- m < 2000: Usar apenas Batch
- m > 2000: Usar potências de 2 (velocidade aumenta pela forma que computador opera memória)
	- 2^6 = 64
	- 2^7 = 128
	- 2^8 = 256
	- 2^9 = 512

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/lBXu8/understanding-mini-batch-gradient-descent