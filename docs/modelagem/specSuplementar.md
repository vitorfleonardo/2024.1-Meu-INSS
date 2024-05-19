# Especificação suplementar

## Introdução
A **Especificação Suplementar**, no contexto da engenharia de software, refere-se à prática de classificar e organizar os requisitos de um sistema em diferentes grupos ou categorias. Essa abordagem facilita a compreensão, o gerenciamento e a priorização dos requisitos durante o ciclo de desenvolvimento do software.

"Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design" <a id="TEC1" href="#RP1">[1]</a>. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário  <a id="TEC2" href="#RP2">[2]</a>.

## Metodologia

A Metodologia utilizada neste artefato foi baseada no modelo FURPS+. "É um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos" <a id="TEC3" href="#RP3">[3]</a>. Dentre elas: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, sendo que o "+" engloba outros requisitos não-funcionais: requisitos de design, requisitos de implementação, requisitos de interface, requisitos físicos <a id="TEC3" href="#RP3">[3]</a>.

A Legenda para identificação dos requisitos em cada acrônimo estão representadas na tabela 1 e na tabela 2.

<p align="center" > <strong> Tabela 1 - </Strong> Legenda das tabelas FURPS</font> <gitbr></p>
<center>

|Acrônimo | Significado | Tradução | Identificador
|:-:|:-:|:-:|:-:|
| F | Functionality | Funcionalidade | - |
| U | Usability | Usabilidade | RU |
| R | Reliability | Confiabilidade | RR |
| P | Performance | Desempenho | RP |
| S | Supportability | Suportabilidade | RS |

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

<p align="center" > <strong> Tabela 2 - </Strong> Legenda das tabelas +</font> <gitbr></p>
<center>

|Acrônimo | Significado | Tradução | Identificador
|:-:|:-:|:-:|:-:|
| +D | Plus: Design constrains | Requisitos de Design | +D |
| +Im | Plus: Implementation constrains | Requisitos de Implementação | +Im |
| +In | Plus: Iterface constrains | Requisitos de interface | +In |
| +P | Plus: Physical constrains | Requisitos físicos | +P |


</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Funcionalidade

A **funcionalidade** trata do núcleo do sistema, abordando as funções e capacidades que o software precisa oferecer. Os requisitos de funcionalidade especificam o que o sistema deve fazer, englobando tarefas, operações, recursos e comportamentos esperados.

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](../elicitacao/brainStorm.md), [Introspeção](../elicitacao/Introspeccao.md), [Entrevista](../elicitacao/entrevista.md), [Questionário](../elicitacao/questionario.md), [Storytelling](../elicitacao/storytelling.md), e podem ser consultados em [Requisitos Elicitados](../elicitacao/requisitosElicitados.md). Os casos de uso também podem ser considerados como requisitos funcionais. 

## Usabilidade

A **usabilidade** se refere a quão eficiente e agradável é para uma pessoa usar um produto ou sistema. Ela envolve aspectos como a simplicidade do uso, a clareza e a organização da interface, a facilidade de acesso para todos os tipos de usuários, e qualquer outro fator que possa melhorar ou prejudicar a interação do usuário com o produto.

Esta seção inclui todos os requisitos que afetam a usabilidade. Os requisitos não funcionais para usabilidade estão representados na tabela 3.

<p align="center" > <strong> Tabela 3 - </Strong> Requisitos de usabilidade</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| RU001 | O aplicativo deve ser fácil e intuitivo, permitindo que um usuário realize sua demanda em menos de 5 minutos.|
| RU002 | O aplicativo deve avisar o usuário, ao clicar em um botão ou link, que será redirecionado para um ambiente externo ao Meu INSS |
| RU003 | Toda imagem significativa no aplicativo deve ter um texto alternativo |
| RU004 | Toda e qualquer mídia no aplicativo não poderá ter autoplay e, se utilizada, deve fornecer transcrição |
| RU005 | O aplicativo deve ter um fluxo lógico e contínuo |
| RU006 | Os rótulos de botões e funcionalidades devem ser objetivos |
| RU007 | O aplicativo deve oferecer o modo contraste |
| RU008 | As fontes devem ter tamanho variavel e não fixo |
| RU009 | O contraste entre objetos gráficos / Componentes da Interface do usuário e cord de fundo devem passar crtério de sucesso WCAG AA |
| RU010 | O contraste entre textos normais e cor de fundo devem passar crtério de sucesso WCAG AAA |
| RU011 | O contraste de textos grandes e cor de fundo devem passar crtério de sucesso WCAG AAA |
| RU012 | A hierarquia de conteúdo das telas do aplicativo devem ser definidas por sua lógica e não pelo tamanho do texto |
| RU013 | Ao se utilizar modais, devem ser fáceis de fechar e evitar utilizar em tela cheia  |
| RU014 | O aplicativo deve permitir ser rotacionado para qualquer orientação do dispositivo móvel  |
| RU015 | O aplicativo não pode ter rolagem horizontal |
| RU016 | O aplicativo deve garantir espaço suficiente entre elementos interativos |
| RU017 | O aplicativo incluir um campo de busca |
| RU018 | O aplicativo exibir mensagens de erro e sucesso visualmente e ter possibilidade de accessibilidade de sonoridade para PcD cega|
| RU019 | O aplicativo ter áreas clicáveis com no mínimo 44px (pixels) de altura e 44px de largura |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Confiabilidade

