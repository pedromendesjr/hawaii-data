# Análise de Dados do Airbnb - Hawaii (Havaí)

## Introdução
Este projeto realiza uma análise dos dados de acomodações do Airbnb no Havaí, utilizando dados disponibilizados pelo [Inside Airbnb](http://insideairbnb.com). O objetivo é entender melhor o mercado de aluguéis no Havaí, explorando diversos aspectos das acomodações oferecidas.

## Objetivo
O objetivo principal deste projeto é estudar os dados das acomodações disponíveis para aluguel no Havaí, proporcionando insights sobre as características das propriedades, padrões de preços, localização e outros fatores relevantes para viajantes e anfitriões.

## Dicionário de Dados
Aqui estão as principais variáveis utilizadas na análise:

| Variável           | Descrição                                                                                      |
|--------------------|------------------------------------------------------------------------------------------------|
| `id`               | Identificador único da propriedade                                                             |
| `name`             | Nome da propriedade                                                                            |
| `host_id`          | Identificador único do anfitrião                                                               |
| `host_name`        | Nome do anfitrião                                                                              |
| `neighbourhood_group` | Grupo do bairro                                                                             |
| `neighbourhood`    | Bairro onde a propriedade está localizada                                                      |
| `latitude`         | Latitude da propriedade                                                                        |
| `longitude`        | Longitude da propriedade                                                                       |
| `room_type`        | Tipo de quarto (e.g., Entire home/apt, Private room, Shared room)                              |
| `price`            | Preço por noite em dólares                                                                     |
| `minimum_nights`   | Número mínimo de noites para reserva                                                           |
| `number_of_reviews`| Número de avaliações recebidas pela propriedade                                                |
| `last_review`      | Data da última avaliação                                                                       |
| `reviews_per_month`| Média de avaliações por mês                                                                    |
| `calculated_host_listings_count` | Número de propriedades listadas pelo anfitrião                                   |
| `availability_365` | Número de dias que a propriedade está disponível para aluguel nos próximos 365 dias            |

## Dados
Os dados utilizados neste projeto foram obtidos a partir do [Inside Airbnb](http://insideairbnb.com), uma fonte confiável de dados de acomodações do Airbnb. O conjunto de dados cobre várias características das propriedades listadas no Havaí.

## Principais Análises e Resultados
### 1. Distribuição das Propriedades por Tipo de Quarto
![Distribuição dos Tipos de Quartos](https://github.com/pedromendesjr/hawaii-data/blob/main/imagens/tipos_quartos.png)

O gráfico mostra a distribuição dos tipos de quartos oferecidos no Airbnb no Havaí. A maioria das acomodações são casas/apartamentos inteiros (aproximadamente 17.500), seguidos por quartos privados (cerca de 2.500). Há poucas ou nenhuma listagem de quartos de hotel e quartos compartilhados. Isso indica uma preferência clara por acomodações que oferecem maior privacidade.

### 2. Análise de Preços por Ilha
![Preços dos Quartos por Ilha](https://github.com/pedromendesjr/hawaii-data/blob/main/imagens/precos_ilhas2.png)

O gráfico mostra os preços médios dos quartos por ilha no Havaí, com as barras pretas verticais representando a faixa de preços (mínimo a máximo). Kauai e Maui têm os preços médios mais altos, em torno de $300, enquanto Hawaii e Honolulu têm preços médios mais baixos, em torno de $200. A variabilidade dos preços é maior em Kauai e Maui, indicando uma maior faixa de opções de preço nessas ilhas.

### 3. Mapa de Distribuição de Preços por Localização
![Mapa de Distribuição de Preços](https://github.com/pedromendesjr/hawaii-data/blob/main/imagens/mapa_hawaii.png)

O mapa mostra a distribuição das acomodações do Airbnb na ilha do Havaí, coloridas de acordo com o preço. As áreas com pontos mais claros e vermelhos indicam acomodações mais caras, enquanto os pontos azuis representam acomodações mais baratas. A maioria das acomodações mais caras está concentrada nas regiões costeiras, especialmente nas áreas turísticas, sugerindo uma correlação entre proximidade ao mar e preço mais elevado.


## Conclusão
Este projeto oferece uma visão detalhada do mercado de aluguéis do Airbnb no Havaí, destacando aspectos importantes que podem ajudar tanto viajantes quanto anfitriões a tomar decisões informadas. As análises fornecem insights valiosos sobre a distribuição de propriedades, padrões de preços, popularidade e disponibilidade das acomodações.
