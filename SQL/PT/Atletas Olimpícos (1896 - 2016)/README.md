
# ATLETAS OLÍMPICOS (1896 - 2016)

Principais conclusões das Olimpíadas de Verão analisando arquivo disponibilizado no Kaggle https://www.kaggle.com/datasets/bhanupratapbiswas/olympic-data/discussion/521684

### Arquivo
Arquivo postado por volta de julho de 2023 com 70.000 linhas e com as colunas:

Name
Sex
Age
Height
Weight
Team: país do atleta
NOC: abreviação do país
Games: ano + verão/inverno
City: cidade sede
Sport: modalidade (exemplo Natação)
Event: categoria (exemplo 100m peito)
Medal: se o atleta ganhou medalha

Os dados começam nas Olimpíadas de Atenas, em 1896, e vão até as Olimpíadas do Rio de Janeiro, em 2016.

### Agrupamento
Cada linha da tabela representa a participação dos atletas conforme a categoria (event). Por exemplo, um atleta que tenha disputado 5 provas na ginástica numa edição olímpica, terá cada modalidade numa linha da tabela.

### Linguagem
SQLite no Jupyter Notebook

### Curiosidades
Questões que instigaram a análise: 
- países com mais participações olímpicas (a nível de atleta e a nível de categoria)
- maiores campeões e medalhistas olímpicos, tanto em números absolutos, quanto relativos às participações
- esportes com maiores médias de altura, e esportes com maiores aumentos de médias de altura em edições antigas e atuais
- questões acima sobre os atletas brasileiros
- como é o histórico do Brasil nas Olimpíadas de Inverno?



