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

Para a criação deste documento, um usuário assumiu o papel de Product Owner (PO) do projeto e foi entrevistado via Teams do dia 26 de Maio de 2024. Durante a entrevista, o PO descreveu as funcionalidades desejadas, enquanto os desenvolvedores/entrevistadores tomavam notas e faziam perguntas. Após a elicitação das histórias de usuário, os critérios de aceitação foram estabelecidos, e as histórias foram priorizadas pelo PO nas categorias , Média ou Baixa prioridade, utilizando o método Three Level Scale de priorização de requisitos. Os participantes da entrevista estão listados na Tabela 1, a gravação da entrevista pode ser visualizada no Vídeo 1, e o modelo de card para as histórias de usuário está descrito na Tabela 2.
<center>

**Tabela 1** - Participantes da entrevista.

| **Participante**                                        | **Função**     |
| :------------------------------------------------------ | :------------- |
|                       | Product Owner  |
|                  | Desenvolvedor  |
|        | Entrevistadora |
|     | Desenvolvedor  |

_Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7) e [NOME](GITHUB)._

</center>

<center>

**Vídeo 1** - Entrevista com o PO.

<iframe width="560" height="315" src="https://www.youtube.com/" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<a href="https://www.youtube.com/" target="blanket">Clique aqui</a>

Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).

</center>
<center>

<font size="3">Tabela 2: Modelo de tabela para histórias de usuário.</font>

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US_[Número de dentificação]                  | Título                                  |
| Descrição              | _Eu, como_ [tipo de usuário], _desejo_ [ação desejada] _para_ [objetivo] |
| Critérios de Aceitação | - [Critério 1] <br> - [Critério 2] <br>                     |
| Prioridade             | Alta, Média ou Baixa                    |


<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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

