# 🏎️ Porsche Sales Dashboard
![Preview da Dashboard](preview.png)

Este projeto foi desenvolvido como parte do desafio da Digital Innovation One (DIO). O objetivo foi transformar uma base de dados de vendas da Porsche (sanitizada) em uma dashboard interativa, publicada na web, sem as limitações do Excel.

## 🎯 Perguntas de Negócio Respondidas

A dashboard foi construída para responder a três perguntas principais:
1. **Onde está o dinheiro?** (Receita e ticket médio por modelo)
2. **Qual o risco operacional?** (Receita por forma de pagamento e status de entrega)
3. **Quem e onde vende melhor?** (Top 10 vendedores, top 12 estados e evolução mensal)

## 🛠️ Tecnologias Utilizadas

- **HTML5 e Tailwind CSS:** Para a estrutura e estilização responsiva.
- **Chart.js:** Para a renderização dos gráficos interativos.
- **JavaScript Vanilla:** Para a lógica de filtros e manipulação dos dados embutidos.
- *Não foi necessário servidor backend; todos os dados foram embutidos em um único arquivo `index.html`.*

## 📊 Sobre os Dados

A base utilizada foi sanitizada previamente. Campos como datas inválidas foram tratados (`INVALID`) e excluídos de análises temporais (como o gráfico de evolução mensal), garantindo a integridade dos indicadores financeiros. O nome dos vendedores também passou por um processo de normalização (alias) para evitar duplicidade.

## 🚀 Como visualizar o projeto

O projeto está publicado via GitHub Pages. Você pode acessá-lo no link abaixo:
👉 **[Acessar a Dashboard](https://arnoldofreire.github.io/porsche-dashboard/)**

# porsche-dashboard
Dashboard interativo de vendas Porsche - Desafio DIO
