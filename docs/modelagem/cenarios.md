# Cenários

## Introdução

Os cenários são responsáveis por nos guiar por uma jornada de descoberta da interação entre o sistema e o ambiente na qual ele está vinculado, isso ocorre através de histórias detalhadas, na qual permite com que as pessoas envolvidas no projeto possam imaginar diferentes situações no mundo real, explorando como o software se comporta em cada uma delas. Nesse sentido, os cenários se tornam uma ferramenta valiosa para compreender as necessidades dos usuários, para auxiliar no desenvolvimento de sistemas robustos e até mesmo contribuem para fazer a validação do software.

## Metodologia

Utilizamos o método do texto estruturado e com base no modelo proposto no material disponibilizado pelo professor, onde esse modelo é descrito pelo uso de uma linguagem natural semi-estruturada, que parte da premissa que a utilização desse tipo de linguagem da aplicação e no do software facilita a compreensão e a validação dos requisitos por parte dos clientes<a id="TEC1" href="#RP1">[1]</a>.

A Legenda para identificação dos elementos dos cenários de cada tabela estão representadas na tabela 1.

<p align="center" > <strong> Tabela 1 - </Strong> Legenda das tabelas dos Cenários</font> <gitbr></p>
<center>

### Título: Identifica o cenário.

| Elemento | Descrição |
|:--|:--|
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
  <div style="text-align: center;">
    <strong>Tabela 2 - Pré-rastreabilidade dos requisitos</strong>
    <table align="center" style="margin-top: 20px; border-collapse: collapse; width: 80%;" border="1">
      <thead>
        <tr>
          <th>Cenário</th>
          <th>Requisitos</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>CEN01 - Acesso Inicial e Autenticação</td>
          <td>RE01, RE02, RE12, RE20, RE23</td>
        </tr>
        <tr>
          <td>CEN02 - Acesso a Informações de Benefícios</td>
          <td>RE03, RE07, RE09, RE10, RE11, RE14, RE16, RE17</td>
        </tr>
        <tr>
          <td>CEN03 - Suporte e Aprendizado</td>
          <td>RE04, RE05</td>
        </tr>
        <tr>
          <td>CEN04 - Solicitação e Atualização de Benefícios</td>
          <td>RE15, RE22, RE24, RE25</td>
        </tr>
        <tr>
          <td>CEN05 - Atualização de Dados Pessoais</td>
          <td>RE17</td>
        </tr>
        <tr>
          <td>CEN06 - Segurança e Alertas</td>
          <td>RE18, RE19</td>
        </tr>
        <tr>
          <td>CEN07 - Perícias Médicas</td>
          <td>RE21</td>
        </tr>
        <tr>
          <td>CEN08 - Acesso para Advogados</td>
          <td>RE26, RE27</td>
        </tr>
      </tbody>
    </table>
    <p><b>Fonte:</b> <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p>
  </div>
</details>


## Cenários

Os cenários foram criados com base nos requisitos funcionais priorizados no método First Things First.

### CEN01 - Acesso Inicial e Autenticação

O cenário de número 1 diz sobre o objetivo de Acesso e Autenticação Inicial e sua descrição está contida na tabela 3.  

<p align="center" > <strong> Tabela 3 - </Strong>  Cenário 1</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Permitir que o usuário possa realizar uma autenticação e acessar o aplicativo com informações já existentes do GOV.br |
| Contexto | Local: Na fila de espera do banco. <br>Tempo: Menos de 5 minutos. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário entra com suas informações do GOV.br na tela de login <br>O aplicativo permite a entrada via biometria depois do primeiro login <br>O usuário agora pode entrar com sua digital ao invés do login do GOV.br |
| Restrição | Se o usuário não possuir leitor de digital no celular a biometria não pode ser ativada |
| Exceção | Erro de conexão <br>Conta do GOV.br apresenta irregularidade |

<font size="3"><p style="text-align: center"><b>Fonte:</b>  <a href="https://github.com/GabrielMS00">Gabriel Souza</a> e <a href="https://github.com/paulohborba">Paulo Borba</a>, 2024</p></font>

### CEN02 - Acesso a Informações de Benefícios

O cenário de número 2 diz sobre o objetivo de Acesso a Informações de Benefícios e sua descrição está contida na tabela 4.  

<p align="center" > <strong> Tabela 4 - </Strong>  Cenário 2</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Permitir que o usuário acesse as informações dos seus benefícios do INSS |
| Contexto | Local: Em casa. <br>Tempo: Menos de 30 segundos por benefício. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular, possuir pelo menos 1 ano de contribuição. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado <br>Pelo menos 1 ano de contribuição |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Benefícios" na tela inicial <br>O usuário é direcionado para uma página onde pode escolher entre diferentes opções de benefícios <br>O usuário seleciona um benefício específico para visualizar mais informações <br>O sistema exibe as informações referentes ao benefício escolhido |
| Restrição | O usuário tem menos de 1 ano de contribuição |
| Exceção | O sistema do MeuINSS está fora do ar |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/JohnnyLopess">Johnny Lopes</a>, 2024</p>

