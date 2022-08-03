# Visualização dos Embeddings de Redações do ENEM

Visualização dos embeddings dos Textos CLínicos gerados pelo BERTimbau utilizando o Embedding Projector.
https://projector.tensorflow.org/


## A pasta **"sempooling"** possui 1 versão de redações nota 1000 no ENEM com os embeddings dos tokens:
- 1 - Concatenação das 4 últimas camadas do BERTimbau large

**Link** para o Embedding Projector sem pooling através do arquivo config-sem-poling.json: https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/RaphaelSilv/embeddings-visualizer/master/config-sem-pooling.json



## A pasta **"compooling"** possui 1 versão de redações nota 1000 no ENEM com os embeddings das palavras e sua POS-Tag:
- 1 - Concatenação das 4 últimas camadas do BERTimbau large

**Link** para o Embedding Projector com pooling através do arquivo config_pool.json: https://projector.tensorflow.org/?config=https://raw.githubusercontent.com/RaphaelSilv/embeddings-visualizer/master/config.json

## Geração dos arquivos

Os arquivos utilizados pelo Embedding Projector foram gerados pelo notebook: [TODO]
