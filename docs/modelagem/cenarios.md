# Cenários

## Introdução



## Metodologia

Utilizamos o método do texto estruturado e com base no modelo proposto no material disponibilizado pelo professor, onde esse modelo é descrito pelo uso de uma linguagem natural semi-estruturada, que parte da premissa que a utilização desse tipo de linguagem da aplicação e no do software facilita a compreensão e a validação dos requisitos por psrte dos clientes<a id="TEC1" href="#RP1">[1]</a>.

A Legenda para identificação dos elementos dos cenários de cada tabela estão representadas na tabela 1.

<p align="center" > <strong> Tabela 1 - </Strong> Legenda das tabelas dos Cenários</font> <gitbr></p>
<center>

### Título: Identifica o cenário.

| Elemento | Descrição |
|:-:|:-:|
| Objetivo | Dita a finalidade de um cenário. O cenário deve descrever de que jeito o objetivo deve ser alcançado. |
| Contexto | Descreve o estado inicial do cenário,suas pré-condições, o local e tempo. |
| Recurso | Identifica os objetos passivos com os quais lidam os atores. |
| Ator | Pessoa ou estrutura organizacional que tem um papel no cenário. |
| Episódio | Representa uma ação realizada por um ator onde outros atores podem participar utilizando recursos disponíveis. |
| Restrição | Imposição que restrinja um episódio do cenário. |
| Exceção | Tratamento para uma situação excepcional ou de erro. |

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

<details>
  <summary>Pré-rastreabilidade dos requisitos agrupados nos cenários</summary>

Tabela onde mostra a relação dos requisitos priorizados anteriormente com os cenários criados.

<p align="center" > <strong> Tabela 2 - </Strong> Tabelas da pré-rastreabilidade dos requisitos</font> <gitbr></p>
<center>

| Cenário | Requisitos |
|:-:|:-:|
| CEN01 - Acesso Inicial e Autenticação | RE01, RE02, RE12, RE20, RE23 |
| CEN02 - Acesso a Informações de Benefícios | RE03, RE07, RE09, RE10, RE11, RE14, RE16, RE17 |
| CEN03 - Suporte e Aprendizado | RE04, RE05 |
| CEN04 - Solicitação e Atualização de Benefícios | RE15, RE22, RE24, RE25 |
| CEN05 -  Atualização de Dados Pessoais | RE17 |
| CEN06 - Segurança e Alertas | RE18, RE19 |
| CEN07 - Perícias Médicas | RE21 |
| CEN08 - Acesso para Advogados | RE26, RE27 |

</center>
<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

</details>

## Cenários

Os cenários foram criados com base nos requisitos funcionais priorizados no método First Things First.

### CEN01 - Acesso Inicial e Autenticação

O cenário de número 1 diz sobre o objetivo de Acesso e Autenticação Inicial e sua descrição está contida na tabela 3.  

<p align="center" > <strong> Tabela 3 - </Strong>  Cenário 1</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo | Permitir que o usuário possa realizar uma autenticação e acessar o aplicativo com informações já existentes do GOV.br |
| Contexto | Local: Na fila de espera do banco. <br>Tempo: Menos de 5 minutos. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário entra com suas informações do GOV.br na tela de login <br>O aplicativo permite a entrada via biometria depois do primeiro login <br>O usuário agora pode entrar com sua digital ao invés do login do GOV.br |
| Restrição | Se o usuário não possuir leitor de digital no celular a biometria não pode ser ativada |
| Exceção | Erro de conexão <br>Conta do GOV.br apresenta irregularidade |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

### CEN02 - Acesso a Informações de Benefícios

O cenário de número 2 diz sobre o objetivo de Acesso a Informações de Benefícios e sua descrição está contida na tabela 4.  

<p align="center" > <strong> Tabela 4 - </Strong>  Cenário 2</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo | Permitir que o usuário acesse as informações dos seus benefícios do INSS |
| Contexto | Local: Em casa. <br>Tempo: Menos de 30 segundos por benefício. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular, possuir pelo menos 1 ano de contribuição. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado <br>Pelo menos 1 ano de contribuição |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Benefícios" na tela inicial <br>O usuário é direcionado para uma página onde pode escolher entre diferentes opções de benefícios <br>O usuário seleciona um benefício específico para visualizar mais informações <br>O sistema exibe as informações referentes ao benefício escolhido |
| Restrição | O usuário tem menos de 1 ano de contribuição |
| Exceção | O sistema do MeuINSS está fora do ar |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p>

