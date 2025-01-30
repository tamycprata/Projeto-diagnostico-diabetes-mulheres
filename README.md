# Predição de Diabetes com Machine Learning

## Descrição do Projeto

Este projeto tem como objetivo desenvolver um modelo de Machine Learning capaz de prever se uma mulher possui ou não diabetes. A análise é baseada em um conjunto de dados contendo fatores clinicamente relevantes para o diagnóstico da doença, como número de gestações, nível de glicose, pressão arterial, entre outros.

O modelo preditivo é construído utilizando algoritmos de aprendizado de máquina, como Regressão Logística e Árvore de Decisão. O desempenho dos modelos é avaliado por meio de validação cruzada, utilizando a métrica de acurácia.

## Dados

Os dados utilizados neste projeto são provenientes do dataset "Pima Indians Diabetes Database", disponível no Kaggle e no repositório da UCI Machine Learning. O conjunto de dados contém informações sobre 768 pacientes do sexo feminino, com 8 variáveis preditoras e 1 variável alvo (diabetes ou não diabetes).

## Metodologia

1. **Análise Exploratória dos Dados:** Inicialmente, é realizada uma análise exploratória para compreender a distribuição dos dados, identificar valores ausentes e verificar a correlação entre as variáveis.
2. **Pré-processamento dos Dados:** Nesta etapa, os dados são preparados para o treinamento dos modelos. Isso pode incluir a normalização ou padronização das variáveis preditoras.
3. **Criação da Máquina Preditiva:** São utilizados dois algoritmos de aprendizado de máquina: Regressão Logística e Árvore de Decisão. A busca por hiperparâmetros otimizados é realizada utilizando o método RandomizedSearchCV.
4. **Avaliação do Modelo:** O desempenho dos modelos é avaliado por meio de validação cruzada com 10 folds. A métrica utilizada para a avaliação é a acurácia.
5. **Comparação dos Modelos:** Os resultados da Regressão Logística e da Árvore de Decisão são comparados para identificar o modelo com melhor desempenho.

## Resultados

Os resultados obtidos indicam que o modelo de **Regressão Logística**, mesmo com parâmetros default, apresentou uma acurácia de **77.86%**, superando o melhor resultado da **Árvore de Decisão** otimizada, que foi de **74.75%**.

## Conclusões

Este projeto demonstra a viabilidade da aplicação de Machine Learning para a predição de diabetes em mulheres. O modelo de Regressão Logística apresentou um bom desempenho, podendo ser utilizado como ferramenta auxiliar no diagnóstico da doença.

## Próximos Passos

* Explorar outros algoritmos de aprendizado de máquina, como Redes Neurais e Support Vector Machines.
* Realizar um ajuste mais fino dos hiperparâmetros dos modelos para otimizar ainda mais o desempenho.
* Desenvolver uma interface gráfica para facilitar a utilização do modelo por profissionais de saúde.

