# Elos

## Introdução
Os elos de rastreabilidade são conexões essenciais que estabelecem vínculos entre diferentes artefatos e atividades ao longo do ciclo de vida de um projeto ou sistema. Esses elos permitem rastrear a origem e a evolução de funcionalidades, decisões de projeto e mudanças, garantindo um gerenciamento eficaz e uma qualidade consistente. Utilizando a rastreabilidade, é possível identificar a proveniência de cada funcionalidade do sistema, assegurar que todos os requisitos foram devidamente testados e validados, registrar decisões críticas para o projeto e gerenciar os riscos de maneira eficiente. Além disso, a rastreabilidade facilita o controle de mudanças ao indicar quais artefatos são impactados por alterações específicas, promovendo uma gestão integrada e transparente do desenvolvimento e manutenção de sistemas.<a id="RP1" href="#TEC1">[1]</a> 

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
- **Elementos**: Lista de identificadores que representam [requisitos](../../elicitacao/requisitosElicitados) (RE01), [casos de uso](../../modelagem/useCase) (US01), [cenários](../../modelagem/cenarios) (CEN01) e [técnicas de elicitação de requisitos](../../elicitacao/brainStorm) (ENT01).
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
| **Elementos:**           | [RE01](../../elicitacao/requisitosElicitados), [BS01](../../elicitacao/brainStorm), [ST02](../../elicitacao/storytelling), [QT01](../../elicitacao/questionario), [UC01](../../modelagem/useCase), [CEN01](../../modelagem/cenarios), [US01](../../modelagem/Agil/historia_de_usuario)|
| **Elos Backward-from:**  | Agregação: RE01 - BS01, ST02, QT01: O requisito originou-se de um Brainstorm, storytelling e de um questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE01 - UC01: O caso de uso (UC01) satisfaz o requisito (RE01) ao descrever o processo de login unificado pelo gov.br. <br> Recurso: RE01 - CEN01: O cenário detalha os recursos necessários para que o usuário realize o login unificado pelo gov.br, conforme requerido pelo RE01. <br> **Satisfação**: RE01 - US01: A história de usuário (US01) satisfaz o requisito (RE01) ao especificar a necessidade de login seguro e integrado pelo gov.br. <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE01.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE02

<div align="center">
  <strong>Tabela 3 -</strong> Cartão do Requisito 02 - C02
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE02](../../elicitacao/requisitosElicitados), [BS02](../../elicitacao/brainStorm), [UC01](../../modelagem/useCase), [CEN01](../../modelagem/cenarios), [US02](../../modelagem/Agil/historia_de_usuario)                            |
| **Elos Backward-from:**  | **Agregação**: RE02 - BS02: O requisito originou-se do Brainstorm. |
| **Elos Forward-from:**   | **Satisfação**: RE02 - UC01: O caso de uso (UC01) inclui um fluxo alternativo que exige que o usuário aceite os termos de uso no primeiro acesso, satisfazendo o requisito (RE02). <br> **Recurso**: RE02 - CEN01: O cenário (CEN01) detalha os recursos necessários para o usuário acessar o aplicativo e receber o termo de uso no primeiro acesso, conforme requerido pelo RE02. <br> **Satisfação**: RE02 - US02:  história de usuário (US02) satisfaz o requisito (RE02) ao especificar que o usuário deve receber e aceitar o termo de uso no primeiro acesso. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE03

<div align="center">
  <strong>Tabela 4 -</strong> Cartão do Requisito 03 - C03
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE03](../../elicitacao/requisitosElicitados), [BS03](../../elicitacao/brainStorm), [UC03](../../modelagem/useCase), [CEN02](../../modelagem/cenarios), [US03](../../modelagem/Agil/historia_de_usuario)                             |
| **Elos Backward-from:**  | **Agregação**: RE03 - BS03: O requisito originou-se do Brainstorm. |
| **Elos Forward-from:**   | **Satisfação**: RE03 - UC03: O caso de uso (UC03) satisfaz o requisito (RE03) ao permitir que o usuário visualize documentos legislativos no sistema. <br> **Agregação**: RE03 - CEN02: O cenário (CEN02) detalha um processo diferente, mas os recursos descritos podem ser parte de uma agregação para acessar várias funcionalidades do sistema, incluindo documentos legislativos. <br> **Satisfação**: RE03 - US03: A história de usuário (US03) satisfaz o requisito (RE03) ao descrever a necessidade de acesso a documentos legislativos para acompanhar a legislação vigente.|

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE04

