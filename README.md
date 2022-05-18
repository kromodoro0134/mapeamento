# mapeamento
Catalogar os tipos de cenários para criação de pipelines


## Contexto: AWS
### Cenário 1
# E
- Ingestão incial full-load
  - Quais opções eu tenho?
    - Airflow
    - Glue Crawler
    - Python API
- Demais ingestões half-load
  - Quais opções eu tenho?
    - Airflow
    - Glue Crawler
    - Python API

#### Nomenclatura de diretórios
> landing-zone (s3//prefixo-projeto_prefixo-cliente/landind/)<br>
> Bronze (s3//prefixo-projeto_prefixo-cliente/bronze/)<br>
> Silver (s3//prefixo-projeto_prefixo-cliente/silver/)<br>
> Gold (s3//prefixo-projeto_prefixo-cliente/gold/)

# T
- Opções te tecnologias
  - Python
  - PySpark
  - Delta

# L
- Opções de visualizadores
  - Power BI
