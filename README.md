# CD4ML

Continuous Delivery for Machine Learning (CD4ML) 

## The End-to-End CD4ML Process

![](assets/imgs/cd4ml-end-to-end.png)

## Stages

### Virtualization

> Docker

### Testes

#### Teste unitário

> Pytest

- teste de previsão: % acertos
- teste de transformação: comparar saídas
- teste de bias: só acerta para alguns dados (desbalanceio)
- teste de aceitação: % acurácia/precisão
- função de predição
- teste de input errado

#### Teste integração

- Integração com BD, API

#### Teste end2end

> Selenium

- UI
- API
- Database
- Model

### Automação

> - Jenkins
> - Github Action
> - GoCD https://docs.gocd.org/current/

#### Evento

- git push
- branchs 

#### Criação de modelo

#### Testes utilizando o modelo

#### Deploy to Production


## EDA Pipeline

- get_data
- prepare_data
- train

### Tools

> - dvc
> - Kedro

## Data/Versioning

### Tools

> - dvc

## Experiment

> - MLFlow

### Metrics

### Hiperparameters

## Model Register/Versioning

> - MLFlow

### Model registry

#### Artefacts

### Model versioning

## Governança de Dados

### Lineage

### LGPD

## Production

### Monitoring &Logs

> - FluendD
> - ElasticSearch

* User
* Region
* App
* Timestamp
* Models
* Data:Inputs
* Data:Transformations
* Data:Predicts
* Data:Real result
* Software metris (4 keys)
    * Elapse time 
    * Elapse time transform

### Monitoring

> - Kibana

## Continuous Monitoring

> - Evidently

## Governança ética

- Porque alguns produtos não são recomendados numa região?
    - Incluir condicionais
    - Testes AB

- Regras de negócios
    - Incluir ajustes de compensação de estratégias de negócio

## Times

### Data Engineer

* Data Acquiring
* Data Quality
* Data Lineage
* Data Catalog

### Data Science

* Models
* Test models
* Experiment Tracking

### Machine Learning Engineer

* Dev Environment
    * Docker: Jupyter Notebook + Experiment Tracking
* Continuous Integration
* Continuos Delivery
* Continuous Monitoring

## Questions

- Quando testar?
- Quando e como colocar o modelo em produção?


## References

- https://martinfowler.com/articles/cd4ml.html
- https://www.thoughtworks.com/pt-br/what-we-do/data/cd4ml