<div align="center">
  <strong>Tabela 5 -</strong> Cartão do Requisito 04 - C04
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE04](../../elicitacao/requisitosElicitados), [BS04](../../elicitacao/brainStorm), [BS13](../../elicitacao/brainStorm), [ENT05](../../elicitacao/entrevista), [ST08](../../elicitacao/storytelling), [QT08](../../elicitacao/questionario), [UC04](../../modelagem/useCase), [CEN03](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE04 - BS04, BS13: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE04 - ENT05: O requisito origino-se de uma Entrevista. <br> **Agregação**: RE04 - ST08 O requisito origino-se de um Storytelling. <br> **Agregação**: RE04 - QT08: O requisito origino-se de um Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE04 - UC04: O requisito RE04 deu origem ao caso de uso UC04. <br> **Satisfação**: RE03 - CEN03: O requisito RE04 contribui para o cenário CEN03. <br> **Satisfação**: RE04 - CDS: O requisito recebeu uma pontuação $8 do Desenvolvedor e $10 do Usuário na técnica $100. <br> **Satisfação**: RE04 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE05

<div align="center">
  <strong>Tabela 6 -</strong> Cartão do Requisito 05 - C05
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE05](../../elicitacao/requisitosElicitados), [BS05](../../elicitacao/brainStorm), [QT08](../../elicitacao/questionario), [CEN03](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE05 - BS05: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE05 - QT08: O requisito origino-se de um Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE05 - UCN03: O requisito RE05 contribui para o cenário CEN03. <br> **Satisfação**: RE05 - CDS: O requisito recebeu uma pontuação $9 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE05 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE06

<div align="center">
  <strong>Tabela 7 -</strong> Cartão do Requisito 06 - C06
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE06](../../elicitacao/requisitosElicitados), [BS06](../../elicitacao/brainStorm), [UC04](../../modelagem/useCase), [CEN07](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE06 - BS06: O requisito originou-se de um Brainstorm. |
| **Elos Forward-from:**   | **Satisfação**: RE06 - UC04: O requisito RE06 deu origem ao caso de uso UC04. <br> **Satisfação**: RE06 - CEN07: O requisito RE06 contribui para o cenário CEN07. <br> **Satisfação**: RE06 - CDS: O requisito recebeu uma pontuação $3 do Desenvolvedor e $3 do Usuário na técnica $100. <br> **Satisfação**: RE06 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.|

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE07

<div align="center">
  <strong>Tabela 8 -</strong> Cartão do Requisito 07 - C07
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE07](../../elicitacao/requisitosElicitados), [BS07](../../elicitacao/brainStorm), [BS11](../../elicitacao/brainStorm), [IT02](../../elicitacao/Introspeccao), [IT05](../../elicitacao/Introspeccao), [ST01](../../elicitacao/storytelling), [ST07](../../elicitacao/storytelling), [ENT10](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario), [QT05](../../elicitacao/questionario), [CEN02](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE07 - BS07, BS11: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE07 - IT02, IT05 O requisito origino-se de uma Introspecção. <br> **Agregação**: RE07 - ST01, ST07 O requisito origino-se de um Storytelling. <br> **Agregação**: RE07 - ENT10: O requisito origino-se de uma Entrevista. <br> **Agregação**: RE07 - QT02, QT05: O requisito origino-se de um Questionário.|
| **Elos Forward-from:**   | **Satisfação**: RE07 - CEN02: O requisito RE07 contribui para o cenário CEN02. <br> **Satisfação**: RE07 - CDS: O requisito recebeu uma pontuação $8 do Desenvolvedor e $12 do Usuário na técnica $100. <br> **Satisfação**: RE07 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE07.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE08

<div align="center">
  <strong>Tabela 9 -</strong> Cartão do Requisito 08 - C08
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE08](../../elicitacao/requisitosElicitados), [BS08](../../elicitacao/brainStorm), [BS12](../../elicitacao/brainStorm), [IT06](../../elicitacao/Introspeccao), [ENT07](../../elicitacao/entrevista), [ST20](../../elicitacao/storytelling), [QT02](../../elicitacao/questionario), [QT03](../../elicitacao/questionario), [UC07](../../modelagem/useCase), [UC11](../../modelagem/useCase) |
| **Elos Backward-from:**  | **Agregação**: RE08 - BS08, BS12: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE08 - IT06 O requisito origino-se de uma Introspecção. <br> **Agregação**: RE08 - ENT07: O requisito origino-se de uma Entrevista. <br> **Agregação**: RE08 - ST20: O requisito origino-se de um Storytelling. <br> **Agregação**: RE08 - QT02, QT03: O requisito origino-se de um Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE08 - UC08, UC11: O requisito RE08 deu origem aos casos de uso UC08 e UC11. <br> **Satisfação**: RE08 - CDS: O requisito recebeu uma pontuação $9 do Desenvolvedor e $20 do Usuário na técnica $100. <br> **Satisfação**: RE08 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE09

<div align="center">
  <strong>Tabela 10 -</strong> Cartão do Requisito 09 - C09
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE09](../../elicitacao/requisitosElicitados), [BS09](../../elicitacao/brainStorm), [ENT11](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista), [QT02](../../elicitacao/questionario), [UC08](../../modelagem/useCase) |
| **Elos Backward-from:**  | **Agregação**: RE09 - BS09: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE09 - ENT11, ENT08: O requisito origino-se de uma Entrevista <br> **Agregação**: RE09 - QT02: O requisito origino-se de um Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE09 - UC08: O requisito RE09 deu origem ao caso de uso UC08. <br> **Satisfação**: RE09 - CDS: O requisito recebeu uma pontuação $2 do Desenvolvedor e $5 do Usuário na técnica $100. <br> **Satisfação**: RE09 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024.</p>

### RE10

<div align="center">
  <strong>Tabela 11 -</strong> Cartão do Requisito 10 - C10
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE10](../../elicitacao/requisitosElicitados), [ENT14](../../elicitacao/entrevista), [UC08](../../modelagem/useCase)                           |
| **Elos Backward-from:**  | **Agregação**: RE10 - ENT14: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE10 - UC08: O requisito RE10 deu origem ao caso de uso UC08. <br> **Satisfação**: RE10 - CDS: O requisito recebeu uma pontuação $2 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE10 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024.</p>

