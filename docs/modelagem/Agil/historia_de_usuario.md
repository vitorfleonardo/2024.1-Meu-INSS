## Introdução

As histórias de usuário desempenham um papel crucial no processo ágil de criação de software, especialmente dentro do método Scrum. Elas consistem em relatos breves que descrevem uma funcionalidade sob a perspectiva do 
usuário final. Cada história de usuário tipicamente detalha quem é o usuário, o que ele pretende alcançar e por que isso é relevante para ele. Essas narrativas são redigidas de forma simples e focadas no usuário, 
facilitando a compreensão por parte de todos os membros da equipe de desenvolvimento, independentemente de suas habilidades técnicas. 

## Objetivo

Dentre os principais objetivos do uso das histórias de usuários como um artefato importante de modelagem para o nosso grupo, que tem como foco o projeto do APP MEU INSS, estão os seguintes tópicos:

* <b>Entendimento das necessidades do usuário:</b> As histórias de usuário capacitam a equipe de desenvolvimento a compreender as demandas, aspirações e prioridades dos usuários finais em relação ao produto ou sistema.
* <b>Orientação pelo usuário:</b> Elas asseguram que o desenvolvimento do produto se concentre nas necessidades reais dos usuários finais, mantendo o usuário como o ponto focal durante todo o processo.
* <b>Comunicação transparente:</b> As histórias de usuário atuam como um meio de comunicação direta entre os interessados no projeto e a equipe de desenvolvimento, garantindo que todos tenham uma visão compartilhada dos
  requisitos e objetivos do projeto.
* <b>Planejamento e priorização eficientes:</b> Elas auxiliam na identificação e priorização das funcionalidades mais relevantes para os usuários, facilitando o processo de tomada de decisão sobre o que deve ser desenvolvido
  primeiro.
* <b>Estimativa e divisão de tarefas detalhadas:</b> As histórias de usuário são desmembradas em tarefas menores durante o planejamento do sprint, simplificando a avaliação do esforço necessário para sua implementação e
  possibilitando a distribuição equitativa entre os membros da equipe.
* <b>Adaptação e flexibilidade:</b> Elas permitem uma abordagem adaptativa e incremental para o desenvolvimento do produto, o que facilita a resposta rápida e eficaz às mudanças nos requisitos ou nas prioridades do projeto ao
  longo do tempo.

## Metodologia

Para a criação deste documento, um usuário assumiu o papel de Product Owner (PO) do projeto e foi entrevistado via Teams do dia 26 de Maio de 2024. Durante a entrevista, o PO descreveu as funcionalidades desejadas, enquanto os desenvolvedores/entrevistadores tomavam notas e faziam perguntas. Após a elicitação das histórias de usuário, os critérios de aceitação foram estabelecidos, e as histórias foram priorizadas pelo PO nas categorias Alta, Média ou Baixa prioridade, utilizando o método Three Level Scale de priorização de requisitos. Os participantes da entrevista estão listados na Tabela 1, a gravação da entrevista pode ser visualizada no Vídeo 1, e o modelo de card para as histórias de usuário está descrito na Tabela 2.
<center>

**Tabela 1** - Participantes da entrevista.

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
|                       | Product Owner  |
|                  | Desenvolvedor  |
|        | Entrevistadora |
|     | Desenvolvedor  |

_Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7) e [NOME](GITHUB)._

</center>

<center>

**Vídeo 1** - Entrevista com o PO.

<iframe width="560" height="315" src="https://www.youtube.com/" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<a href="https://www.youtube.com/" target="blanket">Clique aqui</a>

Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).

</center>
<center>

<font size="3">Tabela 2: Modelo de tabela para histórias de usuário.</font>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US_[Número de dentificação]                  | Título                                  |
| Descrição              | _Eu, como_ [tipo de usuário], _desejo_ [ação desejada] _para_ [objetivo] |
| Critérios de Aceitação | - [Critério 1] <br> - [Critério 2] <br>                     |
| Prioridade             | Alta, Média ou Baixa                    |


<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

## Histórias de Usuário

As tabelas 3 a Y detalham as histórias de usuário elicitadas durante o processo de entrevista e análise. Cada história é representada por um identificador único no formato US[X], onde [X] corresponde ao número específico da história. Estas tabelas fornecem uma visão abrangente das necessidades e funcionalidades desejadas, descritas do ponto de vista do usuário. Além disso, cada história de usuário inclui critérios de aceitação claros, que definem as condições que devem ser atendidas para considerar a história como concluída. A prioridade de cada história, determinada pelo Product Owner, também está incluída para ajudar a guiar o processo de desenvolvimento.

### US01 - Realizar login com acesso unificado do gov.br

<center>

