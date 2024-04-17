# Three-level scale

## Introdução

A técnica de priorização Three-level scale ou escala de três níveis, é uma técnica que envolve categorizar os requisitos em três categorias, onde se possui Alta, média e baixa prioridade.

## Metodologia

Como descrito por Wiegers e Beatty<a id="TEC1" href="#RP1"> [1]</a> essas três categorias são:

- **Alta prioridade:** Os requisitos dessa categoria são extremamente importantes e urgentes, ou seja, os clientes e usuários precisam deles presente na próxima release. Existe também uma alternativa onde um requisito é categorizado como de alta prioridade por um contrato ou acordo. Se o requisito pode esperar a implementação sem prejudicar o andamento do projeto, então ele não se encaixa nessa categoria.

- **Média prioridade:** São requisitos importantes mas que não são urgentes, ou seja, mesmo precisando ser implementados eles podem esperar uma próxima release.

- **Baixa prioridade:** São requisitos que não são nem importantes e nem urgentes, podendo ser adiados e nem implemntados se for o caso.

Também existe uma quarta categoria que diz a respeito de requisitos que podem parecer de extrema importância para o cliente, mas que no fim são completamente desnecessários para o funcionamento do projeto.

### Participantes
Um usuário do aplicativo foi convidado para participar de uma reunião online, durante a qual foi introduzida a técnica do three level scale (escala de três níveis). Ele foi solicitado a fornecer feedback respondendo a uma tabela que delineava os requisitos para uma página onde a técnica three level scale seria aplicada.A Tabela 1 contém os nomes dos participantes da reunião.

<p align="center" > <strong> Tabela 1 - </Strong> Participante da reunião</font> <gitbr></p>

<center>

