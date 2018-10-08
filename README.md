# Atividade de laboratório sobre inferência estatística

- Créditos: Prof. Nazareno Andrade (UFCG)

Nesta atividade, nós usaremos uma amostra de dados da atividade global do github. Os dados brutos contêm a contagem de quantas pessoas editaram arquivos com cada extensão de arquivo em cada dia de 2016 e 2017 no github. Não temos dados de todos os repositórios nem de todos os usuários, portanto estamos trabalhando com uma amostra e queremos fazer inferência sobre a população.

O csv com os dados está aqui em: _dados/github-users-committing-filetypes.csv_

## O que fazer

Vocês devem usar os conceitos aprendidos no assunto de inferência estatística, principalmente no cálculo de intervalos de confiança (IC) para diferentes métricas. Não use apenas a média como métrica principal (ou seja, é interessante user bootstrap para calcular o IC para diferentes métricas. 


### Primeira parte

Nessa parte do problema, você responderá primeiro duas perguntas nossas. Responda ambas as perguntas no relatório.

Escolha duas linguagens de programação que lhe interessem e responda o seguinte:

1. Para cada uma delas, há uma diferença significativa na sua popularidade durante a semana e durante o fim de semana? Essa diferença é grande? (dica: aqui você precisa decidir como medir popularidade: média? mediana? outra estatística?)

2. Existe uma diferença significativa entre a popularidade das duas linguagens nos fins de semana? (a mesma dica vale)

Lembre: não comece sua análise sem antes fazer um descritivo dos dados. Mostre esse descritivo ao leitor. Lide com outliers, valores faltantes e coisas do tipo, se houverem.

Dica: no tipo de dados que estamos usando, parece muito necessário dar uma olhada em uma linha do tempo.

### Segunda parte

Daqui em diante nesse problema você poderá escolher entre dois dados: os dados do github usados na primeira fase, ou dados sobre uma amostra de avaliações de filmes (do [IMDB](https://datasets.imdbws.com/) ou do [Movie Lens](http://grouplens.org/datasets/movielens/latest/Links)). Lembre que esses sites têm apenas uma amostra das avaliações de todas as pessoas. Este problema trata com estimarmos a opinião que a audiência de um filme tem a partir dessa amostra.

Tendo escolhido um ou outro, sua tarefa nessa fase é postar no Google Classroom desta atividade quatro perguntas que possam ser respondidas usando inferências sobre estatísticas calculadas a partir da amostra de dados que você tem. Pelo menos metade dessas perguntas deve ser sobre estatísticas que não a média. Para cada pergunta, escreva também uma resposta possível/plausível (aqui basta adivinhar, não precisa fazer nenhuma análise).


### Terceira parte

Escolha 2 das perguntas que você listou e construa uma resposta para as duas em um relatório. A partir dos resultados dessas 2 perguntas iniciais, derive mais duas e as responda. Lembre de escrever o texto para alguém interessado em linguagens de programaçãos ou em filmes. Os métodos estatísticos devem estar lá, mas o principal deve ser as conclusões a que você chegará.


## Entrega

Você deve usar o relatorio.Rmd como template inicial para desenvolver suas análises. Crie um branch separada para a sua análise, vá fazendo commits incrementais e, ao final, faça um Pull Request para a master tanto do Rmd quanto do HTML gerado. Envie também o HTML para na atividade do Google Classroom.