**Tabela 3 - História de Usuário Realizar login com acesso unificado do gov.br.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US01                   | Realizar login com acesso unificado do gov.br        |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ realizar o login com o acesso unificado do gov.br _para_ garantir uma autenticação segura e integrada com os serviços do governo. |
| Critérios de Aceitação | - O sistema deve permitir login através do gov.br <br> - O sistema deve verificar as credenciais através do serviço gov.br <br> - Após o login, o usuário deve ser redirecionado para a página inicial do aplicativo |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US02 - Receber termo de uso no primeiro acesso

<center>

**Tabela 4 - História de Usuário Receber termo de uso no primeiro acesso.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US02                   | Receber termo de uso no primeiro acesso              |
| Descrição              | _Eu, como_ novo usuário do aplicativo, _desejo_ receber um termo de uso em meu primeiro acesso _para_ estar ciente das condições e políticas do uso do aplicativo. |
| Critérios de Aceitação | - No primeiro login, o sistema deve exibir o termo de uso <br> - O usuário deve ter que aceitar o termo de uso para continuar <br> - O sistema deve registrar a aceitação do termo de uso pelo usuário |
| Prioridade             |                                                 |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US03 - Acessar documentos legislativos

<center>

**Tabela 5 - História de Usuário Acessar documentos legislativos.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US03                   | Acessar documentos legislativos                      |
| Descrição              | _Eu, como_ usuário interessado em informações legislativas, _desejo_ ter acesso a documentos legislativos _para_ acompanhar e consultar a legislação vigente. |
| Critérios de Aceitação | - O sistema deve exibir uma lista de documentos legislativos <br> - O usuário deve poder buscar e filtrar documentos legislativos <br> - O sistema deve permitir a visualização e download dos documentos |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US04 - Acessar suporte técnico

<center>

**Tabela 6 - História de Usuário Acessar suporte técnico.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US04                   | Acessar suporte técnico                              |
| Descrição              | _Eu, como_ usuário com dificuldades técnicas, _desejo_ acessar o suporte técnico diretamente pelo aplicativo ou por um número 0800 ou chat _para_ resolver meus problemas rapidamente e continuar usando o serviço sem interrupções. |
| Critérios de Aceitação | - O sistema deve oferecer uma opção de suporte técnico dentro do aplicativo <br> - O suporte técnico deve estar acessível via número 0800 e chat <br> - O sistema deve registrar as interações de suporte para acompanhamento |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US05 - Acessar tutoriais de uso

<center>

**Tabela 7 - História de Usuário Acessar tutoriais de uso.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US05                   | Acessar tutoriais de uso                             |
| Descrição              | _Eu, como_ usuário que deseja entender melhor o aplicativo, _desejo_ acessar tutoriais de uso _para_ maximizar as funcionalidades e recursos disponíveis. |
| Critérios de Aceitação | - O sistema deve oferecer tutoriais de uso acessíveis na página inicial <br> - Os tutoriais devem cobrir as principais funcionalidades do aplicativo <br> - O sistema deve permitir feedback dos usuários sobre os tutoriais |
| Prioridade             |                                                 |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US06 - Agendar horário em uma agência

<center>

**Tabela 8 - História de Usuário Agendar horário em uma agência.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US06                   | Agendar horário em uma agência                       |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ agendar um horário em uma agência _para_ resolver questões que necessitam de atendimento presencial de maneira organizada. |
| Critérios de Aceitação | - O sistema deve permitir o agendamento de horários em agências <br> - O sistema deve enviar uma confirmação do agendamento ao usuário <br> - O usuário deve poder cancelar ou reagendar o horário, se necessário |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US07 - Visualizar detalhes dos benefícios

<center>

**Tabela 9 - História de Usuário Visualizar detalhes dos benefícios.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US07                   | Visualizar detalhes dos benefícios                   |
| Descrição              | _Eu, como_ beneficiário, _desejo_ |
| visualizar todos os detalhes dos benefícios aos quais tenho direito _para_ ter informações claras sobre valores, datas de pagamento, status e correções. |
| Critérios de Aceitação | - O sistema deve exibir detalhes completos dos benefícios <br> - O usuário deve poder visualizar histórico de benefícios <br> - O sistema deve alertar o usuário sobre mudanças no status dos benefícios |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US08 - Simular tempo de contribuição e aposentadoria

<center>

**Tabela 10 - História de Usuário Simular tempo de contribuição e aposentadoria.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US08                   | Simular tempo de contribuição e aposentadoria        |
| Descrição              | _Eu, como_ contribuinte, _desejo_ acessar uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria _para_ planejar melhor meu futuro financeiro. |
| Critérios de Aceitação | - O sistema deve permitir a entrada de dados sobre o tempo de contribuição <br> - O sistema deve calcular e exibir uma estimativa de aposentadoria com base nos dados fornecidos <br> - O usuário deve poder ajustar os dados e ver como isso impacta na estimativa |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US09 - Checar extrato da aposentadoria

