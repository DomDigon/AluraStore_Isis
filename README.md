# AluraStore_Isis
Desafio AlureStore
Nesse desafio analisei os dados informados pelo Sr. João de suas 4 lojas espalhadas pelo Brasil. O Sr. João precisa saber detalhes de sua operação e qual loja precisa fechar. Após analisar os dados cheguei a conclusão abaixo:
A categoria moveis é a mais vendida e os produtos Cama Box, Kit banqueta, Mesa de Jantar e guarda-roupas vendem bastante. Sugiro aumentar a produção desses itens.
Não recomendo fechar nenhuma loja, visto que todas tem um faturamento muito semelhante. Ajustaria algumas categorias de produtos.
utilidades domesticas, livros e instrumentos musicais deveriam ser vendidos, pois representam uma fatia muito pequena do negócio. Sugiro reaplicar o dinheiro das vendas nas outras categorias que vendem mais como moveis e seguir a sugestão informada anteriormente.
Utilizei três tipos de gráficos: Pizza, linhas e barras. No codigo de barras identifiquei que o faturamento das 4 lojas é muito semelhante. No gráfico de pizza fica mais claro identificar as categorias mais vendidas. No gráfico de linhas foram expostos os itens mais vendidos em cada loja.

Todas essas análises me levaram a conclusão supracitada.
Para executar o notebook, sugiro carregar as bilbiotecas e DataFramse abaixo:

import matplotlib.pyplot as plt
import pandas as pd

url = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv"
url2 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv"
url3 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv"
url4 = "https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv"

loja = pd.read_csv(url)
loja2 = pd.read_csv(url2)
loja3 = pd.read_csv(url3)
loja4 = pd.read_csv(url4)

loja.head()
