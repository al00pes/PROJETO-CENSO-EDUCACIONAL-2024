# PROJETO-LIV

🎓 Análise de Escolas Particulares - Censo Escolar 2024
Este projeto tem como objetivo extrair, tratar, armazenar e visualizar dados do Censo Escolar da Educação Básica 2024, com foco em instituições particulares. A iniciativa busca gerar insights relevantes para apoiar áreas como marketing e comercial, ajudando na definição de estratégias mais assertivas para oferta de produtos e serviços educacionais.

🔍 Objetivo
Extrair os microdados do Censo Escolar 2024 disponibilizados pelo INEP.

Filtrar os dados para instituições de ensino particular.

Realizar o tratamento e limpeza dos dados com Python.

Ingerir os dados tratados no Google BigQuery.

Construir um dashboard interativo para visualização de insights.

🛠️ Tecnologias Utilizadas
Python: Tratamento, limpeza e transformação dos dados.

Google BigQuery: Armazenamento e consulta eficiente dos dados tratados.

Business Intelligence (BI): Visualização e exploração dos dados (ex: Power BI, Looker Studio, etc.).

⚙️ Pipeline do Projeto
Coleta de Dados
Download dos microdados do Censo Escolar 2024 diretamente do portal do INEP.

Tratamento com Python

Leitura e padronização dos arquivos CSV.

Filtragem de escolas privadas.

Limpeza de colunas irrelevantes ou inconsistentes.

Enriquecimento dos dados com novas métricas (se aplicável).

Ingestão para o BigQuery

Criação de dataset e tabelas.

Upload automatizado via pandas-gbq ou google-cloud-bigquery.

Visualização com BI

Conexão com o BigQuery.

Criação de gráficos, KPIs e filtros interativos.

Dashboard focado em métricas como localização, número de matrículas, etapas de ensino, entre outros.
