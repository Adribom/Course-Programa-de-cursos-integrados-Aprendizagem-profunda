202212071650
Status: #idea 
Tags: [[Machine Learning]]

# Normalizing activations

[[Normalizar entradas]] é uma tática eficaz para otimizar o [[Gradient Descent]], de forma que a função de custo fique com um formato simétrico. Porém, é possível expandir esse conceito para outras partes da rede. Normalizar ativações é uma dessas formas que proporciona um treinamento mais acelerado.

Para normalização de ativações, é realizado a normalização de z (caso mais comum) de forma que tenha sua média em zero e variação de 1.

Dessa nova configuração também surgem novos parâmetros passivos de aprendizagem. Gama e beta. Eles serão atualizados assim como w e b e farão com que a média de alguma unidades hidden tenham médias diferentes de 0, dependendo da necessidade. 

O nome dessa [[Otimização (ML)]] é **Batch Norm**.

Um fator importante é que, devido a forma de computação de *gamma* e *beta*, o parâmetro *b* sempre será zerado. Portanto, *b* não é utilizado como parâmetro quando se faz Batch Norm.

**Batch Norm** tbm tem um pequeno efeito de regularização, pois adiciona um pouco de ruído para cada z em cada hidden layer para cada [[Mini-batch Gradient Descent]]. Assim, o modelo passa não depender tão intensamente em nenhuma função de ativação em específico. 

![[Pasted image 20221207165959.png]]

---
# References
