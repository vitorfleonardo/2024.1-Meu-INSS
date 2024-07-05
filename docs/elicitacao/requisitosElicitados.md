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

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a></a>, 2024.</p>

## Tabela dos Requisitos Elicitados versão inicial

<p align="center" > <strong> Tabela 2 - </Strong> Requisitos elicitados versão inicial</font> <gitbr></p>

| Identificador | Tipo | Requisito | Origem | Implementação |
|---------------|------|-----------|--------|---------------|
| RE01          | RF   | O usuário deve realizar o login com o acesso unificado do gov.br. | [BS01](../../elicitacao/brainStorm), [ST02](../../elicitacao/storytelling), [QT01](../../elicitacao/questionario) | Sim |
| RE02          | RF   | O usuário deve receber um termo de uso em seu primeiro acesso. | [BS02](../../elicitacao/brainStorm) | Não |
| RE03          | RF   | O usuário deve ter acesso a documentos legislativos. | [BS03](../../elicitacao/brainStorm) | Não |
| RE04          | RF   | O sistema deve fornecer um serviço de suporte técnico acessível diretamente no aplicativo ou por meio de um número 0800 ou chat de atendimento. | [BS04](../../elicitacao/brainStorm), [BS13](../../elicitacao/brainStorm), [ENT05](../../elicitacao/entrevista), [ST08](../../elicitacao/storytelling), [QT08](../../elicitacao/questionario) | Não |
| RE05          | RF   | O usuário deve conseguir acessar tutoriais para a compreensão e melhor uso do aplicativo. | [BS05](../../elicitacao/brainStorm), [QT08](../../elicitacao/questionario) | Não |
| RE06          | RF   | O usuário deve ser capaz de agendar um horário em uma agência. | [BS06](../../elicitacao/brainStorm) | Sim |
| RE07          | RF   | O usuário deve poder visualizar detalhes de todos os benefícios aos quais tem direito, incluindo valores, datas de pagamento, status e correções. | [BS07](../../elicitacao/brainStorm), [BS11](../../elicitacao/brainStorm), [IT02](../../elicitacao/Introspeccao), [IT05](../../elicitacao/Introspeccao), [ST01](../../elicitacao/storytelling), [ST07](../../elicitacao/storytelling), [ENT10](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario), [QT05](../../elicitacao/questionario) | Sim |
| RE08          | RF   | O usuário deve poder acessar uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria e seus benefícios com base nos seus dados. | [BS08](../../elicitacao/brainStorm), [BS12](../../elicitacao/brainStorm), [IT06](../../elicitacao/Introspeccao), [ENT07](../../elicitacao/entrevista), [ST20](../../elicitacao/storytelling), [QT02](../../elicitacao/questionario), [QT03](../../elicitacao/questionario) | Sim |
| RE09          | RF   | O usuário deve ser capaz de checar o extrato referente ao dinheiro da aposentadoria mensal. | [BS09](../../elicitacao/brainStorm), [ENT11](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario) | Sim |
| RE10          | RF   | O usuário deve ser capaz de acessar um extrato anual de imposto de renda. |  [ENT14](../../elicitacao/entrevista) | Sim |
| RE11          | RF   | O usuário deve ser capaz de acessar um extrato anual de empréstimo. | [ENT15](../../elicitacao/entrevista) | Sim |
| RE12          | RF   | O aplicativo deve permitir o acesso dos usuários através de autenticação biométrica, como impressão digital. | [BS10](../../elicitacao/brainStorm), [QT01](../../elicitacao/questionario) | Sim |
| RE13          | RF   | O aplicativo deve permitir que os usuários acessem e visualizem o Cadastro Nacional de Informações Sociais (CNIS). | [ENT01](../../elicitacao/entrevista) | Sim |
| RE14          | RF   | Deve fornecer ferramentas voltadas para os benefícios dos segurados, incluindo um recurso de pesquisa. | [ENT02](../../elicitacao/entrevista) | Sim |
| RE15          | RF   | Deve permitir o requerimento de benefícios e a atualização do vínculo do CNIS do segurado. | [ENT03](../../elicitacao/entrevista) | Sim |
| RE16          | RF   | Deve fornecer informações sobre pagamentos não recebidos devido a erros e descontos indevidos. | [ENT04](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista) | Não |
| RE17          | RF   | O usuário deve poder atualizar seus dados pessoais, como endereço, telefone, email e localidade. | [ENT06](../../elicitacao/entrevista), [IT07](../../elicitacao/Introspeccao) | Sim |
| RE18          | RF   | O usuário deve ser alertado sobre empréstimos indevidos. | [ENT12](../../elicitacao/entrevista) | Não |
| RE19          | RF   | O usuário deve poder bloquear empréstimos. | [ENT13](../../elicitacao/entrevista) | Não |
| RE20          | RF   | O aplicativo deve permitir que o usuário se autentique usando CPF e senha para acessar informações pessoais e serviços. | [IT01](../../elicitacao/Introspeccao) | Sim |
| RE21          | RF   | O aplicativo deve oferecer a funcionalidade de agendar, reagendar e cancelar perícias médicas. | [IT03](../../elicitacao/Introspeccao) | Sim |
| RE22          | RF   | O usuário deve ser capaz de enviar documentos necessários para o processo de requerimento ou manutenção de benefícios. | [IT04](../../elicitacao/Introspeccao) | Sim |
| RE23          | RF   | O sistema deve oferecer uma opção de recuperação de senha para usuários que a esquecerem. | [ST03](../../elicitacao/storytelling) | Sim |
| RE24          | RF   | O usuário deve conseguir solicitar auxílio-acidente através de um formulário específico. | [ST05](../../elicitacao/storytelling) | Sim |
| RE25          | RF   | O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos. | [ST06](../../elicitacao/storytelling) | Sim |
| RE26          | RF   | O sistema deve permitir que um advogado acesse os processos dos seus clientes com a autorização destes. | [ST09](../../elicitacao/storytelling) | Sim |
| RE27          | RF   | O sistema deve permitir que um advogado solicite e forneça documentos necessários ao processo diretamente ao sistema. | [ST10](../../elicitacao/storytelling), [ST11](../../elicitacao/storytelling) | Sim |
| RE28          | RNF  | O aplicativo deve ser fácil de usar e intuitivo, mesmo para usuários com conhecimento técnico limitado e que minimize o número de cliques para realizar uma tarefa. | [BS16](../../elicitacao/brainStorm),[BS18](../../elicitacao/brainStorm),[ENT16](../../elicitacao/entrevista),[ENT20](../../elicitacao/entrevista), [ENT21](../../elicitacao/entrevista), [IT08](../../elicitacao/Introspeccao) | Não | 
| RE29          | RNF  | O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android e computador. | [BS17](../../elicitacao/brainStorm), [ST12](../../elicitacao/storytelling), [ST19](../../elicitacao/storytelling), [IT15](../../elicitacao/Introspeccao) | Sim |
| RE30          | RNF  | O sistema deve notificar o usuário sobre atualizações importantes em suas solicitações e agendamentos  via notificações no aplicativo ou por email. | [BS17](../../elicitacao/brainStorm), [ST12](../../elicitacao/storytelling),  [QT04](.../../elicitacao/questionario) | Sim |
| RE31          | RNF  | O aplicativo deve criar uma fila digital referente aos agendamentos. | [BS19](../../elicitacao/brainStorm) | Não |
| RE32          | RNF  | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte. | [BS20](../../elicitacao/brainStorm), [IT09](../../elicitacao/Introspeccao), [IT10](../../elicitacao/Introspeccao), [ST13](../../elicitacao/storytelling), [QT06](../../elicitacao/questionario) | Não |
| RE33          | RNF  | O aplicativo deve ter integração com outros serviços do governo. | [BS21](../../elicitacao/brainStorm),  [ST16](../../elicitacao/storytelling) | Sim |
| RE34          | RNF  | O aplicativo deve permitir outras formas de acesso como profissionais do legislativo para o acompanhamento facilitado de documentos e processos. | [BS22](../../elicitacao/brainStorm),  [ST17](../../elicitacao/storytelling) | Sim |
| RE35          | RNF  | O aplicativo deve oferecer suporte em vários idiomas, especialmente português. | [BS25](../../elicitacao/brainStorm), [IT16](../../elicitacao/Introspeccao), [ST18](../../elicitacao/storytelling) | Sim |
| RE36          | RNF  | Deve ser capaz de lidar com um grande número de processos e distribuí-los nacionalmente. | [ENT17](../../elicitacao/entrevista) | Sim |
| RE37          | RNF  | Deve ser eficiente, permitindo que os usuários realizem tarefas rápidas em 1-5 minutos e tarefas mais complexas em até 1h20. | [ENT18](../../elicitacao/entrevista), [ENT22](../../elicitacao/entrevista) | Sim |
| RE38          | RNF  | O aplicativo deve ser compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos. | [IT11](../../elicitacao/Introspeccao), [QT06](../../elicitacao/questionario) | Não |
| RE39          | RNF  | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta. | [BS23](../../elicitacao/brainStorm), [ENT19](../../elicitacao/entrevista), [IT12](../../elicitacao/Introspeccao), [ST15](../../elicitacao/storytelling), [QT07](../../elicitacao/questionario) | Sim |
| RE40          | RNF  | O aplicativo deve responder a comandos do usuário em menos de 3 segundos. | [IT13](../../elicitacao/Introspeccao) | Sim |
| RE41          | RNF  | O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%. | [IT14](../../elicitacao/Introspeccao) | Sim |


