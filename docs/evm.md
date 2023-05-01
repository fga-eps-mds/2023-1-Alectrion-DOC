# EVM Agile

## 1. Introdução

O EVM (Earned Value Management) permite que um projeto seja medido pelo progresso e realizar estimativas de resultados prováveis. O EVM Agile, em contraposição ao EVM Tradicional, aborda esforço, tempo e custo como histórias de usuário, sprints, pontos etc.

Para visualizar o EVM do projeto, [acesse a planilha](https://docs.google.com/spreadsheets/d/1HDJw--5Oj5TzBmZu3-CZmt-1dIVGj5q8RN7LHR7hnbs/edit?usp=sharing)

## 2. Principais métricas EVM

* **Valor planejado (PV, Planned Value)** 

O valor planejado define o trabalho que deve ser realizado e materializa o custo total planejado do projeto a qualquer ponto no tempo.

    PV = custo total do projeto * % de trabalho planejado


* **Valor realizado (EV, Earned Value)**

O valor realizado especifica a medida do trabalho já realizada no projeto a qualquer ponto.


    EV = custo total do projeto * % de trabalho realizada


* **Custo Real (AC, Actual Cost)**

O custo real representa o custo incorrido em uma atividade durante um tempo específico, devendo ser considerados custos com hardware, infra, material etc.
O AC é uma medida cumulativa de todo o custo do projeto desde o início até o fim.

    AC = custo real

* **Orçamento na conclusão (BAC, Budget at Completion)**

O BAC representa o custo total de todo o trabalho planejado e a base é o final do projeto.

    BAC = custo total do trabalho

## 3. Métricas derivadas

A partir das principais métricas, pode-se calcular as variâncias, os índices de desempenho e as estimativas.

### **Variâncias**

* **Variação do custo (CV, Cost Variance)**

É um indicador quantitativo da divergência do que foi planejado no orçamento inicial. Se o CV > 0, o projeto está abaixo do orçamento. Se CV < 0, o projeto está acima do orçamento. Se CV = 0, o projeto está conforme planejado.

$$
CV = EV - AC
$$

* **Variação do prazo (SV, Schedule Variance)**

É um indicador indicativo da divergência do planejado no cronogrma inicial. Se SV > 0, o projeto está adiantado. Se SV < 0, O projeto está atrasado. Se SV = 0, o projeto está conforme o cronograma.

$$
SV = EV - PV
$$

### **índices de desempenho**

* **Índice de desempenho do custo (CPI, Cost Performance Index)**

Expressa a relação do valor realizado para o custo real.

$$
CPI = \dfrac{EV}{AC}
$$

* **Índice de desempenho do prazo (SPI, Schedule Performance Index)**

Expressa a relação do valor realizado para o planejado, por isso mede a eficiencia do tempo.

$$
SPI = \dfrac{EV}{PV}
$$

### **Estimativas**

* **Estimativa para terminar**

Custo esperado para terminar o restante do projeto.

$$
ETC = \dfrac{(BAC-EV)}{CPI}
$$

* **Estimativa na conclusão**

Representa o custo total esperado quando o trabalho for totalmente finalizado.

$$
EAC = AC + ETC
$$

## 4. Planilha

<iframe width="1200" height="600" style="-webkit-transform:scale(0.8);-moz-transform-scale(0.8);" frameborder="0" scrolling="yes" src="https://docs.google.com/spreadsheets/d/1HDJw--5Oj5TzBmZu3-CZmt-1dIVGj5q8RN7LHR7hnbs/edit?usp=sharing"></iframe>

## 5. Referências Bibliográficas

<!-- Referências enumeradas-->

> [1] CASTRO, António Agostinho Freitas. Estudo da utilização do EVM em ambientes ágeis. 2022. Tese de Doutorado. Acesso em: 01 de maio de 2023  
> [2] Earned Value Management: The Basics Disponível em: https://www.ecosys.net/knowledge/earned-value-management-basics/. Acesso em: 01 maio 2023.

## 6. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|01/05/2023| Criação do documento | Dafne Moretti |
