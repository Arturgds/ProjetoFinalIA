# Projeto Final de Aprendizado de Máquina

## Visão geral
Este projeto tem como objetivo prever o tipo de assinatura de um usuário em uma plataforma de streaming musical com base em seus hábitos de uso. O conjunto de dados utilizado foi o **Music Streaming Habits 2026**, que possui 4.000 registros sintéticos e 15 colunas com informações sobre perfil do ouvinte, preferências musicais e comportamento de consumo, como plataforma, gênero favorito, tempo diário de escuta, número de músicas por dia, playlists, taxa de skip e uso de modo offline .

A variável-alvo definida no trabalho é **`subscription`**, com as classes **Free**, **Premium**, **Family** e **Student**, caracterizando uma tarefa de **classificação multiclasse** conforme os critérios do projeto. Os atributos restantes serão utilizados como variáveis preditoras para identificar padrões de comportamento associados a cada tipo de assinatura.

## Introdução curta
Este trabalho propõe a construção de um modelo de aprendizado de máquina para prever o tipo de assinatura (`subscription`) de usuários de streaming musical a partir de seus hábitos de consumo. Como a variável-alvo possui quatro categorias — Free, Premium, Family e Student — o problema foi definido como uma tarefa de classificação multiclasse.

## Objetivo
Desenvolver e comparar modelos de classificação capazes de prever o tipo de assinatura de um usuário com base em variáveis demográficas, preferências musicais e padrões de uso da plataforma .

## Integrantes
- Artur Gabriel Dantas Santos.
- Kaíque Teixeira Rodrigues.
- Matheus Mendonca Santana.


## Fonte dos dados
- Dataset: **Music Streaming Habits 2026** 
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
- `declaracao_uso_ia.md` — descrição do uso de ia no projeto.
- `notebook.ipynb` — notebook principal com análise, pré-processamento, treinamento e avaliação.
- `dados/`.
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
**SGDClassifier** e **RandomForestClassifier**, além de um baseline para comparação.

## Principais resultados
Esta seção pode ser preenchida ao final do projeto com:
- modelo com melhor desempenho;
- métricas principais;
- principais variáveis relacionadas à previsão;
- limitações observadas.

## Como abrir no Colab
Basta fazer o download do .ipynb e executar todas as celulas o data set vai ser carregado diretamente do kaggle.

## Divisão das contribuições
- **Kaíque Teixeira** ficou responsável pelas seções 5.1 e 5.2, relacionadas à definição do problema e compreensão dos dados.
- **Matheus Mendonca** ficou responsável pelas seções 5.3, 5.4 e 5.5, relacionadas à análise exploratória, pré-processamento e separação dos dados.
- **Artur Gabriel** ficou responsável pelas seções 5.6 e 5.7, relacionadas à modelagem, avaliação e discussão dos resultados.

## Vídeo
Inserir aqui o link do vídeo final explicando o trabalho, com participação efetiva de todos os integrantes.

## Uso de ferramentas de IA
Foi usado ferramentas de IA para ajudar na interpretação do problema, solicitando ajuda para fazer a conpreenssão dos dados e a analise exploratória. Também foi feito o uso de IA para ajudar na organização do Notebook, pedindo ajuda em como organizar o fluxo do mesmo e separação de celulas a explicação mais detalhada esta no arquimo md adicionado ao repositorio.
