# Storytelling

## Introdução

A técnica para a elicitação de requisitos, Storytelling, se baseia em uma narrativa de histórias que visam capturar as necessidades, os desejos e as motivações dos usuários de uma forma mais autêntica e profunda, o que 
acaba sendo refletido em produtos mais inovadores e de sucesso. Através do desenvolvimento dessas narrativas, podemos citar alguns benefícios que esta téctica fornece, tais como:
* Engajar os stakeholders.
* Obter uma visão holística das necessidades dos usuários.
* Revelação de novas ideias.
* Uma maneira mais eficaz de realizar a comunicação.
* Refinamento e contextualização dos requisitos.

## Metodologia

Utilizamos as [Personas](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/personas/) e as informações delas criadas anteriormente pela [Amanda Campos](https://github.com/acamposs) e [Bianca Castro](https://github.com/BiancaPatrocinio7), para a elaboração das histórias e contexto, e depois fizemos uma lista contendo todos os requisitos elicitados nesse artefato.

## Storytelling

### História 1

Elisa Silva é uma aposentada que trabalhou a vida toda com o serviço público, possui 63 anos e é viúva. Ela possui apenas um filho, mas este se encontra morando em outra cidade, por conta disso, ela acaba sentindo
bastante falta do contato físico com sua família. Elisa possui uma rotina saudável, costuma realizar caminhadas no período da manhã e sempre prioriza uma alimentação saudável, baseada em alimentos frescos, sempre 
comprados semanalmente.

Como uma senhora aposentada, Elisa costuma utilizar o aplicativo Meu INSS para fazer o gerenciamento da sua aposentadoria - verificar os extratos de pagamento e os comprovantes de rendimentos. 

Mas por se tratar de uma senhora que não possui muita afinidade com a tecnologia, e por não possuir um familiar próximo que possa estar auxiliando ela em seus processos, Elisa deseja que o aplicativo do Meu INSS 
seja o mais simples e acessíevl possível para se utilizar, possuindo uma interface clara e instruções simples para orientá-la em suas tarefas do cotidiano, além disso, ela espera que o aplicativo rode tanto em 
celulares como em computadores, para facilitar seus afazeres cotidianos, e é extremamente importante para a Elisa que o aplicativo forneça suporte para diversos idioams, incluindo o Português, para ajudar na 
interação com o sistema.

### História 2

Rafael Costa atua como um analista de sistemas em uma empresa de tecnologia inovatech, possui 35 anos, é casado e possui um filho pequeno, costuma dedicar seu tempo livre à sua família, buscando sempre atividades ao ar livre e momentos de lazer em casa. Além disso, se dedica bastante ao seu trabalho, sendo bem capacitado e considerado uma referência dentro de sua empresa.

Rafael costuma utilizar constantemente o aplicativo do Meu INSS para obter informações referentes a sua situação previdenciária, incluindo seu tempo de contribuição, o valor estimado da sua aposentadoria e os requisitos necessários para que ele possa se aposentar.

Por utilizar constantemente o aplicativo, Rafael espera que o sistema seja seguro e confiável, garantido sempre a integridade dos seus dados, além disso, ele também deseja que o aplicativo forneça recursos avançados, como simulações de aposentadora e ferramentas de planejamento financeiro, para auxiliá-lo em suas decisões refentes à sua aposentadoria.

### História 3

Melanie Lima, 42 anos, é uma dedicada professora de matemática para o fundamental 2, com uma longa história de trabalho desde os 15 anos. Sua paixão pelo ensino é evidente, mas sua jornada foi marcada por desafios, incluindo uma lesão no pulso que resultou em tendinite, devido ao excesso de escrita nos quadros. Apesar disso, Melanie mantém sua paixão pelo ensino e busca maneiras de tornar suas aulas mais eficazes e envolventes.

Casada e mãe de um filho, Melanie é uma pessoa organizada e planejadora. Ela gosta de acampar e criar planos detalhados, muitas vezes usando planilhas para ajudar a garantir que tudo corra bem. Recentemente, devido à lesão em seu pulso, Melanie decidiu que é hora de buscar auxílio-acidente como indenização.

Para isso, ela decide utilizar o aplicativo Meu INSS. Embora não seja uma usuária frequente de aplicativos, Melanie deseja que sua experiência com o Meu INSS seja simples e eficiente. Ela precisa fazer o login, acessar a tela de auxílios e solicitar o auxílio-acidente. Com sua determinação e habilidades de resolução de problemas, Melanie está confiante de que conseguirá navegar no aplicativo e obter as respostas necessárias para iniciar o processo de solicitação de auxílio.

### História 4

Julyana Batista é uma advogada especializada em direito previdenciário, formada pela Unicamp. Ela dedica sua carreira a garantir benefícios justos para seus clientes, utilizando suas habilidades cruciais para interpretar leis complexas dentro do INSS.

Em seu trabalho, Julyana utiliza o aplicativo Meu INSS para acompanhar processos, solicitar documentos e entrar com recursos. No entanto, existem momentos em que apenas o cliente tem acesso a certos processos, o que torna necessário o seu suporte para orientá-los da melhor forma possível.

Para Julyana, cada caso é único e ela se empenha em oferecer um serviço de qualidade, garantindo que seus clientes tenham acesso aos seus direitos previdenciários de forma eficaz. Ela busca no aplicativo todas as informações necessárias para que o processo de aposentadoria de seus clientes seja bem-sucedido, pois seu objetivo é auxiliá-los nessa importante etapa da vida.


## Lista de Requisitos Elicitados

<table>
  <thead>
    <tr>
      <th>Identificador</th>
      <th>Tipo</th>
      <th>Requisito</th>
      <th>Implementação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ST01</td>
      <td>RF</td>
      <td>O aplicativo deve oferecer informações sempre atualizadas referente aos benefícios previdenciários e os extratos de pagamentos.</td>
      <td>Sim</td>
    </tr>   
    <tr>
      <td>ST02</td>
      <td>RF</td>
      <td>O usuário deve realizar o login com o acesso unificado do gov.br.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST03</td>
      <td>RF</td>
      <td>O sistema deve oferecer uma opção de recuperação de senha para usuários que a esquecerem.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST04</td>
      <td>RF</td>
      <td>O aplicativo deve apresentar uma interface clara e fácil de usar, especialmente para usuários que não são frequentes ou que possam ter limitações físicas.</td>
      <td>Não</td>
    </tr>
        <tr>
      <td>ST05</td>
      <td>RF</td>
      <td> O usuário deve conseguir solicitar auxílio-acidente através de um formulário específico.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST06</td>
      <td>RF</td>
      <td>O formulário deve incluir campos para descrição do acidente, data do acidente, e anexos de documentos médicos.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST07</td>
      <td>RF</td>
      <td>O usuário deve ser capaz de verificar o status de suas solicitações de auxílio.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST08</td>
      <td>RF</td>
      <td>O sistema deve oferecer suporte direto, como um chat ao vivo ou uma linha direta, para assistência imediata.</td>
      <td>Não</td>
    </tr>
        <tr>
      <td>ST09</td>
      <td>RF</td>
      <td>O sistema deve permitir que um advogado acesse os processos dos seus clientes com a autorização destes.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST10</td>
      <td>RF</td>
      <td>O sistema deve permitir que um advogado solicite documentos necessários ao processo diretamente ao sistema.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST11</td>
      <td>RF</td>
      <td>O sistema deve possuir uma funcionalidade onde o advogado possa fornecer documentos.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST12</td>
      <td>RNF</td>
      <td>O sistema deve notificar o usuário sobre atualizações importantes em suas solicitações via notificações no aplicativo ou por email.</td>
    <td>Não</td>
    </tr>
        <tr>
      <td>ST13</td>
      <td>RNF</td>
      <td>O design do aplicativo deve ser acessível, com fontes legíveis e botões grandes, considerando usuários com dificuldades físicas como a tendinite.</td>
      <td>Não</td>
    </tr>
        <tr>
      <td>ST14</td>
      <td>RNF</td>
      <td>O aplicativo deve ser compatível com as principais plataformas móveis.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST15</td>
      <td>RNF</td>
      <td>O aplicativo deve possuir um sistema de segurança que permita que os dados sejam armazenados sem riscos.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST16</td>
      <td>RNF</td>
      <td>O aplicativo deve ser capaz de interagir com outros sistemas governamentais.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST17</td>
      <td>RNF</td>
      <td>O aplicativo deve permitir outras formas de acesso como profissionais do legislativo para o acompanhamento facilitado de documentos e processos.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST17</td>
      <td>RNF</td>
      <td>O sistema deve possuir suporte para os principais idiomas existentes, principalmente o Português.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST19</td>
      <td>RNF</td>
      <td>O sistema deve ser acessível tanto por meio de celulares quanto por meio de computadores.</td>
      <td>Sim</td>
    </tr>
        <tr>
      <td>ST20</td>
      <td>RF</td>
      <td>O sistema deve ser capaz de realizar simulações referentes à aposentadoria.</td>
      <td>Sim</td>
    </tr> 
  </tbody>
</table>

## Referências Bibliográficas

>[1] Sommerville, I., Engenharia de software, 10ª ed., Editora Pearson, 2016.

>[2] Santos, V. G., Daher N., UTILIZAÇÃO DE STORYTELLING COMO FERRAMENTA DE AQUISIÇÃO DE REQUISITOS EM PROCESSO DE DESENVOLVIMENTO DE SOFTWARE APOIADOS EM MODELOS ÁGEIS: O USO APOIADO NO EXTREME PROGRAMMING, Belo Horizonte, 2008. 14 p., Artigo (Análise de Sistemas), e-tec UNI-BH. Disponível em: https://revistas.unibh.br/dtec/article/view/440. 

## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 11/04/2024  | Versão inicial da pagina de Storytelling | [Paulo Borba](https://github.com/paulohborba) & [Gabriel Souza](https://github.com/GabrielMS00)| 12/04/2024|<a href="https://github.com/acamposs">Amanda</a> & <a href="https://github.com/BiancaPatrocinio7">Bianca</a>|
| `1.1` | 12/04/2024  | Complementando informações da pagina de Storytelling | [Paulo Borba](https://github.com/paulohborba) | 14/04/2024 |<a href="https://github.com/acamposs">Amanda</a> & <a href="https://github.com/BiancaPatrocinio7">Bianca</a>|
