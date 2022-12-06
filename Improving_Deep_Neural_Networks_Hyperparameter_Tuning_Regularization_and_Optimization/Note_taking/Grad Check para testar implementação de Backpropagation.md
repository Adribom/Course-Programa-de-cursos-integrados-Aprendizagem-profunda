202212021145
Status: #idea 
Tags: [[Machine Learning]]

# Grad Check para testar implementação de Backpropagation

Uma forma de testar se sua implementação da Backpropagation está correta é utilizar Grad Check. Com esse método, vamos ver se as derivadas computadas para dw e db estão agindo como esperado (pequena variação causa pequenas mudanças). 

Umas notas sobre Grad check são importantes:
- É uma ferramenta de debugging, então não usar no treinamento
- Não funciona com Dropout, tem que desativar ele para fazer o Grad Check
- Pode ser que tenha que executar depois de um pouco de treino, para que w e b saiam de valores muito próximo de zero

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/6igIc/gradient-checking-implementation-notes