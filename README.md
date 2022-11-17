# Machine-Learning-analise-de-sentimentos-sobre-Golf-VW
Trabalho de Machine Learning e análise de Dados


O presente estudo tem como objetivo criar um machine learning que, por meio do Teorema probabilístico de Bayes, consegue classificar um tweet quanto a sua relevância. O foco de estudo foi o carro Golf da marca Volkswagen, tentou-se criar um modelo que identifica aquelas mensagens que revelam a visão dos consumidores sobre o produto, seja no sentido de criticá-lo, seja no sentido de manifestar um desejo de adquiri-lo ou vendê-lo.

Para isso foi importado 750 tweets por meio de uma conta developer no Twitter e analisado um por um quanto ao sua relevância. O critério de exploração foi o seguinte: o tweet recebeu valor 0, ou seja, irrelevante, quando se referia ao esporte golf; recebeu o valor 1, ou seja, neutro aquele tweet relacionado ao carro, mas que não exprimia qualquer juízo de valor e recebeu o valor 2, ou seja, relevante aquele que expunha uma visão do mercado sobre o produto. Para deixar mais claro o critério de avaliação, apresenta-se exemplos de tweets avaliados: - "Queria jogar golf", classificado como irrelevante [0] - "Trouxe o golf lá da casa do Victor", classificado como neutro [1] - "Estou apaixonada pelo golf que vão lançar", classificado como relevante [2]

Dos 750 tweets importados, 500 foram utilizados para identificação de um padrão por meio do Teorema de Bayes e nos 250 restantes foi aplicado o machine learning e comparado os resultados.