<font size="3">Autor: [Bianca Castro](https://github.com/BiancaPatrocinio7).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>

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


<font size="3">Autor: [Gabriel Souza](https://github.com/GabrielMS00).</font>
</center>

### US21.1 - Agendar Perícias Médicas

<center>

**Tabela 23 - História de Usuário Agendar Perícias Médicas**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US21.1_                   | Agendar Perícias Médicas |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ agendar perícias médicas _para_ gerir minhas consultas de forma conveniente |
| Critérios de Aceitação | - O usuário deve poder selecionar uma data e hora disponíveis para agendar uma perícia médica |
| Prioridade             |                                    |


<font size="3">Autor: [José Filipi](https://github.com/JoseFilipi).</font>
</center>


### US21.2 - Reagendar Perícias Médicas

<center>

**Tabela 24 - História de Usuário Reagendar Perícias Médicas**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US21.2_                   | Reagendar Perícias Médicas |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ reagendar perícias médicas _para_ ajustar minhas consultas conforme necessário |
| Critérios de Aceitação | - O usuário deve poder reagendar uma perícia médica já agendada |
| Prioridade             |                                     |


<font size="3">Autor: [José Filipi](https://github.com/JoseFilipi).</font>
</center>

---

### US21.3 - Cancelar Perícias Médicas

<center>

**Tabela 25 - História de Usuário Cancelar Perícias Médicas**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US21.3_                   | Cancelar Perícias Médicas |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ cancelar perícias médicas _para_ gerenciar meus compromissos de forma flexível |
| Critérios de Aceitação | - O usuário deve poder cancelar uma perícia médica já agendada |
| Prioridade             |                                     |


<font size="3">Autor: [José Filipi](https://github.com/JoseFilipi).</font>
</center>


### US22 - Enviar Documentos Necessários para Benefícios

<center>

**Tabela 26 - História de Usuário Enviar Documentos Necessários para Benefícios**

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US22_                   | Enviar Documentos Necessários para Benefícios |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ enviar documentos necessários _para_ o processo de requerimento ou manutenção de benefícios |
| Critérios de Aceitação | - O usuário deve poder anexar documentos em vários formatos (PDF, JPG, PNG) <br> - O sistema deve confirmar o recebimento dos documentos enviados |
| Prioridade             |                                     |

<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>
</center>

### US23 - Recuperação de Senha

<center>

**Tabela 27 - História de Usuário Recuperação de Senha**

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US23_                   | Recuperação de Senha |
| Descrição              | _Eu, como_ usuário do sistema, _desejo_ recuperar minha senha _para_ poder acessar minha conta se eu esquecê-la |
| Critérios de Aceitação | - O usuário deve poder solicitar a recuperação de senha via email <br> - O usuário deve receber um link ou código para redefinir a senha |
| Prioridade             |                                     |

<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>
</center>

### US24 - Solicitar Auxílio-Acidente

<center>

**Tabela 28 - História de Usuário Solicitar Auxílio-Acidente**

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US24_                   | Solicitar Auxílio-Acidente |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ solicitar auxílio-acidente _para_ receber suporte financeiro devido a um acidente |
| Critérios de Aceitação | - O usuário deve poder preencher um formulário específico para auxílio-acidente <br> - O sistema deve confirmar o recebimento da solicitação |
| Prioridade             |                                     |

<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>
</center>

### US25 - Formulário de Auxílio-Acidente

<center>

**Tabela 29 - História de Usuário Preencher Formulário de Auxílio-Acidente**

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| _US25_                   | Preencher Formulário de Auxílio-Acidente |
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ preencher um formulário de auxílio-acidente _para_ descrever o acidente e anexar documentos médicos |
| Critérios de Aceitação | - O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos <br> - O sistema deve validar os campos obrigatórios antes do envio |
| Prioridade             |                                     |

<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>
</center>

### US26 - Acesso de Advogado aos Processos dos Clientes

<center>

**Tabela 30 - História de Usuário Acesso de Advogado aos Processos dos Clientes**

| **ID**                 | **Nome**                                |
| :--------------------- | :-------------------------------------- |
| US21                   | Acesso de Advogado aos Processos dos Clientes      |
| Descrição              | _Eu, como_ advogado, _desejo_ acessar os processos dos meus clientes com a autorização deles _para_ poder acompanhar e gerenciar os casos. |
| Critérios de Aceitação | - O sistema deve permitir que advogados acessem processos com a autorização dos clientes <br> - O sistema deve verificar e registrar a autorização do cliente <br> - O advogado deve poder visualizar, baixar e imprimir os documentos do processo |
| Prioridade             |                                                  |

<font size="3">Autor: [José Filipi](https://github.com/JoseFilipi).</font>

</center>

### US27 - Solicitar e Fornecer Documentos pelo Advogado

<center>

**Tabela 31 - História de Usuário Solicitar e Fornecer Documentos pelo Advogado**

| **ID**                 | **Nome**                                        |
| :--------------------- | :---------------------------------------------- |
| US22                   | Solicitar e Fornecer Documentos pelo Advogado |
| Descrição              | _Eu, como_ advogado, _desejo_ solicitar e fornecer documentos necessários ao processo diretamente ao sistema _para_ agilizar a tramitação dos processos dos meus clientes. |
| Critérios de Aceitação | - O sistema deve permitir que advogados solicitem documentos necessários ao processo <br> - O sistema deve permitir que advogados forneçam documentos diretamente ao processo <br> - O sistema deve notificar os clientes sobre solicitações de documentos |
| Prioridade             |                                                  |

<font size="3">Autor: [José Filipi](https://github.com/JoseFilipi).</font>

</center>

### US28 - Facilidade de Uso e Intuitividade do Aplicativo

<center>

**Tabela 32 - História de Usuário Facilidade de Uso e Intuitividade do Aplicativo**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US28_                   | Facilidade de Uso e Intuitividade do Aplicativo |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo seja fácil de usar e intuitivo, mesmo para usuários com conhecimento técnico limitado, e que minimize o número de cliques para realizar uma tarefa _para_ facilitar a utilização e agilizar o processo de interação |
| Critérios de Aceitação | - O aplicativo deve apresentar uma interface intuitiva, com navegação simples e clara <br> - O número de cliques necessários para realizar uma tarefa deve ser minimizado, priorizando a eficiência e agilidade |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US29 - Compatibilidade com Diferentes Sistemas Operacionais

<center>

**Tabela 33 - História de Usuário Compatibilidade com Diferentes Sistemas Operacionais**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US29_                   | Compatibilidade com Diferentes Sistemas Operacionais |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo seja compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS, Android e computador _para_ garantir que eu possa acessar o aplicativo em qualquer dispositivo que eu utilize |
| Critérios de Aceitação | - O aplicativo deve funcionar corretamente nas versões mais recentes e anteriores dos sistemas operacionais iOS, Android e computador <br> - Todos os recursos do aplicativo devem estar disponíveis em todas as plataformas suportadas |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US30 - Notificação de Atualizações Importantes

<center>

**Tabela 34 - História de Usuário Notificação de Atualizações Importantes**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US30_                   | Notificação de Atualizações Importantes |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ receber notificações sobre atualizações importantes em minhas solicitações e agendamentos via notificações no aplicativo ou por email _para_ ficar atualizado sobre qualquer mudança ou informação relevante |
| Critérios de Aceitação | - O aplicativo deve enviar notificações sobre atualizações importantes relacionadas às solicitações e agendamentos do usuário <br> - O usuário deve poder optar por receber notificações por email ou no aplicativo |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US31 - Criação de Fila Digital para Agendamentos

<center>

**Tabela 35 - História de Usuário Criação de Fila Digital para Agendamentos**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US31_                   | Criação de Fila Digital para Agendamentos |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo crie uma fila digital referente aos agendamentos _para_ organizar e otimizar o processo de marcação de consultas e serviços |
| Critérios de Aceitação | - O aplicativo deve gerenciar uma fila digital de agendamentos, organizando-os por ordem de chegada <br> - Os usuários devem ser notificados quando sua vez na fila chegar |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US32 - Ferramentas de Acessibilidade

<center>

**Tabela 36 - História de Usuário Ferramentas de Acessibilidade**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US32_                   | Ferramentas de Acessibilidade |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo possua ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte _para_ garantir que todas as pessoas, independentemente de suas habilidades ou necessidades, possam utilizar o aplicativo |
| Critérios de Aceitação | - O aplicativo deve oferecer opções de navegação guiada para facilitar a interação para usuários com deficiência visual <br> - Deve ser possível alterar para um modo de alto contraste para usuários com dificuldades de visão |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US33 - Integração com Outros Serviços do Governo

<center>

**Tabela 37 - História de Usuário Integração com Outros Serviços do Governo**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US33_                   | Integração com Outros Serviços do Governo |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo tenha integração com outros serviços do governo _para_ facilitar o acesso e a utilização de diferentes serviços públicos em um único local |
| Critérios de Aceitação | - O aplicativo deve permitir acesso direto a outros serviços do governo, como consulta de informações fiscais e previdenciárias <br> - Deve ser possível realizar transações entre diferentes serviços sem a necessidade de sair do aplicativo |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US34 - Acesso para Profissionais do Legislativo

<center>

**Tabela 38 - História de Usuário Acesso para Profissionais do Legislativo**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US34_                   | Acesso para Profissionais do Legislativo |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo permita outras formas de acesso, como para profissionais do legislativo, para o acompanhamento facilitado de documentos e processos _para_ garantir que todas as partes interessadas tenham acesso às informações relevantes |
| Critérios de Aceitação | - O aplicativo deve oferecer acesso exclusivo para profissionais do legislativo, com permissões específicas para visualização e edição de documentos <br> - Deve ser possível acompanhar o andamento de processos legislativos de forma organizada e intuitiva |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US35 - Suporte em Vários Idiomas

<center>

**Tabela 39 - História de Usuário Suporte em Vários Idiomas**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US35_                   | Suporte em Vários Idiomas |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo ofereça suporte em vários idiomas, especialmente português _para_ facilitar a utilização por usuários de diferentes nacionalidades e idiomas |
| Critérios de Aceitação | - O aplicativo deve disponibilizar a opção de seleção de idioma na interface de usuário <br> - Todas as funcionalidades do aplicativo devem ser totalmente traduzidas para os idiomas suportados |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US36 - Escalabilidade Nacional do Sistema

<center>

**Tabela 40 - História de Usuário Escalabilidade Nacional do Sistema**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US36_                   | Escalabilidade Nacional do Sistema |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o sistema seja capaz de lidar com um grande número de processos e distribuí-los nacionalmente _para_ garantir que o sistema seja escalável e possa atender às demandas de todos os usuários em diferentes regiões do país |
| Critérios de Aceitação | - O sistema deve ser capaz de processar e armazenar um grande volume de dados de forma eficiente <br> - Deve ser possível distribuir os processos e dados de forma equitativa entre diferentes servidores e regiões |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US37 - Eficiência nas Tarefas do Aplicativo

<center>

**Tabela 41 - História de Usuário Eficiência nas Tarefas do Aplicativo**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US37_                   | Eficiência nas Tarefas do Aplicativo |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo seja eficiente, permitindo que eu realize tarefas rápidas em 1-5 minutos e tarefas mais complexas em até 1h20 _para_ otimizar meu tempo e tornar o uso do aplicativo mais produtivo |
| Critérios de Aceitação | - As tarefas comuns do aplicativo devem ser realizadas em um intervalo de tempo entre 1 e 5 minutos <br> - Tarefas mais complexas, como preenchimento de formulários extensos, devem ser concluídas em até 1 hora e 20 minutos |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US38 - Compatibilidade com Tecnologias Assistivas

<center>

**Tabela 42 - História de Usuário Compatibilidade com Tecnologias Assistivas**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US38_                   | Compatibilidade com Tecnologias Assistivas |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo seja compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos _para_ garantir que pessoas com deficiências físicas possam utilizar o aplicativo de forma acessível |
| Critérios de Aceitação | - O aplicativo deve ser totalmente operável através de teclados virtuais e controles por voz <br> - Deve ser possível navegar por todas as funcionalidades do aplicativo utilizando dispositivos de entrada alternativos |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US39 - Garantia de Segurança das Informações Pessoais

<center>

**Tabela 43 - História de Usuário Garantia de Segurança das Informações Pessoais**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US39_                   | Garantia de Segurança das Informações Pessoais |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo garanta a segurança das minhas informações pessoais através de criptografia de dados e autenticação robusta _para_ proteger minha privacidade e confidencialidade |
| Critérios de Aceitação | - Todas as informações pessoais dos usuários devem ser criptografadas durante a transmissão e armazenamento <br> - Deve ser implementada uma autenticação robusta, como autenticação de dois fatores, para garantir o acesso seguro às contas dos usuários |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US40 - Tempo de Resposta do Aplicativo

<center>

**Tabela 44 - História de Usuário Tempo de Resposta do Aplicativo**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US40_                   | Tempo de Resposta do Aplicativo |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo responda a comandos em menos de 3 segundos _para_ garantir uma experiência de uso rápida e eficiente |
| Critérios de Aceitação | - Todas as interações do usuário com o aplicativo, incluindo cliques e entrada de dados, devem ser respondidas em menos de 3 segundos <br> - O tempo de resposta do aplicativo deve ser consistente em diferentes dispositivos e condições de rede |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

</center>

### US41 - Disponibilidade do Aplicativo 24/7

<center>

**Tabela 45 - História de Usuário Disponibilidade do Aplicativo 24/7**

| **ID**                 | **Nome**                                  |
| :--------------------- | :---------------------------------------- |
| _US41_                   | Disponibilidade do Aplicativo 24/7 |                                
| Descrição              | _Eu, como_ usuário do aplicativo, _desejo_ que o aplicativo esteja disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9% _para_ garantir que eu possa acessar o aplicativo sempre que precisar, sem interrupções |
| Critérios de Aceitação | - O aplicativo deve estar disponível para acesso a qualquer momento, sem restrições de horário <br> - A taxa de uptime do aplicativo deve ser monitorada e mantida em 99.9% ou superior |
| Prioridade             |                                     |


<font size="3">Autor: [Amanda Campos](https://github.com/acamposs).</font>

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
|`1.2`|26/05/2024|Adição de histórias do usuário.|[Gabriel Souza](https://github.com/GabrielMS00)|27/05/2024|[José Filipi](https://github.com/JoseFilipi)|
|`1.3`|27/05/2024|Adição de histórias do usuário.|[José Filipi](https://github.com/JoseFilipi)|27/05/2024|[Amanda Campos](https://github.com/acamposs)|
|`1.4`|27/05/2024|Adição de histórias do usuário.|[Amanda Campos](https://github.com/acamposs)|27/05/2024||
