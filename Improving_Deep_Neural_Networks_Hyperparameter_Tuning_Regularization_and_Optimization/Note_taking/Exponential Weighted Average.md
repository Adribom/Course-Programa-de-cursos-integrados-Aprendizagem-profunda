202212051821
Status: #idea 
Tags: [[Machine Learning]]

# Exponential Weighted Average

Existem diversos algoritmos de otimização que podem ser mais rápidos que [[Gradient Descent]] e muitos desses algoritmos utilizam o Exponential Weighted Average.

Exponential Weighted Average é um tipo de medida para se determinar taxas de variações médias a partir de valores presentes e passados. A relação de dados usados para computar a média se move de acordo com o valor presente. Quanto mais nos afastamos do início, menos pesos os primeiros dados terão. Esse peso é determinado pelo fator B (beta).

![[Pasted image 20221205182431.png]]

Essa medida é calculada com a fórmula: ![[Pasted image 20221205182530.png]]

Existe um problema inerente a essa fórmula. Sua computação inicial sempre fica próxxima de zero, assim, é utilizado um fator para fazer com que o início tenda mais para o valor dos dados iniciais. Isso ajuda principalemente com dados que têm início longe de zero

![[Pasted image 20221205191946.png]]

![[Pasted image 20221205182724.png]]


---
# References
<iframe title="Exponentially Weighted Moving Average or Exponential Weighted Average | Deep Learning" src="https://www.youtube.com/embed/XV1f_srZg_E?feature=oembed" height="113" width="200" allowfullscreen="" allow="fullscreen" style="width: 100%; height: 100%; aspect-ratio: 16 / 9;"></iframe>
