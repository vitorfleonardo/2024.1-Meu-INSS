# Especificação suplementar

## Introdução

"Este documento captura os requisitos de sistema que não foram identificados imediatamente nos Casos de Uso do Modelo de Casos de Uso. Entre estes requisitos estão incluídos: o Requisitos legais e reguladores, incluindo padrões de aplicativo; Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade. Outros requisitos, como sistemas operacionais e ambientes, requisitos de compatibilidade e restrições de design" <a id="TEC1" href="#RP1">[1]</a>. Esses requisitos são cruciais para garantir a qualidade do software e a satisfação do usuário  <a id="TEC2" href="#RP2">[2]</a>.

## Metodologia

A Metodologia utilizada neste artefato foi baseada no modelo FURPS+. "É um sistema para a classificação de requisitos, o acrônimo representa categorias que podem ser usadas na definição de requisitos" <a id="TEC3" href="#RP3">[3]</a>. Dentre elas: Funcionalidade, Usabilidade, Confiabilidade, Desempenho, Suportabilidade, sendo que o "+" engloba outros requisitos não-funcionais: requisitos de design, requisitos de implementação, requisitos de interface, requisitos físicos <a id="TEC3" href="#RP3">[3]</a>.

A Legenda para identificação dos requisitos em cada acrônimo estão representadas na tabela 1.

<p align="center" > <strong> Tabela 1 - </Strong> Legenda das tabelas</font> <gitbr></p>
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

## Funcionalidade

Os requisitos funcionais foram capturados ateriormente com as técnicas de [Brainstorming](../elicitacao/brainStorm.md), [Introspeção](../elicitacao/Introspeccao.md), [Entrevista](../elicitacao/entrevista.md), [Questionário](../elicitacao/questionario.md), [Storytelling](../elicitacao/storytelling.md), e podem ser consultados em [Requisitos Elicitados](../elicitacao/requisitosElicitados.md). Os casos de uso também podem ser considerados como requisitos funcionais. 

## Usabilidade

Esta seção inclui todos os requisitos que afetam a usabilidade. Os requisitos não funcionais para usabilidade estão representados na tabela 1.

<p align="center" > <strong> Tabela 2 - </Strong> Requisitos de usabilidade</font> <gitbr></p>

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

Esta seção inclui todos os requisitos que afetam a confiabilidade. "Refere-se a integridade, conformidade e interoperabilidade do software" <a id="TEC3" href="#RP3">[3]</a>. Os requisitos de confiabilidade est'ao representados na tabela 3.

<p align="center" > <strong> Tabela 3 - </Strong> Requisitos de usabilidade</font> <gitbr></p>

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

## Suportabilidade

## Outros requisitos do Produto (+)

### Requisitos de Design

### Requisitos de Implementação

### Requisitos de Interface

### Requisitos Físicos



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