|Participante|Função|
|:--:|:--:|
|[Paulo Borba](https://github.com/paulohborba)|Desenvolvedor|
|Neys Mendes Rossi de Borba|Usuário|

</center>

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

## Lista de Requisitos Priorizados

### Legenda da Tabela de Requisitos

- **Identificador**: Código único para cada requisito, usado para identificação e referência rápida, onde RE significa Requisito Elicitado.
- **Requisito**: Descrição do que o sistema deve realizar (RF) ou das características que deve possuir (RNF).
- **Tipo**: Qual o tipo de requisito, onde RF significa Requisito Funcional e RNF significa Requisito Não Funcioal.
- **Prioridade**: Prioridade dada pelo usuário, Alta ou Média ou Baixa.

### Requisitos
<p align="center" > <strong> Tabela 2 - </Strong> Aplicação da técnica de priorização Three-level scale</font> <gitbr></p>

| Identificador | Tipo | Requisito                                                                                                                                                                             | Prioridade |
|---------------|------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RE01          | RF   | O usuário deve realizar o login com o acesso unificado do gov.br.                                                                                                                     | Alta       |
| RE02          | RF   | O usuário deve receber um termo de uso em seu primeiro acesso.                                                                                                                        | Alta       |
| RE03          | RF   | O usuário deve ter acesso a documentos legislativos.                                                                                                                                   | Alta       |
| RE04          | RF   | O sistema deve fornecer um serviço de suporte técnico acessível diretamente no aplicativo ou por meio de um número 0800 ou chat de atendimento.                                      | Alta       |
| RE05          | RF   | O usuário deve conseguir acessar tutoriais para a compreensão e melhor uso do aplicativo.                                                                                              | Alta       |
| RE06          | RF   | O usuário deve ser capaz de agendar um horário em uma agência.                                                                                                                        | Alta       |
| RE07          | RF   | O usuário deve poder visualizar detalhes de todos os benefícios aos quais tem direito, incluindo valores, datas de pagamento, status e correções.                                     | Alta       |
| RE08          | RF   | O usuário deve poder acessar uma funcionalidade para simular o tempo de contribuição e estimar a aposentadoria e seus benefícios com base nos seus dados.                             | Alta       |
| RE09          | RF   | O usuário deve ser capaz de checar o extrato referente ao dinheiro da aposentadoria mensal.                                                                                          | Alta       |
| RE10          | RF   | O usuário deve ser capaz de acessar um extrato anual de imposto de renda.                                                                                                             | Alta       |
| RE11          | RF   | O usuário deve ser capaz de acessar um extrato anual de empréstimo.                                                                                                                   | Média      |
| RE12          | RF   | O aplicativo deve permitir o acesso dos usuários através de autenticação biométrica, como impressão digital.                                                                          | Alta       |
| RE13          | RF   | O aplicativo deve permitir que os usuários acessem e visualizem o Cadastro Nacional de Informações Sociais (CNIS).                                                                    | Alta       |
| RE14          | RF   | Deve fornecer ferramentas voltadas para os benefícios dos segurados, incluindo um recurso de pesquisa.                                                                                | Alta       |
| RE15          | RF   | Deve permitir o requerimento de benefícios e a atualização do vínculo do CNIS do segurado.                                                                                           | Alta       |
| RE16          | RF   | Deve fornecer informações sobre pagamentos não recebidos devido a erros e descontos indevidos.                                                                                        | Alta       |
| RE17          | RF   | O usuário deve poder atualizar seus dados pessoais, como endereço, telefone, email e localidade.                                                                                      | Alta       |
| RE18          | RF   | O usuário deve ser alertado sobre empréstimos indevidos.                                                                                                                               | Alta       |
| RE19          | RF   | O usuário deve poder bloquear empréstimos.                                                                                                                                             | Alta       |
| RE20          | RF   | O aplicativo deve permitir que o usuário se autentique usando CPF e senha para acessar informações pessoais e serviços.                                                               | Média      |
| RE21          | RF   | O aplicativo deve oferecer a funcionalidade de agendar, reagendar e cancelar perícias médicas.                                                                                        | Alta       |
| RE22          | RF   | O usuário deve ser capaz de enviar documentos necessários para o processo de requerimento ou manutenção de benefícios.                                                               | Alta       |
| RE23          | RF   | O sistema deve oferecer uma opção de recuperação de senha para usuários que a esquecerem.                                                                                             | Média      |
| RE24          | RF   | O usuário deve conseguir solicitar auxílio-acidente através de um formulário específico.                                                                                              | Alta       |
| RE25          | RF   | O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos.                                                                         | Média      |
| RE26          | RF   | O sistema deve permitir que um advogado acesse os processos dos seus clientes com a autorização destes.                                                                              | Alta       |
| RE27          | RF   | O sistema deve permitir que um advogado solicite e forneça documentos necessários ao processo diretamente ao sistema.                                                                 | Alta       |
| RE28          | RNF  | O aplicativo deve ser fácil de usar e intuitivo, mesmo para usuários com conhecimento técnico limitado e que minimize o número de cliques para realizar uma tarefa.                    | Alta       |
| RE29          | RNF  | O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android e computador.                                                      | Alta       |
| RE30          | RNF  | O sistema deve notificar o usuário sobre atualizações importantes em suas solicitações e agendamentos  via notificações no aplicativo ou por email.                                      | Alta       |
| RE31          | RNF  | O aplicativo deve criar uma fila digital referente aos agendamentos.                                                                                                                   | Alta       |
| RE32          | RNF  | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte.                                      | Alta       |
| RE33          | RNF  | O aplicativo deve ter integração com outros serviços do governo.                                                                                                                        | Média      |
| RE34          | RNF  | O aplicativo deve permitir outras formas de acesso como profissionais do legislativo para o acompanhamento facilitado de documentos e processos.                                         | Alta       |
| RE35          | RNF  | O aplicativo deve oferecer suporte em vários idiomas, especialmente português.                                                                                                          | Média      |
| RE36          | RNF  | Deve ser capaz de lidar com um grande número de processos e distribuí-los nacionalmente                                                                                                 | Alta       |
| RE37          | RNF  | Deve ser eficiente, permitindo que os usuários realizem tarefas rápidas em 1-5 minutos e tarefas mais complexas em até 1h20.                                                          | Alta       |
| RE38          | RNF  | O aplicativo deve ser compatível com tecnologias assistivas, como teclados virtuais, controle por voz e dispositivos de entrada alternativos                                              | Alta       |
| RE39          | RNF  | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta.                                                   | Alta       |
| RE40          | RNF  | O aplicativo deve responder a comandos do usuário em menos de 3 segundos.                                                                                                               | Baixa      |


<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

## Gravação

No vídeo 1 localiza-se a gravação da reunião.

<div align="center">
<p style="text-align: center"><a href="https://www.youtube.com/watch?v=oyPoQDCfNsk" target="blanket"><b>Vídeo 1:</b>Reunião Three Level Scale</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/oyPoQDCfNsk?si=WIdCn1U03bmqP26M" title="Reunião 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<p align="center">Fonte: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a> & <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>
</div >

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> Software Requirements Third Edition. In: WIEGERS, Karl E.; BEATTY, Joy. Software Requirements. 3. ed. [S. l.]: Microsoft Press, 2013. cap. 16, p. 313-329. ISBN 0735679665. Disponível em: [https://aprender3.unb.br/pluginfile.php/2844990/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf](https://aprender3.unb.br/pluginfile.php/2844990/mod_resource/content/2/PriorizaA%CC%83%C2%A7A%CC%83%C2%A3o%20de%20Req.pdf). Acesso em: 14 abr. 2024

## Bibliografia
> </a>  Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 16 abr. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 09/04/2024  | Versão inicial da página de Three level. | [Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)| || 
| `1.1` | 17/04/2024  | Adição da tabela de requisitos. | [Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)| || 