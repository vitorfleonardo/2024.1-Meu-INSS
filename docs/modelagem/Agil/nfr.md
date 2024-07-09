## Introdução

Segundo Chung et al. (2000), criador do NFR framework, “foi adotado por propor uma abordagem específica para o tratamento de Requisitos Não-Funcionais e fornecer uma rica representação para expressar esses requisitos, além de suas relações e correlações” (Silva Reinaldo, p. 30, 2019).

## Metodologia

Referenciando a dissertação de mestrado de Reinaldo Antônio, para criação do catálago de requisitos não-funcionais, o projeto do Meu INSS seguiu os seguintes passos:

1.<strong> Desenvolvimento da taxonomia </strong> <br>
Para o desenvolvimento da taxonomia, aproveitou-se da metodologia FURPS+, utilizada na [especificação suplementar](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/specSuplementar/) e [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/) e que auxiliou na identificação dos RNFs. 

2.<strong> Criação do catálogo de requisitos </strong> <br>
Nessa etapa foi realizada a construção de um grafo de Interdependência de Softgoal - Softgoal Interdenpendency Graph (SIG). Além disso foi adotado o cartão de especificação baseado no cartão (snowcard) do processo Volvere (ROBERTSON; ROBERTSON, 2012) para escrita dos exemplos do catálogo (Antônio, Reinaldo, 2019). 

3.<strong> SIG - Softgoal Interdenpendency Graph</strong> Existem três tipos de softgoals: Softgoals NFR, Softgoals de Operacionalização e Softgoals
de Afirmação. Estes são descritos a seguir:


- **Softgoals NFR:**representam os Requisitos Não- Funcionais e podem estar interrelacionados, organizados em catálogos e apresentados de forma hierárquica no desenvolvimento do projeto (CHUNG et al., 2000).

- **Softgoals de Operacionalização:** representam soluções de implementação para
satisfazer softgoals NFR ou outros softgoals de operacionalização. Essas soluções
incluem operações, processos, representações de dados, estruturações e restrições
no sistema alvo para atender às necessidades indicadas pelos softgoals NFR e de
operacionalização (CHUNG et al., 2000).

- **Softgoals de Afirmação:** permitem que as características do domínio (como prioridades e carga de trabalho) sejam consideradas e devidamente refletidas no processo
de tomada de decisão. Eles servem como justificativa para apoiar ou negar a forma
como os softgoals são priorizados, refinados e os componentes são selecionados. Os
softgoals de afirmação fornecem as razões para as decisões de desenvolvimento, facilitando a revisão, a justificativa e a mudança do sistema, bem como o aprimoramento
da rastreabilidade(CHUNG et al., 2000).

<p align="center">
    <strong>Figura 1: Tipos de Softgoal</strong><br>
    <img src="https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/assets/nfr-framework/tipos.png" width="300%">
</p>

<font size="3"><p style="text-align: center">Fonte: (CHUNG et al., 2000)</p></font>

A figura 1 ilustra as representações gráficas dos três tipos de softgoals utilizados pelo
NFR Framework. Para representar os softgoals NFR são utilizadas nuvens claras, os softgoals de operacionalização são nuvens com linhas mais grossas, enquanto os softgoals de
afirmação são representados através de nuvens com linhas tracejadas.



## Taxonomia

