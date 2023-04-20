# Previsão de Vendas - Farmácias Rossmann
![primeira imagem readme](img/Rossmann_img1.jpg)

A Rossmann é uma rede de farmácias com mais de 3000 lojas em 7 países da Europa.
Os dados utilizados nesse projeto foram disponibilizados pela empresa e obtidos através da plataforma de competições [Kaggle](https://www.kaggle.com/competitions/rossmann-store-sales/overview/description) 

# Problema de Negócio

O CFO da rede Rossmann quer fazer reformas nas lojas e para isso precisa ter uma previsão de quanto cada loja vai vender nas proximas 6 semanas para que ele possa saber quanto podera disponibilizar de investimento para cada uma das lojas. 

As vendas da loja são influenciadas por muitos fatores, incluindo promoções, concorrência, feriados escolares e estaduais, sazonalidade e localidade. Com milhares de gerentes individuais prevendo vendas com base em suas circunstâncias únicas, a precisão dos resultados pode variar bastante.

# Premissas do Negócio

asdfasdfasdfasfd

# Estratégia da Solução

A estratégia para resolver esse problema se baseia na metodologia CRISP-DS
O método CRISP-DS se baseia na entrega por ciclos, priorizando a entrega rápida e acrescentando melhorias a cada ciclo. 
Os passos no primeiro ciclo foram os seguintes:

1. Entendimento do Negócio: entender a motivação do time de negócio e a causa raiz do problema, propor o formato de entrega da solução, que no caso será um bot no Telegram que dado a o numero da loja, será retornado a previsão de vendas das proximas 6 semanas.

2. Coleta de Dados: Nesta etapa é feita a coleta de dados do banco de dados da empresa. Para este projeto será feita a importação dos dados em um arquivo .csv vindo da plataforma Kaggle.

3. Limpeza dos Dados: Nesta etapa é feita a descrição dos dados, checagem e preenchimento de valores faltantes, transformação adequada de tipo das variáveis

4. Exploração dos Dados: Nesta etapa é criado a lista de hipóteses, filtragem e seleção de variáveis, validar as hipóteses de negócio, verificar como as variáveis impactam o fenômeno e quais as mais importantes para o modelo.

5. Modelagem dos Dados: Nesta etapa são feitas as transformações necessarias antes de treinar o modelo, como encoding, reescaling e transformação de natureza das variáveis. Também é feita a seleção das features mais relevantes para o modelo e é feita a divisão do dataset entre treino e teste.

6. Algoritmos de Machine Learning: Nesta etapa são aplicados os algoritmos de Machine Learning nos dados preparados. Aqui o
