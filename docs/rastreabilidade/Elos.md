# Elos

## Introdução

### Backward-from

A rastreabilidade backward-from é um processo crítico na engenharia de requisitos, que permite a ligação dos requisitos às suas fontes originais. Esse tipo de rastreabilidade é essencial para garantir que todos os requisitos identificados tenham uma origem bem definida, facilitando a validação e verificação durante o ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade backward-from ajuda a gerenciar mudanças ao rastrear de volta cada requisito até suas bases, assegurando que qualquer modificação no sistema possa ser rapidamente associada à sua origem, permitindo uma resposta eficaz a alterações e garantindo a conformidade com os requisitos iniciais do projeto.<a id="RP1" href="#TEC1">[1]</a> 

### Forward-from

A rastreabilidade forward-to é um componente essencial na engenharia de requisitos, que possibilita a ligação dos requisitos aos artefatos subsequentes, como design, código, testes e documentação. Esse tipo de rastreabilidade é crucial para assegurar que todos os requisitos sejam devidamente implementados e testados ao longo do ciclo de vida do desenvolvimento do software. Além disso, a rastreabilidade forward-to facilita a gestão de mudanças, permitindo que qualquer alteração nos requisitos seja refletida de maneira consistente em todos os artefatos afetados. Isso garante que as modificações sejam corretamente incorporadas e verificadas, mantendo a integridade e a conformidade do sistema em relação aos requisitos definidos inicialmente. <a id="RP2" href="#TEC2">[2]</a>

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
  <strong>Tabela 2 -</strong> Cartão do Requisito 01 - C01
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
  <strong>Tabela 3 -</strong> Cartão do Requisito 02 - C02
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
  <strong>Tabela 4 -</strong> Cartão do Requisito 03 - C03
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
  <strong>Tabela 5 -</strong> Cartão do Requisito 04 - C04
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE04, BS04, BS13, ENT05, ST08, QT08, UC04, CEN03                           |
| **Elos Backward-from:**  | Agregação: RE04 - BS04, BS13, ENT05, ST08, QT08: O requisito originou-se de um Brainstorm, Entrevista, Storytelling e de um Questionário. |
| **Elos Forward-from:**   | Satisfação: RE04 - UC04: O requisito RE04 deu origem ao caso de uso UC04. <br> Satisfação: RE03 - CEN03: O requisito RE04 contribui para o cenário CEN03. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE05

<div align="center">
  <strong>Tabela 6 -</strong> Cartão do Requisito 05 - C05
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS05, QT08, CEN03                           |
| **Elos Backward-from:**  | Agregação: RE05 - BS05, QT08: O requisito originou-se de um Brainstorm e de um Questionário. |
| **Elos Forward-from:**   | Satisfação: RE05 - UCN03: O requisito RE05 contribui para o cenário CEN03. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE06

<div align="center">
  <strong>Tabela 7 -</strong> Cartão do Requisito 06 - C06
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS06, UC04, CEN07                           |
| **Elos Backward-from:**  | Agregação: RE06 - BS06: O requisito originou-se de um Brainstorm. |
| **Elos Forward-from:**   | Satisfação: RE06 - UC04: O requisito RE06 deu origem ao caso de uso UC04. <br> Satisfação: RE06 - CEN07: O requisito RE06 contribui para o cenário CEN07. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE07

<div align="center">
  <strong>Tabela 8 -</strong> Cartão do Requisito 07 - C07
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS07, BS11, IT02, IT05, ST01, ST07, ENT10, QT02, QT05, CEN02                           |
| **Elos Backward-from:**  | Agregação: RE07 - BS07, BS11, IT02, IT05, ST01, ST07, ENT10, QT02, QT05: O requisito originou-se de um Brainstorm, Introspecção, Storytelling, Entrevista e de um questionário. |
| **Elos Forward-from:**   | Satisfação: RE07 - CEN02: O requisito RE07 contribui para o cenário CEN02. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE08

<div align="center">
  <strong>Tabela 9 -</strong> Cartão do Requisito 08 - C08
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS08, BS12, IT06, ENT07, ST20, QT02, QT03, UC07, UC11                           |
| **Elos Backward-from:**  | Agregação: RE08 - BS08, BS12, IT06, ENT07, ST20, QT02, QT03: O requisito originou-se de um Brainstorm, Introspecção, Storytelling, Entrevista e de um questionário. |
| **Elos Forward-from:**   | Satisfação: RE08 - UC08, UC11: O requisito RE08 deu origem aos casos de uso UC08 e UC11. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE09

<div align="center">
  <strong>Tabela 10 -</strong> Cartão do Requisito 09 - C09
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS09, ENT11, ENT08, QT02, UC08                           |
| **Elos Backward-from:**  | Agregação: RE09 - BS09, ENT11, ENT08, QT02: O requisito originou-se de um Brainstorm, Entrevista e de um questionário. |
| **Elos Forward-from:**   | Satisfação: RE09 - UC08: O requisito RE09 deu origem ao caso de uso UC08. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE10

