# Elos

## Introdução

### Backward-from

A rastreabilidade backward-from é um processo crítico na engenharia de requisitos, que permite a ligação dos requisitos às suas fontes originais. Esse tipo de rastreabilidade é essencial para garantir que todos os requisitos identificados tenham uma origem bem definida, facilitando a validação e verificação durante o ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade backward-from ajuda a gerenciar mudanças ao rastrear de volta cada requisito até suas bases, assegurando que qualquer modificação no sistema possa ser rapidamente associada à sua origem, permitindo uma resposta eficaz a alterações e garantindo a conformidade com os requisitos iniciais do projeto.<a id="RP1" href="#TEC1">[1]</a>

### Forward-from


## Metodologia

### Cartões de Relacionamento dos Elos

<div align="center">
  <strong>Tabela 1 -</strong> Exemplo de cartão
</div>

<div align="center">
  <table>
    <tr>
      <td><strong>Categoria:</strong></td>
      <td>Desenvolvimento</td>
    </tr>
    <tr>
      <td><strong>Elementos:</strong></td>
      <td>RE01, UC01, CE01, ENT01</td>
    </tr>
    <tr>
      <td><strong>Elos Backward-from:</strong></td>
      <td>Agregação: RE01 - ENT01: O requisito originou-se da entrevista.</td>
    </tr>
    <tr>
      <td><strong>Elos Forward-from:</strong></td>
      <td>
        Satisfação: RE01 - CS01: O requisito deu origem ao caso de uso.<br>
        Satisfação: RE01 - CE01: O requisito deu origem ao cenário.
      </td>
    </tr>
  </table>
</div>

<p align="center">Autor: <a href="https://github.com/Requisitos-de-Software/2024.1-Meu-INSS">Todos</a>, 2024.</p>

Legenda:

- **Categoria**: Devem ser classificadas em quatro níveis
    - **Ambiental**: Congrega informações oriundas do contexto ambiental onde a organização está inserida e que podem afetar o sistema sendo desenvolvido.
    - **Organizacional**: Reúne informações relacionadas à organização (missão, objetivos, metas e padrões) e que podem impactar os requisitos do sistema.
    - **Gerencial**: Agrega informações que permitem associar tarefas a requisitos, e que podem auxiliar a gerência do projeto.
    - **Desenvolvimento**: Abarca informações relacionadas aos diversos artefatos gerados no processo de desenvolvimento (documento de requisitos, diagramas, programas, casos de testes, ...).
- **Elementos**: Lista de identificadores que representam [requisitos](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/requisitosElicitados/) (RE01), [casos de uso](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/useCase/) (US01), [cenários](https://requisitos-de-software.github.io/2024.1-Meu-INSS/modelagem/cenarios/) (CEN01) e [técnicas de elicitação de requisitos](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/brainStorm/) (ENT01).
- **Elos Backward-from**: Primeiro, mostra-se o tipo de elo e depois a origem do requisito. Por exemplo, o requisito REQ01 originou-se da entrevista ENT01.
- **Elos Forward-from**: Primeiro, mostra-se o tipo de elo e como o requisito é satisfeito ou relacionado a outros elementos. Por exemplo, o requisito RE01 deu origem ao caso de uso CS01 e ao cenário CE01.
- **Tipos de Elos**:
    - **Satisfação**: Indica que a classe de origem tem dependência de satisfação com a classe de destino.
    - **Recurso**: Indica que a classe de origem tem dependência de recurso com a classe de destino.
    - **Responsabilidade**: Registra a participação, responsabilidade e ação de pessoas sobre artefatos.
    - **Representação**: Captura a representação ou modelagem dos requisitos em outras linguagens.
    - **Alocado**: Classe de origem está relacionada à classe de destino, que representa um subsistema.
    - **Agregação**: Indica composição de elementos.


### RE01

<div align="center">
  <strong>Tabela 2 -</strong> Cartão do Requisito 01
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE01, BS01, ST02, QT01, CEN01, UC01                           |
| **Elos Backward-from:**  | Agregação: RE01 - BS01, ST02, QT01: O requisito originou-se de um Brainstorm, storytelling e de um questionário. |
| **Elos Forward-from:**   | Satisfação: RE01 - UC01: O requisito RE01 contribui para a satisfação do caso de uso UC01. <br> Satisfação: RE01 - CEN01: O requisito RE02 contribui para a satisfação do cenário CEN01. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE02

<div align="center">
  <strong>Tabela 3 -</strong> Cartão do Requisito 02
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE02, BS02, CEN01, UC01                            |
| **Elos Backward-from:**  | Agregação: RE02 - BS02: O requisito originou-se do Brainstorm. |
| **Elos Forward-from:**   | Satisfação: RE02 - UC01: O requisito RE02 contribui para a satisfação do caso de uso UC01. <br> Satisfação: RE02 - CEN01: O requisito RE02 contribui para a satisfação do cenário CEN01. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE03

<div align="center">
  <strong>Tabela 4 -</strong> Cartão do Requisito 03
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE03, BS03, CEN02, UC03                            |
| **Elos Backward-from:**  | Agregação: RE03 - BS03: O requisito originou-se do Brainstorm. |
| **Elos Forward-from:**   | Satisfação: RE03 - UC03: O requisito RE03 deu origem ao caso de uso UC03. <br> Recurso: RE03 - CEN02: O requisito RE03 contribui para o cenário CEN02. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE04

<div align="center">
  <strong>Tabela 5 -</strong> Cartão do Requisito 04
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE04, BS04, BS13, ENT05, ST08, QT08, UC04, CEN03                           |
| **Elos Backward-from:**  | Agregação: RE04 - BS04, BS13, ENT05, ST08, QT08: O requisito originou-se de um Brainstorm, Entrevista, Storytelling e de um Questionário. |
| **Elos Forward-from:**   | Satisfação: RE04 - UC04: O requisito RE04 deu origem ao caso de uso UC04. <br> Satisfação: RE03 - CEN03: O requisito RE04 contribui para o cenário CEN03. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

## Referências Bibliográficas
> <a id="RP1" href="#TEC1">1.</a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 21 jun. 2024.

## Bibliografia
> </a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 21 jun. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 21/06/2024  | Criação da página | [Johnny Lopes](https://github.com/JohnnyLopess) |  |  |