### CEN03 - Suporte e Aprendizado

O cenário de número 3 diz sobre o objetivo de Suporte e Aprendizado e sua descrição está contida na tabela 5.  

</font><p align="center" > <strong> Tabela 5 - </Strong>  Cenário 3</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Permitir que o usuário do aplicativo do INSS consiga receber suporte técnico e acessar tutoriais para melhor compreensão e uso do aplicativo |
| Contexto | Local: Em casa. <br>Tempo: Menos de 15 minutos. <br>Pré-condição: Conta no GOV.br regular, celular conectado na internet, o aplicativo MeuINSS instalado no celular. |
| Recurso | Internet <br>Informações de login do GOV.br <br>Aparelho celular <br>Aplicativo MeuINSS instalado |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Suporte e tutoriais" <br>O usuário acessa a opção "Suporte" <br>O aplicativo apresenta uma mensagem informando que o usuário está sendo redirecionado para o suporte esperando a confirmação do mesmo <br>O aplicativo redireciona o usuário para o chat com um funcionário especializado <br>O usuário pode resolver suas dúvidas com essse funcionário |
| Restrição | O suporte estando indisponível |
| Exceção | Erro de conexão |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/vitorfleonardo">Vitor Feijó</a>, 2024</p></font>

### CEN04 - Solicitação e Atualização de Benefícios

 cenário de número 4 diz sobre o objetivo de Solicitação e Atualização de Benefícios e sua descrição está contida na tabela 6.  

<p align="center" > <strong> Tabela 6 - </Strong>  Cenário 4</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
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
|:--|:--|
| Objetivo | Permitir que o usuário possa atualizar seus dados pessoais a qualquer instante dentro do aplicativo |
| Contexto | Local: Em casa. <br>Tempo: Menos que 5 minutos. <br>Pré-condição: Aplicativo do Meu INSS instalado no dispositivo móvel, acesso à internet pelo dispositivo móvel, login e dados iniciais já iniciados. |
| Recurso | Internet <br> Aplicativo Meu INSS instalado <br>Dispositivo móvel com conectividade com a internet <br> Perfil já iniciado com informações básicas no aplicativo |
| Ator | Usuário que já possua um perfil dentro do APP do MEU INSS |
| Episódio | O usuário seleciona a opção "Meu cadastro" situado no menu principal <br>O usuário é direcionado para uma página com seus dados cadastrais <br>O usuário seleciona a opção "Complementar" <br>O sistema exibe os campos com os dados cadastrais do usuário e uma opção de mudar os dados <br>O usuário muda os dados nos campos desejados <br>O usuário clica na opção "concluir" <br>Os dados do usuário são alterados de acordo com suas opções escolhidas |
| Restrição | O servidor do sistema estar fora do ar |
| Exceção | Erro de preenchimento em campos de dados que possuam validação |

<font size="3"><p style="text-align: center"><b>Autor:</b> <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024</p></font>

### CEN06 - Segurança e Alertas

O cenário de número 6 diz sobre o objetivo de Segurança e Alertas e sua descrição está contida na tabela 8. 

<p align="center" > <strong> Tabela 8 - </Strong>Cenário 6</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Garantir a segurança dos dados dos usuários e prover alertas proativos sobre atividades suspeitas ou importantes relacionadas à conta do usuário. |
| Contexto | Local: Em qualquer local com acesso ao aplicativo. <br> Tempo: Alertas e verificações de segurança ocorrem em tempo real durante o uso do aplicativo. <br>Pré-condição: Aplicativo do Meu INSS instalado no dispositivo móvel, usuário Autenticado, configurações de Segurança Ativas, dispositivo Seguro, conexão Segura. |
| Recurso | Conexão segura de internet, ferramentas de autenticação forte (como autenticação de dois fatores), sistema de alertas via e-mail ou SMS. |
| Ator | Usuário do aplicativo Meu INSS, sistema de segurança do Meu INSS. |
| Episódio | O sistema monitora continuamente a sessão do usuário para detectar atividades suspeitas. <br> O usuário recebe alertas via SMS ou e-mail quando uma tentativa de login suspeita é detectada. <br> O usuário deve autenticar novamente usando um método de autenticação de dois fatores se comportamentos atípicos forem identificados. <br> O sistema registra todas as atividades de segurança e alertas emitidos para auditoria e melhoria contínua. |
| Restrição | Dependência de conectividade de internet constante e eficaz para enviar/receber alertas em tempo real. |
| Exceção |  Interrupções de serviço devido a falhas de servidor que afetam a capacidade do sistema de monitorar segurança ou enviar alertas. <br> Falsos positivos em alertas de segurança causando inconvenientes aos usuários.|

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/BiancaPatrocinio7">Bianca</a>, 2024</p></font>

