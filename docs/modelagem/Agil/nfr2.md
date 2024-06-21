## Introdução

Segundo Chung et al. (2000), criador do NFR framework, “foi adotado por propor uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornecer uma rica representação para expressar esses requisitos, além de suas relações e correlações” (Silva Reinaldo, 2019, p. 30,).

## Metodologia

<strong> 1. Identificar NFRs </strong> <br />
    Nessa etapa, identifica-se os principais requisitos não funcionais que o sistema específico em desenvolvimento deve atender  e constrói-se um gráfico inicial de interdependência de objetivos flexíveis - Softgoal interdependency graph (Chung et al, 2000, p. 19). Para isso, foi desenvolvida, de maneira anterior, uma Taxonomia, visando "organizar e entender os Requisitos-Não Funcionais" (Silva Reinaldo, 2019, p. 44). 

<strong> 2. Decomposição de softgoals NFRs </strong> <br />
    Decompõe-se cada um dos softgoals em componentes menores (sub-softgoals) em busca de requisitos mais específicos a fim de satisfazer o softgoal de mais alto nível, hierarquicamente. Em seguida, cria-se um Soaftgoal interdependency graph com a união dos softgoals NFR encontrados.

<strong> 3. Identificar operacionalizações e priozizações </strong> <br />
    Técnicas de desenvolvimento são opracionalizações para os NFR softgoals. Nessa etapa, busca-se fornecer meios de se alcançar os softgoals elicitados, enquanto que se prioriza também.

<strong> 3. Inserir afirmações de design </strong> <br />
    Uma importante premissa do Framework NFR é que as decisões de design devem apresentar bons argumentos ou desgin racional. Essa atapa auxilia a próxima, onde são selecionadas alternativas para solução do desenvolvimento do aplicativo (Chung et al, 2000, p. 33).

<strong> 5. Seleção entre alternativas </strong> <br />
    O processo de refinamento continua até que o desenvolvedor considere que as soluções possíveis para o sistema alvo sejam suficientemente detalhadas e que nenhuma outra alternativa precise ser considerada (Chung et al, 2000, p. 35). Sendo assim, escolhe-se dentre as possíveis operacionalizações para se produzir o aplicativo.

## Identificar NFRs

Como citado anteriormente, em busca de organizar e entender os Requisitos-Não funcionais, foi desenvolvida uma Taxonomia, representada na figura 1. Segundo USMAN et al, 2017, "é um esquema de classificação, que permite descrição de termos e suas relações no contexto de uma área de conhecimento" (Silva Reinaldo, 2019, p. 44). Em seu desenvolvimento, aproveitou-se da metodologia FURPS+, utilizada na [especificação suplementar](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/specSuplementar/) e [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/) anteriormente. 

<p align="center" > <strong> Figura 1:</Strong> Taxonomia de Requisitos Não-Funcionais.</font></p>
<iframe frameborder="0" style="width:100%;height:350px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1giNn5-kisipsC4Gp5FalpvZBydIiVLhj%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [José Filipi](https://github.com/JoseFilipi) & [Vitor Leonardo](https://github.com/vitorfleonardo), 2024.</p></font>

Utilizando o NFR Framework e a Taxonomia desenvolvida, representada na figura 1, constrói-se um Gráfico inicial de interdependência de softgoal com softgoals NFRs, exibido na figura 2. Estes são requisitos não funcionais principais, tratados como softgoals, para o desenvolvimento do aplicavo Meu INSS. Isto é, são objetivos que precisam ser esclarecidos, desambiguados, priorizados, elaborados, etc (Chung et al, 2000, p. 20).