<p align="center">Autor(es): <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

## Tabela dos Requisitos Elicitados com versionamento

<p align="center" > <strong> Tabela 3 - </Strong> Requisitos elicitados com versionamento</font> <gitbr></p>

| ID | Tipo | Requisito | Versão | Motivo | Rastreabilidade |
|---------------|------|-----------|--------|---------------|---------------|
| RE01          | RF   | O usuário deve realizar o login com o acesso unificado do gov.br. | 1.0 | - | [BS01](../../elicitacao/brainStorm), [ST02](../../elicitacao/storytelling), [QT01](../../elicitacao/questionario) |
| RE02          | RF   | O usuário deve receber um termo de uso em seu primeiro acesso. | 1.0 | - | [BS02](../../elicitacao/brainStorm) |
| RE03          | RF   | O usuário deve ter acesso a documentos legislativos. | 1.0 | - | [BS03](../../elicitacao/brainStorm) |
| RE04          | RF   | O sistema deve fornecer um serviço de suporte técnico acessível diretamente no aplicativo ou por meio de um número 0800 ou chat de atendimento. | 1.0 | - | [BS04](../../elicitacao/brainStorm), [BS13](../../elicitacao/brainStorm), [ENT05](../../elicitacao/entrevista), [ST08](../../elicitacao/storytelling), [QT08](../../elicitacao/questionario) |
| RE05          | RF   | O usuário deve conseguir acessar tutoriais para a compreensão e melhor uso do aplicativo. | 1.0 | - | [BS05](../../elicitacao/brainStorm), [QT08](../../elicitacao/questionario) |
| RE06          | RF   | O usuário deve ser capaz de agendar um horário em uma agência. | 1.0 | - | [BS06](../../elicitacao/brainStorm) |
| RE07          | RF   | O usuário deve poder visualizar detalhes de todos os benefícios aos quais tem direito, incluindo valores, datas de pagamento, status e correções. | 1.0 | - | [BS07](../../elicitacao/brainStorm), [BS11](../../elicitacao/brainStorm), [IT02](../../elicitacao/Introspeccao), [IT05](../../elicitacao/Introspeccao), [ST01](../../elicitacao/storytelling), [ST07](../../elicitacao/storytelling), [ENT10](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario), [QT05](../../elicitacao/questionario) |
| RE08          | RF   | O usuário deve poder acessar uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria e seus benefícios com base nos seus dados. | 1.0 | - | [BS08](../../elicitacao/brainStorm), [BS12](../../elicitacao/brainStorm), [IT06](../../elicitacao/Introspeccao), [ENT07](../../elicitacao/entrevista), [ST20](../../elicitacao/storytelling), [QT02](../../elicitacao/questionario), [QT03](../../elicitacao/questionario) |
| RE09          | RF   | O usuário deve ser capaz de checar o extrato referente ao dinheiro da aposentadoria mensal. | 1.0 | - | [BS09](../../elicitacao/brainStorm), [ENT11](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario) |
| RE10          | RF   | O usuário deve ser capaz de acessar um extrato anual de imposto de renda. | 1.0 | - |  [ENT14](../../elicitacao/entrevista) |
| RE11          | RF   | O usuário deve ser capaz de acessar um extrato anual de empréstimo. | 1.0 | - | [ENT15](../../elicitacao/entrevista) |
| RE12          | RF   | O aplicativo deve permitir o acesso dos usuários através de autenticação biométrica, como impressão digital. | 1.0 | - | [BS10](../../elicitacao/brainStorm), [QT01](../../elicitacao/questionario) |
| RE13          | RF   | O aplicativo deve permitir que os usuários acessem e visualizem o Cadastro Nacional de Informações Sociais (CNIS). | 1.0 | - | [ENT01](../../elicitacao/entrevista) |
| RE14          | RF   | Deve fornecer ferramentas voltadas para os benefícios dos segurados, incluindo um recurso de pesquisa. | 1.0 | - | [ENT02](../../elicitacao/entrevista) |
| RE15          | RF   | Deve permitir o requerimento de benefícios e a atualização do vínculo do CNIS do segurado. | 1.0 | - | [ENT03](../../elicitacao/entrevista) |
| RE16          | RF   | Deve fornecer informações sobre pagamentos não recebidos devido a erros e descontos indevidos. | 1.0 | - | [ENT04](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista) |
| RE17          | RF   | O usuário deve poder atualizar seus dados pessoais, como endereço, telefone, email e localidade. | 1.0 | - | [ENT06](../../elicitacao/entrevista), [IT07](../../elicitacao/Introspeccao) |
| RE18          | RF   | O usuário deve ser alertado sobre empréstimos indevidos. | 1.0 | - | [ENT12](../../elicitacao/entrevista) |
| RE19          | RF   | O usuário deve poder bloquear empréstimos. | 1.0 | - | [ENT13](../../elicitacao/entrevista) |
| RE20          | RF   | O aplicativo deve permitir que o usuário se autentique usando CPF e senha para acessar informações pessoais e serviços. | 1.0 | - | [IT01](../../elicitacao/Introspeccao) |
| RE21          | RF   | O aplicativo deve oferecer a funcionalidade de agendar, reagendar e cancelar perícias médicas. | 1.0 | - | [IT03](../../elicitacao/Introspeccao) |
| RE22          | RF   | O usuário deve ser capaz de enviar documentos necessários para o processo de requerimento ou manutenção de benefícios. | 1.0 | - | [IT04](../../elicitacao/Introspeccao) |
| RE23          | RF   | O sistema deve oferecer uma opção de recuperação de senha para usuários que a esquecerem. | 1.0 | - | [ST03](../../elicitacao/storytelling) |
| RE24          | RF   | O usuário deve conseguir solicitar auxílio-acidente através de um formulário específico. | 1.0 | - | [ST05](../../elicitacao/storytelling) |
| RE25          | RF   | O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos. | 1.0 | - | [ST06](../../elicitacao/storytelling) |
| RE26          | RF   | O sistema deve permitir que um advogado acesse os processos dos seus clientes com a autorização destes. | 1.0 | - | [ST09](../../elicitacao/storytelling) |
| RE27          | RF   | O sistema deve permitir que um advogado solicite e forneça documentos necessários ao processo diretamente ao sistema. | 1.0 | - | [ST10](../../elicitacao/storytelling), [ST11](../../elicitacao/storytelling) |
| RE28          | RNF  | O aplicativo deve ser fácil de usar e intuitivo, mesmo para usuários com conhecimento técnico limitado e que minimize o número de cliques para realizar uma tarefa. | 1.1 | O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RU001, +In001)](../../modelagem/specSuplementar) |
| RE29          | RNF  | O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android e computador. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RS001)](../../modelagem/specSuplementar) |
| RE30          | RNF  | O sistema deve notificar o usuário sobre atualizações importantes em suas solicitações e agendamentos  via notificações no aplicativo ou por email. | 1.0 | - | [BS17](../../elicitacao/brainStorm), [ST12](../../elicitacao/storytelling),  [QT04](.../../elicitacao/questionario) |
| RE31          | RNF  | O aplicativo deve criar uma fila digital referente aos agendamentos. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RU007, RU008, RU009, RU010, RU011, +In002)](../../modelagem/specSuplementar) |
| RE32          | RNF  | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte. | 1.0 | - | [BS20](../../elicitacao/brainStorm), [IT09](../../elicitacao/Introspeccao), [IT10](../../elicitacao/Introspeccao), [ST13](../../elicitacao/storytelling), [QT06](../../elicitacao/questionario) |
| RE33          | RNF  | O aplicativo deve ter integração com outros serviços do governo. | 1.1 |  O requisito sofreu mudanças após a criação do NFR framework, resultando numa maior clareza do que estava estabelecido. | [RNF05](../../Agil/nfr) |
| RE34          | RNF  | O aplicativo deve permitir outras formas de acesso como profissionais do legislativo para o acompanhamento facilitado de documentos e processos. | 1.0 | - | [BS22](../../elicitacao/brainStorm),  [ST17](../../elicitacao/storytelling) |
| RE35          | RNF  | O aplicativo deve oferecer suporte em vários idiomas, especialmente português. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RS004)](../../modelagem/specSuplementar) |
| RE36          | RNF  | Deve ser capaz de lidar com um grande número de processos e distribuí-los nacionalmente. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RR002, RR003, RR006, RR007, RR008, RP003, RP004, RP006, RP007, RP008, RP009, RS006, +Im002, +Im005)](../../modelagem/specSuplementar) |
| RE37          | RNF  | Deve ser eficiente, permitindo que os usuários realizem tarefas rápidas em 1-5 minutos e tarefas mais complexas em até 1h20. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RU001, RU005, RU006, RU017, RP001, RP002, RP003, +In001,+In003)](../../modelagem/specSuplementar) |
| RE38          | RNF  | O aplicativo deve ser compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RU003, RU004, RU007, RU018, RU019, +In002)](../../modelagem/specSuplementar) |
| RE39          | RNF  | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RR004, +Im001,+Im003,+Im004)](../../modelagem/specSuplementar) |
| RE40          | RNF  | O aplicativo deve responder a comandos do usuário em menos de 3 segundos. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RP001, RP002)](../../modelagem/specSuplementar) |
| RE41          | RNF  | O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%. | 1.1 |  O requisito sofreu mudanças após a criação da especificação suplementar, resultando numa maior clareza do que estava estabelecido. | [ES(RR001, RR006, RR008, RP005)](../../modelagem/specSuplementar) |

<font size="3"><p style="text-align: center">Autores: [Amanda Campos](https://github.com/acamposs), [Bianca Castro](https://github.com/BiancaPatrocinio7), [Gabriel Souza](https://github.com/GabrielMS00), [Johnny Lopes](https://github.com/JohnnyLopess), [José Souza](https://github.com/JoseFilipi), [Paulo Borba](https://github.com/paulohborba), [Vitor Leonardo](https://github.com/vitorfleonardo).</p></font>

## Bibliografia
> </a> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 17 abr. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 17/04/2024  | Versão inicial da pagina de requisitos elicitados. | [Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)|21/04/2024|[José Filipi](https://github.com/JoseFilipi) & [Gabriel](https://github.com/GabrielMS00)| 
| `1.1` | 22/04/2024  | Ajustes na página. | [Johnny Lopes](https://github.com/JohnnyLopess) |22/04/2024|[Paulo Borba](https://github.com/paulohborba)| 
| `1.2` | 24/06/2024  | Adicionando Versionamento dos Requisitos. | [Paulo Borba](https://github.com/JohnnyLopess) |24/06/2024|[Johnny Lopes](https://github.com/JohnnyLopess)| 