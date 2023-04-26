# Plano de Custos


## 1. Introdução

O plano de custos descreve como os custos do projeto serão planejados, estruturados e controlados, fornecendo detalhes dos processos e ferramentas usadas. A primeira etapa é a estimativa de custos, realizada para estimar o custo dos recursos necessários para a execução do projeto. Depois é determinado o orçamento, agregando todos os custos estimados. Por fim, é feito o controle desses custos para monitorar e possivelmente atualizar o orçamento.

Este documento apresenta a estimativa de custos, orçamentos e controle, para que o projeto possa ser realizado dentro do orçamento planejado.


## 2. Estimativa de custos

### 2.1 Recursos humanos
Para essa estimativa de custos foi utilizado o custo médio anual por aluno de instituto federal. De acordo com [jornal da unesp](https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/) [5], esse custo é de R$40.900 anual por aluno. Para essa estimativa, leva-se também em consideração o curso da equipe, Engenharia de Software, que é um curso de 5 anos, de 232 créditos. Considerando também as 17 semanas de projeto e os 17 integrantes da equipe, temos os seguintes cálculos.

**Custo médio por crédito**
* custo médio anual por integrante x quantidade padrão de anos de curso ÷ quantidade de créditos para formação no curso
* 40.900 x 5 ÷ 232 = R$**881,50**

**Custo médio por integrante na disciplina de EPS/MDS**
*    custo médio por crédito x quantidade de créditos da disciplina
* 881,5 x 4 = R$**3.526,00**

**Custo TOTAL por equipe**
* custo médio por integrante na disciplina de EPS/MDS x quantidade de integrantes da equipe
* 3526,00 x 17 = R$**59.942,00**

**Custo médio semanal por equipe**
* custo TOTAL por equipe ÷ quantidade de semanas do projeto
* 59.942,00 ÷ 17 = R$**3.526,00**