### RE11

<div align="center">
  <strong>Tabela 12 -</strong> Cartão do Requisito 11 - C11
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE11](../../elicitacao/requisitosElicitados), [ENT15](../../elicitacao/entrevista), [UC08](../../modelagem/useCase), [UC10](../../modelagem/useCase) |
| **Elos Backward-from:**  | **Agregação**: RE11 - ENT15: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE11 - UC08, UC10: O requisito RE11 deu origem aos casos de uso UC08 e UC10. <br> **Satisfação**: RE11 - CDS: O requisito recebeu uma pontuação $2 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE11 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024.</p>

### RE12

<div align="center">
  <strong>Tabela 13 -</strong> Cartão do Requisito 12 - C12
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE12](../../elicitacao/requisitosElicitados), [BS10](../../elicitacao/brainStorm), [QT01](../../elicitacao/questionario), [CEN01](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE12 - BS10: O requisito originou-se de um Brainstorm. <br> **Agregação**: RE12 - QT01: O requisito origino-se de um Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE12 - CEN01: O requisito RE12 contribui para o cenário CEN01. <br> **Satisfação**: RE12 - CDS: O requisito recebeu uma pontuação $8 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE12 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024.</p>

### RE13

<div align="center">
  <strong>Tabela 14 -</strong> Cartão do Requisito 13 - C13
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE13](../../elicitacao/requisitosElicitados), [ENT01](../../elicitacao/entrevista), [UC09](../../modelagem/useCase)                          |
| **Elos Backward-from:**  | **Agregação**: RE13 - ENT01: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE13 - UC09: O requisito RE13 deu origem ao caso de uso UC09. <br> **Satisfação**: RE13 - CDS: O requisito recebeu uma pontuação $7 do Desenvolvedor e $10 do Usuário na técnica $100. <br> **Satisfação**: RE13 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE13.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024.</p>

### RE14

<div align="center">
  <strong>Tabela 15 -</strong> Cartão do Requisito 14 - C14
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE14](../../elicitacao/requisitosElicitados), [ENT02](../../elicitacao/entrevista), [UC07](../../modelagem/useCase), [CEN02](../../modelagem/cenarios), [CEN04](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE14 - ENT02: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE14 - UC07: O requisito RE14 deu origem ao caso de uso UC07. <br> **Satisfação**: RE14 - CEN02, CEN04: O requisito RE14 contribui para os cenários CEN02 e CEN04. <br> **Satisfação**: RE14 - CDS: O requisito recebeu uma pontuação 9 do Desenvolvedor e 5 do Usuário na técnica $100. <br> **Satisfação**: RE14 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> Representação: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE14.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024.</p>

### RE15

<div align="center">
  <strong>Tabela 16 -</strong> Cartão do Requisito 15 - C15
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE15](../../elicitacao/requisitosElicitados), [ENT03](../../elicitacao/entrevista), [UC06](../../modelagem/useCase), [UC07](../../modelagem/useCase), [UC09](../../modelagem/useCase), [CEN04](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE15 - ENT03: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE15 - UC06, UC07, UC09: O requisito RE15 deu origem aos casos de uso UC06, UC07, UC09. <br> **Satisfação**: RE15 - CEN04: O requisito RE15 contribui para o cenário CEN04. <br> **Satisfação**: RE15 - CDS: O requisito recebeu uma pontuação $6 do Desenvolvedor e $4 do Usuário na técnica $100. <br> **Satisfação**: RE15 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE15.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024.</p>

### RE16

<div align="center">
  <strong>Tabela 17 -</strong> Cartão do Requisito 16 - C16
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE16](../../elicitacao/requisitosElicitados), [ENT04](../../elicitacao/entrevista), [ENT08](../../elicitacao/entrevista), [CEN02](../../modelagem/cenarios)                          |
| **Elos Backward-from:**  | **Agregação**: RE16 - ENT04, ENT08: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE16 - CEN02: O requisito RE16 contribui para o cenário CEN02. <br> **Satisfação**: RE16 - CDS: O requisito recebeu uma pontuação $6 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE16 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024.</p>

### RE17

<div align="center">
  <strong>Tabela 18 -</strong> Cartão do Requisito 17 - C17
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE17](../../elicitacao/requisitosElicitados), [ENT06](../../elicitacao/entrevista), [IT07](../../elicitacao/Introspeccao), [UC02](../../modelagem/useCase), [CEN05](../../modelagem/cenarios) |
| **Elos Backward-from:**  | **Agregação**: RE17 - ENT06: O requisito originou-se de uma Entrevista. <br> **Agregação**: RE17 - IT07: O requisito origino-se de uma Introspecção.  |
| **Elos Forward-from:**   | **Satisfação**: RE17 - UC02: O requisito RE17 deu origem ao caso de uso UC02. <br> **Satisfação**: RE17 - CEN05: O requisito RE17 contribui para o cenário CEN05. <br> **Satisfação**: RE17 - CDS: O requisito recebeu uma pontuação $9 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE17 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE17.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024.</p>

### RE18

