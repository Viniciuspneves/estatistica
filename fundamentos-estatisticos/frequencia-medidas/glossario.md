# Glossário de Símbolos Estatísticos

>Este arquivo contém os principais símbolos e letras utilizados nas fórmulas estatísticas até o momento atual do projeto. Serve como um guia de referência rápida para interpretar tabelas, fórmulas e gráficos com mais facilidade.

À medida que novos conceitos forem sendo adicionados, este glossário será atualizado.

---

## Tabelas de Frequência

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

- **Fórmula:**
$$f_{r_i} = \dfrac{f_i}{n}$$

- **Exemplo:** Se 5 pessoas têm 20 anos num total de 20 entrevistados, então $f_{r_i} = \dfrac{5}{20} = 0{,}25$

---

### $f_{r_i}$ (%): — Frequência Relativa Percentual

- **Definição:** Frequência relativa expressa em porcentagem.

- **Fórmula:**
$$f_{r_i} = \dfrac{f_i}{n} \cdot  100$$

- **Exemplo:** $25\%$

---

### $F_i$ — Frequência Acumulada Absoluta

- **Definição:** Soma das frequências absolutas até o valor $i$.

- **Fórmula:**
$$F_i = \sum_{j=1}^{i} f_j$$

- **Exemplo:** Se $f_1 = 2$, $f_2 = 3$, $f_3 = 5$, então $F_3 = 2 + 3 + 5 = 10$

---

### $F_{r_i}$ — Frequência Acumulada Relativa

- **Definição:** Soma das frequências relativas até o valor $i$.

- **Fórmula:**
$$F_{r_i} = \dfrac{F_i}{n}$$

---

### $\sum$ — Somatório

- **Definição:** Representa uma soma sequencial de valores.

- **Exemplo:** $\sum_{i=1}^{3} f_i = f_1 + f_2 + f_3$

---

### Observação sobre os índices $i$ e $j$

- $i$: normalmente representa a linha ou posição atual da observação na tabela.

- $j$: usado como contador em somatórios, principalmente para cálculos acumulados.

---

## Medidas de Tendência Central

| Símbolo         | Nome                                | Descrição                                                  |
|-----------------|-------------------------------------|-------------------------------------------------------------|
| $\bar{X}$       | Média Aritmética Amostral           | Média dos valores de uma **amostra**                       |
| $\mu$           | Média Aritmética Populacional       | Média dos valores da **população**                         |
| $X_i$           | Valor Individual                    | O valor da $i$-ésima observação no conjunto de dados       |
| $n$             | Tamanho da Amostra/População        | Número total de observações no conjunto de dados           |
| $Mo$            | Moda                                | Valor mais frequente no conjunto de dados                  |
| $Md$ ou $\tilde{X}$            | Mediana                             | Valor central quando os dados estão ordenados              |
| $x_i$           | Valor Representativo da Classe      | Usado em dados agrupados, valor representativo de uma classe |
| $w_i$ ou $p_i$  | Peso ou Peso Percentual             | Representa a importância de cada valor na média ponderada |

---

### $\bar{X}$ — Média Aritmética Amostral

- **Definição:** A média amostral é a soma dos valores da amostra dividida pelo número total de elementos na amostra. Representa o valor médio de um conjunto amostral.

- **Fórmula:**

$$\bar{X} = \frac{1}{n} \sum_{i=1}^{n} X_i$$

- **Exemplo:**

Se temos a amostra das idades: $18$, $20$, $22$, a soma é $60$ e o número de observações ($n$) é 3.

A média amostral é:

$$\bar{X} = \frac{60}{3} = 20$$

---

### $\mu$ — Média Aritmética Populacional

- **Definição:** A média populacional é a soma dos valores de toda a população dividida pelo número total de elementos da população.

- **Fórmula:**

$$\mu = \frac{1}{N} \sum_{i=1}^{N} X_i$$

onde $N$ é o número total de elementos da população.

- **Exemplo:**

Se a população tem as idades $18$, $20$, $22$, a soma é $60$ e o número de elementos da população ($N$) é 3.

A média populacional é:

$$\mu = \frac{60}{3} = 20$$

---

### $X_i$ — Valor Individual

- **Definição:** Refere-se ao valor da $i$-ésima observação ou dado individual em um conjunto de dados.

- **Exemplo:**

Se a amostra de idades é composta por $18$, $20$, e $22$, então os valores individuais são: $X_1 = 18$, $X_2 = 20$, e $X_3 = 22$.

---

### $n$ — Tamanho da Amostra/População

- **Definição:** O número total de observações ou elementos presentes na amostra ou população.

- **Exemplo:**

Se você tem uma amostra com 5 pessoas, então $n = 5$.

---

### $Mo$ — Moda

- **Definição:** A moda é o valor ou conjunto de valores que aparece com mais frequência em um conjunto de dados.

- **Exemplo:**

Em um conjunto de idades: $20, 21, 20, 22, 23$, a moda é $20$, pois é o valor que aparece mais vezes.

---

### $Md$ ou $\tilde{X}$ — Mediana

- **Definição:** A mediana é o valor que ocupa a posição central de um conjunto de dados ordenados.

- Se houver um **número ímpar** de elementos, a mediana será o valor que está exatamente no meio.

- Se houver um **número par** de elementos, a mediana será a **média dos dois valores centrais**.

- **Exemplo (n ímpar):**

Para o conjunto de idades $18$, $20$, $22$, a mediana é $20$, porque é o valor do meio:

$$\text{Mediana} = 20$$

- **Exemplo (n par):**

Para o conjunto $18$, $20$, $22$, $24$, a mediana será a média dos dois valores centrais:

$$\text{Mediana} = \frac{20 + 22}{2} = 21$$

---

### $x_i$ — Valor Representativo da Classe

- **Definição:** Usado quando os dados estão agrupados em intervalos. É o valor que representa a classe no cálculo de medidas como a média ponderada.

- **Exemplo:**

Se temos um intervalo de idades $[20, 30)$, o valor representativo ($x_i$) pode ser $25$ (o ponto médio do intervalo).

---

### $w_i$ ou $p_i$ — Peso ou Peso Percentual

- **Definição:** Representa a importância de cada valor na média ponderada. O peso pode ser um número ou uma porcentagem associada a cada dado.

- **Exemplo:**

Se em uma média ponderada as idades $20$ e $30$ têm pesos $w_1 = 2$ e $w_2 = 3$, respectivamente, isso significa que a idade $20$ tem o dobro de importância que a idade $30$.
