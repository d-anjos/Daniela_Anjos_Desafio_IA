# Previsão de Cancelamento de Reservas de Hotel


Projeto de conclusão do desafio extra do curso Introdução à Inteligência Artificial (Carreira Tech SCTEC).


## Visão geral


Este projeto utiliza o dataset público Hotel Booking Demand (Kaggle) para:


- Realizar análise exploratória de dados (AED) com visualizações estatísticas.
- Criar novas features a partir dos dados brutos.
- Treinar e avaliar modelos de classificação supervisionada (Árvore de Decisão e Random Forest) para prever se uma reserva de hotel será cancelada (`is_canceled = 1`).


## Estrutura do repositório


| Arquivo | Descrição |
|---------|-----------|
| `Daniela_Anjos_desafio_extra_ia.ipynb` | Notebook com todo o código Python executado no Google Colab. |
| `hotel_bookings.csv` | Conjunto de dados original (Hotel Booking Demand). |
| `documentacao.md` | Documentação completa do projeto (etapas, decisões, insights, resultados). |
| `README.md` | Este arquivo – resumo do projeto. |
| `*.png` | Gráficos gerados durante a análise exploratória e avaliação dos modelos. |


## Links importantes


- Notebook no Google Colab  
  [https://colab.research.google.com/drive/1EmFpElY3DJBSZZLMM6utcPRD1Z8gBr-1](https://colab.research.google.com/drive/1EmFpElY3DJBSZZLMM6utcPRD1Z8gBr-1)


- Pasta no Google Drive (arquivos do projeto)  
  [https://drive.google.com/drive/folders/1ltF-kaFPt99CzfLwATIxseiIbliweeIJ](https://drive.google.com/drive/folders/1ltF-kaFPt99CzfLwATIxseiIbliweeIJ)


- Repositório GitHub  
  [https://github.com/d-anjos/Daniela_Anjos_Desafio_IA](https://github.com/d-anjos/Daniela_Anjos_Desafio_IA)


## Principais resultados


- Acurácia do Random Forest: 81% (baseline de 63%).
- Recall para a classe Cancelado: 68%.
- AUC-ROC: 0,86 (boa capacidade discriminativa).
- Feature mais importante: `lead_time` (dias de antecedência da reserva).


## Como executar


1. Baixe o arquivo `hotel_bookings.csv` do Kaggle ou utilize o link do Google Drive.
2. Abra o notebook no Google Colab (link acima) ou localmente com Jupyter.
3. Execute as células sequencialmente.


## Licença


Este projeto é de uso educacional, conforme os termos do dataset (CC BY 4.0).


## Autora


Daniela dos Anjos  
Curso: Introdução à Inteligência Artificial – Carreira Tech SCTEC  
Data de conclusão: 14/06/2026