A **confiabilidade** refere-se à habilidade do sistema de operar continuamente e sem problemas, reduzindo ao máximo as falhas. Isso envolve a capacidade de lidar com falhas, a forma como os erros são gerenciados e a disponibilidade constante do sistema. "Refere-se a integridade, conformidade e interoperabilidade do software" <a id="TEC3" href="#RP3">[3]</a>.

Esta seção inclui todos os requisitos que afetam a confiabilidade.. Os requisitos de confiabilidade estão representados na tabela 4.

<p align="center" > <strong> Tabela 4 - </Strong> Requisitos de confiabilidade</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| RR001 | Para Tempo Médio para Reparo (MTTR), o aplicativo não poderá ficar mais de 24 horas sem funcionar após uma falha |
| RR002 | O aplicativo deve ser capaz de lidar com um aumento de 500% na carga de usuários simultâneos sem comprometer a sua estabilidade ou desempenho. |
| RR003 | O aplicativo deve ser capaz de suportar 30 milhões de acessos em um único mês |
| RR004 | Os dados do usuário e as informações críticas do aplicativo devem ser armazenados de forma segura e protegidos contra perda de dados  |
| RR005 | Para o Tempo Médio entre Falhas (MTBF), espera-se 520 horas  |
| RR006 | O aplicativo deve ter um mecanismo de monitoramento contínuo que alerta a equipe de suporte técnico sobre quaisquer problemas críticos em tempo real. A equipe de suporte deve estar disponível 24/7 para resolver esses problemas.  |
| RR007 | As atualizações de software e manutenções planejadas devem ser agendadas fora do horário de pico de uso do aplicativo e os usuários devem ser notificados com antecedência.  |
| RR008 | Em caso de interrupções não planejadas que afetem o funcionamento do aplicativo, os usuários devem ser informados de maneira clara e precisa sobre o problema, o progresso da solução e o tempo estimado de restauração do serviço  |


<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Desempenho

O **desempenho** diz respeito à rapidez e eficiência com que o sistema opera. Os requisitos de desempenho incluem fatores como a velocidade de resposta, a capacidade de processamento de dados e a habilidade do sistema de crescer e se adaptar a maiores demandas.

Esta seção inclui todos os requisitos que afetam o desempenho. Os requisitos de desempenho estão representados na tabela 5.

<p align="center" > <strong> Tabela 5 - </Strong> Requisitos de desempenho</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| RP001 | O tempo médio de resposta para uma transação deve ser de 200 milissegundos durante o horário de pico. |
| RP002 | O tempo máximo de resposta para uma transação não deve exceder 5 segundos em qualquer circunstância. |
| RP003 | O aplicativo deve ser capaz de processar pelo menos 1000 transações por segundo durante o horário de pico. |
| RP004 | O aplicativo deve ser capaz de processar pelo menos 29,4 milhões de transações por mês (com base nos dados de fevereiro de 2022) |
| RP005 | Em caso de falha no aplicativo, o aplicativo deve entrar em um modo de operação degradado que permita pelo menos 70% da capacidade normal |
| RP006 | O aplicativo deve ser capaz de se recuperar de um modo degradado para a operação normal em não mais que 15 minutos |
| RP007 | O aplicativo deve utilizar não mais que 60% da memória disponível sob carga normal |
| RP008 | O aplicativo deve utilizar não mais que 50% do espaço em disco disponível |
| RP009 | O aplicativo deve utilizar não mais que 70% da largura de banda disponível sob carga normal |


<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Suportabilidade

A **suportabilidade** refere-se à facilidade de manter e suportar o sistema ao longo do tempo. Isso envolve requisitos como a frequência e facilidade de atualizações, a manutenção contínua, a disponibilidade de documentação completa e a necessidade de treinamento para os usuários e administradores.

Esta seção inclui todos os requisitos que afetam a suportabilidade. Os requisitos de suportabilidade estão representados na tabela 6.

