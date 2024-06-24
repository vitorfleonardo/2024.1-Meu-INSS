# Matriz de rastreabildade

## Introdução
Uma matriz de rastreabilidade é uma ferramenta fundamental na engenharia de requisitos e no gerenciamento de projetos, utilizada para estabelecer e visualizar conexões entre diferentes elementos ao longo do ciclo de vida de um projeto. Esta técnica permite acompanhar e documentar a relação entre requisitos, componentes do sistema, testes, e outras entidades relevantes. Geralmente implementada em formatos acessíveis como editores de texto ou planilhas eletrônicas, a matriz de rastreabilidade facilita a identificação de dependências, verificações de cobertura e o controle de mudanças, promovendo uma gestão mais eficiente e integrada do desenvolvimento de sistemas e produtos. <a id="TEC1" href="#RP1">[1]</a>.


## Metodologia


<details>
  <summary>Legenda da tabela</summary>
  <ul>
    <li><strong>Requisito</strong>: Código único para cada requisito, usado para identificação e referência rápida, onde RE significa Requisito Elicitado.</li>
    <li><strong>Tipo</strong>: Qual o tipo de requisito, onde RF significa Requisito Funcional e RNF significa Requisito Não Funcional.</li>
    <li><strong>Implementação</strong>: Estado atual da implementação do requisito, indicando se já foi implementado.</li>
    <li><strong>Versão</strong>: Referente ao versionamento do requisito.</li>
    <li><strong>Elicitação</strong>: Código para indicar as técnicas utilizadas para a elicitação do requisito referente, podendo ser:
      <ul> 
        <li>BS: Brainstorming</li>
        <li>IT: Introspecção</li>
        <li>ENT: Entrevista</li>
        <li>QT: Questionário</li>
        <li>ST: Storytelling</li>
      </ul>
    </li>
    <li><strong>Modelagem</strong>: Código para indicar as técnicas de modelagem utilizadas no projeto, podendo ser:
      <ul>
        <li>ES: Especificação suplementar</li>
        <li>US: Casos de Uso</li>
        <li>CEN: Cenários</li>
        <li>US: Histórias de Usuário</li>
        <li>RNF: NFR Framework</li>
      </ul>
    </li>
    <li><strong>Elos</strong>: Código único para cada Elo, usado para identificação e referência rápida, onde C significa o Cartão de Elos referente.</li>
  </ul>
</details>

<p align="center">Autor: <a href="https://github.com/Requisitos-de-Software/2024.1-Meu-INSS">Todos</a></a>, 2024.</p>

## Tabela da Matriz de rastreabildade

<p align="center" > <strong> Tabela 2 - </Strong> Matriz de rastreabilidade</font> <gitbr></p>



