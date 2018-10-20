# Análise exploratória de vinhos

![](https://confessoquebebi.files.wordpress.com/2017/06/vinho_branco_free_big.jpg)

Análise sobre dataset de vinhos utilizando a linguagem R.

## Contribuições

* Igor Leal
* Carolene Bertoldi

## Conteúdo

Para um entendimento completo da análise, é recomendado seguir a análise conforme a sequência e os arquivos abaixo:

1. [Análise Exploratória Geral](#descriptive-analysis): `descriptive_analysis.Rmd`
2. [Análise Exploratória Vinhos Brancos x Tintos](#descriptive-analysis-red-wines-x-white-wines): `descriptive-analysis-red-wines-x-white-wines.Rmd`
3. [Análise Exploratória Vinhos Brancos](#descriptive-analysis-white-wines): `descriptive-analysis-red-wines-x-white-wines.Rmd`
4. [Modelos e Predições](#preditions): `preditions.Rmd`

Todos os arquivos possuem instruções para instalar e carregar as bibliotecas necessárias para a análise e predição.

### Análise Exploratória Geral <a name="descriptive-analysis"></a>

Contém a análise contemplando o primeiro contato com o dataset de vinhos. Decidimos dividir a análise em duas categorias: vinhos brancos e vinhos tintos.

Em resumo, aborda os seguintes tópicos:

* Amostras;
* Visão geral;
* Valores nulos;
* Distribuição dos dados;
* Média e Mediana: Vinhos Tintos x Vinhos Brancos;
* Outliers/Quartis;
* Medidas de Dispersão: Desvio Padrão e Variância.

### Análise Exploratória Vinhos Brancos x Vinhos Tintos <a name="descriptive-analysis-red-wines-x-white-wines"></a>

Contém uma análise mais aprofundada, porém separadas entre vinhos brancos e tintos. No final, decidimos continuar a análise somente com o vinho branco.

Em resumo, aborda os seguintes tópicos:

* Dividindo conjunto de dados em vinhos tintos e vinhos brancos;
* Distribuição do dados por tipo de vinho (para cada campo);
* Outliers (Vinhos brancos x Vinhos Tintos x Dataset original);
* Correlações (Positivas / Negativas);
* Decisão Final (seguir a análise somente com vinhos brancos).

### Análise Exploratória Vinhos Brancos <a name="descriptive-analysis-white-wines"></a>

Contém uma análise dos itens que estavam faltando relacionados ao vinho branco. Com esta análise, é possível rodar modelos preditivos.

Em resumo, aborda os seguintes tópicos:

* Tratamento de Outliers (para cada campo);
* PCA.

### Modelos e predições <a name="preditions"></a>

Por fim, executamos quatro modelos diferentes para predição e escolhemos aquele que melhor previu os resultados.

Em resumo, aborda os seguintes tópicos:

* Correlações
* Classificando a Qualidade
* Modelo 1: Regressão Linear;
* Modelo 2: Árvore de Regressão Linear;
* Modelo 3: Árvore de Decisão;
* Modelo 4: Árvore de Regressão Logística;
* Técnica (explicação resumida teórica sobre o modelo);
* Separando o dataset em treinamento/teste;
* Análise da Qualidade do Modelo (Matriz de Confusão);
* Conclusões.