<p align="center" > <strong> Figura 1:</Strong> Taxonomia de Requisitos Não-Funcionais</font></p>
<iframe frameborder="0" style="width:100%;height:350px;" src="https://viewer.diagrams.net/?tags=%7B%7D&highlight=0000ff&edit=_blank&layers=1&nav=1&title=Untitled%20Diagram.drawio#Uhttps%3A%2F%2Fdrive.google.com%2Fuc%3Fid%3D1giNn5-kisipsC4Gp5FalpvZBydIiVLhj%26export%3Ddownload"></iframe>
<font size="3"><p style="text-align: center"><b>Autor</b> - [José Filipi](https://github.com/JoseFilipi) & [Vitor Leonardo](https://github.com/vitorfleonardo), 2024</p></font>


## Catálogo de requisitos

### NFR01 - Usabilidade

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 1:</Strong> Cartão de Especificação 1</font></p>

| Nº Requisito: 1 ([RNF01](#NF0)) | Classificação: Usabilidade |
|----------------------------------|-----------------------------|
| **Descrição:** | O aplicativo deve possuir ferramentas de acessibilidade como navegação guiada, alto contraste, comando por voz e possibilidade de aumentar a fonte. |
| **Justificativa:** | As ferramentas de acessibilidade são essenciais para garantir que todos os usuários, incluindo aqueles com deficiência visual ou dificuldades motoras, possam utilizar o aplicativo de forma eficiente e confortável. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve fornecer navegação guiada, opções de alto contraste, comandos por voz e ajuste de tamanho de fonte que possam ser testados e utilizados por pessoas com deficiências. |
| **Dependências:** | Padrões de acessibilidade, SDKs de acessibilidade dos sistemas operacionais |
| **Prioridade:** | 1,50 |
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024|

Autor: [José Filipi](https://github.com/JoseFilipi)

</center>

### NFR02 - Desempenho

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 2:</Strong> Cartão de Especificação 2</font></p>

| Nº Requisito: 2 ([RNF02](#NF02)) | Classificação: Desempenho |
|----------------------------------|-----------------------------|
| **Descrição:** | O aplicativo deve responder a comandos do usuário em menos de 3 segundos. |
| **Justificativa:** | Um tempo de resposta rápido é essencial para garantir uma experiência de usuário satisfatória e eficiente. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve ser testado para garantir que todas as respostas a comandos do usuário sejam executadas em menos de 3 segundos. |
| **Dependências:** | Desempenho do servidor, otimização do código, infraestrutura de rede |
| **Prioridade:**  | 1,00|
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024 |

Autor: [Vitor Leonardo](https://github.com/vitorfleonardo)

</center>

### NFR03 - Segurança

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 3:</Strong> Cartão de Especificação 3</font></p>

| Nº Requisito: 3 ([RNF03](#NF03)) | Classificação: Segurança |
|----------------------------------|---------------------------|
| **Descrição:** | O aplicativo deve garantir a segurança das informações pessoais dos usuários através de criptografia de dados e autenticação robusta. |
| **Justificativa:** | A proteção das informações pessoais é crucial para manter a confiança dos usuários e cumprir com regulamentações de privacidade e segurança de dados. |
| **Origem do Requisito:** | Projetista de Software |
| **Critério de Aceitação:** | O sistema deve implementar e ser testado para garantir a criptografia de dados e métodos de autenticação robustos, conforme padrões de segurança. |
| **Dependências:** |Protocolos de criptografia, serviços de autenticação, regulamentos de segurança de dados |
| **Prioridade:** | 1,59|
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024 |

Autor: [José Filipi](https://github.com/JoseFilipi)

</center>

### NFR04 - Confiabilidade

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 4:</Strong> Cartão de Especificação 4</font></p>

| Nº Requisito: 4 ([RNF05](#NF04)) | Classificação: Confiabilidade |
|----------------------------------|-------------------------------|
| **Descrição:**| O aplicativo deve estar disponível 24 horas por dia, 7 dias por semana, com uma taxa de uptime de 99.9%. |
| **Justificativa:**| Alta disponibilidade é essencial para garantir que os usuários possam acessar o aplicativo a qualquer momento, aumentando a confiança e satisfação dos usuários. |
| **Origem do Requisito:**| Projetista de Software |
| **Critério de Aceitação:**| O sistema deve ser monitorado continuamente e deve manter um uptime de 99.9% ou superior, calculado mensalmente. |
| **Dependências:**| Infraestrutura de servidores, rede de distribuição de conteúdo, manutenção e monitoramento contínuos |
| **Prioridade:**| 2,45|
| **Conflitos:** | Nenhum |
| **História:** | 27/05/2024 |

Autor: [Vitor Leonardo](https://github.com/vitorfleonardo)

</center>

### NFR05 - Manuntenibilidade

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 5:</Strong> Cartão de Especificação 5</font></p>

| Nº Requisito: 5 ([RNF05](#NF05)) | Classificação: Manuntenibilidade |
|----------------------------------|----------------------------|
| **Descrição:**| O aplicativo deve ter integração com outros serviços do governo. |
| **Justificativa:**| A integração com outros serviços governamentais é necessária para oferecer uma experiência mais completa e eficiente aos usuários, permitindo o acesso e a troca de informações entre diferentes plataformas governamentais. |
| **Origem do Requisito:**| Projetista de Software |
| **Critério de Aceitação:**| O sistema deve ser capaz de se comunicar e trocar dados de forma segura e eficaz com outros serviços do governo, conforme especificado nas APIs governamentais. |
| **Dependências:**| APIs dos serviços governamentais, protocolos de segurança, conformidade com padrões de interoperabilidade |
| **Prioridade:**| 1,12|
| **Conflitos:**| Nenhum |
| **História:**| 27/05/2024 |

Autor: [José Filipi](https://github.com/JoseFilipi)

</center>

### NFR06 - Portabilidade

#### Grafo de Interdependência de Softgoal

#### Cartão de especificação

<center>

<p align="center" > <strong> Tabela 6:</Strong> Cartão de Especificação 6</font></p>

| Nº Requisito: 6 ([RNF06](#NF06)) | Classificação: Portabilidade |
|----------------------------------|-------------------------------|
| **Descrição:**| O aplicativo deve ser compatível com as versões mais recentes e anteriores dos sistemas operacionais iOS e Android e computador. |
| **Justificativa:**| A compatibilidade com múltiplas versões dos sistemas operacionais garante que o aplicativo alcance uma base maior de usuários, independentemente do dispositivo ou versão do sistema operacional que utilizem. |
| **Origem do Requisito:**| Projetista de Software |
| **Critério de Aceitação:**| O aplicativo deve ser testado e funcionar corretamente em pelo menos duas versões anteriores e na versão mais recente dos sistemas operacionais iOS, Android e em plataformas de computador. |
| **Dependências:**| Ferramentas de desenvolvimento multi-plataforma, atualizações dos sistemas operacionais |
| **Prioridade:**| 1,73|
| **Conflitos:**| Nenhum |
| **História:** |27/05/2024 |

Autor:[José Filipi](https://github.com/JoseFilipi),2024.
</center>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 15. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 15](https://aprender3.unb.br/pluginfile.php/2845040/mod_resource/content/1/Requisitos%20-%20Aula%2015a.pdf). Acesso em: 27 de Maio de 2024.
>

> SILVA, Reinaldo Antônio. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019. Dissertação (Mestrado em Ciência da Computação) - Centro de Informática da Universidade Federal de Pernambuco, [S. l.], 2019. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf](https://aprender3.unb.br/pluginfile.php/2845051/mod_resource/content/2/DISSERTA%C3%87%C3%83O%20Reinaldo%20Ant%C3%B4nio%20da%20Silva.pdf). Acesso em: 27 mai. 2024.

> </a> Requisitos de Software. Economia-DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/agil/nfr-framework/#cartao-de-especificacao](https://requisitos-de-software.github.io/2023.1-BilheteriaDigital/modelagem/agil/historia-de-usuario/). Acesso em: 27 mai. 2024.

## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0`|27/05/2024|Criação do documento.|[José Filipi](https://github.com/JoseFilipi) & [Vitor Feijó](https://github.com/vitorfleonardo) |27/05/2024|[Paulo Borba](https://github.com/paulohborba)|
