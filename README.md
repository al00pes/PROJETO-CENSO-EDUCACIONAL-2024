# 🎓 Análise de Escolas Particulares - Censo Escolar 2024

Este projeto tem como objetivo **extrair, tratar, armazenar e visualizar dados** do Censo Escolar da Educação Básica 2024, com foco em instituições **particulares**. A iniciativa visa apoiar áreas como **marketing** e **comercial**, gerando insights para estratégias mais assertivas na oferta de produtos e serviços educacionais.

---

## 🔍 Objetivos

- Extrair os microdados do Censo Escolar 2024 disponibilizados pelo INEP.
- Filtrar os dados para instituições de ensino **privadas**.
- Realizar o **tratamento e limpeza** com Python.
- Ingerir os dados tratados no **Google BigQuery**.
- Construir um **dashboard interativo** com foco em dados educacionais privados.

---

## 🛠️ Tecnologias Utilizadas

- **Python**: para leitura, tratamento e transformação dos dados.
- **Google BigQuery**: para armazenamento e consultas rápidas.
- **Business Intelligence (BI)**: visualização com Power BI, Looker Studio ou equivalente.

---

## ⚙️ Pipeline do Projeto

### 1. Coleta de Dados
- Download dos microdados do portal oficial do [INEP](https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados).

### 2. Tratamento com Python
- Leitura e padronização dos arquivos `.CSV`.
- Filtragem de escolas privadas.
- Limpeza de colunas irrelevantes ou inconsistentes.
- Enriquecimento dos dados com métricas adicionais (quando aplicável).

📁 Acesse o código de tratamento: [🔗 `codigo/tratamento_dados.py`](./codigo/tratamento_dados.py)

### 3. Ingestão no BigQuery
- Criação do dataset e tabelas no BigQuery.
- Upload automatizado com `pandas-gbq` ou `google-cloud-bigquery`.

### 4. Visualização com BI
- Conexão do BI ao BigQuery.
- Construção de gráficos, KPIs e filtros interativos.
- Dashboard com foco em localização, matrículas, etapas de ensino, entre outros.

📊 Veja o exemplo de visualização: [🔗 `imagem/censo-2024.jpg`](./imagem/censo-2024.jpg)

---

## 📂 Estrutura do Projeto

