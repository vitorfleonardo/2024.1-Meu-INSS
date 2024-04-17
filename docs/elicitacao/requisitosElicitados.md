# Requisitos Elicitados

## Introdução
Nessa página você encontrará uma compilação abrangente dos requisitos funcionais e não funcionais elicitados por meio das técnicas de [brainstorming](../brainStorm), [introspecção](../Introspeccao), [entrevista](../entrevista), [questionário](../questionario) e [Storytelling](../storytelling).

## Metodologia
Na tabela 2 será apresentado os requisitos funcionais e não funcionais elicitados.

Legenda da tabela 2:

- **Identificador**: Código único para cada requisito, usado para identificação e referência rápida, onde RE significa Requisito Elicitado.
- **Tipo**: Qual o tipo de requisito, onde RF significa Requisito Funcional e RNF significa Requisito Não Funcioal.
- **Requisito**: Descrição do que o sistema deve realizar (RF) ou das características que deve possuir (RNF).
- **Implementação**: Estado atual da implementação do requisito, indicando se já foi implementado.
- **Origem**: Esta seção indica a origem de cada requisito, ou seja, a técnica específica utilizada para elicitar o requisito. Na Tabela 1, você encontrará o código correspondente a cada técnica e sua respectiva descrição.

<p align="center" > <strong> Tabela 1 - </Strong> Técnicas de elicitação</font> <gitbr></p>

<center>

|Código|Técnica|
|:--:|:--:|
|BS00|Brainstorming|
|IT00|Introspecção|
|ENT00|Entrevista|
|QT00|Questionário|
|ST00|Storytelling|

</center>

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a></a>, 2024.</p>

<p align="center" > <strong> Tabela 2 - </Strong> Requisitos elicitados</font> <gitbr></p>