<div align="center">
  <strong>Tabela 11 -</strong> Cartão do Requisito 10 - C10
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT14, UC08                           |
| **Elos Backward-from:**  | Agregação: RE10 - ENT14: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE10 - UC08: O requisito RE10 deu origem ao caso de uso UC08. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE11

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito 11 - C11
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT15, UC08, UC10                          |
| **Elos Backward-from:**  | Agregação: RE11 - ENT15: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE11 - UC08, UC10: O requisito RE11 deu origem aos casos de uso UC08 e UC10. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE12

<div align="center">
  <strong>Tabela 13 -</strong> Cartão do Requisito 12 - C12
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | BS10, QT01, CEN01                          |
| **Elos Backward-from:**  | Agregação: RE12 - BS10, QT01: O requisito originou-se de um Brainstorm e de um Questionário. |
| **Elos Forward-from:**   | Satisfação: RE12 - CEN01: O requisito RE12 contribui para o cenário CEN01. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE13

<div align="center">
  <strong>Tabela 14 -</strong> Cartão do Requisito 13 - C13
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT01, UC09                          |
| **Elos Backward-from:**  | Agregação: RE13 - ENT01: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE13 - UC09: O requisito RE13 deu origem ao caso de uso UC09. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE14

<div align="center">
  <strong>Tabela 15 -</strong> Cartão do Requisito 14 - C14
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT02, UC07, CEN02, CEN04                          |
| **Elos Backward-from:**  | Agregação: RE14 - ENT02: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE14 - UC07: O requisito RE14 deu origem ao caso de uso UC07. <br> Satisfação: RE14 - CEN02, CEN04: O requisito RE14 contribui para os cenários CEN02 e CEN04. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE15

<div align="center">
  <strong>Tabela 16 -</strong> Cartão do Requisito 15 - C15
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT03, UC06, UC07, UC09, CEN04                          |
| **Elos Backward-from:**  | Agregação: RE15 - ENT03: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE15 - UC06, UC07, UC09: O requisito RE15 deu origem aos casos de uso UC06, UC07, UC09. <br> Satisfação: RE15 - CEN04: O requisito RE15 contribui para o cenário CEN04. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE16

<div align="center">
  <strong>Tabela 17 -</strong> Cartão do Requisito 16 - C16
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT04, ENT08, CEN02                          |
| **Elos Backward-from:**  | Agregação: RE16 - ENT04, ENT08: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE16 - CEN02: O requisito RE16 contribui para o cenário CEN02. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE17

<div align="center">
  <strong>Tabela 18 -</strong> Cartão do Requisito 17 - C17
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT06, IT07, UC02, CEN05                          |
| **Elos Backward-from:**  | Agregação: RE17 - ENT06, IT07: O requisito originou-se de uma Entrevista e uma Introspecção. |
| **Elos Forward-from:**   | Satisfação: RE17 - UC02: O requisito RE17 deu origem ao caso de uso UC02. <br> Satisfação: RE17 - CEN05: O requisito RE17 contribui para o cenário CEN05.|

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE18

<div align="center">
  <strong>Tabela 19 -</strong> Cartão do Requisito 18 - C18
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | ENT12, UC10                         |
| **Elos Backward-from:**  | Agregação: RE18 - ENT12: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Satisfação: RE18 - UC10: O requisito RE18 deu origem ao caso de uso UC10. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE19

<div align="center">
  <strong>Tabela 20 -</strong> Cartão do Requisito 19 - C19
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE19, ENT13,   , UC10, BC, US19,                         |
| **Elos Backward-from:**  | Satisfação: RE19 - ENT13: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | Agregação: RE19 - UC10: O requisito RE19 está no conjunto que deu origem ao caso de uso UC10. <br> Satisfação: RE19 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> Satisfação: RE19 - CDS: O requisito recebeu um valor de $4 do Desenvolvedor e $2 do Usuário na técnica $100. <br> Satisfação: RE19 - FTF: O requisito recebeu uma pontuação de 1,69 no First Things First. <br> Agregação: RE19 - BC: O requisito e a US19 são classificados no Épico 2.1 do Backlog. <br> Satisfação: RE19 - US19: O requisito foi utilizado para produzir a História de Usuário 19.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE20

<div align="center">
  <strong>Tabela 21 -</strong> Cartão do Requisito 20 - C20
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE20, IT01, TLS, CDS, FTF, BC, US20                         |
| **Elos Backward-from:**  | Satisfação: RE20 - IT01: O requisito originou-se de uma Instrospecção. |
| **Elos Forward-from:**   | Satisfação: RE20 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> Satisfação: RE20 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $4 do Usuário na técnica $100. <br> Satisfação: RE20 - FTF: O requisito recebeu uma pontuação de 1,40 no First Things First. <br> Agregação: RE20 - BC: O requisito e a US20 são classificados no Épico 1.1 do Backlog. <br> Satisfação: RE20 - US20: O requisito foi utilizado para produzir a História de Usuário 20.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE21