| Requisito | Tipo  | Implementação | Versão | Elicitação | Priorizaçaõ | Modelagem | Elos |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| [RE01](../../elicitacao/requisitosElicitados)|  RF  | Sim |  1.0 | [BS01](../../elicitacao/brainStorm), [ST02](../../elicitacao/storytelling), [QT01](../../elicitacao/questionario) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things)  | [UC01](../../modelagem/useCase), [CEN01](../../modelagem/cenarios), [US01](../../Agil/historia_de_usuario) | [C01](../../rastreabilidade/Elos)  |
| [RE02](../../elicitacao/requisitosElicitados)|  RF  | Não |  1.0 | [BS02](../../elicitacao/brainStorm) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things)  | [UC01](../../modelagem/useCase), [CEN01](../../modelagem/cenarios), [US02](../../Agil/historia_de_usuario) | [C02](../../rastreabilidade/Elos)  |
| [RE03](../../elicitacao/requisitosElicitados)|  RF  | Não |  1.0 | [BS03](../../elicitacao/brainStorm) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things)  | [UC03](../../modelagem/useCase), [CEN02](../../modelagem/cenarios), [US03](../../Agil/historia_de_usuario) | [C03](../../rastreabilidade/Elos)  |
| [RE04](../../elicitacao/requisitosElicitados)| RF   | Não |  1.0 | BS, ENT, ST, QT |  TLS, CDS, FTF | UC, CE, LE, BC, HU | [C04](../../rastreabilidade/Elos)  |
| [RE05](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C05](../../rastreabilidade/Elos)  |
| [RE06](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C06](../../rastreabilidade/Elos)  |
| [RE07](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C07](../../rastreabilidade/Elos)  |
| [RE08](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C08](../../rastreabilidade/Elos)  |
| [RE09](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C09](../../rastreabilidade/Elos)  |
| [RE10](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C10](../../rastreabilidade/Elos)  |
| [RE11](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C11](../../rastreabilidade/Elos)  |
| [RE12](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C12](../../rastreabilidade/Elos)  |
| [RE13](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C13](../../rastreabilidade/Elos)  |
| [RE14](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C14](../../rastreabilidade/Elos)  |
| [RE15](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C15](../../rastreabilidade/Elos)  |
| [RE16](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C16](../../rastreabilidade/Elos)  |
| [RE17](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C17](../../rastreabilidade/Elos)  |
| [RE18](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C18](../../rastreabilidade/Elos)  |
| [RE19](../../elicitacao/requisitosElicitados)| RF   | Não | 1.0 | [ENT13](../../elicitacao/entrevista) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things)[BC](../../modelagem/Agil/backlog), [US19](../../modelagem/Agil/historia_de_usuario)  | [C19](../../rastreabilidade/Elos)  |
| [RE20](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [IT01](../../elicitacao/Introspeccao) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [BC](../../modelagem/Agil/backlog), [US20](../../modelagem/Agil/historia_de_usuario) | [C20](../../rastreabilidade/Elos)  |
| [RE21](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [IT03](../../elicitacao/Introspeccao) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [UC04](../../modelagem/useCase), [UC05](../../modelagem/useCase), [BC](../../modelagem/Agil/backlog), [US21.1](../../modelagem/Agil/historia_de_usuario), [US21.2](../../modelagem/Agil/historia_de_usuario), [US21.3](../../modelagem/Agil/historia_de_usuario) | [C21](../../rastreabilidade/Elos)  |
| [RE22](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [IT04](../../elicitacao/Introspeccao) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [BC](../../modelagem/Agil/backlog), [UC06](../../modelagem/useCase), [US22](../../modelagem/Agil/historia_de_usuario) | [C22](../../rastreabilidade/Elos)  |
| [RE23](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [ST03](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [BC](../../modelagem/Agil/backlog), [US23](../../modelagem/Agil/historia_de_usuario) | [C23](../../rastreabilidade/Elos)  |
| [RE24](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [ST05](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [BC](../../modelagem/Agil/backlog), [US24](../../modelagem/Agil/historia_de_usuario), [UC06](../../modelagem/useCase) | [C24](../../rastreabilidade/Elos)  |
| [RE25](../../elicitacao/requisitosElicitados)| RF   | Sim | 1.0 | [ST06](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [BC](../../modelagem/Agil/backlog), [US25](../../modelagem/Agil/historia_de_usuario), [UC06](../../modelagem/useCase) | [C25](../../rastreabilidade/Elos)  |
| [RE26](../../elicitacao/requisitosElicitados) | RF    | Sim | 1.0 | [ST09](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things) | [UC12](../../modelagem/useCase), [CEN08](../../modelagem/cenarios), [US26](../../Agil/historia_de_usuario) |  [C26](../../rastreabilidade/Elos) | 
| [RE27](../../elicitacao/requisitosElicitados)|  RF  | Sim |  1.0 | [ST10](../../elicitacao/storytelling) |  [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things)  |  [UC12](../../modelagem/useCase), [CEN08](../../modelagem/cenarios), [L03](../../modelagem/lexicos)| [C27](../../rastreabilidade/Elos)  |
| [RE28](../../elicitacao/requisitosElicitados)|  RNF  | |  1.0 |  |   |  | [C28](../../rastreabilidade/Elos)  |
| [RE29](../../elicitacao/requisitosElicitados)| RNF   | |  1.0 |  |   |  | [C29](../../rastreabilidade/Elos)  |
| [RE30](../../elicitacao/requisitosElicitados)|    | |  1.0 |  |   |  | [C30](../../rastreabilidade/Elos)  |
| [RE31](../../elicitacao/requisitosElicitados) | RNF    | Não | 1.0 | [BS](../../elicitacao/brainStorm) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog) | [US](../../Agil/historia_de_usuario) |  [C31](../../rastreabilidade/Elos) |
| [RE32](../../elicitacao/requisitosElicitados)|  RNF  | Não |  1.0 | [BS](../../elicitacao/brainStorm), [IT](../../elicitacao/Introspeccao), [ST](../../elicitacao/storytelling), [QT](../../elicitacao/questionario),  |  [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog) | [ES](../../modelagem/specSuplementar), [US](../../Agil/historia_de_usuario) | [C32](../../rastreabilidade/Elos)  |
| [RE33](../../elicitacao/requisitosElicitados)|  RNF  | Sm |  1.0 | [BS](../../elicitacao/brainStorm),  [ST](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog)  | [US](../../Agil/historia_de_usuario), [RNF](../../Agil/nfr) | [C33](../../rastreabilidade/Elos)  |
| [RE34](../../elicitacao/requisitosElicitados)|  RNF  | Sim |  1.0 | [BS](../../elicitacao/brainStorm),  [ST](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog)  | [US](../../Agil/historia_de_usuario) | [C34](../../rastreabilidade/Elos)  |
| [RE35](../../elicitacao/requisitosElicitados)|  RNF  | Sim |  1.0 | [BS](../../elicitacao/brainStorm), [IT](../../elicitacao/Introspeccao), [ST](../../elicitacao/storytelling) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$), [FTF](../../elicitacao/Priorização/first_things), [BC](../../modelagem/Agil/backlog) | [ES](../../modelagem/specSuplementar), [US](../../Agil/historia_de_usuario) | [C35](../../rastreabilidade/Elos)  |
| [RE36](../../elicitacao/requisitosElicitados)| RNF  | Sim |  1.0 | [ENT17](../../elicitacao/entrevista) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.) | [BC](../../modelagem/Agil/backlog), [ES(RR002, RR003, RR006, RR007, RR008, RP003, RP004, RP006, RP007, RP008, RP009, RS006, +Im002, +Im005)](../../modelagem/specSuplementar), [US36](../../Agil/historia_de_usuario) | [C36](../../rastreabilidade/Elos)  |
| [RE37](../../elicitacao/requisitosElicitados)| RNF   | Sim |  1.0 | [ENT18](../../elicitacao/entrevista), [ENT22](../../elicitacao/entrevista) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.)  | [BC](../../modelagem/Agil/backlog), [ES(RU001, RU005, RU006, RU017, RP001, RP002, RP003, +In001,+In003)](../../modelagem/specSuplementar), [US37](../../Agil/historia_de_usuario) | [C37](../../rastreabilidade/Elos)  |
| [RE38](../../elicitacao/requisitosElicitados)| RNF   | Não |  1.0 |  [IT11](../../elicitacao/Introspeccao), [QT06](../../elicitacao/questionario) | [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.)  | [BC](../../modelagem/Agil/backlog), [ES(RU003, RU004, RU007, RU018, RU019, +In002)](../../modelagem/specSuplementar), [US38](../../Agil/historia_de_usuario) | [C38](../../rastreabilidade/Elos)  |
| [RE39](../../elicitacao/requisitosElicitados)| RNF   | Sim |  1.0 | [BS23](../../elicitacao/brainStorm), [ENT19](../../elicitacao/entrevista), [IT12](../../elicitacao/Introspeccao), [ST15](../../elicitacao/storytelling), [QT07](../../elicitacao/questionario) |  [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.) | [BC](../../modelagem/Agil/backlog), [ES(RR004, +Im001,+Im003,+Im004)](../../modelagem/specSuplementar), [US29](../../Agil/historia_de_usuario), [US39](../../Agil/historia_de_usuario) | [C39](../../rastreabilidade/Elos)  |
| [RE40](../../elicitacao/requisitosElicitados)| RNF  | Sim |  1.0 | [IT13](../../elicitacao/Introspeccao) |  [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.) | [BC](../../modelagem/Agil/backlog), [ES(RP001, RP002)](../../modelagem/specSuplementar), [US40](../../Agil/historia_de_usuario) | [C40](../../rastreabilidade/Elos)  |
| [RE41](../../elicitacao/requisitosElicitados)| RNF  | Sim |  1.0 | [IT14](../../elicitacao/Introspeccao) |  [TLS](../../elicitacao/Priorização/threelevelscale), [CDS](../../elicitacao/Priorização/100$.) | [BC](../../modelagem/Agil/backlog), [ES(RR001, RR006, RR008, RP005)](../../modelagem/specSuplementar), [US41](../../Agil/historia_de_usuario) | [C41](../../rastreabilidade/Elos)  |

<p align="center">Autor: <a href="https://github.com/Requisitos-de-Software/2024.1-Meu-INSS">Todos</a></a>, 2024.</p>


## Bibliografia
> <a id="RP1" href="#TEC1">1.</a> SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: [https://www-di.inf.puc-rio.br/~julio/rastre.pdf](https://www-di.inf.puc-rio.br/~julio/rastre.pdf). Acesso em: 18 jun. 2024.

> <a id="RP2" href="#TEC2">2.</a> WIEGERS, Karl; BEATTY, Joy. Software Requirements. 3. ed. Redmond: Microsoft Press, 2013. disponível em: [https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf](https://www.booksfree.org/wp-content/uploads/2022/03/Software_Requirements_3rd_Edition_compressed.pdf). Acesso em: 18 jun. 2024.

> <a id="RP3" href="#TEC3">3.</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 26): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. disponível em: [https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf](https://github.com/Requisitos-de-Software/2024.1-Meu-INSS/blob/rastrear/docs/imagens/referencias/rastreabilidade/Requisitos%20-%20Aula%20026.pdf). Acesso em: 18 jun. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 18/06/2024  | Criação da página | [Paulo Borba](https://github.com/paulohborba) | | | 
| `1.1` | 23/06/2024  | Adicionando os requisitos à tabela. | [Johnny Lopes](https://github.com/JohnnyLopess) | 23/06/2024 | [Amanda Campos](https://github.com/acamposs)| 
| `1.2` | 23/06/2024  | Adicionando os requisitos à tabela. | [Amanda Campos](https://github.com/acamposs) | | | 