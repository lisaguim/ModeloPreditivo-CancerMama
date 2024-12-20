# ModeloPreditivo-CancerMama

Esse projeto desenvolvido no jupyter notebook tem como objetivo criar um modelo preditivo para predizer quando uma pessoa tem câncer dado o exame de sequenciamento do RNA com base no TCGA e
estudar as técnicas de redução de dimensionalidade dos dados (PCA), regressão logística e treinamento do modelo. 

# Descrição dos dados:

Dados foram coletados do The Cancer Genome Atlas Program (TCGA), que é um programa internacional e de referência mundial de
caracterização de mais de 33 tipos de câncer. Os dados são reais e foram devidamente anonimizados. Cada linha representa a
amostra retirada de uma pessoa. AS colunas são os tipo de microRNA e cada entrada representa a instensidade com que aquele
microRNA está expressado. Os valores de expressão variam entre [0,infinito]. Valores próximos a zero indicam pouca expressão
enquanto que o contrário indica uma alta expressão. Os dados também apresentam rótulos (veja atributo class) sendo TP(primary
solid tumor) indicando tumor e NT (normal tissue) indicando que não há tumor.

# Fonte dataset: 

(https://www.cancer.gov/ccg/research/genome-sequencing/tcga)

# Links e Referências:

The Cancer Genome Atlas Program (TCGA)
O que é Mirco RNA? (https://www.bbc.com/portuguese/articles/cvgl5yqd33vo)

# Linguagem: 

Python

# Bibliotecas:

Pandas
Numpy
Seaborn
Matplotlib
Sklearn