<p align="center" > <strong> Tabela 6 - </Strong> Requisitos de suportabilidade</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| RS001 | O aplicativo deve ser compatível e otimizado para smartphones e tablets fabricados por Samsung, Apple, Motorola, Xiaomi, entre outros principais fabricantes. |
| RS002 | O aplicativo é projetado de forma modular, facilitando a manutenção e atualizações. As atualizações de segurança são lançadas a cada trimestre, enquanto as atualizações de recursos são lançadas semestralmente. |
| RS003 | O aplicativo deve suportar as versões mais recentes e as duas versões anteriores dos sistemas operacionais iOS (para dispositivos Apple) e Android (para dispositivos Samsung, Motorola, Xiaomi, etc.).  |
| RS004 | O aplicativo permite a personalização de configurações pelo usuário final, incluindo notificações, preferências de idioma e configurações de privacidade.  |
| RS005 | O aplicativo oferece um processo de instalação simples e direto através das lojas de aplicativos Google Play e Apple App Store. |
| RS006 | O aplicativo é capaz de escalar para acomodar um aumento no número de usuários ou transações. Ele pode suportar até 30 milhões de usuários por mês |
| RS007 | O aplicativo executa testes automatizados de integração e sistema, garantindo a qualidade e experiẽncia do usuário. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Outros requisitos do Produto (+)

A categoria "+", também conhecida como "Suplementar" ou "Qualidades do Sistema", abrange quaisquer requisitos que não se enquadrem nas categorias anteriores. Isso pode incluir exigências legais, éticas, regulatórias, ambientais ou outros requisitos específicos do projeto.

### Requisitos de Design

"Requisitos de design (desenho) – Um requisito de design, freqüentemente chamado de uma restrição de design, especifica ou restringe o design de um sistema. Exemplos podem incluir: linguagens de programação, processo de software, uso de ferramentas de desenvolvimento, biblioteca de classes, etc"  <a id="TEC3" href="#RP3">[3]</a>. Os requisitos de design estão representados na tabela 7.

<p align="center" > <strong> Tabela 7 - </Strong> Requisitos de Design</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| +D001 | O aplicativo deve ser desenvolvido usando Java para o backend e Javascript para o frontend |
| +D002 | O desenvolvimento deve seguir a metodologia Agile, com sprints de duas semanas e revisões de código regulares |
| +D003 | O código deve ser desenvolvido e mantido usando Git para controle de versão, Jira para rastreamento de problemas e Jenkins para integração contínua |
| +D004 | O aplicativo deve seguir uma arquitetura microserviços para permitir a escalabilidade e a manutenção independentes dos diferentes componentes do sistema |
| +D005 | O sistema deve usar a biblioteca Spring Boot para o backend e a biblioteca React Navigation para a navegação no frontend. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

### Requisitos de Implementação

"Requisitos de design (desenho) – Um requisito de design, freqüentemente chamado de uma restrição de design, especifica ou restringe o design de um sistema. Exemplos podem incluir: linguagens de programação, processo de software, uso de ferramentas de desenvolvimento, biblioteca de classes, etc"  <a id="TEC3" href="#RP3">[3]</a>. Os requisitos de design estão representados na tabela 8.

<p align="center" > <strong> Tabela 8 - </Strong> Requisitos de Design</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| +D001 | O aplicativo deve ser desenvolvido usando Java para o backend e Javascript para o frontend |
| +D002 | O desenvolvimento deve seguir a metodologia Agile, com sprints de duas semanas e revisões de código regulares |
| +D003 | O código deve ser desenvolvido e mantido usando Git para controle de versão, Jira para rastreamento de problemas e Jenkins para integração contínua |
| +D004 | O aplicativo deve seguir uma arquitetura microserviços para permitir a escalabilidade e a manutenção independentes dos diferentes componentes do sistema |
| +D005 | O sistema deve usar a biblioteca Spring Boot para o backend e a biblioteca React Navigation para a navegação no frontend. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

### Requisitos de Interface

"Requisitos de implementação – Um requisito de implementação especifica ou restringe o código ou a construção de um sistema. Como exemplos, podemos citar: padrões obrigatórios, linguagens de implementação, políticas de integridade de banco de dados, limites de recursos, ambientes operacionais" <a id="TEC3" href="#RP3">[3]</a>. Os requisitos de implementação estão representados na tabela 9.

<p align="center" > <strong> Tabela 9 - </Strong> Requisitos de Implementação</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| +Im001 | O aplicativo deve estar em conformidade com a Lei Geral de Proteção de Dados (LGPD) do brasil, garantindo a privacidade e segurança dos dados dos usuários. |
| +Im002 | O aplicativo deve suportar protocolos de comunicação padrão, como HTTP/HTTPS para comunicação web. |
| +Im003 | O aplicativo deve seguir as melhores práticas de segurança, incluindo a criptografia de dados em trânsito. |
| +Im003 | O aplicativo deve garantir a integridade dos dados do usuário. Isso inclui a implementação de políticas e recuperação de dados, bem como medidas para previnir a corrupção de dados |
| +Im004 | O aplicativo deve ser otimizado para uso eficiente de recursos, garantindo que funcione de maneira eficaz mesmo em dispositivos com recursos limitados. |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>


