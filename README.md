# 📊 Dashboard de People Analytics - Análise de Absenteísmo

Projeto de Business Intelligence criado para praticar SQL, Power BI e DAX em um cenário de People Analytics.
O objetivo foi analisar dados de presença de 250 colaboradores e transformar essas informações em indicadores de faltas, horas perdidas e custo do absenteísmo.

## 🚀 Tecnologias utilizadas
- Power BI
- SQL


## 📌 Perguntas respondidas com SQL

### 1. Qual equipe possui mais funcionários?
A consulta conta quantos colaboradores existem em cada equipe.

![Desf 1 - Equipe com mais funcionários](./equipe-maior.png)

**O que descobri**
- Operações é a maior equipe da empresa (69 colaboradores).
- Financeiro é a menor equipe (29 colaboradores).

---

### 2. Qual equipe teve mais faltas?
A consulta soma todos os registros de falta por equipe.

![Desafio 2 - Equipe com mais faltas](./faltas-equipe.png)

**O que descobri**
- Operações teve o maior número de faltas (115).
- Dados ficou em segundo lugar (79).

---

### 3. Qual a taxa de faltas por equipe?
A consulta calcula a proporção de faltas em relação ao total de colaboradores de cada equipe.

![Desf 3 - Taxa de faltas por equipe](images/sql_03_taxa_faltas.png)

**O que descobri**
- Dados apresentou a maior taxa de faltas (213,51%).
- Operações teve muitas faltas em números absolutos, mas por ter mais colaboradores, sua taxa relativa é menor (166,67%).

---

### 4. Quais colaboradores perderam mais horas?
A consulta cria um ranking dos 10 colaboradores com mais horas perdidas.

![Desf 4 - Top 10 colaboradores](images/sql_04_top10_horas_perdidas.png)

**O que descobri**
- Bianca Gomes liderou o ranking, com 75 horas perdidas.
- O Top 10 mostra quem teve maior impacto individual nas horas perdidas.

---

### 5. Qual equipe perdeu mais horas de trabalho?
A consulta soma todas as horas perdidas por equipe.

![Desf 5 - Horas perdidas por equipe](images/sql_05_horas_perdidas_equipe.png)

**O que descobri**
- Operações perdeu mais horas de trabalho (2.069 horas).
- Suporte (1.274) e Marketing (1.259) também tiveram números altos.

---

## 📈 Principais resultados da análise
- 250 colaboradores analisados.
- 450 faltas registradas.
- 7.570 horas perdidas.
- R$ 134.879 de custo estimado do absenteísmo.
- 8,60% de taxa de absenteísmo.

## 🎯 Próxima etapa
Com essas consultas prontas, os dados foram levados para o Power BI, onde criei um dashboard com KPIs, gráficos e filtros para facilitar a análise dos indicadores.
