# Cubo_Gelatinoso
Repositório para a Criatura Lendária (Cubo Gelatinoso), trabalho final da disciplina de Aprendizado de Máquina no 2º Semestre na Ilum, Escola de Ciência.

### Descrição do projeto

Este trabalho foi desenvolvido para o projeto final da disciplina de Aprendizado de Máquina. Seu objetivo é criar um modelo de classificação utilizando o algoritmo dos k-vizinhos mais próximos (KNN) em um conjunto de dados previamente selecionado, considerando diferentes combinações de hiperparâmetros. O modelo buscará identificar qual combinação de parâmetros e atributos prediz da melhor forma o target escolhido. Esse processo será realizado com o intuito de praticar a análise de dados e estudar o desempenho de modelos computacionais de aprendizado de máquina.


### Instalação e instruções

Para executar o projeto, é necessário ter o Python 3.13.7 instalado, bem como as bibliotecas numpy, matplotlib e scikit-learn. Em seguida, basta abrir os arquivos Cubo gelatinoso.ipynb e mutantes_e_mutados_marvel.xlsx pelo Jupyter Notebook, executar todas as células em ordem.


### Tecnologias utilizadas

- **Python**: Linguagem de programação utilizada como base de todo o projeto.
- **Jupyter Notebook**: Ambiente de desenvolvimento interativo no qual o projeto foi desenvolvido e documentado.
- **Numpy**: Biblioteca responsável pela manipulação de arrays numéricos e operações vetorizadas.
- **Matplotlib**: Biblioteca de visualização gráfica usada para gerar todos os gráficos do projeto (versão 3.10.6).
- **sklearn**: Biblioteca da qual foram utilizados os módulos accuracy_score, KNeighborsClassifier, StandardScaler, train_test_split, MinMaxScaler, Pipeline, GridSearchCV, cross_val_score, cross_val_predict, confusion_matrix, classification_report, ConfusionMatrixDisplay.


### Professores

##### Daniel Roberto Cassar
Doutorado: Ciência e Engenharia de Materiais (UFSCar) - Pós-doutorado: UFSCar. Área de atuação: Informática dos materiais


### Autoria

Beatriz Pessoa de Souza discente do curso de bacharelado em ciência e tecnologia na Ilum Escola de Ciência.

### Referência

GS, Sergio. Marvel_vs_DC: SuperheroDataset.csv. Repositório derivado do dataset "Superhero Set" (originalmente publicado por Claudio Davi no Kaggle, com dados extraídos de superherodb.com). Disponível em: https://github.com/sergi0gs/Marvel_vs_DC/blob/main/datasets/SuperheroDataset.csv. Acesso em: 19 ago. 2026.

AKABAB. Superhero API — all.json. Dados republicados a partir da superheroapi.com. Disponível em: https://github.com/akabab/superhero-api. Acesso em: 19 ago. 2026.

MARVEL COMICS DATABASE (Fandom). Mutant; Mutate. Usado como referência de curadoria para classificação de personagens nas categorias Mutant e Mutate. Disponível em: https://marvel.fandom.com/wiki/Mutant e https://marvel.fandom.com/wiki/Mutate. Acesso em: 19 ago. 2026.

WIKIPEDIA. Mutant (Marvel Comics). Disponível em: https://en.wikipedia.org/wiki/Mutant_(Marvel_Comics). Acesso em: 19 ago. 2026.

ANTHROPIC. Claude (Sonnet 5). Conversa realizada em 25 ago. 2026. Utilizado para: tratamento da coluna Team Affiliation, transformando o texto livre com múltiplas afiliações por personagem (separadas por vírgula, incluindo marcações como "Formerly:" e "(Leader)") em um atributo numérico discreto correspondente à contagem de times por personagem. Disponível em: https://claude.ai.

ANTHROPIC. Claude (Sonnet 5). Conversa realizada em 31 ago. 2026. Utilizado para: apoio na correção de um erro de inconsistência de amostras entre df_final e df_genero que afetou o tópico Busca de Hiperparâmetros. Disponível em: https://claude.ai.

ANTHROPIC. Claude (Sonnet 5). Conversa realizada em 02 set. 2026. Utilizado para: revisão e correção de erros de digitação e concordância nos textos em markdown do notebook e esclarecimento de dúvidas conceituais sobre os parâmetros do KNN (weights, metric, p) e sobre a diferença entre hiperparâmetros do modelo e parâmetros do pipeline experimental. Disponível em: https://claude.ai.

SCIKIT-LEARN. KNeighborsClassifier — scikit-learn 1.9.0 documentation. Documentação oficial da classe utilizada para implementar o algoritmo dos k-vizinhos mais próximos (KNN) neste trabalho. Disponível em: https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html. Acesso em: 02 set. 2026.
