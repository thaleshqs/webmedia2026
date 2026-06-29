# Repositório de Dados e Código

Este repositório contém os dados e os códigos utilizados nas análises apresentadas no artigo.

## Estrutura do Repositório

| Arquivo                      | Descrição                                                                                                    |
| ---------------------------- | ------------------------------------------------------------------------------------------------------------ |
| `comments.zip`               | Conjunto de comentários coletados durante o estudo.                                                          |
| `videos.jsonl`               | Dados dos vídeos utilizados nas análises. Cada linha corresponde a um vídeo em formato JSON.                 |
| `data_analysis.ipynb`        | Notebook responsável pela análise exploratória dos dados e pela geração dos gráficos apresentados no artigo. |
| `topicgpt.ipynb`             | Notebook contendo o processo de modelagem de tópicos utilizando um modelo de linguagem (LLM).                |
| `classificacao_topicgpt.csv` | Classificações de tópicos produzidas pelo modelo de linguagem durante a etapa de modelagem de tópicos.       |
| `topic_stats.ipynb`          | Notebook com estatísticas agregadas por tópico                                                               |
## Requisitos

Os notebooks foram desenvolvidos em Python utilizando Jupyter Notebook. Recomenda-se o uso de um ambiente virtual contendo as bibliotecas necessárias para execução das análises.

## Reprodução das Análises

1. Extraia o conteúdo de `comments.zip`.
2. Certifique-se de que os arquivos de dados estejam no mesmo diretório dos notebooks (ou ajuste os caminhos conforme necessário).
3. Execute `data_analysis.ipynb` para reproduzir as análises estatísticas e os gráficos.
4. Execute `topicgpt.ipynb` para reproduzir a modelagem de tópicos baseada em LLM.

## Licença

Este repositório disponibiliza os dados e o código exclusivamente para fins de pesquisa científica.