<div align="center">
  <strong>Tabela 19 -</strong> Cartão do Requisito 18 - C18
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE18](../../elicitacao/requisitosElicitados), [ENT12](../../elicitacao/entrevista), [UC10](../../modelagem/useCase)                         |
| **Elos Backward-from:**  | **Agregação**: RE18 - ENT12: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE18 - UC10: O requisito RE18 deu origem ao caso de uso UC10. <br> **Satisfação**: RE18 - CDS: O requisito recebeu uma pontuação $2 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE18 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. |

</center>

<p align="center">Autor: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024.</p>

### RE19

<div align="center">
  <strong>Tabela 20 -</strong> Cartão do Requisito 19 - C19
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE19](../../elicitacao/requisitosElicitados), [ENT13](../../elicitacao/entrevista), [UC10](../../modelagem/useCase), [BC](../../modelagem/Agil/backlog), [US19](../../modelagem/Agil/historia_de_usuario)                   |
| **Elos Backward-from:**  | **Satisfação**: RE19 - ENT13: O requisito originou-se de uma Entrevista. |
| **Elos Forward-from:**   | **Agregação**: RE19 - UC10: O requisito RE19 está no conjunto que deu origem ao caso de uso UC10. <br> **Satisfação**: RE19 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Satisfação**: RE19 - CDS: O requisito recebeu um valor de $4 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE19 - FTF: O requisito recebeu uma pontuação de 1,69 no First Things First. <br> **Agregação**: RE19 - BC: O requisito e a US19 são classificados no Épico 2.1 do Backlog. <br> **Satisfação**: RE19 - US19: O requisito foi utilizado para produzir a História de Usuário 19.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE20

<div align="center">
  <strong>Tabela 21 -</strong> Cartão do Requisito 20 - C20
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE20](../../elicitacao/requisitosElicitados), [IT01](../../elicitacao/Introspeccao), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog), [US20](../../modelagem/Agil/historia_de_usuario)                        |
| **Elos Backward-from:**  | **Satisfação**: RE20 - IT01: O requisito originou-se de uma Instrospecção. |
| **Elos Forward-from:**   | **Satisfação**: RE20 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> **Satisfação**: RE20 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $4 do Usuário na técnica $100. <br> **Satisfação**: RE20 - FTF: O requisito recebeu uma pontuação de 1,40 no First Things First. <br> **Agregação**: RE20 - BC: O requisito e a US20 são classificados no Épico 1.1 do Backlog. <br> **Satisfação**: RE20 - US20: O requisito foi utilizado para produzir a História de Usuário 20.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE21

<div align="center">
  <strong>Tabela 22 -</strong> Cartão do Requisito 21 - C21
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE21](../../elicitacao/requisitosElicitados), [IT03](../../elicitacao/Introspeccao),[TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [UC04](../../modelagem/useCase), [UC05](../../modelagem/useCase), [BC](../../modelagem/Agil/backlog), [US21.1](../../modelagem/Agil/historia_de_usuario), [US21.2](../../modelagem/Agil/historia_de_usuario), [US21.3](../../modelagem/Agil/historia_de_usuario)                       |
| **Elos Backward-from:**  | **Satisfação**: RE21 - IT03: O requisito originou-se de uma Introspecção. |
| **Elos Forward-from:**   | **Satisfação**: RE21 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Satisfação**: RE21 - CDS: O requisito recebeu um valor de $4 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE21 - FTF: O requisito recebeu uma pontuação de 1,44 no First Things First. <br> Agregação: RE21 - BC: O requisito e as US21.1, US21.2 e US21.3 são classificados no Épico 2.2 do Backlog. <br> **Agregação**: RE21 - UC04: O requisito RE21 está no conjunto que deu origem ao caso de uso UC04. <br> **Agregação**: RE21 - UC05: O requisito RE21 está no conjunto que deu origem ao caso de uso UC05. <br> **Satisfação**: RE21 - US21.N: O requisito deu origem às US21.N.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE22

<div align="center">
  <strong>Tabela 23 -</strong> Cartão do Requisito 22 - C22
</div>

<center>

| **Categoria:**           | Desenvolvimento                 |
|:--|:--|
| **Elementos:**           | [RE22](../../elicitacao/requisitosElicitados), [IT04](../../elicitacao/Introspeccao),[TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog), [UC06](../../modelagem/useCase), [US22](../../modelagem/Agil/historia_de_usuario)                       |
| **Elos Backward-from:**  | **Satisfação**: RE22 - IT04: O requisito originou-se de uma Instrospecção. |
| **Elos Forward-from:**   | **Satisfação**: RE22 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Satisfação**: RE22 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $4 do Usuário na técnica $100. <br> **Satisfação**: RE22 - FTF: O requisito recebeu uma pontuação de 1,80 no First Things First. <br> **Agregação**: RE22 - BC: O requisito e a US22 são classificados no Épico 3.2 do Backlog. <br> **Satisfação**: RE22 - US22: O requisito deu origem a US22.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE23

<div align="center">
  <strong>Tabela 24 -</strong> Cartão do Requisito 23 - C23
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE23](../../elicitacao/requisitosElicitados), [ST03](../../elicitacao/storytelling), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog), [US23](../../modelagem/Agil/historia_de_usuario)                          |
| **Elos Backward-from:**  | **Satisfação**: RE23 - ST03: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE23 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> **Satisfação**: RE23 - CDS: O requisito recebeu um valor de $6 do Desenvolvedor e $5 do Usuário na técnica $100. <br> **Satisfação**: RE23 - FTF: O requisito recebeu uma pontuação de 1,64 no First Things First. <br> **Agregação**: RE23 - BC: O requisito e a US23 são classificados no Épico 1.2 do Backlog. <br> **Satisfação**: RE23 - US23: O requisito deu origem a US23. |

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE24