<div align="center">
  <strong>Tabela 22 -</strong> Cartão do Requisito 21 - C21
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE21, IT03, TLS, CDS, FTF, UC04, UC05, BC, US21.1, US21.2, US21.3                         |
| **Elos Backward-from:**  | Satisfação: RE21 - IT03: O requisito originou-se de uma Introspecção. |
| **Elos Forward-from:**   | Satisfação: RE21 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> Satisfação: RE21 - CDS: O requisito recebeu um valor de $4 do Desenvolvedor e $2 do Usuário na técnica $100. <br> Satisfação: RE21 - FTF: O requisito recebeu uma pontuação de 1,44 no First Things First. <br> Agregação: RE21 - BC: O requisito e as US21.1, US21.2 e US21.3 são classificados no Épico 2.2 do Backlog. <br> Agregação: RE21 - UC04: O requisito RE21 está no conjunto que deu origem ao caso de uso UC04. <br> Agregação: RE21 - UC05: O requisito RE21 está no conjunto que deu origem ao caso de uso UC05. <br> Satisfação: RE21 - US21.N: O requisito deu origem às US21.N.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE22

<div align="center">
  <strong>Tabela 23 -</strong> Cartão do Requisito 22 - C22
</div>

<center>

| **Categoria:**           | Desenvolvimento                 |
|:--|:--|
| **Elementos:**           | RE22, IT04, TLS, CDS, FTF, BC, UC06, US22                       |
| **Elos Backward-from:**  | Satisfação: RE22 - IT04: O requisito originou-se de uma Instrospecção. |
| **Elos Forward-from:**   | Satisfação: RE22 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> Satisfação: RE22 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $4 do Usuário na técnica $100. <br> Satisfação: RE22 - FTF: O requisito recebeu uma pontuação de 1,80 no First Things First. <br> Agregação: RE22 - BC: O requisito e a US22 são classificados no Épico 3.2 do Backlog. <br> Satisfação: RE22 - US22: O requisito deu origem a US22.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE23

<div align="center">
  <strong>Tabela 24 -</strong> Cartão do Requisito 23 - C23
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE23, ST03, TLS, CDS, FTF, BC, US23                         |
| **Elos Backward-from:**  | Satisfação: RE23 - ST03: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | Satisfação: RE23 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> Satisfação: RE23 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $5 do Usuário na técnica $100. <br> Satisfação: RE23 - FTF: O requisito recebeu uma pontuação de 1,64 no First Things First. <br> Agregação: RE23 - BC: O requisito e a US23 são classificados no Épico 1.2 do Backlog. <br> Satisfação: RE23 - US23: O requisito deu origem a US23. |

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE24

<div align="center">
  <strong>Tabela 25 -</strong> Cartão do Requisito 24 - C24
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE24, ST05, TLS, CDS, FTF, BC, US24, UC06                          |
| **Elos Backward-from:**  | Satisfação: RE24 - ST05: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | Satisfação: RE24 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> Satisfação: RE24 - CDS: O requisito recebeu um valor de $2 do Desenvolvedor e $3 do Usuário na técnica $100. <br> Satisfação: RE24 - FTF: O requisito recebeu uma pontuação de 1,71 no First Things First. <br> Agregação: RE24 - BC: O requisito e a US24 são classificados no Épico 2.1 do Backlog. <br> Satisfação: RE24 - US24: O requisito deu origem a US24. <br> Agregação: RE24 - UC06: O requisito RE24 está no conjunto que deu origem ao caso de uso UC06.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE25

<div align="center">
  <strong>Tabela 26 -</strong> Cartão do Requisito 25 - C25
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | RE25, ST06, TLS, CDS, FTF, BC, US25, UC06                         |
| **Elos Backward-from:**  | Satisfação: RE25 - ST06: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | Satisfação: RE25 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> Satisfação: RE25 - CDS: O requisito recebeu um valor de $3 do Desenvolvedor e $2 do Usuário na técnica $100. <br> Satisfação: RE25 - FTF: O requisito recebeu uma pontuação de 1,64 no First Things First. <br> Agregação: RE25 - BC: O requisito e a US25 são classificados no Épico 2.1 do Backlog. <br> Satisfação: RE25 - US25: O requisito deu origem a US25. <br> Agregação: RE25 - UC06: O requisito RE25 está no conjunto que deu origem ao caso de uso UC06. |

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>


## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 21 jun. 2024.

> <a id="RP2" href="#TEC2">2.</a> Kotonya, Gerald, and Ian Sommerville. "Requirements Engineering: Processes and Techniques." John Wiley & Sons, 1998. Disponível em: (https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf).Acesso em: 22 jun. 2024.

## Bibliografia
> </a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 18 jun. 2024.

> </a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf). Acesso em: 18 jun. 2024.

> </a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: [https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 18 jun. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 21/06/2024  | Criação da página | [Johnny Lopes](https://github.com/JohnnyLopess) |  |  |
| `1.1` | 23/06/2024  | Adicionando informações na página | [Paulo Borba](https://github.com/paulohborba) |  |  |