### CEN07 - Perícias Médicas

O cenário de número 7 diz sobre o objetivo de Perícias Médicas e sua descrição está contida na tabela 9. 

<p align="center" > <strong> Tabela 9 - </Strong>  Cenário 7</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Permitir que o usuário realize agendamentos, reagendamentos e cancelamento de perícias médicas  |
| Contexto | Local: Em casa. <br>Tempo: Menos de 10 minutos. <br>Pré-condição: Aplicativo do Meu INSS instalado no dispositivo móvel, acesso à internet pelo dispositivo móvel, login já efetivado no aplicativo. |
| Recurso | Internet <br>Informações de login GOV.br <br>Dispositivo móvel com acesso à internet <br>Aplicativo Meu INSS instalado |
| Ator | Usuário com cadastro no GOV.br |
| Episódio | O usuário seleciona a opção "Novo pedido" situado no menu principal <br>O usuário é direcionado para uma página com diversas opções de solicitações <br>O usuário seleciona a opção "Perícia médica" <br>O usuário seleciona a opção desejada para agendar, reagendar ou cancelar uma perícia <br>O usuário é direcionado para uma página onde coloca as informações necessárias de acordo com a opção escolhida <br>O usuário clica em "Concluir" <br>Os dados são processados e as informações referentes a perícia médica são atualizados |
| Restrição | A data desejada para agendamento ou reagendamento não está disponível |
| Exceção | O servidor estar fora do ar |

<font size="3"><p style="text-align: center"><b>Fonte: <a href="https://github.com/acamposs">Amanda</a>, 2024</p></font>

### CEN08 - Acesso para Advogados

O cenário de número 8 diz sobre o objetivo de Acesso para Advogados e sua descrição está contida na tabela 10. 

<p align="center" > <strong> Tabela 10 - </Strong>  Cenário 8</font> <gitbr></p>

| Elemento | Descrição |
|:--|:--|
| Objetivo | Permitir que um advogado possua acesso aos documentos e processos referentes aos seus clientes dentro do sistema |
| Contexto | Local: Em um escritório de advocacia. <br>Tempo: Menos que 15 minutos. <br>Pré-condição: Aplicativo do MEU INSS instalado no dispositivo móvel, acesso à internet pelo dispositivo móvel. <br>Autorização de acesso aos processos e documentos de seus clientes dentro do sistema, perfil com condição especial de advogado. |
| Recurso | Internet <br>Aplicativo MEU INSS instalado <br>Dispositivo móvel com conectividade com a internet <br>Autorização prévia para acessar os dados de seus clientes |
| Ator | Advogado que possua um perfil dentro do APP do MEU INSS |
| Episódio | O advogado seleciona a opção "Clientes" situado no menu principal <br>O advogado é direcionado para uma página onde ele visualiza todos os seus clientes que possuam processos vinculados à previdência <br>O advogado seleciona o cliente desejado <br>É disponibilizado para o advogado todos os processos que estão vinculados ao seu cliente <br>O advogado passa a ter acesso às informações necessárias para o andamento do processo |
| Restrição | Erro de vínculo entre usuário cliente e usuário advogado, impedidndo que o advogado tenha acesso aos processos do seu cliente |
| Exceção | O servidor estar fora do ar |

<font size="3"><p style="text-align: center"><b>Fonte:</b> <a href="https://github.com/JoseFilipi">José Filipi</a>, 2024</p></font>

## Referências Bibliográficas

> <a id="RP1" href="#TEC1">1.</a> CENÁRIOS: Rastreamento de Cenários. [S. l.]. Disponível em: [http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf](http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf). Acesso em: 15 mai. 2024.

## Bibliografia
> </a> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 15 mai. 2024.


## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 15/05/2024 | Versão inicial da pagina de Cenários. | [Paulo Borba](https://github.com/paulohborba) | 16/05/2024 |[Johnny Lopes](https://github.com/JohnnyLopess)| 
| `1.1` | 16/05/2024 | Adição do cenário 2 e 6. | [Johnny Lopes](https://github.com/JohnnyLopess) | 17/05/2024| [Paulo Borba](https://github.com/paulohborba)| 
| `1.2` | 16/05/2024 | Adição do cenário 7 e 8 | [Gabriel Souza](https://github.com/GabrielMS00) | 19/05/2024 |[Johnny Lopes](https://github.com/JohnnyLopess)|
| `1.3` | 19/05/2024 | Correção da pagina de Cenários. | [Paulo Borba](https://github.com/paulohborba) | 19/05/2024 |[Johnny Lopes](https://github.com/JohnnyLopess)|