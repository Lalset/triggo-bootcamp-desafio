# triggo-bootcamp-desafio
Solução para o desafio técnico do Programa Trainee de Excelência em Engenharia de Dados e DataOps 2025 - triggo.ai.   O projeto envolve análise exploratória, modelagem preditiva, segmentação de clientes, visualizações e geração de insights a partir de um dataset de e-commerce brasileiro.

# Teste Técnico - Triggo.ai | Programa de Trainee em Engenharia de Dados e DataOps 2025

Este repositório contém a solução desenvolvida para o teste técnico do processo seletivo da **triggo.ai**. O objetivo foi analisar dados do e-commerce **Olist** utilizando técnicas de análise exploratória, machine learning, segmentação e visualização de dados.

## Etapas do Desafio

### ✅ Tarefa 1: Preparação dos Dados

- Carregamento e limpeza dos datasets CSV.
- Tratamento de nulos, normalização e conversão de tipos.
- Modelagem relacional entre tabelas principais.
- Documentação de decisões no notebook.

### ✅ Tarefa 2: Análise Exploratória de Dados

- Volume de pedidos por mês e identificação de sazonalidade.
- Distribuição do tempo de entrega.
- Correlação entre valor do frete e distância de entrega.
- Top categorias de produtos em faturamento.
- Estados com maior ticket médio.
- Extras:
  - Distribuição de avaliações dos clientes.
  - Distribuição de pedidos por estado.

### ✅ Tarefa 3: Solução de Problemas de Negócio

- **Retenção**: Apenas 3,12% dos clientes são recorrentes.
- **Predição de Atraso**:
  - Modelo de Regressão Logística para prever atrasos.
  - Matriz de confusão e métricas de avaliação.
  - Ajustes para melhorar o recall da classe minoritária.
---

## Principais Insights

- SP lidera com folga em número de pedidos, refletindo seu peso econômico.
- Produtos com maior faturamento incluem eletrônicos, cama/mesa/banho e moda.
- Fretes mais caros estão ligados a maiores distâncias, com correlação ~0.39.
- Clientes com entregas dentro do prazo tendem a dar notas maiores.
- A taxa de atrasos é de aproximadamente 8,1%.

## Imagens do Insight para fácil acesso:
### Gráficos da Análise Exploratória

- [Volume de Pedidos por Mês](https://github.com/Lalset/triggo-bootcamp-desafio/blob/main/images/Volume%20de%20Pedidos%20por%20M%C3%AAs.png)
- [Distribuição do Tempo de Entrega (em dias)](https://github.com/Lalset/triggo-bootcamp-desafio/blob/main/images/Distribui%C3%A7%C3%A3o%20do%20tempo%20de%20Entrega(em%20dias).png)
- [Quantidade de Pedidos por Estado](https://github.com/Lalset/triggo-bootcamp-desafio/blob/main/images/Quantidade%20de%20Pedidos%20por%20Estado.png)
- [Relação entre Distância e Valor do Frete](https://github.com/Lalset/triggo-bootcamp-desafio/blob/main/images/Rela%C3%A7%C3%A3o%20entre%20dist%C3%A2ncia%20e%20valor%20do%20frete.png)
- [Top 10 Categorias por Faturamento](https://github.com/Lalset/triggo-bootcamp-desafio/blob/main/images/Top%2010%20Categorias%20por%20Faturamento.png)

---

##  Como Executar

1. Clone este repositório:
git clone https://github.com/Lalset/triggo-bootcamp-desafio
cd triggo-bootcamp-desafio

3. Instale os pacotes necessários:
pip install -r requirements.txt

4. Abra o notebook na plataforma de sa escolha e execute as células.

## Tecnologias Utilizadas
- Python
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- SQL (pandasql)

## Contato
Em caso de dúvidas ou sugestões é só vir aqui: <br> Talles - Email: tallesg.work@gmail.com / Linkedin: www.linkedin.com/in/talles-aragão

## Obrigado pela oportunidade, triggo.ai!




