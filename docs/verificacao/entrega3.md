## Introdução

Essa página tem como objetivo verificar os artefatos da Terceira Entrega do [grupo 8](https://requisitos-de-software.github.io/2024.1-Consumidor.gov/).

## Metodologia

A verificação foi realizada utilizando a Tabela 1 como template.

<font size="3"><p style="text-align: center">Tabela 1: Template para verificação</p></font>

<center>

Critérios | Avaliação | Fonte
--|--|--
Pergunta para avaliação| Sim/Não/Incompleto| Página e livro de referência

</center>

#### Comentários
Os comentários relacionados a cada artefato serão detalhados aqui.




### Diagrama de Casos de Uso


<font size="3"><p style="text-align: center">Tabela 1: Verificação do diagrama de casos de uso </p></font>

Critérios  | Sim/Não/Incompleto | Fonte
--------- | ------ | ------
1 - O Diagrama Casos de Uso fornece uma visão geral clara e concisa da finalidade e da funcionalidade do sistema? | Sim | <a id="TEC1" href="#RP1">[1]</a>
2 – Não existem longas cadeias de relacionamentos de inclusão, como quando um caso de uso incluído inclui outros casos de uso? Isso pode obscurecer a compreensão. | Sim | <a id="TEC1" href="#RP1">[1]</a>
3 - Os casos de uso identificados respondem coletivamente por todo o comportamento exigido do sistema? | Sim | <a id="TEC1" href="#RP1">[1]</a>
4 - Você verificou que o modelo de casos de uso não contém comportamento supérfluo (conhecido como "gold-plating")? | Sim | <a id="TEC1" href="#RP1">[1]</a>
5 - Cada caso de uso concreto está associado a pelo menos um Ator, como deveria ser? | Sim | <a id="TEC1" href="#RP1">[1]</a>
6 - Cada ator está associado a pelo menos um caso de uso? | Sim | <a id="TEC1" href="#RP1">[1]</a>
7 - Cada caso de uso incluído torna o modelo mais fácil de entender, implementar e manter? | Sim | <a id="TEC1" href="#RP1">[1]</a>
8 - Não há dois casos de uso com o mesmo nome? | Sim | <a id="TEC1" href="#RP1">[1]</a>
9 - Cada ator tem um nome que descreva efetivamente o papel dessa pessoa? | Sim | <a id="TEC1" href="#RP1">[1]</a>

<font size="3"><p style="text-align: center">Fonte: Grupo 7</p></font>


### Especificação dos casos de Uso

<font size="3"><p style="text-align: center">Tabela 2: Verificação das especificações de casos de uso </p></font>

Critérios  | Sim/Não/Incompleto | Fonte</a>
--------- | ------ | ------
1 - O caso de uso tem um nome exclusivo? | Sim | <a id="TEC1" href="#RP1">[1]</a>
2 - O nome é um verbo + frase nominal (por exemplo, Retirar dinheiro)? | Sim | <a id="TEC1" href="#RP1">[1]</a>
3 - O nome resume com precisão o objetivo principal do caso de uso? | Sim | <a id="TEC1" href="#RP1">[1]</a>
4 - O nome é independente do ator? | Sim | <a id="TEC1" href="#RP1">[1]</a>
5 - Está claro na breve descrição qual é o objetivo principal do caso de uso? | Sim | <a id="TEC1" href="#RP1">[1]</a>
6 - O caso de uso está associado a um ou mais atores? | Sim | <a id="TEC1" href="#RP1">[1]</a>
7 - O ator primário ou ator inicial está definido? | Sim | <a id="TEC1" href="#RP1">[1]</a>
8 - Está claro quem executa as ações no caso de uso? | Sim | <a id="TEC1" href="#RP1">[1]</a>
9 - Todas as informações trocadas entre os atores e o sistema são claramente especificadas? | Sim | <a id="TEC1" href="#RP1">[1]</a>
10 - Cada pré-condição representa um estado tangível do sistema (por exemplo, o caso de uso Sacar Dinheiro para um caixa eletrônico tem como pré-condição que o usuário tenha uma conta)? | Sim | <a id="TEC1" href="#RP1">[1]</a>
11 - Está claro como o caso de uso começa? | Sim | <a id="TEC1" href="#RP1">[1]</a>
12 - O fluxo tem um final definido? | Sim | <a id="TEC1" href="#RP1">[1]</a>
13 - Cada etapa progride em direção à meta? | Sim | <a id="TEC1" href="#RP1">[1]</a>
14 - As etapas estão numeradas corretamente? | Sim | <a id="TEC1" href="#RP1">[1]</a>
15 - Para cada fluxo alternativo, as condições para início do fluxo estão claramente definidas? | Sim | <a id="TEC1" href="#RP1">[1]</a>

<font size="3"><p style="text-align: center">Fonte: Grupo 7</p></font>


<font size="3"><p style="text-align: center">Tabela 2: Verificação das especificações de casos de uso </p></font>

Critérios  | Sim/Não/Incompleto | Fonte</a>
--------- | ------ | ------
1 - Requisitos de usabilidade: Apresenta o tempo de treinamento necessário para que usuários normais e avançados se tornem produtivos em operações específicas? | Sim | <a id="TEC2" href="#RP2">[2]</a>
2 - Requisitos de usabilidade: Apresenta especificação de tempo de tarefas mensuráveis ​​para tarefas típicas? | Sim | <a id="TEC2" href="#RP2">[2]</a>
3 - Requisitos de usabilidade: Apresenta especificação de critérios de acessibilidade? | Sim | <a id="TEC2" href="#RP2">[2]</a>
4 - Requisitos de usabilidade: Disponibilidade: Especificação quanto a porcentagem de tempo disponível <número>%, horas de uso, acesso para manutenção, operações em modo degradado, etc.| Sim | <a id="TEC2" href="#RP2">[2]</a>
5 - Requisitos de confiabilidade: Disponibilidade: Especificação quanto a porcentagem de tempo disponível <número>%, horas de uso, acesso para manutenção, operações em modo degradado, etc.| Sim | <a id="TEC2" href="#RP2">[2]</a>
6 - Requisitos de confiabilidade: Apresenta Tempo médio entre falhas (MTBF)?| Sim | <a id="TEC2" href="#RP2">[2]</a>
7 - Requisitos de confiabilidade: Apresenta Tempo médio de reparo (MTTR)?| Sim | <a id="TEC2" href="#RP2">[2]</a>
8 - Requisitos de Desempenho: Apresenta tempo de resposta para transações? (media ou máximo)| Sim | <a id="TEC2" href="#RP2">[2]</a>
9 - Requisitos de Desempenho: Apresenta taxas de transação? (transações por segundo)| Sim | <a id="TEC2" href="#RP2">[2]</a>
10 - Requisitos de Desempenho: Capacidade? (número de clientes ou transações que o sistema pode acomodar)| Sim | <a id="TEC2" href="#RP2">[2]</a>
11 - Requisitos de Desempenho: Capacidade? 4 - Modo degradação? | Sim | <a id="TEC2" href="#RP2">[2]</a>
12 - Requisitos de Suportabilidade: Padrões de codificação? | Sim | <a id="TEC2" href="#RP2">[2]</a>
13 - Requisitos de Suportabilidade: Bibliotecas? | Sim | <a id="TEC2" href="#RP2">[2]</a>
14 - Requisitos de Suportabilidade: Padrões de nomeações? | Sim | <a id="TEC2" href="#RP2">[2]</a>
15 - Requisitos de restrição de design: linguagens de programação, restrições de arquitetura, componentes adquiridos, bibliotecas de classes, requisitos de processo de software.  | Sim | <a id="TEC2" href="#RP2">[2]</a>
15 - Requisitos de segurança: linguagens de programação, restrições de arquitetura, componentes adquiridos, bibliotecas de classes, requisitos de processo de software. | Sim | <a id="TEC2" href="#RP2">[2]</a>

<font size="3"><p style="text-align: center">Fonte: Grupo 7</p></font>

<font size="3"><p style="text-align: center">Tabela 3: Verificação do  First Things First </p></font>

| Critérios | Sim/Não/Incompleto | Fonte |
|-----------|---------------------|-------|
| 1 - Os objetivos principais do projeto foram identificados? | Sim | <a id="TEC1" href="#RP1">p.313</a> |
| 2 - Os objetivos foram priorizados de acordo com a técnica "First Things First"? | Sim | <a id="TEC1" href="#RP1">p.314</a> |
| 3 - Os critérios para priorização dos objetivos foram definidos e documentados? | Sim | <a id="TEC1" href="#RP1">p.313</a> |
| 4 - A equipe de desenvolvimento foi envolvida no processo de priorização? | Sim | <a id="TEC1" href="#RP1">p.313</a> |
| 5 - As decisões de priorização foram validadas com os stakeholders? | Sim | <a id="TEC1" href="#RP1">p.313</a> |
| 6 - Foi criada uma lista de tarefas baseada nos objetivos priorizados? | Não | <a id="TEC1" href="#RP1">p.313</a> |
| 7 - A tabela possui os pesos relativos e sua justificativa? | Sim | <a id="TEC1" href="#RP1">p.314</a> |
| 8 - Participação dos representantes dos desenvolvedores na classificação dos custos e dos riscos? | Sim | <a id="TEC1" href="#RP1">p.313</a> |

<font size="3"><p style="text-align: center">Fonte: Grupo 7</p></font>


## Referências Bibliográficas
> <a id="RP1" href="#TEC1">1.</a> Universidade Tecnológica de la Mixteca. Checklist: Use case. Disponível em: [https://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/checklists/use_case_C5362874.html](https://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/checklists/use_case_C5362874.html). Acesso em: 06 de junho de 2024.
> <a id="RP2" href="#TEC2">1.</a> USDA Farm Service Agency. Supplementary Specification. Disponível em: [https://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/checklists/use_case_C5362874.html](https://www.utm.mx/~caff/doc/OpenUPWeb/openup/guidances/checklists/use_case_C5362874.html). Acesso em: 06 de junho de 2024.
><a id="RP1" href="#TEC1">1.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf).
><a id="RP2" href="#TEC2">2.</a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Centro de Informática da Universidade Federal de Pernambuco, [S. l.], 2019. Disponível em: [https://attena.ufpe.br/bitstream/123456789/34150/1/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://attena.ufpe.br/bitstream/123456789/34150/1/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 10 jun. 2024.
><a id="RP3" href="#TEC3">3.</a> Chung, L., Nixon, B. A., Yu, E., & Mylopoulos, J. (2000). Non-Functional Requirements in Software Engineering. Springer. Disponível em: [https://link.springer.com/book/10.1007/978-1-4615-5269-7](https://link.springer.com/book/10.1007/978-1-4615-5269-7). Acesso em : 30 mai. 2024.


## Histórico de Versões

| Versão | Data | Descrição | Autor(es) | Data da revisão | Revisor(es) |
| :--: | :--: | :--: | :--: | :--: | :--: |
|`1.0` | 10/06/2024 | Criação do documento. |[José Filipi](https://github.com/JoseFilipi) | 10/06/2024| [Bianca Castro](https://github.com/BiancaPatrocinio7)
|`1.1` | 10/06/2024 | Adicionando a verificaçãdo do First Things First, casos de uso e especificação suplementar |[Bianca Castro](https://github.com/BiancaPatrocinio7) & [Vitor Feijó](https://github.com/vitorfleonardo) & [Johnny Lopes](https://github.com/JohnnyLopess)| 10/06/2024| [José Filipi](https://github.com/JoseFilipi)