### CEN03 - Suporte e Aprendizado

O cenário de número 3 diz sobre o objetivo de Suporte e Aprendizado e sua descrição está contida na tabela 5.  

</font><p align="center" > <strong> Tabela 5 - </Strong>  Cenário 3</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo | Permitir que o usuário do aplicativo do INSS consiga receber suporte técnico e acessar tutoriais para melhor compreensão e uso do aplicativo |
| Contexto | Local: Em casa. <br>Tempo: Menos de 15 minutos. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Suporte e tutoriais" <br>O usuário acessa a opção "Suporte" <br>O aplicativo apresenta uma mensagem informando que o usuário está sendo redirecionado para o suporte esperando a confirmação do mesmo <br>O aplicativo redireciona o usuário para o chat com um funcionário especializado <br>O usuário pode resolver suas dúvidas com essse funcionário |
| Restrição | O suporte estando indisponível |
| Exceção | Erro de conexão |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

### CEN04 - Solicitação e Atualização de Benefícios

 cenário de número 4 diz sobre o objetivo de Solicitação e Atualização de Benefícios e sua descrição está contida na tabela 6.  

<p align="center" > <strong> Tabela 6 - </Strong>  Cenário 4</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo | O usuário precisa acessar o aplicativo do INSS para conseguir solicitar ou atualizar benefícios previdenciários. |
| Contexto | Local: Em casa. <br>Tempo: Menos de 5 minutos. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular, possuir pelo menos 1 ano de contribuição. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado <br>Pelo menos 1 ano de contribuição |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Benefícios" na tela inicial <br>O usuário é direcionado para uma página onde pode escolher entre diferentes opções de benefícios <br>O usuário seleciona um benefício específico para ser emitido <br>O sistema exibe as informações que necessitam ser preenchidas referentes ao benefício escolhido <br>O usuário preenche essas informações necessárias para a emissão <br>O aplicativo gera a emissão do benefício escolhido |
| Restrição | Benefício escolhido não estar disponível |
| Exceção | Erro de preenchimento |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

### CEN05 - Atualização de Dados Pessoais

O cenário de número 5 diz sobre o objetivo de Atualização de Dados Pessoais e sua descrição está contida na tabela 7. 

<p align="center" > <strong> Tabela 7 - </Strong>  Cenário 5</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo |  |
| Contexto |  |
| Recurso |  |
| Ator |  |
| Episódio |  |
| Restrição |  |
| Exceção |  |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/"></a>, 2024</p></font>

### CEN06 - Segurança e Alertas

O cenário de número 6 diz sobre o objetivo de Segurança e Alertas e sua descrição está contida na tabela 8. 

<p align="center" > <strong> Tabela 8 - </Strong>  Cenário 6</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo |  |
| Contexto |  |
| Recurso |  |
| Ator |  |
| Episódio |  |
| Restrição |  |
| Exceção |  |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/"></a>, 2024</p></font>

### CEN07 - Perícias Médicas

O cenário de número 7 diz sobre o objetivo de Perícias Médicas e sua descrição está contida na tabela 9. 

<p align="center" > <strong> Tabela 9 - </Strong>  Cenário 7</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo |  |
| Contexto |  |
| Recurso |  |
| Ator |  |
| Episódio |  |
| Restrição |  |
| Exceção |  |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/"></a>, 2024</p></font>

### CEN08 - Acesso para Advogados

O cenário de número 8 diz sobre o objetivo de Acesso para Advogados e sua descrição está contida na tabela 10. 

<p align="center" > <strong> Tabela 10 - </Strong>  Cenário 8</font> <gitbr></p>

| Elemento | Descrição |
|:-:|:-:|
| Objetivo |  |
| Contexto |  |
| Recurso |  |
| Ator |  |
| Episódio |  |
| Restrição |  |
| Exceção |  |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/"></a>, 2024</p></font>

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: [http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf). Acesso em: 15 abr. 2024.

## Bibliografia

> </a> 

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 15/05/2024 | Versão inicial da pagina de Cenários. | [Paulo Borba](https://github.com/paulohborba) | || 
