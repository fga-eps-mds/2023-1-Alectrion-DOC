# Plano de Qualidade do Produto

## 1. Introdução

Um dos pilares mais importantes de um produto é a qualidade deste.
A ISO9126 define qualidade como "totalidade de características e critérios de um produto ou serviço que exercem suas habilidades para satisfazer as necessidades declaradas ou envolvidas” 
A ISO 25010, disponibilizada em 2011, padroniza a qualidade de produtos de software, define qualidade como  e define 8 características para a qualidade, sendo adequação funcional, eficiência de desempenho, compatibilidade, usabilidade, confiabilidade, segurança, manutenção e portabilidade.

## 2. Objetivo

O objetivo da elaboração deste plano de qualidade é especificar as ferramentas que serão utilizadas e as métricas analisadas pela equipe para que seja definida a qualidade do produto e tomadas decisões. Assim, os objetivos deste documento são:
- Definir os objetivos de qualidades.
- Apresentar formas de atingir os objetivos de qualidade.
- Selecionar e coletar métricas
- Apresentar a interpretação e uso das metricas para o produto.
- Especificar procedimentos, tecnicas e ferramentas

## 3. Objetivos de qualidade

## 4. Verificação e validação

## 5. Padrões, práticas, convenções e métricas

### ISOs e modelos de qualidade

### Métricas

### Métricas para o produto

## 6. Testes

O software é uma das construções mais complexas dos humanos por isto está sujeito a inconsistências e erros. O conjunto de processos para validar o correto funcionamento de um software são chamados testes e as atividades de teste surgiram justamente para evitar que estes erros cheguem ao usuário final.

* Testes de unidade: a maior parte dos testes se encontram nesta categorização e são utilizados para verificar pequenas partes de um código, normalmente uma classe somente.

* Testes de integração: estes testes verificam uma transação completa ou uma funcionalidade

* Testes de sistema: testes que simulam uma sessão com usuário real

## 7. Ferramentas, técnicas e metodologias

[Jest](https://jestjs.io/pt-BR/): Framework de testes para TypeScript;
[ESLint](https://eslint.org/):  Ferramenta de verificação de código, que garante que o código esteja de acordo com os padrões encontrados no ECMAScript;
[Codcov](https://about.codecov.io/): Ferramenta que verifica cobertura de código;
[SonarCloud](https://www.sonarsource.com/products/sonarcloud/?gads_campaign=SC-Class01-Brand&gads_ad_group=SonarCloud&gads_keyword=sonarcloud&gclid=Cj0KCQjwyLGjBhDKARIsAFRNgW_ldned9rPbZ6BecorNDUxvGxjLbdoawwMROpUJnpr5qGlKr3oBOh0aAnZlEALw_wcB): Ferramenta de varredura de código para analisar o código de acordo com as regras e métricas definidas.

## 8. Controle de código 

A fim de assegurar a execução de procedimentos de qualidade, utilizamos uma combinação de tarefas automatizadas e manuais. As tarefas automatizadas incluem documentação, controle de versão, controle de código, controle de commits, testes automatizados. Essas tarefas são realizadas por ferramentas e sistemas que auxiliam na garantia da qualidade do software.

## 9. Coleta e manutenção

O processo de manutenção de sistemas de software tem como objetivo principal realizar modificações no produto de software após liberações de releases. Essas modificações podem ser feitas para melhorar o desempenho, corrigir falhas, outros atributos do software, ou adaptá-lo às mudanças do ambiente em que ele opera.

Existem categorias de manutenção que abrangem as necessidades de modificação do software:

* Manutenção Adaptativa: Essa categoria envolve a adaptação do software ao ambiente em que ele está sendo executado. Isso pode incluir a atualização de dependências, a compatibilidade com novas versões de sistemas operacionais ou plataformas, e a incorporação de novos requisitos legais ou regulatórios.

* Manutenção Corretiva: Nessa categoria, o foco está na identificação e correção de erros no software. Essas correções visam resolver problemas que foram identificados após a liberação do software, seja por meio de relatórios de erros ou por meio de testes e monitoramento contínuo.

* Manutenção Preventiva: A manutenção preventiva tem como objetivo melhorar a manutenibilidade e a confiabilidade futuras do software. Isso pode envolver a refatoração de código, a identificação e correção de áreas propensas a erros, aprimoramentos na documentação e a implementação de boas práticas de desenvolvimento.

* Manutenção Perfectiva: Essa categoria abrange as modificações solicitadas pelos usuários para modificar funções existentes, adicionar novas funcionalidades ou realizar melhorias gerais no software. Essas modificações visam atender às necessidades dos usuários e aprimorar a experiência geral com o software.

O processo de manutenção de sistemas de software é fundamental para garantir que o software esteja sempre atualizado, funcional e alinhado com as necessidades dos usuários e do ambiente em que ele opera.

## 4. Referências

[1] Importância dos testes de software na qualidade do sistema. TreinaWeb. Disponível em: https://www.treinaweb.com.br/blog/importancia-dos-testes-de-software-na-qualidade-do-sistema. Acesso em: 24 mai. 2023.

Eng de software moderna

## 5. Histórico de versão

|**Data**|**Descrição**|**Autor(es)**|
|--------|-------------|--------------|
| 23/05/2023 | Criação de plano de comunicação | Dafne Moretti |