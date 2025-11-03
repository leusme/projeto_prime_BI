# 📊 Análise de Vendas e Desempenho Comercial – Power BI  
**Projeto AulaPrime**

## 🧭 Visão Geral
Este projeto tem como objetivo **analisar o desempenho de vendas**, **monitorar indicadores financeiros** e **comparar resultados entre períodos** (como anos e meses anteriores), auxiliando na **tomada de decisão** e na **identificação de oportunidades de melhoria em faturamento e lucros**.

Os dados são **reais**, porém correspondem a **anos anteriores**, garantindo a privacidade das informações atuais.  
O projeto foi desenvolvido no **Power BI Desktop**, com foco em **modelagem de dados**, **criação de métricas DAX** e **estruturação do modelo analítico**.

---

## ⚙️ Tecnologias e Recursos Utilizados
- **Power BI Desktop** – criação do modelo, medidas e visualizações  
- **Excel** – fonte de dados principal  
- **DAX (Data Analysis Expressions)** – criação de medidas e KPIs  
- **Power Query** – limpeza, transformação e integração dos dados  
- **Modelagem Dimensional** – organização em tabelas de fatos e dimensões  

---

## 📂 Estrutura e Etapas do Projeto
| Etapa | Descrição | Status |
|-------|------------|--------|
| **Coleta e Importação de Dados** | Conexão e carregamento da base Excel | ✅ Concluído |
| **Limpeza e Transformação** | Tratamento de colunas, tipos e valores nulos | ✅ Concluído |
| **Modelagem de Dados** | Criação de relacionamentos e estrutura fato/dimensão | ✅ Concluído |
| **Criação de Métricas DAX** | KPIs como faturamento bruto, receita líquida, custos e comparativos LY | ✅ Concluído |
| **Construção de Visualizações** | Dashboards interativos e layout visual | 🚧 Em andamento |
| **Storytelling e Publicação** | Organização de insights e publicação no Power BI Service | 🔜 Próxima etapa |

---

## 📈 Principais Métricas e Indicadores
As principais medidas desenvolvidas até o momento incluem:

- **Faturamento Bruto**  
- **Receita Líquida**  
- **Custos (LY)** – custos do ano anterior  
- **Descontos (LY)** – descontos aplicados no mesmo período do ano anterior  
- **Variação de Faturamento** – comparação entre anos e meses  
- **Percentuais e Margens** – lucros e crescimento relativo  

> As medidas foram criadas utilizando **funções DAX** como `CALCULATE()`, `DIVIDE()`, `SAMEPERIODLASTYEAR()` e `PREVIOUSMONTH()`.

---

## 🔍 Funcionalidades e Filtros
Atualmente é possível realizar **filtragens dinâmicas** e análises por:
- **Categoria de Produto**  
- (Novos filtros poderão incluir período, região, cliente e canal de venda nas próximas versões)

---

## 🧱 Estrutura de Dados
O modelo foi construído com **separação clara entre tabelas de fatos e dimensões**, garantindo melhor performance e organização.

Exemplo:
- `Fato_Vendas` – valores de faturamento, custo, desconto, lucro  
- `Dim_Produto` – informações de categoria, marca, tipo  
- `Dim_Tempo` – calendário para análises sazonais e comparativos

---

## 🎨 Visualizações (em desenvolvimento)
A parte visual ainda está em fase de construção.  
As próximas etapas incluirão:
- Painel principal com **indicadores de desempenho**  
- Gráficos de **evolução de vendas por período**  
- Análises de **categoria de produto e margens**  
- Seções de **comparativos entre anos (YoY)**

> 💡 **Preview das telas** será adicionado aqui futuramente, assim que a parte visual estiver finalizada.  


---

## 🚀 Próximos Passos
- [ ] Construir layout visual e identidade do dashboard  
- [ ] Adicionar filtros adicionais (região, cliente, etc.)  
- [ ] Refinar storytelling e insights  
- [ ] Publicar no Power BI Service  
- [ ] Documentar principais medidas DAX no README  

---

## 🧠 Objetivos de Aprendizado
Este projeto também serve como **portfólio pessoal de Business Intelligence**, demonstrando domínio das etapas fundamentais de um projeto BI:
- Entendimento do negócio e indicadores-chave  
- Tratamento e modelagem de dados  
- Criação de medidas analíticas em DAX  
- Construção de relatórios e storytelling de dados  

---

## 🪪 Autor
**Leonardo Bezerra**  
📧 contatoleonardoboliveira@gmail.com
💼 Projeto em desenvolvimento para portfólio Power BI

---

## 🗂️ Como abrir o projeto
1. Baixe o arquivo [`projeto_prime_bi.pbix`](./projeto_prime_bi.pbix)  
2. Abra com o **Microsoft Power BI Desktop**  
3. Explore as tabelas, medidas e relacionamentos criados  
4. (Visualizações e dashboards serão adicionados nas próximas versões)

---

## 🧩 Licença
Este projeto é de uso pessoal e educativo.  
Você pode utilizá-lo como referência para estudos em **Power BI**, **DAX** e **modelagem de dados**.

---

