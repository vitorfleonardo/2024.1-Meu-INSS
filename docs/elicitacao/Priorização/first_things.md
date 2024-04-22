
## Introdução 

A técnica First Thing First é uma abordagem de priorização de requisitos de software que ajuda a determinar a importância relativa dos requisitos. Ela leva em consideração tanto o valor do negócio, benefícios e penalidades relativas de requisitos, quanto o custo e riscos relativos a implementação dos requisitos. Por isso, neste artefato será apresentado a metodologia de aplicação da técnica, requisitos priorizados e gravação da reunião com usuário e desenvolvedores. 

## Metodologia
Para se realizar a técnica foram seguidos os passos em ordem: 

1. Preparação
2. Agendamento da reunião
3. Participantes e uso da técnica 
4. Análise

## Passo a passo de execução da técnica

#### 1. Preparação

Foi preparada uma planilha automatizada com fórmulas para os cáculos da técnica First Thing First, utilizando a ferramenta do google sheets e o repositório do projeto Economia-DF de 2023.2 como referência. 

A planilha consiste em 11 colunas, sendo elas: 

- ID: identificador do requisito.
- Funcionalidades: descrição do requisito.
- Benefício relativo: classificação do benefício do requisito por parte do usuário, de 1 a 9, onde 1 é menos significativo e 9, o máximo. 
- Penalidade relativa: classificação do penalidade do requisito por parte do usuário, de 1 a 9, onde 1 significa que não há penalidade se o requsito não for implementado e 9 indica uma grande desvantagem. 
- Valor total: é o resultado da fórmula ( benefício relativo * peso relativo ) + ( penalidade relativa * peso relativo ) e foi usado o peso relativo dos benefícios igual a 2 e o peso relativo das penalidades igual a 1, para dar maior importância aos benefícios.
- Custo relativo : Classificação do custo por parte do desenvolvedor, de 1 a 9, onde 1 significa baixa complexidade de implementação, baixo potencial de reutilização de telas ou código, testes e documentações necessárias, e sendo 9 o inverso.
- Risco relativo : Classificação do risco por parte do desenvolvedor, de 1 a 9, onde 1 significa muito fácil de programar e 9 indica sérias preocupações sobre viabilidade, disponibilidade de pessoal com o conhecimento necessário ou uso de ferramentas e tecnologias desconhecidas
- Valor %: é o resultado da fórmula ( valor total / soma de todos os valores totais ) * 100 
- Custo %: é o resultado da fórmula ( custo relativo / soma de todos os custos relativos ) * 100 
- Risco %: é o resultado da fórmula ( risco relativo / soma de todos os riscos relativos ) * 100 
- Prioridade: é o resultado da fórmula ( valor % ) / (  custo %  +  risco %  ) 


#### 2. Agendamento da reunião 

A reunião foi agendada pelo [Paulo Borba](https://github.com/paulohborba) para o dia 16 de abril de 2024, às 20:00, por ser o contato principal com usuária. Representado na Tabela 1.

<div align="center">
<font size="3"><p style="text-align: center"><b>Tabela 1:</b> Cronograma da reunião </p></font>
</div>
| Data & Horário | Local | Assunto | 
| :-: | :-: | :-: | 
| 16/04/2024  às 20:00  | Teams | Priorização de requisitos elicitados utilizando a técnica First Thing First | 

<div>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>
</div>

#### 3. Participantes e uso da técnica 

A reunião contou com a participação de um moderador, um secretário, uma usuária do aplicativo MeuINSS e dois desenvolvedores. Representado na tabela 2.

<p align="center" > <strong> Tabela 2 - </Strong> Participantes</font> <gitbr></p>
<center>

|Nome|Função|
|:-:|:-:|
|[Vitor Leonardo](https://github.com/vitorfleonardo)|Moderador|
|[Paulo Borba](https://github.com/paulohborba)|Secretário|
|[Bianca Castro](https://github.com/BiancaPatrocinio7)|Desenvolvedora|
|[José Souza](https://github.com/JoseFilipi)|Desenvolvedora|
| Neysa Mendes Rossi de Borba |Usuária| 

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>
</center>

Na aplicação da técnica peguntava-se a classificação, de 1 a 9, do benefício realativo e depois a penalidade relativa para o usuário. Logo após o custo e risco relativos para cada um dos desenvolvedores, de 1 a 9, anotando-se sempre a maior calssificação. Repetia-se esse processo para cada um dos requisitos.


#### 4. Análise 

Após o término da reunião, as formulas caluclaram os resultados da priorização. sendo assim o resultado da aplicação da técnica pode ser observado abaixo.


## Gravação

No vídeo 1 localiza-se a gravação da utilização da técnica.

<div align="center">

<p style="text-align: center"><a href="https://www.youtube.com/embed/fFj1F8-Ci_s" target="blanket"><b>Vídeo 1:</b> Reunião - First THings First</a></p>

<iframe width="560" height="315" src="https://www.youtube.com/embed/fFj1F8-Ci_s" title="First things first do Grupo 7 Meu INSS" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>
</div >

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> SERRANO, Milene, SERRANO, Maurício. Requisitos (Aula 07): Elicitação, Modelagem e Análise. UnB Gama, Brasília, 2023. Disponível em: [https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdfg](https://aprender3.unb.br/pluginfile.php/2844984/mod_resource/content/2/Requisitos%20-%20Aula%2007.pdf). Acesso em: 14 abr. 2024.

## Bibliografia

> </a> Requisitos de Software. Economia DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/](https://requisitos-de-software.github.io/2023.2-Economia-DF/). Acesso em: 17 abr. 2024.

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 17/04/2024  | Preenchimento do artefato da técnica First Things First | [Vitor Feijó](https://github.com/vitorfleonardo)  | 19/042024| [Johnny Lopes](https://github.com/JohnnyLopess) |
