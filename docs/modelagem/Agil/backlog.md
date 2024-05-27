# Backlog

## Introdução
A metodologia ágil é uma abordagem flexível de gestão de projetos que se concentra na colaboração, adaptação e entrega contínua de valor ao cliente. No contexto dessa metodologia, o backlog desempenha um papel crucial. Ele é uma lista priorizada de requisitos, funcionalidades e tarefas que precisam ser executados em um projeto ou produto. O backlog é especialmente enfocado na divisão de grandes tarefas em temas, épicos e histórias do usuário, permitindo uma gestão mais eficiente e clara das atividades necessárias para o desenvolvimento de software. Este processo iterativo e incremental garante que o desenvolvimento se mantenha alinhado com as necessidades e expectativas do cliente, proporcionando entregáveis de valor a cada ciclo​​.

## Metodologia
Para organizar nosso backlog de forma eficiente, seguimos uma metodologia que começa pela definição dos temas principais. Estes temas representam grandes áreas de trabalho que englobam diversos aspectos do projeto. Uma vez definidos os temas, identificamos os épicos dentro de cada um deles. Os épicos são grandes blocos de trabalho que precisam ser realizados. Finalmente, dividimos esses épicos em tarefas menores, conhecidas como histórias de usuário, que detalham as funcionalidades específicas a serem desenvolvidas. As histórias de usuário poderão ser vistas com mais detalhes na aba de [histórias de usuário]().

### Temas
* **Tema 1:** Autenticação e Segurança
* **Tema 2:** Gerenciamento de Benefícios
* **Tema 3:** Acesso a Documentos
* **Tema 4:** Suporte e Tutoriais
* **Tema 5:** Usabilidade e Acessibilidade
* **Tema 6:** Integração e Desempenho

### Épicos

* **Épico 1.1: Autenticação e Segurança**
Eu, como usuário, gostaria de realizar o login com o acesso unificado do gov.br, autenticar-me usando CPF e senha, e utilizar autenticação biométrica para segurança adicional.
* **Épico 1.2: Autenticação e Segurança** 
Eu, como usuário, gostaria de que minhas informações pessoais sejam criptografadas e ter uma opção de recuperação de senha para garantir a segurança dos meus dados. 
* **Épico 2.1: Gerenciamento de Benefícios**
Eu, como usuário, gostaria de visualizar detalhes de todos os benefícios, simular tempo de contribuição, estimar aposentadoria, e checar o extrato da aposentadoria mensal para planejar meu futuro financeiro.
* **Épico 2.2: Gerenciamento de Benefícios**
Eu, como usuário, gostaria de agendar um horário em uma agência, ter a flexibilidade de agendar, reagendar e cancelar perícias médicas.
* **Épico 3.1: Acesso a Documentos**
Eu, como usuário, gostaria de acessar extratos anuais de imposto de renda e empréstimo, e visualizar o Cadastro Nacional de Informações Sociais (CNIS) para ter um registro detalhado das minhas contribuições.
* **Épico 3.2: Acesso a Documentos**
Eu, como usuário, gostaria de enviar documentos necessários para requerimento ou manutenção de benefícios, e como advogado, acessar processos dos meus clientes e fornecer documentos pelo sistema para agilizar o atendimento jurídico.
* **Épico 4.1: Suporte e Tutoriais**
Eu, como usuário, gostaria de acessar tutoriais para entender melhor o uso do aplicativo e um serviço de suporte técnico acessível para resolver problemas rapidamente.
* **Épico 4.2: Suporte e Tutoriais**
Eu, como usuário, gostaria de ser notificado sobre atualizações importantes em minhas solicitações e agendamentos via notificações no aplicativo ou por email.
* **Épico 5: Usabilidade e Acessibilidade**
Eu, como usuário, gostaria de que o aplicativo seja fácil de usar e intuitivo, mesmo para quem tem conhecimento técnico limitado.
* **Épico 6: Integração e Desempenho**
Eu, como usuário, gostaria de que o aplicativo tenha integração com outros serviços do governo para facilitar o acesso a diversas informações e funcionalidades em um único lugar. 

### Tabela de backlog

A tabela 1 é um esqueleto de como a tabela de backlog foi feita.

<p align="center" > <strong> Tabela 1 - </Strong>Esqueleto para o backlog</font> <gitbr></p>
<center>

|Tema|Épico|Histórias de Usuário|ID US|Prioridade|Rastreabilidade|
|:--|:--|:--|:--|:--|:--|
|Nome do tema definido|Código do Épico|Descrição da História de Usuário|identificador da História de Usuário|Prioriade baseada na técnica do three level scale|Código do requisito referente a História de usuário|

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024</p></font>




<p align="center" > <strong> Tabela 2 - </Strong>backlog</font> <gitbr></p>
<center>