### Requisitos de interface

"Requisitos de interface – especifica ou restringe as funcionalidades inerentes a interface do sistema com usuário" <a id="TEC3" href="#RP3">[3]</a>. Os requisitos de interface estão representados na tabela 11.

<p align="center" > <strong> Tabela 11 - </Strong> Requisitos de Interface</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| +In001 | A interface do usuário deve ser intuitiva e fácil de usar, mesmo para usuários com pouca experiência em tecnologia. |
| +In002 | O aplicativo deve ser acessível para todos os usuários, incluindo aqueles com deficiências visuais, auditivas ou motoras. Isso pode incluir recursos como leitores de tela, ampliação de texto e contraste de cores ajustável. |
| +In003 | A navegação deve ser clara e consistente em todo o aplicativo, com menus e botões facilmente identificáveis. |
| +In004 | A interface do usuário deve permitir atualizações fáceis e fornecer acesso a suporte ao usuário, como FAQs e tutoriais em vídeo. |


<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

### Requisitos Físicos

"Requisitos físicos – especifica uma limitação física pelo hardware utilizado, por exemplo: material, forma, tamanho ou peso. Podendo representar requisitos de hardware, como as configurações físicas de rede obrigatórias" <a id="TEC3" href="#RP3">[3]</a>. Os requisitos físicos estão representados na tabela 12.

<p align="center" > <strong> Tabela 12 - </Strong> Requisitos de Físicos</font> <gitbr></p>

|ID|Descrição do requisito|
|:-:|:-:|
| +P001 | O aplicativo deve funcionar em redes 3G, 4G e 5G, bem como em conexões Wi-Fi. Deve ser otimizado para uso eficiente de dados. |
| +P002 | O aplicativo deve ser otimizado para uso mínimo de armazenamento no dispositivo. Isso é especialmente importante para usuários com dispositivos que têm capacidades de armazenamento limitadas. |
| +P003 | O aplicativo deve ser otimizado para consumo mínimo de energia para não esgotar rapidamente a bateria do dispositivo do usuário. 

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> Gois, Samily; Sobrinho, Francisco. PHP SOFTWARE COMPANY - Projeto de Software Floricultura Beija-Flor, Especificação Suplementar. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845019/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf](https://aprender3.unb.br/pluginfile.php/2845019/mod_resource/content/1/Especificacao_Suplementar_Exemplo.pdf). Acesso em: 10 abr. 2024.

> <a id="RP2" href="#TEC2">2.</a> Requisitos de Software. Economia-DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#metodologia](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/especificacao-suplementar/#metodologia). Acesso em: 10 Mai. 2024.

> <a id="RP3" href="#TEC3">3.</a> Eeles, Peter. QualidadeBR: FURPS+. jun, 2008. Disponível em: [https://qualidadebr.wordpress.com/2008/07/10/furps/](https://qualidadebr.wordpress.com/2008/07/10/furps/). Acesso em: 10 Mai. 2024.

## Bibliografia

> </a> SERRANO, et al. Requisitos - Aula 13.. Disponível em: [https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf](https://aprender3.unb.br/pluginfile.php/2845007/mod_resource/content/1/Requisitos%20-%20Aula%20013a.pdf). Acesso em: 10 Mai. 2024.

> </a> Feijó, Vitor, et al. VerificAAA - Projeto do Curso de Interação Humano-Computador. 2024. Disponível em: [https://vitorfleonardo.github.io/VerificaAAA/](https://vitorfleonardo.github.io/VerificaAAA/). Acesso em: 10 Mai. 2024.

> </a> Gov.br - Instituto Nacional do Seguro Social - INSS. Meu INSS registra 29,4 milhões de acessos em fevereiro de 2022. 2022. Disponível em: [https://www.gov.br/inss/pt-br/assuntos/meu-inss-registra-29-4-milhoes-acessos-em-fevereiro-de-2022](https://www.gov.br/inss/pt-br/assuntos/meu-inss-registra-29-4-milhoes-acessos-em-fevereiro-de-2022). Acesso em: 10 Mai. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 10/05/2024 | Versão inicial da pagina de Especificação Suplementar. | [Vitor Feijó](https://github.com/vitorfleonardo) | || 
| `1.1` | 13/05/2024 | Preenchimento de toda Especificação Suplementar. | [Vitor Feijó](https://github.com/vitorfleonardo) & [Amanda Campos](https://github.com/acamposs)| || S