<div align="center">
  <strong>Tabela 25 -</strong> Cartão do Requisito 24 - C24
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE24](../../elicitacao/requisitosElicitados), [ST05](../../elicitacao/storytelling), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog), [US24](../../modelagem/Agil/historia_de_usuario), [UC06](../../modelagem/useCase)                         |
| **Elos Backward-from:**  | **Satisfação**: RE24 - ST05: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE24 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale. <br> **Satisfação**: RE24 - CDS: O requisito recebeu um valor de $2 do Desenvolvedor e $3 do Usuário na técnica $100. <br> **Satisfação**: RE24 - FTF: O requisito recebeu uma pontuação de 1,71 no First Things First. <br> **Agregação**: RE24 - BC: O requisito e a US24 são classificados no Épico 2.1 do Backlog. <br> **Satisfação**: RE24 - US24: O requisito deu origem a US24. <br> **Agregação**: RE24 - UC06: O requisito RE24 está no conjunto que deu origem ao caso de uso UC06.|

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE25

<div align="center">
  <strong>Tabela 26 -</strong> Cartão do Requisito 25 - C25
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE25](../../elicitacao/requisitosElicitados), [ST06](../../elicitacao/storytelling), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog), [US25](../../modelagem/Agil/historia_de_usuario), [UC06](../../modelagem/useCase)                         |
| **Elos Backward-from:**  | **Satisfação**: RE25 - ST06: O requisito originou-se de um Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE25 - TLS: O requisito recebeu uma priorização Média no Three Level Scale. <br> **Satisfação**: RE25 - CDS: O requisito recebeu um valor de $3 do Desenvolvedor e $2 do Usuário na técnica $100. <br> **Satisfação**: RE25 - FTF: O requisito recebeu uma pontuação de 1,64 no First Things First. <br> **Agregação**: RE25 - BC: O requisito e a US25 são classificados no Épico 2.1 do Backlog. <br> **Satisfação**: RE25 - US25: O requisito deu origem a US25. <br> **Agregação**: RE25 - UC06: O requisito RE25 está no conjunto que deu origem ao caso de uso UC06. |

</center>

<p align="center">Autor: <a href="https://github.com/JoseFilipi">José Filpi</a>, 2024.</p>

### RE26

<div align="center">
  <strong>Tabela  27-</strong> Cartão do Requisito 26-C26
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE26](../../elicitacao/requisitosElicitados), [ST09](../../elicitacao/storytelling), [UC12](../../modelagem/useCase), [CEN08](../../modelagem/cenarios), [US26](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | **Agregação**: RE26 - ST09: O requisito originou-se da técnica de Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE26 - UC12: O caso de uso (UC12) pode ser visto como uma forma de satisfazer o requisito (RE26). <br> Responsabilidade: RE26 - CEN08: O Cenário (CEN08) detalha a participação e ação dos advogados sobre os processos dos clientes (RE26). <br> **Satisfação**: RE26 - US26: A história de usuário (US26) pode ser vista como uma expressão de satisfação do requisito (RE26). <br> **Representação**: [Print do requisito](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/main/docs/imagens/prints/RE26.jpeg). |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE27

<div align="center">
  <strong>Tabela  28-</strong> Cartão do Requisito 27 - C27
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE27](../../elicitacao/requisitosElicitados), [ST10](../../elicitacao/storytelling),[ST11](../../elicitacao/storytelling), [UC12](../../modelagem/useCase), [CEN08](../../modelagem/cenarios), [US27](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | **Agregação**: RE27 - ST10/ST11: O requisito originou-se da técnica de Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE27 - UC12: O caso de uso (UC12) satisfaz o requisito (RE27) ao permitir que advogados solicitem e forneçam documentos necessários ao processo diretamente no sistema. <br> **Recurso**: RE27 - CEN08: O cenário (CEN08) detalha os recursos necessários para que o advogado acesse e gerencie documentos e processos dos clientes, conforme requerido pelo RE27. <br> **Satisfação**: RE27 - US27: A história de usuário (US27) satisfaz o requisito (RE27) ao descrever como os advogados podem solicitar e fornecer documentos diretamente ao sistema para agilizar os processos dos clientes. <br> |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE28

<div align="center">
  <strong>Tabela  29 -</strong> Cartão do Requisito 28 - C28
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE28](../../elicitacao/requisitosElicitados), [BS16](../../elicitacao/brainStorm),[BS18](../../elicitacao/brainStorm),[ENT16](../../elicitacao/entrevista),[ENT20](../../elicitacao/entrevista), [ENT21](../../elicitacao/entrevista), [IT08](../../elicitacao/Introspeccao), [ES(RU001, +In001)](../../modelagem/specSuplementar), [US28](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | **Agregação**: RE28 - BS16/BS18/ENT16/ENT20/ENT21/IT08: O requisito originou-se das técnicas de BrainStorm, Entrevista e Introspecção. |
| **Elos Forward-from:**   | **Representação**: RE28 - RU001/+In001: A especificação suplementar (RU001, In001) representa detalhamentos do requisito (RE28) sobre a facilidade de uso e intuitividade do aplicativo. <br> **Satisfação**: RE28 - US28: A história de usuário (US28) satisfaz o requisito (RE28) ao descrever a necessidade de um aplicativo fácil de usar e intuitivo, com um número minimizado de cliques para realizar tarefas. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE29

<div align="center">
  <strong>Tabela  30 -</strong> Cartão do Requisito 29 - C29
</div>

<center>



| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE29](../../elicitacao/requisitosElicitados), [BS17](../../elicitacao/brainStorm), [ST12](../../elicitacao/storytelling), [ST19](../../elicitacao/storytelling), [IT15](../../elicitacao/Introspeccao), [ES(RS001)](../../modelagem/specSuplementar), [US29](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | **Agregação**: RE29 - BS15/BS24/ST14/ST19/IT15: O requisito originou-se das técnicas de BrainStorm, Storytelling e Introspecção. |
| **Elos Forward-from:**   | **Representação**: RE29 - RS001: A especificação suplementar (RS001) representa detalhes do requisito (RE29) sobre a compatibilidade do aplicativo com dispositivos de diferentes fabricantes. <br> **Satisfação**: RE29 - US29: A história de usuário (US29) satisfaz o requisito (RE29) ao descrever a necessidade de compatibilidade do aplicativo com versões recentes e anteriores dos sistemas operacionais iOS, Android e computador. |

</center>

<p align="center">Autor: <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024.</p>

### RE30

<div align="center">
  <strong>Tabela  31 -</strong> Cartão do Requisito 30 - C30
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE30](../../elicitacao/requisitosElicitados), [BS17](../../elicitacao/brainStorm), [ST12](../../elicitacao/storytelling),  [QT04](.../../elicitacao/questionario), [US30](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | **Agregação**: RE30 - BS17/ST12/QT04: O requisito originou-se das técnicas de BrainStorm, Storytelling e Questionário. |
| **Elos Forward-from:**   | **Representação**: RE30 - US30:  A história de usuário (US30) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE30). | |

