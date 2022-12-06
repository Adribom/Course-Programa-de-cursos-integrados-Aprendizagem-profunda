202212020928
Status: #idea 
Tags: [[Machine Learning]]

# Variável Keep-prop para cada camada de uma rede neural

A Keep-Prob é uma variável probabilística (0 <= Keep-Prob <= 1), presente na [[Dropout Regularization]], que demonstra a probabilidade de cada neurônio presente na camada permanecer ativo. Ter um Keep-Prob de 0.7 significa que há 70% de chance do nódulo permanecer ativo. 

O seu valor pode variar para cada camada, portanto, colocamos valores menores para camadas em que sabemos que está gerando mais [[Overfitting]], enquanto deixamos valores mais altos para camadas que não estão aumentando muito o valor da variância e valores unitários para as que estão presentes na saída.

---
# References
