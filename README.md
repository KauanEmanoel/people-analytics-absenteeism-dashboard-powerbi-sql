# 📊 Dashboard de People Analytics - Análise de Absenteísmo

Projeto de Business Intelligence criado para praticar SQL, Power BI e DAX em um cenário de People Analytics.

O objetivo foi analisar dados de presença de 250 colaboradores e transformar essas informações em indicadores de faltas, horas perdidas e custo do absenteísmo.

## 🚀 Tecnologias utilizadas

- Power BI
- MySQL
- SQL
- DAX

## 📌 Perguntas respondidas com SQL

### 1. Qual equipe possui mais colaboradores?

A consulta conta quantos colaboradores existem em cada equipe.

![Desf 1 - Equipe com mais colaboradores](images/sql/desf_1_equipe_mais_colaboradores.png)

**O que descobri**

- Operações é a maior equipe da empresa.
- Financeiro é a menor equipe.

---

### 2. Qual equipe teve mais faltas?

A consulta soma todos os registros de falta por equipe.

![Desf 2 - Equipe com mais faltas](images/sql/desf_2_equipe_mais_faltas.png)

**O que descobri**

- Operações teve o maior número de faltas.
- Dados ficou em segundo lugar.

---

### 3. Qual a taxa de faltas por equipe?

A consulta calcula a porcentagem de faltas em relação ao total de colaboradores de cada equipe.

![Desf 3 - Taxa de faltas por equipe](images/sql/desf_3_taxa_faltas_equipe.png)

**O que descobri**

- Dados apresentou a maior taxa de faltas.
- Operações teve muitas faltas, mas possui mais colaboradores.

---

### 4. Quais colaboradores perderam mais horas?

A consulta cria um ranking dos 10 colaboradores com mais horas perdidas.

![Desf 4 - Top 10 colaboradores](images/sql/desf_4_top10_horas_perdidas.png)

**O que descobri**

- Bianca Gomes liderou o ranking.
- O Top 10 mostra quem teve maior impacto nas horas perdidas.

---

### 5. Qual equipe perdeu mais horas de trabalho?

A consulta soma todas as horas perdidas por equipe.

![Desf 5 - Horas perdidas por equipe](images/sql/desf_5_horas_perdidas_equipe.png)

**O que descobri**

- Operações perdeu mais horas de trabalho.
- Suporte e Marketing também tiveram números altos.

---

## 📈 Principais resultados da análise

- 250 colaboradores analisados.
- 450 faltas registradas.
- 7.570 horas perdidas.
- R$ 134.879 de custo estimado do absenteísmo.
- 8,60% de taxa de absenteísmo.

## 🎯 Próxima etapa

Com essas consultas prontas, os dados foram levados para o Power BI, onde criei um dashboard com KPIs, gráficos e filtros para facilitar a análise dos indicadores.
