# Retail Sales Dashboard – Projeto Power BI

## 🚀 Visão Geral
Este repositório contém o projeto **Retail Sales Dashboard**, um dashboard interativo desenvolvido no Power BI Desktop, que faz análise de vendas de um dataset fictício de comércio varejista. O objetivo é demonstrar habilidades em:

- **Modelagem de dados**: tabela de fatos e tabela de datas (Calendário).
- **DAX avançado**: criação de KPIs, análise temporal e segmentações.
- **Visualização**: design limpo, interatividade e storytelling.

## 🗂️ Estrutura do Repositório
```
├── retail_sales_dataset.csv        # Base de dados original (vendas)
├── README.md                       # Este arquivo de documentação
├── RetailSales_Dashboard.pbix      # Arquivo Power BI Desktop
└── assets/                         # Imagens e mockups (screenshots)
```

## 📝 Descrição do Dataset
O arquivo `retail_sales_dataset.csv` contém 1.000 registros com as seguintes colunas:

| Coluna             | Descrição                                 |
|--------------------|-------------------------------------------|
| Transaction ID     | Identificador único de cada venda         |
| Date               | Data da transação                         |
| Customer ID        | Identificador único do cliente            |
| Gender             | Gênero do cliente                         |
| Age                | Idade do cliente                          |
| Product Category   | Categoria do produto (Beauty/Clothing/Electronics) |
| Quantity           | Quantidade vendida                        |
| Price per Unit     | Preço unitário                            |
| Total Amount       | Valor total da transação                  |

## ✨ Funcionalidades Principais
- **Página 1 – Visão Geral**: KPIs (Receita Total, Ticket Médio, Clientes Únicos, Lucro Estimado), receita por categoria e por mês.
- **Página 2 – Análise por Categoria**: comparação de vendas e lucros por categoria, sazonalidade, perfil de gênero e faixa etária.
- **Página 3 – Perfil do Cliente**: distribuição de idade, ticket médio por faixa etária, mapa de clientes (se disponível).
- **Página 4 – Top Clientes**: ranking dos 10 maiores compradores, análise de comportamento mensal do cliente top.


## 📊 Como Usar o Dashboard

### 1. Pré-requisitos
- **Power BI Desktop** (versão mais recente recomendada).

### 2. Clonar o Repositório
```bash
git clone https://github.com/seu_usuario/retail-sales-dashboard.git
cd retail-sales-dashboard
```

### 3. Carregar os Dados
1. Abra `RetailSales_Dashboard.pbix` no Power BI Desktop.  
2. No painel **Transformar Dados**, confirme que a fonte de dados está apontando para `retail_sales_dataset.csv`.  
3. Clique em **Aplicar** para atualizar o modelo.

### 4. Explorar as Páginas
- **Geral**: obtenha visão executiva inicial.  
- **Categoria**: explore detalhadamente cada categoria de produto.  
- **Perfil do Cliente**: entenda quem são seus clientes.  
- **Top Clientes**: veja os maiores consumidores e seu comportamento.  
- **Insights & Conclusão**: leia as análises finais e recomendações.

### 5. Interagir com o Dashboard
- Utilize os **Slicers** (filtros) no topo de cada página para **Ano**, **Gênero**, **Categoria** e **Faixa Etária**.  
- Clique em elementos dos gráficos para **realce cruzado** e obtenha detalhes específicos.


## 🚀 Próximos Passos
- Incluir **análise de margem por produto** e **previsão de vendas** com Azure Machine Learning.  
- Adicionar **visual customizado** (ex: decomposition tree) para maior interação.  
- Publicar no **Power BI Service** e compartilhar com stakeholders.

## 👤 Sobre o Autor
Ygor de Freitas Caixeta — Analista de Dados Jr. com foco em Power BI e DAX.  
[LinkedIn](https://www.linkedin.com/in/ygorcaixeta) | [GitHub](https://github.com/seu_usuario)
