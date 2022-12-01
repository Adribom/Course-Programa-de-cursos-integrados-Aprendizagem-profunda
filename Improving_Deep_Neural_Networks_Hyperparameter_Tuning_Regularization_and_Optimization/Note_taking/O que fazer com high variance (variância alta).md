202211271700
Status: #idea 
Tags:

# O que fazer com high variance (variância alta)

Uma variance alta, assim como abordado na [[Bias and Variance trade-off]], normalmente produz overfitting. Isso ficará bem refletidio no dev e test set. As formas mais diretas de melhorar esse problema é:
- Mais dados
- [[Regularization ou Weight Decay]]
- [[Dropout Regularization]]
- Pesquisar por uma arquitetura de rede diferente
- Diminuir o número de features (otimizar para ter apenas os que realmente fazem a diferença)

---
# References
https://www.coursera.org/learn/deep-neural-network/lecture/ZBkx4/basic-recipe-for-machine-learning