# Léxicos

## Introdução

O Léxico é uma técnica utilizada para descrever os símbolos de uma linguagem. Os engenheiros de requisitos têm como objetivo identificar frases e símbolos específicos para a aplicação em questão. Cada símbolo é descrito com uma noção e um impacto, onde a noção está relacionada ao símbolo e o impacto à descrição dos efeitos do símbolo na aplicação ou do efeito da aplicação sobre o símbolo.

Para essas descrições, são aplicados os princípios da circularidade e do vocabulário mínimo. O princípio da circularidade estabelece que cada extensão da descrição ou conotação deve referir-se a outros símbolos da linguagem. Além disso, a descrição deve utilizar um conjunto limitado de palavras com significado claro (vocabulário mínimo), evitando termos excessivamente técnicos ou ambíguos.

Léxicos podem ser classificados como verbos, objetos ou estados. Os léxicos do tipo verbo são aqueles cuja noção consiste em um agente que realiza os procedimentos, e cujo impacto é o reflexo da ação do agente. Os do tipo objeto possuem a definição do objeto em questão na noção, além dos outros objetos com os quais se relaciona, e no impacto são descritas as ações que podem ser aplicadas ao objeto. Por fim, os estados apresentam seu significado e quais ações levam a esse estado na noção do léxico, e seu impacto consiste nos estados e ações que podem ocorrer a partir do estado em questão.

## Metodologia

Os léxicos do sistema Meu INSS foram identificados a partir da utilização do aplicativo e dos [requisitos elicitados](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/) nas etapas anteriores. Na tabela 1 abaixo, temos um exemplo de como os léxicos serão apresentados e descritos:

| Léxico         | Sinônimo | Noção   | Impacto             | Classificação       |
| -------------- | -------- | ------- | ------------------- | ------------------- |
| Nome do Léxico | Sinônimo | Símbolo | Descrição do efeito | Verbo/Objeto/Estado |

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos (Fonte: Bianca, 2024).</p>
</div>

## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro do aplicativo "Meu INSS". Na Tabela 2, é possível verificar os principais léxicos classificados como objetos que foram identificados no Meu INSS. Esses léxicos incluem elementos como "Benefício", "Solicitação", "Documentação", entre outros. Cada um desses léxicos é descrito detalhadamente, incluindo sua noção, que define o objeto e seus relacionamentos com outros objetos, e seu impacto, que descreve as ações possíveis sobre o objeto. 



|   Léxico     |     Sinônimo      |        Noção        |                    Impacto                    | Classificação |
| :----------: | :---------------: | :-----------------: | :-------------------------------------------: | :-----------: |
| L01 -  Benefício    | Auxílio, Provento | Tipo de Benefício   | O usuário pode visualizar e solicitar benefícios |    Objeto     |
| L02 - Solicitação  | Pedido, Requisição| Enviar Solicitação  | O usuário pode enviar, acompanhar e verificar o status das solicitações |    Objeto     |
| L03 - Documentação | Arquivo, Prova    | Enviar Documentos   | O usuário pode enviar, visualizar e gerenciar documentos necessários para os processos |    Objeto     |
| L04 - Usuário      | Cliente, Assinante| Dados do Usuário    | Informações pessoais do usuário, permitindo personalização e acesso aos serviços |    Objeto     |




<div align="center">

<font size="3"><p style="text-align: center"><b>Tabela 2: </b>Léxicos classificados como Objetos (Fonte: Bianca, 2024)</p></font>
</div>


<div align="center">
<font size="3"><p style="text-align: center"></p></font>

</div>

## Verbos

Os léxicos do tipo verbo representam ações ou operações que os usuários podem executar dentro do aplicativo "Meu INSS". Essas ações detalham as funcionalidades acessíveis para os usuários, permitindo interações específicas e operações dentro do aplicativo. Na Tabela 3, é possível conferir os principais léxicos classificados como verbos que foram identificados no Meu INSS. Esses léxicos incluem ações como "Solicitar", "Consultar" e "Simular", cada uma descrevendo uma interação essencial que os usuários podem realizar. Além disso, esses léxicos ajudam a definir os fluxos de uso do aplicativo, orientando os usuários em suas tarefas e melhorando a experiência de navegação e uso dos serviços disponíveis.



|   Léxico    |    Sinônimo    |       Noção       |                         Impacto                          | Classificação |
| :---------: | :------------: | :---------------: | :-----------------------------------------------------: | :-----------: |
| L05 - Solicitar | Pedir, Requerer | Enviar Solicitação | O usuário pode enviar, acompanhar e verificar o status das solicitações |    Verbo     |
| L06 - Consultar | Verificar, Checar | Consultar Informações | O usuário pode buscar e visualizar informações relacionadas a benefícios e processos |    Verbo     |
| L07 - Simular    | Estimar, Prever  | Simular Cenários  | O usuário pode simular diferentes cenários e calcular possíveis benefícios e impactos |    Verbo     |

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 3: </b>Léxicos classificados como Verbos (Fonte: Bianca, 2024)</p></font>

</div>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem ocorrer dentro do aplicativo "Meu INSS". Esses estados representam diversos cenários em que o usuário ou o sistema pode se encontrar durante a interação com o aplicativo. Na Tabela 4, é possível verificar os principais léxicos classificados como estados que foram identificados no Meu INSS. Esses léxicos incluem estados como "Pendente", "Aprovado" e "Em Análise", cada um descrevendo uma condição específica que afeta as ações subsequentes e as opções disponíveis para o usuário. A compreensão desses estados é essencial para navegar eficientemente pelo aplicativo e utilizar suas funcionalidades de forma eficaz.



|   Léxico    |     Sinônimo      |        Noção        |                    Impacto                    | Classificação |
| :---------: | :---------------: | :-----------------: | :-------------------------------------------: | :-----------: |
| L08 - Pendente    |   Em Espera       |   Status Pendente   | O usuário está aguardando a aprovação ou análise de uma solicitação  |    Estado     |
| L09 - Aprovado    |    Confirmado     |   Status Aprovado   | O usuário teve sua solicitação aprovada, permitindo o acesso aos benefícios ou serviços |    Estado     |
| L10 - Em Análise  |    Avaliando      |   Status Em Análise | A solicitação do usuário está sendo avaliada, sem uma decisão final ainda tomada    |    Estado     |

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 4: </b>Léxicos classificados como Estados (Fonte: Bianca, 2024)</p></font>

</div>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf). Acesso em: 16 de Maio de 2024.
>
## Histórico de Versões

|Versão|Data|Descrição|Autor|Revisor|
|:----:|----|---------|-----|:-------:|
|`1.0`|16/05/2024|Criação do documento e adição dos lexicos|[Bianca Castro](https://github.com/BiancaPatrocinio7)||