| Identificador | Tipo | Requisito | Origem | Implementação |
|---------------|------|-----------|--------|---------------|
| RE01          | RF   | O usuário deve realizar o login com o acesso unificado do gov.br. | BS01, ST02, QT01 | Sim |
| RE02          | RF   | O usuário deve receber um termo de uso em seu primeiro acesso. | BS02 | Não |
| RE03          | RF   | O usuário deve ter acesso a documentos legislativos. | BS03 | Não |
| RE04          | RF   | O sistema deve fornecer um serviço de suporte técnico acessível diretamente no aplicativo ou por meio de um número 0800 ou chat de atendimento. | BS04, BS13, ENT05, ST08, QT08 | Não |
| RE05          | RF   | O usuário deve conseguir acessar tutoriais para a compreensão e melhor uso do aplicativo. | BS05, QT08 | Não |
| RE06          | RF   | O usuário deve ser capaz de agendar um horário em uma agência. | BS06 | Sim |
| RE07          | RF   | O usuário deve poder visualizar detalhes de todos os benefícios aos quais tem direito, incluindo valores, datas de pagamento, status e correções. | BS07, BS11, IT02, IT05, ST01, ST07, ENT10, QT02, QT05 | Sim |
| RE08          | RF   | O usuário deve poder acessar uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria e seus benefícios com base nos seus dados. | BS08, BS12, IT06, ENT07, ST20, QT02, QT03 | Sim |
| RE09          | RF   | O usuário deve ser capaz de checar o extrato referente ao dinheiro da aposentadoria mensal. | BS09, ENT11, ENT08, QT02 | Sim |
| RE10          | RF   | O usuário deve ser capaz de acessar um extrato anual de imposto de renda. | ENT14 | Sim |
| RE11          | RF   | O usuário deve ser capaz de acessar um extrato anual de empréstimo. | ENT15 | Sim |
| RE12          | RF   | O aplicativo deve permitir o acesso dos usuários através de autenticação biométrica, como impressão digital. | BS10, QT01 | Sim |
| RE13          | RF   | O aplicativo deve permitir que os usuários acessem e visualizem o Cadastro Nacional de Informações Sociais (CNIS). | ENT01 | Sim |
| RE14          | RF   | Deve fornecer ferramentas voltadas para os benefícios dos segurados, incluindo um recurso de pesquisa. | ENT02 | Sim |
| RE15          | RF   | Deve permitir o requerimento de benefícios e a atualização do vínculo do CNIS do segurado. | ENT03 | Sim |
| RE16          | RF   | Deve fornecer informações sobre pagamentos não recebidos devido a erros e descontos indevidos. | ENT04, ENT08 | Não |
| RE17          | RF   | O usuário deve poder atualizar seus dados pessoais, como endereço, telefone, email e localidade. | ENT06, IT07 | Sim |
| RE18          | RF   | O usuário deve ser alertado sobre empréstimos indevidos. | ENT12 | Não |
| RE19          | RF   | O usuário deve poder bloquear empréstimos. | ENT13 | Não |
| RE20          | RF   | O aplicativo deve permitir que o usuário se autentique usando CPF e senha para acessar informações pessoais e serviços. | IT01 | Sim |
| RE21          | RF   | O aplicativo deve oferecer a funcionalidade de agendar, reagendar e cancelar perícias médicas. | IT03 | Sim |
| RE22          | RF   | O usuário deve ser capaz de enviar documentos necessários para o processo de requerimento ou manutenção de benefícios. | IT04 | Sim |
| RE23          | RF   | O sistema deve oferecer uma opção de recuperação de senha para usuários que a esquecerem. | ST03 | Sim |
| RE24          | RF   | O usuário deve conseguir solicitar auxílio-acidente através de um formulário específico. | ST05 | Sim |
| RE25          | RF   | O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos. | ST06 | Sim |
| RE26          | RF   | O sistema deve permitir que um advogado acesse os processos dos seus clientes com a autorização destes. | ST09 | Sim |
| RE27          | RF   | O sistema deve permitir que um advogado solicite e forneça documentos necessários ao processo diretamente ao sistema. | ST10, ST11 | Sim |
| RE28          | RF   | O app deve enviar notificações sobre liberação de benefícios, lembretes de datas importantes e agendamento de perícias. | ST12, QT04 | Não |
| RE29          | RNF  | O aplicativo deve ser fácil de usar e intuitivo, mesmo para usuários com conhecimento técnico limitado e que minimize o número de cliques para realizar uma tarefa. | BS16, BS18, ENT16, ENT20, ENT21, IT08 | Não |
| RE30          | RNF  | O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android e computador. | BS15, BS24, IT15, ST14, ST19 | Sim |
| RE31          | RNF  | O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android. | IT15 | Sim |
| RE32          | RNF  | O sistema deve notificar o usuário sobre atualizações importantes em suas solicitações e agendamentos  via notificações no aplicativo ou por email. | BS17, ST12 | Sim |
| RE33          | RNF  | O aplicativo deve criar uma fila digital referente aos agendamentos. | BS19 | Não |
| RE34          | RNF  | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte. | BS20, IT09, IT10, ST13, QT06 | Não |
| RE35          | RNF  | O aplicativo deve ter integração com outros serviços do governo. | BS21, ST16 | Sim |
| RE36          | RNF  | O aplicativo deve permitir outras formas de acesso como profissionais do legislativo para o acompanhamento facilitado de documentos e processos. | BS22, ST17 | Sim |
| RE37          | RNF  | O aplicativo deve oferecer suporte em vários idiomas, especialmente português. | BS25, IT16, ST18 | Sim |
| RE38          | RNF  | Deve ser capaz de lidar com um grande número de processos e distribuí-los nacionalmente. | ENT17 | Sim |
| RE39          | RNF  | Deve ser eficiente, permitindo que os usuários realizem tarefas rápidas em 1-5 minutos e tarefas mais complexas em até 1h20. | ENT18, ENT22 | Sim |
| RE40          | RNF  | O aplicativo deve ser compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos. | IT11, QT06 | Não |
| RE41          | RNF  | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta. | BS23, ENT19, IT12, ST15, QT07 | Sim |
| RE42          | RNF  | O aplicativo deve responder a comandos do usuário em menos de 3 segundos. | IT13 | Sim |
| RE43          | RNF  | O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%. | IT14 | Sim |

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

## Bibliografia
> </a> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 17 abr. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 17/04/2024  | Versão inicial da pagina de requisitos elicitados. | [Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)| || 
