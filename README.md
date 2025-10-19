# Sprint 7 – Análise Exploratória de Dados e Teste de Hipóteses

## Descrição do Projeto

Neste projeto, atuo como analista de dados de empresas de táxi em Chicago. Meu objetivo é realizar uma análise exploratória dos dados, identificar padrões e testar hipóteses sobre o comportamento das corridas, de forma a gerar insights confiáveis para a tomada de decisão.

---

## Passo 4 – Análise Exploratória de Dados (Python)

Recebi dois conjuntos de dados:

1. `/datasets/project_sql_result_01.csv`  
   - Contém a coluna **trips_amount**, que indica o número de corridas para cada empresa de táxi entre 15 e 16 de novembro de 2017.

2. `/datasets/project_sql_result_04.csv`  
   - Contém as colunas **dropoff_location_name**, indicando os bairros de Chicago onde as corridas terminaram, e **average_trips**, que apresenta o número médio de viagens que terminaram em cada bairro durante novembro de 2017.

Minhas tarefas foram:

- Importar os arquivos e estudar os dados contidos neles.  
- Verificar se os tipos de dados estão corretos e fazer ajustes quando necessário.  
- Identificar os 10 principais bairros em termos de número de destinos.  
- Criar gráficos para:
  - Visualizar as empresas de táxi e o número de corridas realizadas.  
  - Mostrar os 10 bairros com maior número de corridas finalizadas.  
- Tirar conclusões a partir de cada gráfico e explicar os resultados obtidos.

---

## Passo 5 – Testando Hipóteses (Python)

O arquivo `/datasets/project_sql_result_07.csv` contém os seguintes campos:

- **start_ts**: data e hora da coleta da corrida.  
- **weather_conditions**: condições meteorológicas no início da corrida.  
- **duration_seconds**: duração da corrida em segundos.  

Formulei a seguinte hipótese para testar:

> "A duração média dos passeios do Loop para o Aeroporto Internacional O'Hare muda nos sábados chuvosos."

Para testar a hipótese, defini o nível de significância (alfa) e:

- Formulei a **hipótese nula**, assumindo que a duração média não muda nos sábados chuvosos.  
- Formulei a **hipótese alternativa**, considerando que a duração média muda nos sábados chuvosos.  
- Escolhi o critério estatístico adequado para testar a hipótese, levando em conta a distribuição dos dados e o tamanho da amostra.  
- Analisei os resultados e tirei conclusões sobre o efeito das condições climáticas na duração das corridas.

---

## Avaliação do Projeto

Meu projeto será avaliado com base nos seguintes pontos:

- Como recuperei e preparei os dados para análise.  
- A forma como fatiei e agrupei os dados corretamente.  
- Se utilizei os métodos adequados para combinar os dados.  
- Como formulei as hipóteses e escolhi os critérios para testá-las.  
- A clareza e relevância das conclusões.  
- Comentários detalhados em cada passo do projeto.


