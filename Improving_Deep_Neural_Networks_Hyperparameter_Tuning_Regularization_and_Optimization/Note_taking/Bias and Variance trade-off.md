202211260916
Status: #idea 
Tags: [[Machine Learning]]

# Bias and Variance trade-off

**Bias** é uma métrica que assume o quanto o modelo faz suposições para os dados, isso é refletido na diferença entre a previsão feita pelo algoritmo com os valores reais esperados.- 
	- **Bias pequeno:** menas suposições feitas pelo modelo.
	- **Bias alto:** mais suposições feitas pelo modelo --> **underfitting**  

**Variance** é uma métrica que toma em conta a mudança dos valores de predição ao se mudar o conjunto de dados de treinamento, isso é refletido em quanto uma variável aleatória é diferente de seu valor esperado.
	- **Variance pequena:** pequenas variações na previsão com mudanças no training set
	- **Variance alta:** modelo com alta complexidade que reflete muito em variações dos dados --> **Overfitting**

![[Pasted image 20221126093124.png]]

Para configuração de um bom modelo, é necessário prestar atenção no balanço entre Bias e Variance. Se o modelo for simples e houver poucos parâmetros, ele poderá exibir Bias alto e variância baixa. Se for um modelo complexo com muitos parâmetros, pode exibir pequeno Bias e alta Variância. O balanco entre essas duas métricas é chamada de **Bias-Variance trade-off** .

![[Pasted image 20221126093512.png]]


---
# References
https://www.javatpoint.com/bias-and-variance-in-machine-learning