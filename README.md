# Brazilian Air Traffic Network Analysis

An simple analysis of Brazilian air traffic network. It's a project of Network Analysis class.

## Dataset

In this project, we used two datasets (you can find them in /data) to get the final dataset:

- **[ANAC Air Transport Estatistic Data](https://www.anac.gov.br/assuntos/setor-regulado/empresas/envio-de-informacoes/base-de-dados-estatisticos-do-transporte-aereo):** Data of all brazilian flights in 2021 from the [Nation Civil Aviation Agency - Brazil](https://www.anac.gov.br/en);
- **[DataHub Airport Codes](https://datahub.io/core/airport-codes):** Data of coordinates of all airports;

To get the final air traffic network used in this project, we made a filter in flights dataset, getting only domestic and regular flights. We also removed 13 little airports because the missing coordinates in Airport Codes dataset.

## Authorship

[Matheus de Andrade](https://github.com/matheusmas132) and [Pedro Henrique](https://github.com/pedrocardoso5).

©️ [Metrópole Digital Institute](https://imd.ufrn.br/)/[Federal University of Rio Grande do Norte](https://ufrn.br/), 2020.
