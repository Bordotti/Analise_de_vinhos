# Análise de dados de review sobre vinhos
O objetivo desta análise foi sumarizar alguns dados disponíveis no dataset e gerar visualizações a fim de conhecer melhor este mundo de vinhos.

Para esta análise foram utilizados o dataset winemag-data-130k-v2.csv encontrado em: https://www.kaggle.com/zynicide/wine-reviews e para visualização no mapa foram utilizados dados auxiliares encontrados em: https://github.com/google/dspl/blob/master/samples/google/canonical/countries.csv. 

## Informações do dataset
São disponibilizados 130 mil reviews de vinho com 13 colunas.
Abaixo é apresentado as colunas disponíveis e seus tipos identificados na análise:

   ` country: Categórica Nominal,
    description: Categórica Nominal,
    designation: Categórica Nominal,
    points: Numérica Discreta,
    price: Numérica Contínua,
    province: Categórica Nominal,
    region_1: Categórica Nominal,
    region_2: Categórica Nominal,
    taster_name: Categórica Nominal,
    taster_twitter_handle: Categórica Nominal,
    title: Categórica Nominal,
    variety: Categórica Nominal,
    winery: Categórica Nominal`

## Requerimentos de sistema
python 3.8
pyarrow
numpy
pyspark
pandas
matplotlib
