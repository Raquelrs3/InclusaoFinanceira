# Inclusão Financeira na África

Imagem

Este é um projeto realizado com dados públicos disponibilizados pela empresa na plataforma do [KAGGLE](https://www.kaggle.com/competitions/inclusao-financeira-na-africa/data).


## 1. Problema de Negócio
O governo africano entende que a inclusão financeira é um obstáculo ao desenvolvimento econômico e humano na África.

Apesar de, em 2022, o último relatório do Banco Central da África Ocidental demonstrar taxas de inclusão financeira próxima de 82%, o governo tem uma necessidade de impulsionar essas aquisições.

Afirmam que situações como: promoção do empoderamento das pessoas vulneráveis, combate a redes crimiosas e conectividade dos setores público e privado para um crescimento sustentável, são 3 razões paralelas que podem ocorrer ao apostarem na inclusão financeira.

## 2. Entendimento do Negócio
#### Motivação
O governo da África fez uma pesquisa, por meio do seu Banco Central, e teve o entendimento que aumentar o número de inclusão financeira de seus paises é uma forma de combater redes criminosas, aumentar o empoderazmento de pessoas vulneráveis e impulsiona o crescimento sustentável.

#### Causa Raiz do Problema
O governo africano está analisando uma possibilidade em aumentar a inclusão financeira africana.

#### Quem é o Stakeholder
Sociedade africana


#### Formato da Solução

* Modelo de classificação prever quem tem mais probabilidade de ter uma conta bancária.
 
 
## 3. Metodologia de Desenvolvimento do Projeto
 O projeto está sendo desenvolvido pela técnica CRISP-DM
 * Versão END-TO_END da solução,
 * Velocidade na entrega de valor,
 * Mapeamento de todos os possíveis problems.


##### Passo 01 - Descrição dos dados: Conhecimento dos dados, tipos, métricas estatísticas para identificar outliers, analise das métricas estatísticas e ajustes em features do dataset (preenchimento de NA's).


##### Passo 02 - Feature Engineering: Desenvolvimento de mapa mental para analisar o fenômeno, as variáveis e os principais aspectos que impactam cada uma delas. 


##### Passo 03 - Filtragem dos dados: Filtragem das linhas e excluir as colunas que não são relevantes para o modelo ou não fazem parte do escopo do negócio. EX: Dias em que as lojas estavam fevhadas ou inoperantes.


##### Passo 04 - Análise Exploratória dos dados: Exploração dos dados para encontrar insights.


##### Passo 05 - Preparação dos dados: Preparação para as aplicações de modelos de machine learning.


##### Passo 06 - Seleção de Features: Seleção dos melhores atributos para treinar o modelo. Utilizamos o algoritmo Boruta para essa seleção.


##### Passo 07 - Modelagem de Machine Learning: Foram realizados testes e treinamentos de alguns modelos de machine learning, para possibilitar a comparação da performance e escolha do modelo ideal para o projeto. Foi utilizada a técnica de Cross Validation para garantir a performance real sobre os dados selecionados.


##### Passo 08 - Hyperparameter Fine Tunning: Análise pelo método Random Search, em cima do algoritmo escolhido XBoost, para escolha dos melhores valores de cada parâmetro do modelo.


##### Passo 9 - Submissão do arquivo .csv com o modelo de machine learning escolhido para a plataforma Kaggle.


## 4. Entendendo os Dados
* Dados disponibilizados pela empresa na plataforma do [KAGGLE](https://www.kaggle.com/anmolkumar/health-insurance-cross-sell-prediction).

| VARIÁVEL  |  DEFINIÇÃO  |
| ------------------- | ------------------- |
|  Country	 |  Pais de Origem.|
|  Year | Ano da Inclusão.|
| Uniqueid | Id do Usuário.|
| Bank_account	| Possui ou Não a Conta no Banco.|
| Location_type | Tipo de Localidade (Rural...)|
| Cellphone_access | Possui ou Não Celular.|
| Household_size | Tamanho da Casa.|
| Age_of_respondent | Idade do Usuário.|
| Gender_of_respondent | Gênero do Usuário.|
| Relationship_with_head | Status com o Dono da Conta.|
| Marital_status | Situação Civil.|
| Education_level | Nível de Educação.|
| Job_type | Tipo de Trabalho.|


## 5. Principais Insights

**Hipótese 1-** 

![Hipotese 1]()


**Hipótese 2-** 

![Hipotese 2]()


**Hipótese 3-** 

![Hipotese 3]()


## 6. Performance do Modelo

Para a realização desta etapa do projeto, foram aplicados os seguintes modelos:

* 
* 
* 


### Comparação da performance dos modelos


### Performance final do modelo escolhido após Hyperparameter Fine Tuning


### Comparação da performance dos modelos


### Performance final do modelo escolhido após Hyperparameter Fine Tuning


## 7. Resultado Final


## - Conclusão

