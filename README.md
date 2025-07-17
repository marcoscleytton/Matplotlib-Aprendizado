# 📊 Comparação de Grupos: Teste A/B (Botões Azul vs Verde)

Este projeto tem como objetivo comparar o desempenho de dois grupos de usuários expostos a diferentes versões de um botão — **azul (Grupo A)** e **verde (Grupo B)** — com foco na taxa de conversão (cliques por visita).

## ⚙️ Metodologia

- Coleta de dados de visitas e cliques para os dois grupos
- Cálculo das taxas de conversão
- Montagem da tabela de contingência
- Aplicação do **teste qui-quadrado** para verificar a significância estatística

## 🧮 Ferramentas Utilizadas

- **Python**
- **NumPy** para manipulação de dados
- **SciPy** para análise estatística (`chi2_contingency`)

## 📈 Resultados

- **Taxa de conversão Grupo A** (botão azul): **12%**
- **Taxa de conversão Grupo B** (botão verde): **16%**
- **Valor-p** obtido: **0.01196**

✅ Como o valor-p é menor que **0.05**, podemos concluir que **a diferença entre os grupos é estatisticamente significativa**.

> **Conclusão**: O botão verde apresenta melhor desempenho e pode ser adotado com maior confiança.