</center>

<p align="center">Autor: <a href="https://github.com/BiancaPatrocinio7">Bianca Castro</a>, 2024.</p>


### RE31

<div align="center">
  <strong>Tabela  32-</strong> Cartão do Requisito 31-C31
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE31](../../elicitacao/requisitosElicitados), [BS19](../../elicitacao/brainStorm), [US31](../../modelagem/Agil/historia_de_usuario)          |
| **Elos Backward-from:**  | Agregação: RE31 - BS19: O requisito originou-se da técnica de Brainstorming. |
| **Elos Forward-from:**   | Satisfação: RE31 - US31: A história de usuário (US31) pode ser vista como uma expressão de uma necessidade do usuário que será satisfeita pelo requisito (RE31). |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE32

<div align="center">
  <strong>Tabela  33-</strong> Cartão do Requisito 32-C32
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE32](../../elicitacao/requisitosElicitados), [BS20](../../elicitacao/brainStorm), [IT09](../../elicitacao/Introspeccao), [IT10](../../elicitacao/Introspeccao), [ST13](../../elicitacao/storytelling), [QT06](../../elicitacao/questionario), [ES(RU007, RU008, RU009, RU010, RU011, +In002)](../../modelagem/specSuplementar), [US32](../../modelagem/Agil/historia_de_usuario) |
| **Elos Backward-from:**  | **Agregação**: RE32 - BS20: O requisito originou-se da técnica de Brainstorming. <br> **Agregação**: RE32 - IT09: O requisito originou-se da técnica de Introspecção. <br> **Agregação**: RE32 - IT10: O requisito originou-se da técnica de Introspecção. <br> **Agregação**: RE32 - ST13: O requisito originou-se da técnica de Storytelling. <br> **Agregação**: RE32 - QT06: O requisito originou-se da técnica de Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE32 - US32:  A história de usuário (US32) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE32). <br>  **Satisfação**: RE32 - ES(RU007, RU008, RU009, RU010, RU011, +In002): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE32). |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE33

<div align="center">
  <strong>Tabela  34-</strong> Cartão do Requisito 33-C33
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE33](../../elicitacao/requisitosElicitados), [BS21](../../elicitacao/brainStorm),  [ST16](../../elicitacao/storytelling), [US33](../../modelagem/Agil/historia_de_usuario), [RNF05](../../Agil/nfr) |
| **Elos Backward-from:**  | **Agregação**: RE33 - BS21: O requisito originou-se da técnica de Brainstorming. <br> **Agregação**: RE33 - ST16: O requisito originou-se da técnica de Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE33 - US33:  A história de usuário (US33) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE33). <br>  **Satisfação**: RE32 - RNF05: A técnica (RNF05) detalha uma forma de garantir que o requisito (RE33) seja satisfeito. |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE34

<div align="center">
  <strong>Tabela  35-</strong> Cartão do Requisito 34-C34
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE34](../../elicitacao/requisitosElicitados), [BS22](../../elicitacao/brainStorm),  [ST17](../../elicitacao/storytelling), [US34](../../modelagem/Agil/historia_de_usuario) |
| **Elos Backward-from:**  | **Agregação**: RE34 - BS22: O requisito originou-se da técnica de Brainstorming. <br> **Agregação**: RE34 - ST17: O requisito originou-se da técnica de Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE33 - US34:  A história de usuário (US34) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE34). |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE35