<center>

**Tabela 11 - História de Usuário Checar extrato da aposentadoria.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US09                   | Checar extrato da aposentadoria                      |
| Descrição              | _Eu, como_ aposentado, _desejo_ checar o extrato do dinheiro da minha aposentadoria mensal _para_ acompanhar meus recebimentos de maneira detalhada. |
| Critérios de Aceitação | - O sistema deve exibir o extrato mensal da aposentadoria <br> - O usuário deve poder ver detalhes sobre cada pagamento <br> - O sistema deve permitir a exportação do extrato para outros formatos, como PDF |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US10 - Acessar extrato anual de imposto de renda

<center>

**Tabela 12 - História de Usuário Acessar extrato anual de imposto de renda.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US10                   | Acessar extrato anual de imposto de renda            |
| Descrição              | _Eu, como_ contribuinte, _desejo_ acessar um extrato anual de imposto de renda _para_ preencher corretamente minha declaração anual de imposto. |
| Critérios de Aceitação | - O sistema deve exibir o extrato anual de imposto de renda <br> - O usuário deve poder visualizar detalhes de cada item do extrato <br> - O sistema deve permitir a exportação do extrato para formatos como PDF |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US11 - Acessar extrato anual de empréstimo

<center>

**Tabela 13 - História de Usuário Acessar extrato anual de empréstimo.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US11                   | Acessar extrato anual de empréstimo                  |
| Descrição              | _Eu, como_ usuário com empréstimos, _desejo_ acessar um extrato anual de empréstimo _para_ controlar e verificar meus empréstimos anuais. |
| Critérios de Aceitação | - O sistema deve exibir o extrato anual de empréstimos <br> - O usuário deve poder ver detalhes de cada item do extrato <br> - O sistema deve permitir a exportação do extrato para formatos como PDF |
| Prioridade             |                                                 |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US12 - Autenticação biométrica

<center>

**Tabela 14 - História de Usuário Autenticação biométrica.**

| **ID**                 | **Nome**                                             |
| :--------------------- | :--------------------------------------------------- |
| US12                   | Autenticação biométrica                              |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ acessar o aplicativo utilizando autenticação biométrica como impressão digital _para_ ter um acesso seguro e rápido. |
| Critérios de Aceitação | - O sistema deve suportar autenticação biométrica, como impressão digital <br> - O usuário deve poder configurar a autenticação biométrica nas configurações do aplicativo <br> - O sistema deve garantir que a autenticação biométrica seja segura e confiável |
| Prioridade             |                                                  |

<font size="3">Fonte: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

</center>

### US13 - Acesso e visualização do Cadastro Nacional de Informações Sociais (CNIS) 

<center>

**Tabela 15 - História de Usuário Acesso CNIS.**

| **ID**                 | **Nome**                                                                 |
| :--------------------- | :----------------------------------------------------------------------- |
| US13                   | Acesso e visualização do Cadastro Nacional de Informações Sociais (CNIS) |                                  
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ ter total acesso ao CNIS através do próprio sistema _para_ poder visualizar o meu histórico de contribuições da Previdência Social. |
| Critérios de Aceitação | - O sistema deve oferecer a opção de acesso ao CNIS através de um link no menu principal <br> - O documento gerado deve apresentar todos os vínculos, remunerações e contribuições previdenciárias <br>                    |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US14 - Acesso à área de ferramentas dos benefícios dos segurados

<center>

**Tabela 16 - História de Usuário Acesso a ferramentas de benefícios dos segurados.**

| **ID**                 | **Nome**                                          |
| :--------------------- | :------------------------------------------------ |
| US14                   | Acesso a ferramentas de benefícios dos segurados. |                                  
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ ter acesso a uma área dentro do sistema com ferramentas voltadas aos benefícios, como um recurso de pesquisa _para_ poder rastrear e acompanhar o andamento dos meus benefícios. |
| Critérios de Aceitação | - O sistema deve oferecer uma página com ferramentas voltadas exclusivamente para os benefícios <br> - A área de ferramenta dos benefícios deve permitir fazer buscas e realizar filtros <br> - Deve haver uma descrição detalhada sobre a origem de cada benefício |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US15 - Requerimento de benefícios e atualização do vínculo do CNIS

<center>

**Tabela 17 - História de Usuário Requerimento de benefícios e atualização do vínculo do CNIS.**

| **ID**                 | **Nome**                                                     |
| :--------------------- | :----------------------------------------------------------- |
| US15                   |  Requerimento de benefícios e atualização do vínculo do CNIS |                                  
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ poder realizar o requerimento de um benefício _para_ poder ter acesso aos recursos na qual tenho direito. |
| Critérios de Aceitação | - O sistema deve ofertar uma área para realizar o requerimento de benefícios <br> - A área deve permitir realizar também a atualização do vínculo CNIS <br> - Benefícios de quaisquer natureza devem poder sofrer o requerimento |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US16 - Fornecimento de informações referentes a pagamentos não recebidos

