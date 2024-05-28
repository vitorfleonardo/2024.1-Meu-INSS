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
### Tabela de Backlog Completa (Com Rastreabilidade Corrigida)

|Tema|Épico|Histórias de Usuário|ID US|Prioridade|Rastreabilidade|
|:--:|:--:|:--:|:--:|:--:|:--:|
|Autenticação e Segurança|Épico 1.1|Realizar login com acesso unificado do gov.br|US01|Média|RE01|
|Autenticação e Segurança|Épico 1.1|Autenticação utilizando CPF e senha|US20|Baixa|RE20|
|Autenticação e Segurança|Épico 1.1|Autenticação biométrica|US12|Baixa|RE12|
|Autenticação e Segurança|Épico 1.2|Recuperação de senha|US23|Alta|RE23|
|Autenticação e Segurança|Épico 1.2|Garantia de segurança das informações pessoais|US39|Alta|RE39|
|Gerenciamento de Benefícios|Épico 2.1|Visualizar detalhes dos benefícios|US07|Alta|RE07|
|Gerenciamento de Benefícios|Épico 2.1|Simular tempo de contribuição e aposentadoria|US08|Alta|RE08|
|Gerenciamento de Benefícios|Épico 2.1|Checar extrato da aposentadoria|US09|Alta|RE09|
|Gerenciamento de Benefícios|Épico 2.1|Solicitar auxílio-acidente|US24|Média|RE24|
|Gerenciamento de Benefícios|Épico 2.1|Preencher formulário de auxílio-acidente|US25|Alta|RE25|
|Gerenciamento de Benefícios|Épico 2.1|Acesso à área de ferramentas dos benefícios dos segurados|US14|Alta|RE14|
|Gerenciamento de Benefícios|Épico 2.1|Alerta sobre empréstimos indevidos|US18|Média|RE18|
|Gerenciamento de Benefícios|Épico 2.1|Bloquear empréstimos|US19|Alta|RE19|
|Gerenciamento de Benefícios|Épico 2.2|Agendar horário em uma agência|US06|Alta|RE06|
|Gerenciamento de Benefícios|Épico 2.2|Agendar perícias médicas|US21.1|Média|RE21|
|Gerenciamento de Benefícios|Épico 2.2|Reagendar perícias médicas|US21.2|Média|RE21|
|Gerenciamento de Benefícios|Épico 2.2|Cancelar perícias médicas|US21.3|Média|RE21|
|Gerenciamento de Benefícios|Épico 2.2|Fornecimento de informações referentes a pagamentos não recebidos|US16|Média|RE16|
|Gerenciamento de Benefícios|Épico 2.2|Requerimento de benefícios e atualização do vínculo do CNIS|US15|Alta|RE15|
|Acesso a Documentos|Épico 3.1|Acessar extrato anual de imposto de renda|US10|Média|RE10|
|Acesso a Documentos|Épico 3.1|Acessar documentos legislativos|US03|Baixa|RE03|
|Acesso a Documentos|Épico 3.1|Acessar extrato anual de empréstimo|US11|Média|RE11|
|Acesso a Documentos|Épico 3.1|Acesso e visualização do CNIS|US13|Alta|RE13|
|Acesso a Documentos|Épico 3.2|Enviar documentos necessários para benefícios|US22|Alta|RE22|
|Acesso a Documentos|Épico 3.2|Acesso de advogado aos processos dos clientes|US26|Média|RE26|
|Acesso a Documentos|Épico 3.2|Solicitar e fornecer documentos pelo advogado|US27|Alta|RE27|
|Suporte e Tutoriais|Épico 4.1|Acessar tutoriais de uso|US05|Média|RE05|
|Suporte e Tutoriais|Épico 4.1|Acessar suporte técnico|US04|Alta|RE04|
|Suporte e Tutoriais|Épico 4.2|Notificação de atualizações importantes|US30|Alta|RE30|
|Usabilidade e Acessibilidade|Épico 5|Facilidade de uso e intuitividade do aplicativo|US28|Alta|RE28|
|Usabilidade e Acessibilidade|Épico 5|Ferramentas de acessibilidade|US32|Média|RE32|
|Usabilidade e Acessibilidade|Épico 5|Compatibilidade com tecnologias assistivas|US38|Alta|RE38|
|Usabilidade e Acessibilidade|Épico 5|Suporte em vários idiomas|US35|Baixa|RE35|
|Usabilidade e Acessibilidade|Épico 5|Garantia de segurança das informações pessoais|US39|Alta|RE39|
|Integração e Desempenho|Épico 6|Integração com outros serviços do governo|US33|Baixa|RE33|
|Integração e Desempenho|Épico 6|Tempo de resposta do aplicativo|US40|Alta|RE40|
|Integração e Desempenho|Épico 6|Disponibilidade do aplicativo 24/7|US41|Média|RE41|
|Integração e Desempenho|Épico 6|Escalabilidade nacional do sistema|US36|Alta|RE36|
|Integração e Desempenho|Épico 6|Eficiência nas tarefas do aplicativo|US37|Alta|RE37|
|Integração e Desempenho|Épico 6|Compatibilidade com diferentes sistemas operacionais|US29|Alta|RE29|

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
