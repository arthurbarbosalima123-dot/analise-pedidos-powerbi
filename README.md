# 📦 Análise de Pedidos — Visão Gerencial | Power BI

## 🧭 O Problema de Negócio

O CEO de uma empresa de e-commerce precisava entender como a operação estava
evoluindo em relação às metas estabelecidas e como os dados do ano atual se
comparavam com anos anteriores — ou seja, precisava de **inteligência temporal
sobre os pedidos**.

A pergunta central era:
> *"Estamos crescendo? Estamos batendo as metas? Onde estão os clientes que
> mais compram?"*

---

## 🎯 Objetivo

Desenvolver um painel gerencial interativo no Power BI que permitisse ao CEO
e ao time diretivo acompanhar a evolução dos pedidos, monitorar aderência às
metas e identificar padrões geográficos de comportamento dos clientes.

---

## 📊 Métricas e Análises Desenvolvidas

### Cartões de Resumo
| Indicador | Valor |
|---|---|
| Total de Pedidos | 99.441 |
| Total de Clientes | 99.441 |
| Pedidos em 2017 | 45.101 |
| Pedidos em 2018 | 54.011 |
| Taxa de Crescimento (17→18) | +19,76% |

### Análises Gráficas
- **Pedidos x Meta Anual** — acompanhamento do realizado vs meta do ano
- **Pedidos x Meta Mensal** — visão mês a mês do avanço em relação ao planejado
- **Pedidos por Estado** — mapa de calor geográfico com distribuição dos clientes
- **Detalhes por Ano, Mês, Estado e Cidade** — drill-down completo da operação

### Filtros Interativos
- Período (Data de Compra)
- Ano / Mês
- Estado do Cliente
- Cidade do Cliente
- Status do Pedido

---

## 🔍 Principais Insights

**1. Crescimento real, mas meta não atingida**
A operação cresceu 19,76% de 2017 para 2018 — de 45K para 54K pedidos.
Ainda assim, ficou 25,15% abaixo da meta anual de 72,16K pedidos.
O crescimento é positivo, mas insuficiente para o planejamento estabelecido.
Isso indica necessidade de revisão das metas ou aceleração das estratégias
comerciais.

**2. Concentração geográfica em SP e RJ**
SP e RJ dominam o volume de pedidos no mapa de estados.
Oportunidade clara de expansão para estados como MG, RS e PR, que aparecem
com volume relevante mas ainda distante dos líderes.

**3. Relação 1:1 entre pedidos e clientes**
O total de pedidos (99.441) é igual ao total de clientes (99.441), indicando
que cada cliente realizou em média apenas 1 pedido no período.
Isso sinaliza baixa retenção e recompra — uma oportunidade estratégica de
fidelização que poderia multiplicar a receita sem necessidade de aquisição
de novos clientes.

---

## 🛠️ Ferramentas Utilizadas

- **Power BI** — Desenvolvimento do dashboard interativo
- **Power Query** — ETL: limpeza, transformação e padronização dos dados
- **DAX** — Criação de medidas: metas, taxa de crescimento, KPIs temporais
- **Excel** — Base de dados e validação inicial das métricas


## 🚀 Como Visualizar

1. Faça o download do arquivo `.pbix`
2. Abra no **Power BI Desktop** (gratuito)
3. Explore os filtros e visões interativas

---

## 👤 Autor

**Arthur Lima**
[LinkedIn](https://www.linkedin.com/in/arthur-lima17/) •
[Portfólio](https://arthurbarbosalima123-dot.github.io/portfolio_projetos/)