<p align="center" > <strong> Figura 2:</Strong> Gráfico inicial de interdependência de softgoal com softgoals NFRs. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=softgoals.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1R_2RmflaaBlniUi0GrhkMzEdW-ZZCRli%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [José Filipi](https://github.com/JoseFilipi) & [Vitor Leonardo](https://github.com/vitorfleonardo), 2024.</p></font>

## Decomposição de softgoals NFRs 

Em seguida, os oito softgoals representados na Figura 2 são decompostos individualmente, conforme mostrado nas Figuras 3, 4, 5, 6, 7, 8, 9 e 10.

Além disso, são criados cartões de especificação, que têm como objetivo ilustrar os Requisitos Não-Funcionais (RNFs) no contexto real de um sistema embarcado. A Tabela 1 apresenta o formato que deve ser seguido para a criação de um cartão de especificação.

<p align="center" > <strong> Tabela 1 -</Strong> Modelo para o cartão de especificação </font></p>

<center>

| Nº Requisito: um número sequencial (classificação) | Classificação: Classificação do RNF conforme hierarquia do catálogo. |
|----------------------------------|----------------------------|
| **Descrição:**| Descrição única do significado do requisito.  |
| **Justificativa:**| Justificativa sobre a criação do requisito.|
| **Origem do Requisito:**| Origem do requisito. |
| **Critério de Aceitação:**| Métrica do requisito que possa ser testada e que deve ser satisfeita. |
| **Dependências:**| Requisitos relacionados a este. |
| **Prioridade:**| Um número usado para decidir a importância relativa deste requisitos entre os outros RNFs (varia 1 e 10). A priordade mínima é 1 e a máxima é 10.|
| **Conflitos:**| Requisitos conflitantes com este. |
| **História:**| Data de criação e modificações. |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Johnny Lopes](https://github.com/JohnnyLopess), 2024.</p></font>

### NFR01: Usabilidade

<p align="center" > <strong> Figura 3:</Strong> Decomposição do softgoal Usabilidade em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Vitor Leonardo](https://github.com/vitorfleonardo), 2024.</p></font>

<p align="center" > <strong> Tabela 2:</Strong> Cartão de especificação NFR01 </font></p>

<center>

| Nº Requisito: 1 (NFR01) | Classificação: Usabilidade |
|----------------------------------|-----------------------------|
| **Descrição:** | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte. |
| **Justificativa:** | As ferramentas de acessibilidade são essenciais para garantir que todos os usuários, incluindo aqueles com deficiência visual ou dificuldades motoras, possam utilizar o aplicativo de forma eficiente e confortável. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve fornecer navegação guiada, opções de alto contraste, comandos por voz e ajuste de tamanho de fonte que possam ser testados e utilizados por pessoas com deficiências. |
| **Dependências:** | Padrões de acessibilidade, SDKs de acessibilidade dos sistemas operacionais |
| **Prioridade:** | 1,50 |
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024|

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Vitor Leonardo](https://github.com/vitorfleonardo), 2024.</p></font>

### NFR02: Confiabilidade

<p align="center" > <strong> Figura 4:</Strong> Decomposição do softgoal Confiabilidade em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=N8aEGRbs_lslEPsWCd_S&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Vitor Leonardo](https://github.com/vitorfleonardo), 2024 & Chung et al, 2000, p. 24.</p></font>


<p align="center" > <strong> Tabela 3:</Strong> Cartão de especificação NFR02 </font></p>

<center>

| Nº Requisito: 2 (NFR02) | Classificação: Confiabilidade |
|----------------------------------|-------------------------------|
| **Descrição:**| O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%. |
| **Justificativa:**| Alta disponibilidade é essencial para garantir que os usuários possam acessar o aplicativo a qualquer momento, aumentando a confiança e satisfação dos usuários. |
| **Origem do Requisito:**| Projetista de Software |
| **Critério de Aceitação:**| O sistema deve ser monitorado continuamente e deve manter um uptime de 99.9% ou superior, calculado mensalmente. |
| **Dependências:**| Infraestrutura de servidores, rede de distribuição de conteúdo, manutenção e monitoramento contínuos |
| **Prioridade:**| 2,45|
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024 |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Vitor Leonardo](https://github.com/vitorfleonardo), 2024.</p></font>

### NFR03: Desempenho

<p align="center" > <strong> Figura 5:</Strong> Decomposição do softgoal Desempenho em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=h3lqgF3nMLwTmG0sS_oK&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024 & Chung et al, 2000, p. 24.</p></font>

<p align="center" > <strong> Tabela 4:</Strong> Cartão de especificação NFR03. </font></p>

<center>

| Nº Requisito: 3 (NFR03) | Classificação: Desempenho |
|----------------------------------|-----------------------------|
| **Descrição:** | O aplicativo deve responder a comandos do usuário em menos de 3 segundos. |
| **Justificativa:** | Um tempo de resposta rápido é essencial para garantir uma experiência de usuário satisfatória e eficiente. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve ser testado para garantir que todas as respostas a comandos do usuário sejam executadas em menos de 3 segundos. |
| **Dependências:** | Desempenho do servidor, otimização do código, infraestrutura de rede |
| **Prioridade:**  | 1,00|
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024 |

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Bianca Castro](https://github.com/BiancaPatrocinio7), 2024.</p></font>

</center>

### NFR04: Físico

<p align="center" > <strong> Figura 7:</Strong> Decomposição do softgoal Interface em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=i6-boJ5dRXbtqCUiacrp&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Gabriel Souza](https://github.com/GabrielMS00), 2024.</p></font>

<p align="center" > <strong> Tabela 5:</Strong> Cartão de especificação NFR04. </font></p>

<center>

| Nº Requisito: 4 (NFR04) | Classificação: Físico |
|----------------------------------|-----------------------------|
| **Descrição:** | - |
| **Justificativa:** | - |
| **Origem do Requisito:** | - |
| **Critério de Aceitação:** | - |
| **Dependências:** | -|
| **Prioridade:**  | -|
| **Conflitos:** | - |
| **História:** | - |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Gabriel Souza](https://github.com/GabrielMS00), 2024.</p></font>

### NFR05: Interface

<p align="center" > <strong> Figura 7:</Strong> Decomposição do softgoal Interface em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=FWwiJ7CwBqTNnmuijmUT&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [José Filipi](https://github.com/JoseFilipi), 2024.</p></font>

<p align="center" > <strong> Tabela 6:</Strong> Cartão de especificação NFR05. </font></p>

<center>

| Nº Requisito: 5 (NFR05) | Classificação: Interface |
|----------------------------------|-----------------------------|
| **Descrição:** | - |
| **Justificativa:** | - |
| **Origem do Requisito:** | - |
| **Critério de Aceitação:** | - |
| **Dependências:** | -|
| **Prioridade:**  | -|
| **Conflitos:** | - |
| **História:** | - |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [José Filipi](https://github.com/JoseFilipi), 2024.</p></font>

### NFR06: Design

<p align="center" > <strong> Figura 8:</Strong> Decomposição do softgoal Design em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=SMal-kwEujG9ZFxwmq8E&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Amanda Campos](https://github.com/acamposs), 2024.</p></font>

<p align="center" > <strong> Tabela 7:</Strong> Cartão de especificação NFR06. </font></p>

<center>

| Nº Requisito: 6 (NFR06) | Classificação: Design |
|----------------------------------|-----------------------------|
| **Descrição:** | - |
| **Justificativa:** | - |
| **Origem do Requisito:** | - |
| **Critério de Aceitação:** | - |
| **Dependências:** | -|
| **Prioridade:**  | -|
| **Conflitos:** | - |
| **História:** | - |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Amanda Campos](https://github.com/acamposs), 2024.</p></font>


### NFR07: Implementação

<p align="center" > <strong> Figura 9:</Strong> Decomposição do softgoal Implementação em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=Ffid3B1iIyGyJCZ9zvo6&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Johnny Lopes](https://github.com/JohnnyLopess), 2024.</p></font>

<p align="center" > <strong> Tabela 8:</Strong> Cartão de especificação NFR07. </font></p>

<center>

| Nº Requisito: NFR07 ([RF39](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/)) | Classificação: Implementação |
|----------------------------------|-----------------------------|
| **Descrição:** | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta. |
| **Justificativa:** | A proteção das informações pessoais é crucial para manter a confiança dos usuários e cumprir com regulamentações de privacidade e segurança de dados. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve implementar e ser testado para garantir a criptografia de dados e métodos de autenticação robustos, conforme padrões de segurança. |
| **Dependências:** |Protocolos de criptografia, serviços de autenticação, regulamentos de segurança de dados |
| **Prioridade:** | 10|
| **Conflitos:** | Nenhum |
| **História:** | 21/06/2024 |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Johnny Lopes](https://github.com/JohnnyLopess), 2024.</p></font>


### NFR08: Suportabilidade

<p align="center" > <strong> Figura 10:</Strong> Decomposição do softgoal Suportabilidade em requisitos não funcionais mais específicos. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=Ps6S_oxP5CK2rWNoZUKd&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - [Paulo Borba](https://github.com/paulohborba), 2024.</p></font>

<p align="center" > <strong> Tabela 9:</Strong> Cartão de especificação NFR08. </font></p>

<center>

| Nº Requisito: 8 (NFR08) | Classificação: Implementação |
|----------------------------------|-----------------------------|
| **Descrição:** | - |
| **Justificativa:** | - |
| **Origem do Requisito:** | - |
| **Critério de Aceitação:** | - |
| **Dependências:** | -|
| **Prioridade:**  | -|
| **Conflitos:** | - |
| **História:** | - |

</center>

<font size="3"><p style="text-align: center"><b>Fonte</b> - [Paulo Borba](https://github.com/paulohborba), 2024.</p></font>

### Softgoal Interdependency Graph

<p align="center" > <strong> Figura 11:</Strong> Softgoals NFR do Meu INSS. </font></p>
<iframe frameborder="0" style="width:100%;height:398px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=ILsYYq8ouLFGnrmj7oqu&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - grupo 7, 2024.</p></font>

## Operacionalização e priozição

Enquanto que o processo de refinamento até agora fornece interpretações mais especificas do que os NFRs iniciais, como "Usabilidade", significam, isso não fornece ainda meios para realmente alcançar o requisito. Em algum ponto, quando os requisitos funcionais forem suficientemente refinados, será possível identificar possíveis técnicas de desenvolvimento para alcançar tais requisitos (Chung et al, 2000, p. 27). 

<p align="center" > <strong> Figura 12:</Strong> Identificação de operacionalizações e priorizações. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=NYTGmn3TqblnIOBQkdR6&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<<font size="3"><p style="text-align: center"><b>Fonte</b> - grupo 7, 2024.</p></font>

## Afirmações de design
Foca-se, aqui, na inserção de calim softgoals, ou seja, o terceiro tipo de softgoal, em que se anexa aos links de interdependência, dessa forma, argumentando a relação entre os concetados. Os claim softgoals são representadas como nuvens tracejadas no gráfico de interdependência de metas flexíveis. Seus vínculos de interdependência representam os argumentos (Chung et al, 2000, p. 33 e 35). 

<p align="center" > <strong> Figura 13:</Strong> Inserção de afirmações de design. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=bL-RBclApFra9mjxN7nl&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - grupo 7, 2024.</p></font>

## Seleção entre alternativas
Nessa etapa, foram escolhidas as melhoras alteranativas, pelo desenvolvedores. Respretentadas na imagem 14.

<p align="center" > <strong> Figura 14:</Strong> Seleção das alternativas. </font></p>
<iframe frameborder="0" style="width:100%;height:500px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&page-id=KlURLMkGPNRzwtXcyA2Y&title=Usabilidade.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1nD_FrQ6lV77Rs1sjp3uvCtf7IaTTWK1V%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Fonte</b> - grupo 7, 2024.</p></font>

## Bibliografia

> </a> Islam, S.M. Zahidul. “What are some ways to reduce network usage in a mobile app?” MUO, 15 de março de 2017. Disponível em: [https://www.linkedin.com/advice/3/what-some-ways-reduce-network-usage-mobile-app-jjo1e](https://www.linkedin.com/advice/3/what-some-ways-reduce-network-usage-mobile-app-jjo1e). Acesso em : 30 mai. 2024.

> </a> Mwaura, Waweru. “Making HTTP requests with Axios.” CircleCI, 6 de fevereiro de 2023. Disponível em: [https://circleci.com/blog/making-http-requests-with-axios/](https://circleci.com/blog/making-http-requests-with-axios/). Acesso em : 30 mai. 2024.

> </a> Ipsen, Adam. “Backup Software vs Data Recovery: Pros and Cons.” Cyber Resilience Blog, 9 de novembro de 2016. Disponível em: [https://www.backupassist.com/blog/backup-software-vs-data-recovery-pros-and-cons](https://www.backupassist.com/blog/backup-software-vs-data-recovery-pros-and-cons). Acesso em : 30 mai. 2024.

## Referências Bibliográficas
> </a> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Centro de Informática da Universidade Federal de Pernambuco, [S. l.], 2019. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 27 mai. 2024.

> </a> Chung, L., Nixon, B. A., Yu, E., & Mylopoulos, J. (2000). Non-Functional Requirements in Software Engineering. Springer. Disponível em: [https://link.springer.com/book/10.1007/978-1-4615-5269-7](https://link.springer.com/book/10.1007/978-1-4615-5269-7). Acesso em : 30 mai. 2024.


## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0`|27/05/2024|Criação do documento|[José Filipi](https://github.com/JoseFilipi) & [Vitor Feijó](https://github.com/vitorfleonardo) |27/05/2024|[Paulo Borba](https://github.com/paulohborba)|
|`1.1`|30/06/2024|Metodologia & Softgoal 1 e 2|[Vitor Feijó](https://github.com/vitorfleonardo) |30/05/2024|[Paulo Borba](https://github.com/paulohborba)|
|`1.2`|30/05/2024|Softgoal 3|[Bianca Castro](https://github.com/BiancaPatrocinio7)|30/05/2024|[Gabriel Souza](https://github.com/GabrielMS00)|
|`1.3`|30/05/2024|Softgoal 4| [Gabriel Souza](https://github.com/GabrielMS00)|30/05/2024|[José Filipi](https://github.com/JoseFilipi)|
|`1.4`|30/05/2024|Softgoal 5| [José Filipi](https://github.com/JoseFilipi)|30/05/2024|[Amanda Campos](https://github.com/acamposs)|
|`1.5`|30/05/2024|Softgoal 6| [Amanda Campos](https://github.com/acamposs)|30/05/2024|[Johnny Lopes](https://github.com/JohnnyLopess)|
|`1.6`|30/05/2024|Softgoal 7| [Johnny Lopes](https://github.com/JohnnyLopess)|30/05/2024|[Vitor Feijó](https://github.com/vitorfleonardo)|
|`1.7`|30/05/2024|Softgoal 8| [Paulo Borba](https://github.com/paulohborba)|30/05/2024|[Gabriel Souza](https://github.com/GabrielMS00)|
|`1.9`|02/06/2024|Adição dos SIGs de operacionalização, afirmação e seleção de alternativas.| [Vitor Feijó](https://github.com/vitorfleonardo)|02/06/2024|[Bianca Castro](https://github.com/BiancaPatrocinio7)|
|`2.0`|21/06/2024|Adição dos cartões de especificação.| [Johnny Lopes](https://github.com/JohnnyLopess)|-|-|



