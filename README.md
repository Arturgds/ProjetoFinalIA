# Projeto Final de Aprendizado de Máquina

## Visão geral
Este projeto tem como objetivo prever o tipo de assinatura de um usuário em uma plataforma de streaming musical com base em seus hábitos de uso. O conjunto de dados utilizado foi o **Music Streaming Habits 2026**, que possui 4.000 registros sintéticos e 15 colunas com informações sobre perfil do ouvinte, preferências musicais e comportamento de consumo, como plataforma, gênero favorito, tempo diário de escuta, número de músicas por dia, playlists, taxa de skip e uso de modo offline .

A variável-alvo definida no trabalho é **`subscription`**, com as classes **Free**, **Premium**, **Family** e **Student**, caracterizando uma tarefa de **classificação multiclasse** conforme os critérios do projeto [file:2]. Os atributos restantes serão utilizados como variáveis preditoras para identificar padrões de comportamento associados a cada tipo de assinatura.

## Introdução curta
Este trabalho propõe a construção de um modelo de aprendizado de máquina para prever o tipo de assinatura (`subscription`) de usuários de streaming musical a partir de seus hábitos de consumo. Como a variável-alvo possui quatro categorias — Free, Premium, Family e Student — o problema foi definido como uma tarefa de classificação multiclasse.

## Objetivo
Desenvolver e comparar modelos de classificação capazes de prever o tipo de assinatura de um usuário com base em variáveis demográficas, preferências musicais e padrões de uso da plataforma .

## Integrantes
- Artur Gabriel Dantas Santos.
- Kaíque Teixeira Rodrigues.
- Matheus Mendonca Santana.


## Fonte dos dados
- Dataset: **Music Streaming Habits 2026** [web:4]
- Link: [Kaggle - Music Streaming Habits 2026](https://www.kaggle.com/datasets/uditjain13/music-streaming-habits-2026) 

## Tipo de tarefa
- **Classificação multiclasse** 
- Variável-alvo: **`subscription`** 

## Atributos utilizados
### Variável-alvo
- `subscription`

### Variáveis preditoras
- `age`
- `country`
- `platform`
- `top_genre`
- `top_artist`
- `daily_listening_minutes`
- `songs_per_day`
- `playlists_count`
- `skip_rate_pct`
- `discover_weekly_user`
- `top_mood`
- `uses_offline_mode`
- `podcasts_too`

### Variável descartada
- `listener_id` — identificador do registro, sem valor preditivo relevante para o problema.

## Organização dos arquivos
- `README.md` — descrição geral do projeto.
- `notebook.ipynb` — notebook principal com análise, pré-processamento, treinamento e avaliação.
- `data/` ou carregamento por URL — obtenção do dataset em fonte pública.
- Arquivos auxiliares, se necessários.

## Etapas previstas no notebook
1. Identificação e descrição do problema 
2. Compreensão dos dados 
3. Análise exploratória 
4. Pré-processamento 
5. Separação entre treino e teste 
6. Modelagem com baseline, `SGDClassifier` e `RandomForestClassifier` 
7. Avaliação com matriz de confusão, acurácia, precisão, revocação e F1-score 
8. Discussão crítica dos resultados 

## Modelos utilizados
Os modelos mínimos exigidos para tarefas de classificação incluem **SGDClassifier** e **RandomForestClassifier**, além de um baseline para comparação.

## Principais resultados
Esta seção pode ser preenchida ao final do projeto com:
- modelo com melhor desempenho;
- métricas principais;
- principais variáveis relacionadas à previsão;
- limitações observadas.

## Como abrir no Colab
O notebook deve ser disponibilizado no repositório GitHub e abrir normalmente no Google Colab, conforme exigido no projeto. Os dados devem ser carregados por link público ou por script dentro do próprio notebook, sem depender de arquivos locais.

## Divisão das contribuições
Descrever objetivamente a participação de cada integrante no desenvolvimento do trabalho, incluindo análise, implementação, documentação e apresentação em vídeo.

## Vídeo
Inserir aqui o link do vídeo final explicando o trabalho, com participação efetiva de todos os integrantes.

## Uso de ferramentas de IA
Este trabalho poderá utilizar ferramentas de inteligência artificial como apoio à organização textual, revisão de estrutura, esclarecimento conceitual e apoio à implementação. Conforme o enunciado, o grupo deve declarar qual ferramenta foi utilizada, em que parte do trabalho ela foi aplicada e como o conteúdo gerado foi verificado pelos integrantes.
