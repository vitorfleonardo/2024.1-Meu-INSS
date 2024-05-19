# Léxicos

## Introdução

O Léxico é uma técnica utilizada para descrever os símbolos de uma linguagem. Os engenheiros de requisitos têm como objetivo identificar frases e símbolos específicos para a aplicação em questão. Cada símbolo é descrito com uma noção e um impacto, onde a noção está relacionada ao símbolo e o impacto à descrição dos efeitos do símbolo na aplicação ou do efeito da aplicação sobre o símbolo.

Para essas descrições, são aplicados os princípios da circularidade e do vocabulário mínimo. O princípio da circularidade estabelece que cada extensão da descrição ou conotação deve referir-se a outros símbolos da linguagem. Além disso, a descrição deve utilizar um conjunto limitado de palavras com significado claro (vocabulário mínimo), evitando termos excessivamente técnicos ou ambíguos.

Léxicos podem ser classificados como verbos, objetos ou estados. Os léxicos do tipo verbo são aqueles cuja noção consiste em um agente que realiza os procedimentos, e cujo impacto é o reflexo da ação do agente. Os do tipo objeto possuem a definição do objeto em questão na noção, além dos outros objetos com os quais se relaciona, e no impacto são descritas as ações que podem ser aplicadas ao objeto. Por fim, os estados apresentam seu significado e quais ações levam a esse estado na noção do léxico, e seu impacto consiste nos estados e ações que podem ocorrer a partir do estado em questão.

## Metodologia

Os léxicos do sistema Meu INSS foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       | Fonte      |
| -------------- | -------- | ------- | ------------------- | ------------------- | ------------------- |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado | Pessoa responsável |

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos (Fonte: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024).</p>
</div>

## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo "Meu INSS". Na Tabela 2, é possível verificar os principais léxicos classificados como objetos que foram identificados no Meu INSS. Esses léxicos incluem elementos como "Benefício", "Solicitação", "Documentação", entre outros. Cada um desses léxicos é descrito detalhadamente, incluindo sua noção, que define o objeto e seus relacionamentos com outros objetos, e seu impacto, que descreve as ações possíveis sobre o objeto. 



