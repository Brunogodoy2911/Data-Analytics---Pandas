# 📊 Data Analytics com Pandas

Este repositório armazena as anotações práticas e códigos desenvolvidos durante a formação de Data Analytics. Abaixo você encontra um guia do conteúdo estudado em cada notebook, organizado por tópicos de aprendizado.

## 🗂️ Sumário dos Estudos

### 1. Fundamentos e Estruturas de Dados
Conceitos iniciais sobre as principais estruturas da biblioteca Pandas.

* **[`Pandas_series.ipynb`](./Pandas_series.ipynb)**
    * **O que é:** Introdução ao objeto `Series` (array unidimensional).
    * **Conteúdo:** Criação de Series a partir de listas e dicionários, indexação personalizada e acesso a elementos.
* **[`dataframes_pandas.ipynb`](./dataframes_pandas.ipynb)**
    * **O que é:** Introdução ao objeto `DataFrame` (tabela bidimensional).
    * **Conteúdo:** Criação de DataFrames via dicionários e listas de dicionários, além de métodos básicos para seleção de colunas.

### 2. Exploração e Inspeção de Dados
Métodos essenciais para "conhecer" os dados assim que são carregados.

* **[`head_tail_shape_info_describe.ipynb`](./head_tail_shape_info_describe.ipynb)**
    * **Conteúdo:**
        * `head()` e `tail()`: Visualizar primeiras e últimas linhas.
        * `shape`: Verificar dimensões (linhas x colunas).
        * `info()`: Resumo dos tipos de dados e valores não nulos.
        * `describe()`: Estatísticas descritivas básicas (média, desvio padrão, min, max).

### 3. Seleção, Filtragem e Ordenação
Técnicas para extrair e organizar partes específicas dos dados.

* **[`loc_iloc_pandas.ipynb`](./loc_iloc_pandas.ipynb)**
    * **Conteúdo:** Diferença entre seleção por rótulo (`loc`) e seleção por posição/índice numérico (`iloc`), incluindo fatiamento (slicing) de linhas e colunas.
* **[`filter_pandas.ipynb`](./filter_pandas.ipynb)**
    * **Conteúdo:** Filtragem condicional (boolean indexing), uso de operadores lógicos (`&` para E, `|` para OU) e método `isin()` para filtros múltiplos.
* **[`sort_values_pandas.ipynb`](./sort_values_pandas.ipynb)**
    * **Conteúdo:** Ordenação de dados com `sort_values()`, controlando a ordem (crescente/decrescente) e ordenando por múltiplas colunas.

### 4. Limpeza e Tratamento de Dados
Processos para garantir a qualidade e consistência dos dados.

* **[`astype_isna_filna_dropna.ipynb`](./astype_isna_filna_dropna.ipynb)**
    * **Conteúdo:**
        * `astype()`: Conversão de tipos de dados (ex: string para int).
        * `isna()`: Identificação de valores nulos.
        * `fillna()`: Preenchimento de valores ausentes (com média, zero, etc.).
        * `dropna()`: Remoção de linhas ou colunas com dados faltantes.
* **[`formatando_colunas.ipynb`](./formatando_colunas.ipynb)**
    * **Conteúdo:** Renomeação de colunas (`rename`), criação de colunas calculadas (operações aritméticas entre colunas) e remoção de colunas indesejadas (`drop`).

### 5. Transformação e Agregação Avançada
Manipulações mais complexas para análise e resumo de informações.

* **[`apply_map.ipynb`](./apply_map.ipynb)**
    * **Conteúdo:** Aplicação de funções personalizadas e funções anônimas (`lambda`) em colunas inteiras com `apply()` e substituição de valores com `map()`.
* **[`funcoes_agregacao_pandas.ipynb`](./funcoes_agregacao_pandas.ipynb)**
    * **Conteúdo:** Uso do `groupby()` para agrupar dados por categorias e aplicação de funções estatísticas (soma, média) para resumir grupos.

### 6. Entrada e Saída (I/O)
Como trazer dados para o Pandas e exportar seus resultados.

* **[`read_save_pandas.ipynb`](./read_save_pandas.ipynb)**
    * **Conteúdo:** Leitura de dados externos (CSV via URL e arquivos locais), leitura de Excel (`read_excel`) e exportação de DataFrames processados para CSV e Excel (`to_csv`, `to_excel`).

---
*Este repositório serve como referência rápida para sintaxe e funcionalidades da biblioteca Pandas.*
