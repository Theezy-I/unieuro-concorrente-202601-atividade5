# unieuro-concorrente-202601-atividade5

Testar a solução MPI construindo relatório de avaliação de performance para 2, 4, 8, 12 processos.

## Instalação MPI

1) Instalar o MPI para Windows  
https://www.microsoft.com/en-us/download/details.aspx?id=100593

2) Instalar mpi4py
pip install -r requeriments.txt

## Onde buscar os dados

O site do Kaggle apresenta vários desafios, bancos de dados e projetos que estão abertos a comunidade para apoio. Alguns deles tem prêmios em dinheiro.

Para esse experimento devemos buscar o arquivo "nlp_features_train.csv" no Quora Question Paris.

https://www.kaggle.com/datasets/elemento/quora-question-pairs?select=nlp_features_train.csv

## Executar

Como executar o projeto:

### Versão serial
```
python avaliador.py
```
### Versão distribuída
```
mpiexec -n 4 python avaliador_mpi.py
```

