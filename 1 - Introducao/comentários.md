bb## Definições
### Métodos preditivos
#### Classificação
* Divisão em classes para cada um das classes
  * Exemplos: marketing direto, insatisfação de clientes, risco de crédito, filtros de SPAM, separação de notícias, reconhecimento de voz, reconhecimento de face, previsão de doenças.
* Atributos: 
  > Envolve uma base de dados histórica. 
  * Previsores 
  * Meta/classe
  * Representação da classificação (método indutivo): 
    * Fase 1:  
        1. Conjunto de exemplos - atributos previsores + atributos meta
        2. Sistema de aprendizado
        3. Classificador
    * Fase 2: 
        1. Caso a ser classificado (atributo meta não conhecido)
        2. Classificador
        3. Decisão
#### Regressão
* Não tem classes, faz previsão de valores numéricos. 
  * Exemplos: gastos propaganda -> valor de venda, temperatura, umidade e pressão do ar -> velocidade do vento,  fatores externos -> valor do dólar, resultados do exame -> probabilidade de um paciente sobreviver, risco de investimento, gastos no cartão de crédito histórico -> limite, valores anteriores -> valores de produtos. 
### Métodos descritivos
#### Associação
* Exemplos: prateleira de mercados, promoções com itens que são vendidos em conjunto, planejar catálogos das lojas e folhetos de promoções, controle de evasão em universidades.
#### Agrupamento
* Exemplos: Segmentação de mercado, encontrar grupos que irão comprar um produto, agrupamento de documentos ou noticias, agrupamento de produtos similares, perfis de clientes, análises de redes sociais
#### Detecção de desvios
* Exemplos: Detectar fraude em cartão de crédito, intrusão em redes, uso de energia elétrica ou água, desempenho de atletas(doping), monitoramento de máquinas em data center
#### Padrões sequenciais
* Exemplos: Livrarias, loja de equipamentos, computadores, prevensão de doenças, navegação em sites
#### Sumarização 
* Exemplos: Segmentação de mercado, segmentar pessoas em faixa etária e nível de instrução, assim por diante. 

### Tipos de aprendizagem de máquina
#### Supervisionada
Fase 1
1. Extração de características 
2. Algoritmo de aprendizagem 
3. Modelo aprendido 

Fase 2
1. Extração de características
2. Modelo aprendido
3. Objetivo

* Classificação 
* Regressão 

#### Não supervisionada 
> analisar automaticamente os dados (associação, agrupamento) </br>
> necessita análise para determinar o significado dos padrões encontrados
* Associação
* Agrupamento
* Detecção de desvios
* Padrões sequenciais 
* Sumarização 
### Reforço 
> aprender com as interações com o ambiente (causa e efeito) </br>
> aprender com a sua própria experiência</br>
> robô coletando lixo aprendendo a andar em um ambiente