|   Léxico     |     Sinônimo      |        Noção        |                    Impacto                    | Classificação |Fonte      |
| :-------------- | :--------------- | :----------------- | ------------------------------------------- | :----------- |:----------- |
| L01 -  Benefício    | Auxílio, Provento | Tipo de Benefício   | O usuário pode visualizar e solicitar benefícios. |    Objeto     | [Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L02 - Solicitação  | Pedido, Requisição| Enviar Solicitação  | O usuário pode enviar, acompanhar e verificar o status das solicitações. |    Objeto     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L03 - Documentação | Arquivo, Prova    | Enviar Documentos   | O usuário pode enviar, visualizar e gerenciar documentos necessários para os processos. |    Objeto     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L04 - Usuário      | Cliente, Assinante| Dados do Usuário    | Informações pessoais do usuário, permitindo personalização e acesso aos serviços. |    Objeto     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L05 - Autenticação     | Login, Acesso| Processo de Acesso| O usuário pode realizar login no sistema para acessar e gerenciar seus benefícios e informações pessoais de forma segura. |    Objeto     |[Johnny Lopes](https://github.com/JohnnyLopess)|
|L06 - Notificação|Alerta, Aviso|Receber Notificações|O usuário recebe notificações sobre atualizações de status das solicitações, novos documentos necessários, ou outras informações importantes relacionadas aos seus benefícios e solicitações.|Objeto|[Johnny Lopes](https://github.com/JohnnyLopess)|
|L17 - Atendimento|Suporte, Assistência|Acesso ao Atendimento|O usuário pode solicitar atendimento para resolver dúvidas ou problemas relacionados aos benefícios e serviços.|Objeto|[José Filipi](https://github.com/JoseFilipi)|
|L18 - Extrato|Sumário, Documento|Emissão de benefícios|O usuário pode gerar um documento que contém informações sobre os benefícios e/ou salário do aposentado.|Objeto|[Paulo Borba](https://github.com/paulohborba)|
|L19 - Saldo | Quantia  | Benefício disponível  | O usuário pode acessar uma visão clara de seus recursos financeiros ou benefícios  |Objeto|[Amanda Campos](https://github.com/acamposs)|



<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2: </b>Léxicos classificados como Objetos (Fonte: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024)</p></font>
</div>


<div align="center">
<font size="3"><p style="text-align: center"></p></font>

</div>

## Verbos

Os léxicos do tipo verbo representam ações ou operações que os usuários podem executar dentro do aplicativo "Meu INSS". Essas ações detalham as funcionalidades acessíveis para os usuários, permitindo interações específicas e operações dentro do aplicativo. Na Tabela 3, é possível conferir os principais léxicos classificados como verbos que foram identificados no Meu INSS. Esses léxicos incluem ações como "Solicitar", "Consultar" e "Simular", cada uma descrevendo uma interação essencial que os usuários podem realizar. Além disso, esses léxicos ajudam a definir os fluxos de uso do aplicativo, orientando os usuários em suas tarefas e melhorando a experiência de navegação e uso dos serviços disponíveis.



|   Léxico    |    Sinônimo    |       Noção       |                         Impacto                          | Classificação |Fonte      |
| :----------- | :------------ | :---------------: | :----------------------------------------------------- | :----------- |:----------- |
| L07 - Solicitar | Pedir, Requerer | Enviar Solicitação | O usuário pode enviar, acompanhar e verificar o status das solicitações. |    Verbo     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L08 - Consultar | Verificar, Checar | Consultar Informações | O usuário pode buscar e visualizar informações relacionadas a benefícios e processos. |    Verbo     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L09 - Simular    | Estimar, Prever, Demonstrar  | Simular Cenários  | O usuário pode simular a questão de sua aposentadoria, o tempo de contribuição ou renda inicial. |    Verbo     |[Bianca Castro](https://github.com/BiancaPatrocinio7) e [Paulo Borba](https://github.com/paulohborba)|
| L10 - Atualizar    | Modificar, Alterar  | Atualizar Dados Pessoais  | O usuário pode atualizar seus dados pessoais, como endereço, contato e informações bancárias. |    Verbo     |[Johnny Lopes](https://github.com/JohnnyLopess)|
|L11 - Rastrear|Monitorar, Acompanhar|Rastrear Solicitação|O usuário pode acompanhar o progresso detalhado das suas solicitações, visualizando cada etapa até a conclusão.|Verbo|[Johnny Lopes](https://github.com/JohnnyLopess)|
|L18 - Avaliar|Analisar, Julgar|Avaliar Situação|O usuário pode avaliar sua situação atual em relação aos benefícios disponíveis, identificando possíveis opções e etapas necessárias.|Verbo|[José Filipi](https://github.com/JoseFilipi)|
|L19 - Enviar  |  Submeter |Enviar Documentos | O usuário pode enviar documentos para processos que requerem documentação adicional  |Verbo|[Amanda Campos](https://github.com/acamposs)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3: </b>Léxicos classificados como Verbos (Fonte: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024)</p></font>

</div>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem ocorrer dentro do aplicativo "Meu INSS". Esses estados representam diversos cenários em que o usuário ou o sistema pode se encontrar durante a interação com o aplicativo. Na Tabela 4, é possível verificar os principais léxicos classificados como estados que foram identificados no Meu INSS. Esses léxicos incluem estados como "Pendente", "Aprovado" e "Em Análise", cada um descrevendo uma condição específica que afeta as ações subsequentes e as opções disponíveis para o usuário. A compreensão desses estados é essencial para navegar eficientemente pelo aplicativo e utilizar suas funcionalidades de forma eficaz.



|   Léxico    |     Sinônimo      |        Noção        |                    Impacto                    | Classificação |Fonte      |
| :--------- | :--------------- | :----------------- | :------------------------------------------- | :----------- |:----------- |
| L12 - Pendente    |   Em Espera       |   Status Pendente   | O usuário está aguardando a aprovação ou análise de uma solicitação.  |    Estado     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L13 - Aprovado    |    Confirmado, Deferido     |   Status Aprovado   | O usuário teve sua solicitação aprovada, permitindo o acesso aos benefícios ou serviços. |    Estado     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L14 - Em Análise  |    Avaliando      |   Status Em Análise | A solicitação do usuário está sendo avaliada, sem uma decisão final ainda tomada.    |    Estado     |[Bianca Castro](https://github.com/BiancaPatrocinio7)|
| L15 - Rejeitado  |    Negado, Recusado, Indeferido      |   Status Rejeitado | O usuário teve sua solicitação rejeitada devido a não conformidade com os requisitos necessários ou por erros no processo de solicitação.    |    Estado     |[Johnny Lopes](https://github.com/JohnnyLopess)|
|L16 - Incompleto |Pendente, Inacabado|Status Incompleto |O usuário é notificado para fornecer informações ou documentos adicionais necessários para o prosseguimento ou conclusão da sua solicitação.|Estado|[Johnny Lopes](https://github.com/JohnnyLopess)|
|L19 - Suspenso|Interrompido, Parado|Status Suspenso|O benefício ou solicitação do usuário foi temporariamente interrompido, podendo ser retomado após a resolução de pendências ou conformidades.|Estado|[José Filipi](https://github.com/JoseFilipi)|
|L20 - Beneficiário|Favorecido, Contemplado|Tipo específico de usuário|Representa um tipo específico de usuário, onde esse está apto a receber os benefícios do INSS.|Estado|[Paulo Borba](https://github.com/paulohborba)|
|L21 - Logado | Autenticado  |  Status Logado |  O usuário passou com sucesso pelo processo de verificação de acesso unificado (gov.br) e obteve acesso ao sistema. |Estado|[Amanda Campos](https://github.com/acamposs)|

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4: </b>Léxicos classificados como Estados (Fonte: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024)</p></font>

</div>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 16 de Maio de 2024.
>
## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0`|16/05/2024|Criação do documento e adição dos lexicos.|[Bianca Castro](https://github.com/BiancaPatrocinio7)|19/05/2024|[Johnny Lopes](https://github.com/JohnnyLopess)|
|`1.1`|19/05/2024|Adição de lexicos e ajustes nas tabelas.|[Johnny Lopes](https://github.com/JohnnyLopess)|19/05/2024|[Paulo Borba](https://github.com/paulohborba)|
|`1.2`|19/05/2024|Adição de novos léxicos |[José Filipi](https://github.com/JoseFilipi)|19/05/2024|[Paulo Borba](https://github.com/paulohborba)|
|`1.3`|19/05/2024|Adição de novos léxicos |[Paulo Borba](https://github.com/paulohborba)|19/05/2024|[Amanda Campos](https://github.com/acamposs)|
|`1.4`|19/05/2024|Adição de novos léxicos |[Amanda Campos](https://github.com/acamposs)|||