<div align="center">
  <strong>Tabela  36-</strong> Cartão do Requisito 35-C35
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE35](../../elicitacao/requisitosElicitados), [BS25](../../elicitacao/brainStorm), [IT16](../../elicitacao/Introspeccao), [ST18](../../elicitacao/storytelling), [ES(RS004)](../../modelagem/specSuplementar), [US35](../../modelagem/Agil/historia_de_usuario) |
| **Elos Backward-from:**  | **Agregação**: RE35 - BS25: O requisito originou-se da técnica de Brainstorming. <br> **Agregação**: RE35 - IT16: O requisito originou-se da técnica de Introspecção. <br>  **Agregação**: RE35 - ST18: O requisito originou-se da técnica de Storytelling. |
| **Elos Forward-from:**   | **Satisfação**: RE35 - US35:  A história de usuário (US35) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE35). <br>  **Satisfação**: RE35 - ES(RS004): A especificação suplementar fornece critérios e detalhes que satisfazem o requisito de acessibilidade (RE32). |

</center>

<p align="center">Autor: <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024.</p>

### RE36

<div align="center">
  <strong>Tabela 37 -</strong> Cartão do Requisito 36 - C36
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE36](../../elicitacao/requisitosElicitados), [ENT17](../../elicitacao/entrevista), [US36](../../modelagem/Agil/historia_de_usuario), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$),[BC](../../modelagem/Agil/backlog), [ES(RR002, RR003, RR006, RR007, RR008, RP003, RP004, RP006, RP007, RP008, RP009, RS006, +Im002, +Im005)](../../modelagem/specSuplementar)                    |
| **Elos Backward-from:**  | **Agregação**: RE36 - ENT17: O requisito originou-se da Entrevista.|
| **Elos Forward-from:**   | **Satisfação**: RE36 - US36: A história de usuário (US36) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE36) <br> **Satisfação**: RE36 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.  <br> Satisfação: RE36 - CDS: O requisito recebeu um valor de $2 do Desenvolvedor e $2 do Usuário na técnica $100. <br>  **Satisfação**: RE36 - ES(RR002, RR003, RR006, RR007, RR008, RP003, RP004, RP006, RP007, RP008, RP009, RS006, +Im002, +Im005): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE36). |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>


### RE37

<div align="center">
  <strong>Tabela 38 -</strong> Cartão do Requisito 37 - C37
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE37](../../elicitacao/requisitosElicitados), [ENT18](../../elicitacao/entrevista), [ENT22](../../elicitacao/entrevista),  [US37](../../modelagem/Agil/historia_de_usuario), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [BC](../../modelagem/Agil/backlog), [ES(RU001, RU005, RU006, RU017, RP001, RP002, RP003, +In001,+In003)](../../modelagem/specSuplementar)                     |
| **Elos Backward-from:**  | **Agregação**: RE37 - ENT18 e ENT22: O requisito originou-se da Entrevista. |
| **Elos Forward-from:**   | **Satisfação**: RE37 - US37: A história de usuário (US37) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE37) <br> **Satisfação**: RE37 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.  <br> **Satisfação**: RE37 - CDS: O requisito recebeu um valor de $3 do Desenvolvedor e $7 do Usuário na técnica $100. <br>  **Satisfação**: RE37 - ES(RU001, RU005, RU006, RU017, RP001, RP002, RP003, +In001,+In003): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE37). |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>

### RE38

<div align="center">
  <strong>Tabela 39 -</strong> Cartão do Requisito 38 - C38
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE38](../../elicitacao/requisitosElicitados), [IT11](../../elicitacao/Introspeccao), [QT06](../../elicitacao/questionario),[US38](../../modelagem/Agil/historia_de_usuario), [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [BC](../../modelagem/Agil/backlog), [ES(RU003, RU004, RU007, RU018, RU019, +In002)](../../modelagem/specSuplementar)                          |
| **Elos Backward-from:**  | **Agregação**: RE38 - IT11: O requisito originou-se da técnica de Introspecção. <br> Agregação: RE38 - QT06: O requisito originou-se da técnica de Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE38 - US38: A história de usuário (US38) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE38) <br> **Satisfação**: RE38 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.  <br> **Satisfação**: RE38 - CDS: O requisito recebeu um valor de $2 do Desenvolvedor e $2 do Usuário na técnica $100. <br>  **Satisfação**: RE38 - ES(RU003, RU004, RU007, RU018, RU019, +In002): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE38).  |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>

### RE39

<div align="center">
  <strong>Tabela 40 -</strong> Cartão do Requisito 39 - C39
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           |  [RE39](../../elicitacao/requisitosElicitados),[BS23](../../elicitacao/brainStorm), [ENT19](../../elicitacao/entrevista), [IT12](../../elicitacao/Introspeccao), [ST15](../../elicitacao/storytelling), [QT07](../../elicitacao/questionario), [US29](../../modelagem/Agil/historia_de_usuario),[US39](../../modelagem/Agil/historia_de_usuario) [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [BC](../../modelagem/Agil/backlog), [ES(RR004, +Im001,+Im003,+Im004)](../../modelagem/specSuplementar)                        |
| **Elos Backward-from:**  | **Agregação**: RE39 - BS23: O requisito originou-se da técnica de Brainstorming. **Agregação**: RE39 - ENT19: O requisito originou-se da Entrevista. <br> **Agregação**: RE39 - IT12: O requisito originou-se da técnica de Introspecção. . <br> **Agregação**: RE39 - ST15: O requisito originou-se da técnica de Storytelling. <br> **Agregação**: RE39 - QT07: O requisito originou-se da técnica de Questionário. |
| **Elos Forward-from:**   | **Satisfação**: RE39 - US29 e US39: AS históriaS de usuário (US29 e US39) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE39) <br> **Satisfação**: RE39 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.  <br> **Satisfação**: RE39 - CDS: O requisito recebeu um valor de $10 do Desenvolvedor e $2 do Usuário na técnica $100. <br>  **Satisfação**: RE39 - ES(RR004, +Im001,+Im003,+Im004): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE39). |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>