|Tema|Épico|Histórias de Usuário|ID US|Prioridade|Rastreabilidade|
|:--|:--|:--|:--|:--|:--|
|Autenticação e Segurança|EP1.1|Como usuário, eu quero realizar o login com o acesso unificado do gov.br para ter uma autenticação segura e padronizada.|US1|-|RE01|
|Autenticação e Segurança|EP1.1|Como usuário, eu quero autenticar-me usando CPF e senha para acessar informações pessoais e serviços.|US2|-|RE20|
|Autenticação e Segurança|EP1.1|Como usuário, eu quero que o aplicativo permita autenticação biométrica, como impressão digital, para uma segurança adicional.|US3|-|RE12|
|Autenticação e Segurança|EP1.2|Como usuário, eu quero que minhas informações pessoais sejam criptografadas para garantir a segurança dos meus dados.|US4|-|RE39|
|Autenticação e Segurança|EP1.2|Como usuário, eu quero uma opção de recuperação de senha caso eu a esqueça para não perder o acesso ao aplicativo.|US5|-|RE23|
|Gerenciamento de Benefícios|EP2.1|Como usuário, eu quero visualizar detalhes de todos os benefícios aos quais tenho direito, incluindo valores, datas de pagamento, status e correções para melhor gerenciar meus benefícios.|US6|-|RE07|
|Gerenciamento de Benefícios|EP2.1|Como usuário, eu quero simular o tempo de contribuição e estimar a aposentadoria e seus benefícios com base nos meus dados para planejar meu futuro financeiro.|US7|-|RE08|
|Gerenciamento de Benefícios|EP2.1|Como usuário, eu quero checar o extrato referente ao dinheiro da aposentadoria mensal para monitorar meus recebimentos.|US8|-|RE09|
|Gerenciamento de Benefícios|EP2.2|Como usuário, eu quero agendar um horário em uma agência para resolver pendências presencialmente.|US9|-|RE06|
|Gerenciamento de Benefícios|EP2.2|Como usuário, eu quero agendar, reagendar e cancelar perícias médicas para ter flexibilidade e controle sobre minhas consultas.|US10|-|RE21|
|Acesso a Documentos|EP3.1|Como usuário, eu quero acessar um extrato anual de imposto de renda para cumprir minhas obrigações fiscais.|US11|-|RE10|
|Acesso a Documentos|EP3.1|Como usuário, eu quero acessar um extrato anual de empréstimo para controlar minhas dívidas.|US12|-|RE11|
|Acesso a Documentos|EP3.1|Como usuário, eu quero acessar e visualizar o Cadastro Nacional de Informações Sociais (CNIS) para ter um registro detalhado das minhas contribuições.|US13|-|RE13|
|Acesso a Documentos|EP3.2|Como usuário, eu quero enviar documentos necessários para o processo de requerimento ou manutenção de benefícios para facilitar o processamento do meu pedido.|US14|-|RE22|
|Acesso a Documentos|EP3.2|Como advogado, eu quero acessar os processos dos meus clientes e solicitar/fornecer documentos necessários ao processo diretamente pelo sistema para agilizar o atendimento jurídico.|US15|-|RE26, RE27|
|Suporte e Tutoriais|EP4.1|Como usuário, eu quero acessar tutoriais para compreender melhor o uso do aplicativo para aproveitar todas as funcionalidades disponíveis.|US16|-|RE05|
|Suporte e Tutoriais|EP4.1|Como usuário, eu quero um serviço de suporte técnico acessível diretamente no aplicativo ou por meio de um número 0800 ou chat de atendimento para resolver problemas e tirar dúvidas rapidamente.|US17|-|RE04|
|Suporte e Tutoriais|EP4.2|Como usuário, eu quero ser notificado sobre atualizações importantes em minhas solicitações e agendamentos via notificações no aplicativo ou por email para me manter informado sobre o status dos meus pedidos.|US18|-|RE30|
|Usabilidade e Acessibilidade|EP5|Como usuário, eu quero que o aplicativo seja fácil de usar e intuitivo, mesmo para quem tem conhecimento técnico limitado.|US19|-|RE28|
|Integração e Desempenho|EP6|Como usuário, eu quero que o aplicativo tenha integração com outros serviços do governo para facilitar o acesso a diversas informações e funcionalidades em um único lugar.|US20|-|RE33|



</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 15. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 15](https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 25 de Maio de 2024.
>

> </a> Requisitos de Software. Lichess (2022.2). Disponível em: [https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/](https://requisitos-de-software.github.io/2022.2-Lichess/modelagem/agil/backlog/). Acesso em: 25 mai. 2024.

> </a> Requisitos de Software. Economia DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/backlog/). Acesso em: 25 mai. 2024.

## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0`|25/05/2024|Criação do documento.|[Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)|[Gabriel Souza](https://github.com/GabrielMS00)|27/05/2024|
`1.1`|27/05/2024|Alteração do documento.|[Paulo Borba](https://github.com/paulohborba)|[Gabriel Souza](https://github.com/GabrielMS00)|27/05/2024|