### 2.2 Equipamentos
Para a estimativa de custos dos equipamento será considerado o preço de um _notebook_ com as configurações mínimas de um Intel Core I5 ou AMD Ryzen 5 com 8gb de memória RAM em 2023. Segundo [Kabum](https://www.kabum.com.br/computadores/notebooks) [7], o preço de um notebook com essas características está em torno de R$ 3 mil. Considerando os 17 integrantes da equipe:

**Custo TOTAL dos equipamentos**
* custo médio do notebook x quantidade de integrantes da equipe
* 3.000 x 17 = R$**51.000,00**


### 2.3 Ferramentas
A estimativa de custos com ferramentas será considerado como R$0, pois as plataformas e ferramentas utilizadas pela equipe são gratuitas.

### 2.4 Capacitação
A estimativa de custos com cursos de capacitação será considerado como R$0, pois as plataformas e ferramentas utilizadas pela equipe foram gratuitas.


### 2.5 Infraestrutura
A estimativa de custos de infraestrutura foi planejada considerando o uso de energia elétrica e internet.

#### Internet
Para cálculo do custo de internet utilizaremos o preço médio de planos de 250 MB por mês que, de acordo com [melhorescolha](https://melhorescolha.com/internet-banda-larga/brasilia-df/) [4],é cerca de R$ 89,99.

**Custo semanal de internet por integrante**
* custo mensal da internet ÷ quantidade de semana no mês
* 89,99 ÷ 4 = R$**22,50**

**Custo semanal de internet por equipe**
* custo semanal da internet por integrante x quantidade integrantes
* 22,50 x 17 = R$**382,50**

**Custo TOTAL de internet por equipe**
* custo semanal da internet por equipe x quantidade de semanas do projeto
* 382,50 x 17 = R$**6502,50**

#### Energia
Para a estimativa de energia, seguiu-se os dados da [tabela de tarifas](https://www.neoenergiabrasilia.com.br/residencial-e-rural/Documents/tafiras%20vigentes/01_nbsb_tarifas_energia_eletrica_grupoB_nov_2022_reh3134.pdf) [2] da [neoenergiabrasilia](https://www.neoenergiabrasilia.com.br/Paginas/default.aspx), com os dados vigentes de novembro de 2022 à outubro de 2023. Segundo essa tabela, o custo do KW/h residencial, consumo ativo, de Brasília é cerca de R$0,70.
Segundo dados de 2021 da [cultura uol](https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html) [3], um notebook consome em média cerca de 65W/h, conectado ao carregador. Consideramos que cada integrante da equipe trabalhará 4 horas por semana em sua residência, ao longo de 17 semanas. Utilizando esses dados para cálculo, temos:

**Consumo do notebook em KW/h:**
* potência x horas ÷ 1000  
* 65 x 1 ÷ 1000 = **0,065** KW/h

**Custo semanal de energia por integrante**

* horas de trabalho x consumo do notebook x tarifa
* 4h x x 0,065KW/h x R$0,70
* 4 x 0,065 x 0,70 = R$**0,18**

**Custo semanal de energia por equipe**
* custo semanal por aluno x quantidade de integrantes da equipe
* 0,18 x 17 = R$**3,06**

**Custo TOTAL de energia por equipe**
* custo semanal por equipe x quantidade de semanas do projeto
* 3,06 x 17 = R$**52,02**

#### Custo TOTAL infraestrutura
Somando as estimativas de custo semanal de internet (R$**382,50**) e energia (R$**3,06**) por equipe, têm-se um custo semanal de infraestrutura de **R$385,56**. Considerando as 17 semanas de projeto, o custo total de infrastrutura será de **R$6554,52**.


## 3. Definição do orçamento

Considerando as estimativas de custos acima calculadas e uma margem de 10%, o orçamento total para o projeto em 17 semanas é:

* custo recursos humanos + custo equipamentos + custo ferramentas + custo capacitação + custo infraestrutura
* R$59.942,00 + R$51.000,00 + R$0 + R$0 + R$6554,52 = **R$117.496,52**

O custo do MVP é calculado com base nas semanas até sua entrega, calculado para - semanas. Sendo assim, o custo do MVP é de **R$-**.  
A planilha a seguir apresenta uma melhor visualização dos custos semanais, de projeto e do MVP.


## 4. Planilha de custos

Para consolidação dos custos, utilizamos a planilha conforme abaixo.

<iframe width="1200" height="600" style="-webkit-transform:scale(0.8);-moz-transform-scale(0.8);" frameborder="0" scrolling="yes" src="https://docs.google.com/spreadsheets/d/1kdzz1YNHFtB67Of6R2GIzyFhf1q0JpOVAvLvgTXxyiE/edit#gid=0"></iframe>

## 5. Referências Bibliográficas

<!-- Referências enumeradas-->

> [1] Escritório de Projetos. Gerenciamento dos custos: O que é, objetivo e processos. Disponível em: https://escritoriodeprojetos.com.br/gerenciamento-dos-custos-do-projeto. Acesso em: 19 de abril de 2023  
> [2] Neoenergia Brasília. Tarifas. Disponível em: https://www.neoenergiabrasilia.com.br/residencial-e-rural/Paginas/tarifas.aspx. Acesso em: 19 de abril de 2023  
> [3] Cultura UOL. 6 maneiras de economizar na conta de luz do home office. Disponível em: https://cultura.uol.com.br/noticias/26097_6-maneiras-de-economizar-na-conta-de-luz-do-home-office.html. Acesso em: 19 de abril de 2023  
> [4] Melhor escolha. Internet em Brasília. Disponível em: https://melhorescolha.com/internet-banda-larga/brasilia-df/. Acesso em: 19 de abril de 2023  
> [5] Jonal da Unesp. Cobrança de mensalidade não é a solução para o financiamento da universidade pública. Disponível em: https://jornal.unesp.br/2022/06/08/cobranca-de-mensalidade-nao-e-a-solucao-para-o-financiamento-da-universidade-publica/. Acesso em: 19 de abril de 2023  
> [6] Alectrion. Disponível em: https://fga-eps-mds.github.io/2022-2-Alectrion-DOC. Acesso em: 19 de abril de 2023  
> [7] Kabum. Disponível em: https://www.kabum.com.br/computadores/notebooks. Acesso em: 20 de abril de 2023  

## 6. Histórico de versão

|**Data**|**Descrição**|**Autore(es)**|
|--------|-------------|--------------|
|19/04/2023| Criação do documento | Lucas Lima |
|25/04/2023| Revisão do documento | Aline Lermen e João Pedro |
