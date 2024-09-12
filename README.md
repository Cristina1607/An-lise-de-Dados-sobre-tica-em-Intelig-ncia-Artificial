# Análise de Dados sobre Ética em Inteligência Artificial (IA)

Este projeto foi desenvolvido para realizar uma análise de dados de artigos sobre ética em IA. O objetivo é identificar tendências, principais tópicos e preocupações relacionadas à ética em IA, além de realizar uma análise de sentimento.

## Objetivos do Projeto

1. **Análise Exploratória de Dados (AED):** Explorar o conjunto de dados para entender sua estrutura e características.
2. **Identificação de Tendências:** Identificar as tendências ao longo do tempo nos temas discutidos sobre ética em IA.
3. **Principais Tópicos:** Determinar os tópicos mais relevantes discutidos nos artigos.
4. **Análise de Sentimento:** Realizar uma análise de sentimento para compreender a percepção geral sobre a ética em IA.
5. **Visualizações:** Criar gráficos e visualizações para comunicar os insights de forma clara.

## Estrutura do Projeto

- `data/`: Conjunto de dados contendo os artigos.
- `src/`: Scripts para análise de dados, modelagem de tópicos, análise de tendências e sentimentos, e visualização.
- `results/`: Pasta para armazenar os gráficos e resultados da análise.
- `README.md`: Detalhes e instruções do projeto.
- `requirements.txt`: Lista de bibliotecas Python necessárias.
- `.gitignore`: Arquivo para ignorar arquivos indesejados no Git.
- `LICENSE`: Licença do projeto.

## Como Executar

1. Clone o repositório:
    ```bash
    git clone https://github.com/Cristina1607/An-lise-de-Dados-sobre-tica-em-Intelig-ncia-Artificial.git
    cd An-lise-de-Dados-sobre-tica-em-Intelig-ncia-Artificial
    ```

2. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

3. Execute os scripts localizados na pasta `src/` para realizar a análise de dados, por exemplo:
    ```bash
    python src/exploratory_analysis.py
    ```

4. Alternativamente, você pode abrir e executar o notebook `analysis_notebook.ipynb` para realizar a análise de forma interativa.

## Conjunto de Dados

O conjunto de dados `ethics_in_ai_articles.csv` contém informações sobre artigos relacionados à ética em IA, incluindo:
- Título do artigo
- Autor(es)
- Data de publicação
- Texto do artigo
- Sentimento

## Resultados

Os resultados da análise serão salvos na pasta `results/figures/`, contendo gráficos de tendências, principais tópicos e análise de sentimento.