### RE40

<div align="center">
  <strong>Tabela 41 -</strong> Cartão do Requisito 40 - C40
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE40](../../elicitacao/requisitosElicitados), [IT13](../../elicitacao/Introspeccao), [US40](../../modelagem/Agil/historia_de_usuario) [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [BC](../../modelagem/Agil/backlog), [ES(RP001, RP002)](../../modelagem/specSuplementar)      |
| **Elos Backward-from:**  | **Agregação**: RE40 - IT13: O requisito originou-se da técnica de Introspecção.  |
| **Elos Forward-from:**   | **Satisfação**: RE40 - US40: A história de usuário (US40) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE40) <br> **Satisfação**: RE40 - TLS: O requisito recebeu uma priorização Alta no Three Level Scale.  <br> **Satisfação**: RE40 - CDS: O requisito recebeu um valor de $2 do Desenvolvedor e $15 do Usuário na técnica $100. <br>  **Satisfação**: RE40 - ES(RP001, RP002): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE40). |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>

### RE41

<div align="center">
  <strong>Tabela 42 -</strong> Cartão do Requisito 41 - C41
</div>

<center>

| **Categoria:**           | Desenvolvimento                                   |
|:--|:--|
| **Elementos:**           | [RE41](../../elicitacao/requisitosElicitados), [IT14](../../elicitacao/Introspeccao), [US41](../../modelagem/Agil/historia_de_usuario) [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [BC](../../modelagem/Agil/backlog), [ES(RR001, RR006, RR008, RP005)](../../modelagem/specSuplementar)     |
| **Elos Backward-from:**  | **Agregação**: RE41 - IT14: O requisito originou-se da técnica de Introspecção.  |
| **Elos Forward-from:**   | **Satisfação**: RE41 - US41: A história de usuário (US41) especifica uma necessidade do usuário que será satisfeita pelo requisito (RE41) <br> **Satisfação**: RE41 - TLS: O requisito recebeu uma priorização Baixa no Three Level Scale.  <br> **Satisfação**: RE41 - CDS: O requisito recebeu um valor de $8 do Desenvolvedor e $5 do Usuário na técnica $100. <br>  **Satisfação**: RE41 - ES(RR001, RR006, RR008, RP005): As especificações suplementares fornecem critérios e detalhes que satisfazem o requisito de acessibilidade (RE41). |

</center>

<p align="center">Autor: <a href="https://github.com/acamposs">Amanda Campos</a>, 2024.</p>


## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a>SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 21 jun. 2024.

> <a id="RP2" href="#TEC2">2.</a> Kotonya, Gerald, and Ian Sommerville. "Requirements Engineering: Processes and Techniques." John Wiley & Sons, 1998. Disponível em: (https://www.acqnotes.com/Attachments/The%20Requirements%20Engineering%20Handbook%20by%20Ralph%20R.%20Young.pdf).Acesso em: 22 jun. 2024.

## Bibliografia
> <a id="RP1" href="#TEC1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 18 jun. 2024.

> <a id="RP2" href="#TEC2">2.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf). Acesso em: 18 jun. 2024.

> <a id="RP3" href="#TEC3">3.</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: [https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/doimagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 18 jun. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 21/06/2024  | Criação da página | [Johnny Lopes](https://github.com/JohnnyLopess) | 22/06/2024 |  [Amanda Campos](https://github.com/acamposs) |
| `1.1` | 23/06/2024  | Adicionando informações na página | [Paulo Borba](https://github.com/paulohborba) | 23/06/2024 | [Johnny Lopes](https://github.com/JohnnyLopess) |
| `1.2` | 23/06/2024  | Adicionando Elos. | [Johnny Lopes](https://github.com/JohnnyLopess) | 23/06/2024 | [Amanda Campos](https://github.com/acamposs)  |
| `1.3` | 23/06/2024  | Adicionando Elos. | [Amanda Campos](https://github.com/acamposs) | 23/06/2024 | [Vitor Feijó](https://github.com/vitorfleonardo) |
| `1.4` | 23/06/2024  | Adicionando Elos. | [Vitor Feijó](https://github.com/vitorfleonardo)| 23/06/2024 |[Bianca Castro](https://github.com/BiancaPatrocinio7) |
| `1.5` | 23/06/2024  | Adicionando Elos. | [Bianca Castro](https://github.com/BiancaPatrocinio7) | 23/06/2024 | [Gabriel Souza](https://github.com/GabrielMS00) |
| `1.6` | 23/06/2024  | Adicionando Elos. | [Gabriel Souza](https://github.com/GabrielMS00) | 24/06/2024 |[Johnny Lopes](https://github.com/JohnnyLopess) | 
