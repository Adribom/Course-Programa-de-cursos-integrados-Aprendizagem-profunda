202212071036
Status: #idea 
Tags: [[Machine Learning]]

# Hyperparameter Tunning Process

Sabendo dos Hyperparameters que existem e seus usos, ainda resta testá-los em prática para decobrirmos como que cada um deles afeta o problema em específico.

Baseado nesses testes, algumas práticas podem ajudar:
- Realizar amostragem aleatória, para que seja possível testar o máximo de valores diferentes de hyperparameters
- Utilizar o método de procura [[Coarse to fine]] 
- Utilizar uma escala logarítmica para a amostragem aleatória, já que a escala linear pode concentrar a maior parte da computação para valores em intervalos específicos

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/dknSn/tuning-process