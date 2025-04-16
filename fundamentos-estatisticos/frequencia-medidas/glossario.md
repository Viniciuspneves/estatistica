# Glossário de Símbolos Estatísticos

Este arquivo contém os principais símbolos e letras utilizados nas fórmulas estatísticas até o momento atual do projeto. Serve como um guia de referência rápida para interpretar tabelas, fórmulas e gráficos com mais facilidade.

À medida que novos conceitos forem sendo adicionados, este glossário será atualizado.

---

## Símbolos e Significados

| Símbolo         | Nome                                | Descrição                                                  |
|-----------------|-------------------------------------|-------------------------------------------------------------|
| $n$             | Total de dados                      | Tamanho da amostra                                          |
| $f_i$           | Frequência Absoluta                 | Quantidade de vezes que o valor aparece                    |
| $f_{r_i}$       | Frequência Relativa                 | Proporção em relação ao total                              |
| $f_{r_i}$ (%)      | Frequência Relativa Percentual      | Frequência em porcentagem                                  |
| $F_i$           | Frequência Acumulada Absoluta       | Soma das frequências até o valor $i$                       |
| $F_{r_i}$       | Frequência Acumulada Relativa       | Soma das proporções até o valor $i$                        |
| $\sum$          | Somatório                           | Soma de valores sequenciais                                |

---

### $n$ — Total de dados

- **Definição:** Quantidade total de elementos no conjunto de dados.
- **Exemplo:** Se foram entrevistadas 20 pessoas, então $n = 20$.

---

### $f_i$ — Frequência Absoluta

- **Definição:** Número de vezes que um valor ou classe aparece.
- **Exemplo:** Se a idade "20 anos" apareceu 5 vezes na amostra, então $f_i = 5$.

---

### $f_{r_i}$ — Frequência Relativa

- **Definição:** Proporção do valor em relação ao total.
- **Fórmula:** $f_{r_i} = \dfrac{f_i}{n}$
- **Exemplo:** Se 5 pessoas têm 20 anos num total de 20 entrevistados, então $f_{r_i} = \dfrac{5}{20} = 0{,}25$

---

### $f_{r_i}$ (%): — Frequência Relativa Percentual

- **Definição:** Frequência relativa expressa em porcentagem.
- **Fórmula:** $f_{r_i} = \dfrac{f_i}{n} \cdot 100$
- **Exemplo:** $25\%$

---

### $F_i$ — Frequência Acumulada Absoluta

- **Definição:** Soma das frequências absolutas até o valor $i$.
- **Fórmula:** $F_i = \sum_{j=1}^{i} f_j$
- **Exemplo:** Se $f_1 = 2$, $f_2 = 3$, $f_3 = 5$, então $F_3 = 2 + 3 + 5 = 10$

---

### $F_{r_i}$ — Frequência Acumulada Relativa

- **Definição:** Soma das frequências relativas até o valor $i$.
- **Fórmula:** $F_{r_i} = \dfrac{F_i}{n}$

---

### $\sum$ — Somatório

- **Definição:** Representa uma soma sequencial de valores.
- **Exemplo:** $\sum_{i=1}^{3} f_i = f_1 + f_2 + f_3$

---

## Observação sobre os índices $i$ e $j$

- $i$: normalmente representa a linha ou posição atual da observação na tabela.
- $j$: usado como contador em somatórios, principalmente para cálculos acumulados.

---
