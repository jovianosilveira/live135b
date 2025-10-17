# 💰 **PROJETO ELIZER ALMEIDA**

**Supervisionado por:** *Edson Garlini*

---

## 🧾 Descrição do Projeto

O **Projeto Elizer Almeida** é um **painel de controle financeiro desenvolvido em Power BI**, criado para simplificar a visualização e o acompanhamento de receitas, despesas e metas mensais.  
O objetivo é **transformar planilhas confusas em insights claros e visuais**, permitindo ao usuário tomar decisões mais inteligentes sobre o orçamento pessoal e empresarial.

---

## 📊 Principais Indicadores (KPIs)

- 💸 **Saldo Atual**: diferença entre receitas e despesas do mês  
- 📈 **Evolução Mensal de Lucro**: acompanhamento da performance financeira mês a mês  
- 🎯 **Meta de Economia**: percentual atingido em relação à meta definida  
- 🧮 **Distribuição de Gastos**: análise por categoria (alimentação, transporte, lazer, investimentos, etc.)

---

## ⚙️ Fontes de Dados

O painel é atualizado automaticamente a partir de múltiplas fontes:

- Planilhas Excel de lançamentos financeiros  
- Conexão direta com extratos bancários via **API REST**  
- Importação de relatórios de cartão de crédito em CSV  
- Base auxiliar com metas e categorias de despesas

---

## 📐 Estrutura do Modelo de Dados

- **FatoFinanceiro**: contém todas as transações (data, valor, tipo, categoria)  
- **DimCategoria**: classificação de despesas e receitas  
- **DimTempo**: calendário completo para análise temporal  
- **DimConta**: informações sobre contas bancárias e cartões  

Relacionamentos modelados no formato *estrela (Star Schema)*, garantindo performance e facilidade de uso no Power BI.

---

## 🎨 Visualizações Principais

- **Dashboard Resumo Financeiro:** visão geral com saldo, metas e alertas  
- **Análise de Gastos:** gráfico de pizza com filtro dinâmico por categoria  
- **Evolução Mensal:** gráfico de linhas com tendência de lucro e despesas  
- **Mapa de Despesas por Localização:** integração com coordenadas de compras  
- **Tabela Dinâmica:** drill-down de transações detalhadas

---

## 🧠 Insights Gerados

- Identificação de picos de gasto em lazer durante fins de semana  
- Crescimento de 12% na economia após implementação do painel  
- Redução de 8h semanais em tempo de análise financeira manual  

---

## 🚀 Tecnologias Utilizadas

| Tecnologia | Descrição |
|-------------|------------|
| **Power Query** | Tratamento e limpeza dos dados |
| **DAX** | Cálculo de indicadores e medidas |
| **Power BI Service** | Publicação e atualização automática |
| **OneDrive** | Armazenamento de planilhas base |
| **Excel** | Input manual de lançamentos financeiros |

---

## 🏁 Conclusão

O **Projeto Elizer Almeida** mostra como o **Power BI pode ser o herói do controle financeiro**, ajudando a visualizar para onde o dinheiro está indo e onde ele deveria estar indo 😅.  
Com um painel interativo e automatizado, o tempo de controle cai drasticamente — e a clareza sobre as finanças aumenta na mesma proporção!

> 💡 *"O que não se mede, não se controla. O que não se controla, escapa da carteira."*

---
