# Web Scraping Wikipédia – Top 10 Diretores por Bilheteria

Este projeto realiza **coleta, limpeza e análise de dados de bilheteria** de filmes a partir do site Wikipedia com a lista das maiores bilheterias de todos os tempos. O objetivo é gerar insights e visualizar os **10 diretores com maior bilheteria acumulada**.

---

## Tecnologias Utilizadas
- [Jupyter Notebook](https://jupyter.org/) — ambiente interativo para desenvolvimento
- [Python](https://www.python.org/) — linguagem principal do projeto
- [Requests](https://docs.python-requests.org/) — acesso HTTP à Wikipedia com headers personalizados  
- [Pandas](https://pandas.pydata.org/) — manipulação e tratamento de tabelas  
- [Matplotlib](https://matplotlib.org/) — criação do gráfico de barras  
  
---

## Etapas do Projeto
1. **Coleta de Dados**  
   - Web scraping da Wikipedia utilizando `requests` e `pandas`.
2. **Tratamento dos Dados**  
   - Seleção das colunas relevantes: Diretor(a) e Bilheteria (US$)  
   - Limpeza e padronização dos valores de bilheteria
3. **Análise e Consolidação**  
   - Soma da bilheteria por diretor  
   - Seleção do Top 10 diretores
4. **Visualização**  
   - Gráfico de barras mostrando os 10 diretores com maior bilheteria  
   - Ajuste de layout e formatação para melhor visualização
     