<center>

**Tabela 18 - História de Usuário Fornecimento de informações referentes a pagamentos não recebidos.**

| **ID**                 | **Nome**                                                           |
| :--------------------- | :----------------------------------------------------------------- |
| US16                   |  Fornecimento de informações referentes a pagamentos não recebidos |                                  
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ ter acesso a uma área que me mostre as informações referentes aos pagamentos não recebidos devido erros e descontos indevidos, _para_ que eu possa acompanhar o status dos meus benefícios e saber o motivo do seu bloqueio.  |
| Critérios de Aceitação | - O sistema deve ofercer uma área dedicada a mostrar as informações dos pagamentos não efetivados <br> - Deve haver uma descrição a respeito de cada pagamento não realizado e seus motivadores |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US17 - Atualização de dados pessoais

<center>

**Tabela 19 - História de Usuário Atualização de dados pessoais.**

| **ID**                 | **Nome**                        |
| :--------------------- | :------------------------------ |
| US17                   |  Atualização de dados pessoais  |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ poder atualizar meus dados pessoais sempre que desejar, _para_ que eu possa manter meu status e minhas informações pessoais sempre atualizadas. |
| Critérios de Aceitação | - O sistema deve oferecer de forma clara uma opção de atualização dos dados cadastrais pessoais no menu princiapl do sistema <br> - O sistema deve me permitir alterar meus dados pessoais sempre que eu desejar, sem haver limitações desnecessárias |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US18 - Alerta sobre empréstimos indevidos

<center>

**Tabela 20 - História de Usuário Alertas sobre empréstimos indevidos.**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| US18                   |  Alertas caso haja empréstimos indevidos  |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ receber alertas no dispositivo por meio do sistema caso haja empréstimos indevidos, _para_ que eu possa me manter atualizado sobre os empréstimos solicitados. |
| Critérios de Aceitação | - O sistema deve enviar alertas ao dispositivo sempre que houver empréstimos indevidos <br> - Os alertas devem especificar o empréstimo que se configura como indevido <br> - Os alertas devem ser enviados imediatamente após o empréstimo ser configurado como indevido |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US19 - Bloquear empréstimos

<center>

**Tabela 21 - História de Usuário Bloqueio de empréstimos.**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| US19                   |  Exibir a opção de bloquear o empréstimo  |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ ter a opção de bloquear meus empréstimos solicitados, _para_ que eu possa cancelar uma decisão de empréstimo se assim for da minha vontade. |
| Critérios de Aceitação | - O sistema deve, em uma área própria de empréstimos, exibir uma opção para cada empréstimo solicitado oferecendo a opção de realizar o bloqueio dele <br> - A opção de bloqueio deve ficar visível logo após a solicitação do empréstimo <br> - A opção de bloqueio de empréstimo deve ser de fácil identificação dentro do sistema |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

### US20 - Acesso ao sistema mediante CPF e senha

<center>

**Tabela 22 - História de Usuário Acesso ao sistema mediante CPF e senha.**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| US20                   |  Oferecer a opção de ingresso ao sistema mediante CPF e senha  |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ ter a opção de me logar ao sistema por meio do meu CPF e minha senha, _para_ que eu possa ter uma maior variedade de opções ao me logar no sistema. |
| Critérios de Aceitação | - Na área de login, deve existir uma opção de cadastro no sistema por meio do CPF e de uma senha que será criada no momento do cadastro <br> - A opção de cadastro mediante CPF e senha deve ser de fácil identificação na área de login, garantido que todos possam ver as opções de logine  escolher a que melhor lhe agrada |
| Prioridade             |                     |


<font size="3">Fonte: [Gabriel Souza](https://github.com/GabrielMS00).</font>

</center>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 15. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 15](https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 25 de Maio de 2024.
>

> </a> Requisitos de Software. Mei (2022.2). Disponível em: [https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/](https://requisitos-de-software.github.io/2022.2-MEI/Modelagem/UserCases/). Acesso em: 25 mai. 2024.

> </a> Requisitos de Software. Bilheteria DIgital (2023.1). Disponível em: [https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/). Acesso em: 25 mai. 2024.

## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0`|25/05/2024|Criação do documento.|[Gabriel Souza](https://github.com/GabrielMS00)|25/05/2024|[Bianca Castro](https://github.com/BiancaPatrocinio7)|
|`1.1`|25/05/2024|Adição de histórias do usuário.|[Bianca Castro](https://github.com/BiancaPatrocinio7)|26/05/2024|[Gabriel Souza](https://github.com/GabrielMS00)|
|`1.2`|26/05/2024|Adição de histórias do usuário.|[Gabriel Souza](https://github.com/GabrielMS00)|||
