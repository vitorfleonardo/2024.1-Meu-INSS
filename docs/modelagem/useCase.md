# Casos de Uso

## Introdução

Os Casos de Uso, também conhecidos como diagramas comportamentais na notação da UML, são empregados para descrever ações específicas que um sistema, ou conjunto de sistemas (denominado "subject"), deve realizar em colaboração com um ou mais usuários externos (os "actors"). Esta técnica, fundamental na modelagem de sistemas, permite aos participantes de diversas áreas contribuir com suas perspectivas únicas, enriquecendo o processo de desenvolvimento.<a id="back1" href="#ref1">[1]</a>

Cada caso de uso busca proporcionar um resultado observável e valioso para os atores ou outros interessados, garantindo que as funcionalidades do sistema se alinhem efetivamente às necessidades dos usuários. Durante as sessões de desenvolvimento, ideias são livremente propostas e discutidas, com as mais adequadas sendo priorizadas para implementação, promovendo uma abordagem criativa e focada na resolução de problemas específicos dos usuários.

## Metodologia

A metodologia para criar o diagrama de casos de uso inicia com a identificação dos atores, utilizando a persona [Rafael Costa](https://requisitos-de-software.github.io/2024.1-Meu-INSS/elicitacao/personas/) para definir as necessidades dos usuários finais. Em seguida, os casos de uso são determinados com base nos requisitos funcionais elicitados, descrevendo funcionalidades ou ações do sistema.

Cada caso de uso é detalhadamente descrito, incluindo fluxos básicos, alternativos e de exceção, além de pré-condições e pós-condições. Utilizamos a ferramenta [Lucidchart](https://requisitos-de-software.github.io/2024.1-Meu-INSS/planejamento/ferramentas/) para criar o diagrama visual, mostrando os atores, casos de uso e suas inter-relações.

## Diagrama de Casos de Uso
A figura 1 demonstra o diagrama de casos de uso.
<p align="center" > <font><strong>Figura 1:</strong> Diagrama de casos de uso</font> <br><img src="../../imagens/Diagrama_UseCase.png" width = 300%></p>
<font size="3"><p style="text-align: center">Autor: [Johnny Lopes](https://github.com/JohnnyLopess) & [Vitor Leonardo](https://github.com/vitorfleonardo) & [José Souza](https://github.com/JoseFilipi), 2024</p></font>

### Legenda
<p align="center" > <font><strong>Tabela 1:</strong> Legenda do diagrama de casos de uso</font> <br></p>

|Elemento|Nome|Função|
|:--:|:--:|:--:|
|<img src="../../imagens/Ator.png" alt="Ator" width="100px">|Ator|Usuário do sistema, ou melhor, um tipo de usuário.<a id="back2" href="#ref2">[2]</a>|
|<img src="../../imagens/CasoUso.png" alt="Caso de uso" width="100px">|Elipse (Caso de uso)|É uma tarefa ou uma funcionalidade realizada pelo ator.<a id="back2" href="#ref2">[2]</a>|
|<img src="../../imagens/Sistema.png" alt="Sistema" width="100px">|Retângulo (Sistema)|Usado para representar o sistema ou o bloco em análise. Ele envolve os casos de uso e atores relacionados.<a id="back3" href="#ref3">[3]</a>|
|<img src="../../imagens/Relação.png" alt="Relação" width="100px">|Flecha (Relação)|As flechas são usadas para representar as relações ou interações entre atores e casos de uso.<a id="back3" href="#ref3">[3]</a>|

<font size="3"><p style="text-align: center">Autor: [Johnny Lopes](https://github.com/JohnnyLopess), 2024</p></font>

## Especificação de Casos de Uso
As tabelas abaixo demonstram a especificação dos casos de usos.

A tabela 2 demonstra como deve ser feito cada especificação.

<p align="center" > <font><strong>Tabela 2:</strong> Exemplo para especificação dos casos de uso</font> <br></p>

|<strong>Código do caso de uso|<strong>Nome do caso de uso|
|:--|:--|
|<strong>Descrição|Explicação detalhada do que o caso de uso realiza, incluindo qualquer interação específica com o usuário ou o sistema.|
|<strong>Ator|Quem ou o que interage diretamente com o caso de uso|
|<strong>Fluxo básico|Sequência principal de passos que descreve a interação padrão do ator com o sistema para atingir o objetivo do caso de uso.|
|<strong>Fluxos alternativos|Variantes do fluxo básico que ocorrem sob condições específicas, oferecendo caminhos alternativos ou adicionais.|
|<strong>Fluxo de exeção|Descreve o que acontece quando ocorre um erro ou uma situação excepcional durante a execução do caso de uso.|
|<strong>Pré-condições|Condições que devem ser verdadeiras ou cumpridas antes da execução do caso de uso.|
|<strong>Pós-condições|Estado do sistema ou condições que são verdadeiras após a conclusão do caso de uso.|
|<strong>Data da criação|Data em que o caso de uso foi criado ou documentado.|
|<strong>Rastreabilidade|Ligações do caso de uso a requisitos específicos.|

<font size="3"><p style="text-align: center">Autor: [Johnny Lopes](https://github.com/JohnnyLopess), 2024</p></font>

### UC01 -  Fazer Login

<p align="center" > <font><strong>Tabela 3:</strong>  Fazer Login</font> <br></p>

|<strong>UC01|<strong>Fazer Login|
|:--|:--|
|<strong>Descrição|Este caso de uso descreve o processo pelo qual um usuário autentica no sistema usando seu nome de usuário e senha.|
|<strong>Ator|Usuário|
|<strong>Fluxo básico|1. O usuário insere seu nome de usuário e senha.<br>2. O sistema valida as credenciais.<br>3. Se as credenciais forem válidas, o usuário é autenticado e ganha acesso ao sistema.|
|<strong>Fluxos alternativos|1. Caso de uso “Termo de Uso”: Antes de fazer login pela primeira vez, o usuário deve aceitar os termos de uso.<br>2. Caso de uso “Recuperar Senha”: Se o usuário esquecer sua senha, ele pode optar por recuperá-la.|
|<strong>Fluxo de exeção|1. Se as credenciais não forem válidas, o sistema informa ao usuário que o nome de usuário ou a senha estão incorretos.|
|<strong>Pré-condições| O usuário deve ter uma conta registrada no sistema.|
|<strong>Pós-condições| O usuário ganha acesso ao sistema após autenticação bem-sucedida.|
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade| RE01, RE02 |

<font size="3"><p style="text-align: center">Autor: [Vitor Feijó](https://github.com/vitorfleonardo), 2024</p></font>

### UC02 -  Editar Perfil

<p align="center" > <font><strong>Tabela 4:</strong>  Editar Perfil </font> <br></p>

|<strong>UC02|<strong> Editar Perfil |
|:--|:--|
|<strong>Descrição| Este caso de uso descreve o processo pelo qual um usuário pode alterar as informações do seu perfil no sistema. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico| 1. O usuário seleciona a opção para editar o perfil.<br>2. O sistema apresenta as informações atuais do perfil.<br>3. O usuário altera as informações desejadas.<br>4. O usuário salva as alterações.<br>5. O sistema valida e atualiza as informações do perfil. |
|<strong>Fluxos alternativos| N/A |
|<strong>Fluxo de exeção| 1. Se as informações fornecidas pelo usuário não forem válidas (por exemplo, formato de e-mail inválido), o sistema informa ao usuário sobre o erro. |
|<strong>Pré-condições|  O usuário deve estar autenticado no sistema. |
|<strong>Pós-condições| As informações do perfil do usuário são atualizadas no sistema. |
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade| RE17 |

<font size="3"><p style="text-align: center">Autor: [Bianca Patrocínio](https://github.com/BiancaPatrocinio7), 2024</p></font>

### UC03 -  Acessar documentos legislativos

<p align="center" > <font><strong>Tabela 5:</strong>  Acessar documentos legislativos </font> <br></p>

|<strong>UC03|<strong> Acessar documentos legislativos |
|:--|:--|
|<strong>Descrição| Permite que o usuário visualize documentos legislativos relevantes disponíveis no sistema. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico| 1. Usuário acessa a opção "Documentos Legislativos" na tela inicial do aplicativo.<br>2. O usuário é direcionado para uma página que lista categorias de documentos legislativos (por exemplo, Leis, Decretos, Medidas Provisórias).<br>3. Usuário seleciona uma categoria de documento.<br>4. O sistema exibe uma lista de documentos dentro da categoria selecionada.<br>5. Usuário seleciona um documento específico.<br>6. O sistema exibe o conteúdo detalhado do documento selecionado. |
|<strong>Fluxos alternativos| 1. Usuário utiliza a função de busca para encontrar um documento específico inserindo palavras-chave relacionadas ao documento desejado. |
|<strong>Fluxo de exeção| 1. Se o sistema estiver fora do ar ou o documento solicitado não estiver disponível, o usuário recebe uma mensagem de erro informando que o serviço não está disponível ou o documento não pode ser encontrado. |
|<strong>Pré-condições|  O usuário deve estar autenticado no sistema. |
|<strong>Pós-condições| O usuário obtém as informações necessárias sobre o documento legislativo selecionado. |
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade| RE03 |


<font size="3"><p style="text-align: center">Autor: [Johnny Lopes](https://github.com/JohnnyLopess), 2024</p></font>

### UC04 -  Acionar Suporte

<p align="center" > <font><strong>Tabela 6:</strong>  Acionar Suporte </font> <br></p>

|<strong>UC04|<strong> Acionar Suporte |
|:--|:--|
|<strong>Descrição| Este caso de uso descreve o processo pelo qual um usuário pode solicitar suporte ao sistema. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico| 1. O usuário seleciona a opção para acionar suporte.<br>2. O sistema apresenta as opções de suporte disponíveis.<br>3. O usuário escolhe a opção desejada e segue as instruções fornecidas pelo sistema. |
|<strong>Fluxos alternativos| 1. Caso de uso “Acessar Tutoriais”: Se o usuário optar por acessar tutoriais, ele será direcionado para a seção de tutoriais.<br>2. Caso de uso “Agendar Horários para Atendimento Presencial”: Se o usuário optar por agendar um horário para atendimento presencial, ele será direcionado para a seção de agendamento. |
|<strong>Fluxo de exeção|  	1. Se o usuário tentar acionar uma opção de suporte que não está disponível, o sistema informa ao usuário sobre a indisponibilidade. |
|<strong>Pré-condições|  O usuário deve estar autenticado no sistema. |
|<strong>Pós-condições|  O usuário recebe o suporte necessário ou é direcionado para a seção apropriada para obter mais assistência. |
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade| RE04, RE06, RE21 |

<font size="3"><p style="text-align: center">Autor: [Gabriel](https://github.com/GabrielMS00), 2024</p></font>

### UC05 - Agendar horários para atendimento presencial

<p align="center" > <font><strong>Tabela 7:</strong> Agendar horários para atendimento presencial</font> <br></p>

| <strong>UC05 | <strong>Agendar horários para atendimento presencial|
|:--|:--|
|<strong>Descrição| Permite que o usuário agende um horário para atendimento presencial em uma agência do INSS, escolhendo data, hora e local conforme disponibilidade. |
| <strong>Ator | Usuário |
| <strong>Fluxo básico | 1. Usuário acessa a opção "Novo Pedido" na tela inicial do aplicativo. <br>2. O usuário é direcionado a uma página de seleção de pedidos. <br>3. Usuário seleciona um pedido na opção "Atendimento Presencial".<br>4. São fornecidas Informações do Serviço solicitado ao usuário.<br>5. São solicitados os dados do requerente da solicitação, celular e email. <br>6. É solicitado o endereço para que as Agências mais próximas sejam listadas. <br>7. O usuário seleciona a agência e sua solicitação é atribuída. |
| <strong>Fluxos alternativos | 1. O usuário acessa a opção "Consultar Pedidos" e seleciona "Novo Pedido". |
| <strong>Fluxo de exceção | 1. Caso o usuário não preencha os campos obrigatórios será solicitado a revisão das informações do formulário|
| <strong>Pré-condições | 1. Usuário deve estar autenticado no sistema MeuINSS com uma conta GOV.br regular.<br> 2. O aplicativo MeuINSS deve estar instalado e o dispositivo conectado à internet.|
| <strong>pós-condições | 1. O usuário consegue agendar o atendimento solicitado na agência mais próxima do endereço fornecido. |
| <strong>Data da criação | 17/05/2024 |
| <strong>Rastreabilidade | RE06, RE21 |

<font size="3"><p style="text-align: center">Autor: [José Filipi](https://github.com/JoseFilipi), 2024</p></font>

### UC06 - Solicitar benefício

<p align="center" > <font><strong>Tabela 8:</strong> Solicitar benefício</font> <br></p>

| <strong>UC06 | <strong>Solicitar benefício |
|:--|:--|
|<strong>Descrição| Permite que o usuário solicite os benefícios aos quais tem direito no sistema MeuINSS. |
| <strong>Ator | Usuário |
| <strong>Fluxo básico | 1. Usuário acessa a opção "Benefícios" na tela inicial do aplicativo.<br>2. O usuário é direcionado para uma página de seleção de benefícios.<br>3. Usuário seleciona um benefício específico para poder emitir.<br>4. O sistema exibe um formulário para preencher informações do benefício selecionado para a emissão.<br>5. O sistema armazena e protocola a emissão. |
| <strong>Fluxos alternativos | 1. Se o formulário não for preenchido corretamente ,o sistema alerta o usuário e não permite o envio da solicitação até que todas as informações sejam fornecidas corretamente. |
| <strong>Fluxo de exceção | 1. Se ocorrer um erro no envio da solicitação, o sistema deve apresentar uma mensagem de erro e permitir que o usuário tente enviar novamente. |
| <strong>Pré-condições | 1. Usuário deve estar autenticado no sistema MeuINSS com uma conta GOV.br regular.<br> 2. Usuário deve ter pelo menos 1 ano de contribuição.<br> 3. O aplicativo MeuINSS deve estar instalado e o dispositivo conectado à internet.<br>4. O usuário deve estar apto a receber o benefício selecionado. |
| <strong>pós-condições | O usuário consegue realizar a emissão da solicitação garantindo o seu benefício. |
| <strong>Data da criação | 16/05/2024 |
| <strong>Rastreabilidade | RE15, RE22, RE24, RE25 |

<font size="3"><p style="text-align: center">Autor: [Paulo Borba](https://github.com/paulohborba), 2024</p></font>

### UC07 - Consultar benefícios

<p align="center" > <font><strong>Tabela 9:</strong> Consultar benefícios</font> <br></p>

|<strong>UC07|<strong>Consultar benefícios|
|:--|:--|
|<strong>Descrição|Permite que o usuário visualize informações detalhadas sobre os benefícios aos quais tem direito no sistema MeuINSS.|
|<strong>Ator|Usuário|
|<strong>Fluxo básico|1. Usuário acessa a opção "Benefícios" na tela inicial do aplicativo.<br>2. O usuário é direcionado para uma página de seleção de benefícios.<br>3. Usuário seleciona um benefício específico.<br>4. O sistema exibe as informações detalhadas do benefício selecionado.|
|<strong>Fluxos alternativos|1. Usuário seleciona a opção de ver todos os benefícios, o sistema lista todos os benefícios aos quais o usuário tem direito.|
|<strong>Fluxo de exeção|1. Se o sistema MeuINSS estiver fora do ar, o usuário recebe uma mensagem de erro informando que o serviço não está disponível no momento.|
|<strong>Pré-condições|1. Usuário deve estar autenticado no sistema MeuINSS com uma conta GOV.br regular.<br>2. Usuário deve ter pelo menos 1 ano de contribuição.<br>3. O aplicativo MeuINSS deve estar instalado e o dispositivo conectado à internet.|
|<strong>Pós-condições|O usuário obtém as informações necessárias sobre o benefício selecionado.|
|<strong>Data da criação|16/05/2024|
|<strong>Rastreabilidade|RE08,RE14,RE15|

<font size="3"><p style="text-align: center">Autor: [Amanda](https://github.com/acamposs), 2024</p></font>

### UC08 - Consultar extratos

<p align="center" > <font><strong>Tabela 10:</strong> Consultar extratos</font> <br></p>

|<strong>UC08|<strong> Consultar extratos |
|:--|:--|
|<strong>Descrição|Permite que o usuário visualize os extratos referentes a benefícios, imposto de renda e empréstimos no sistema MeuINSS. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico|1. Usuário acessa a opção "Extratos" na tela inicial do aplicativo.<br>2. O sistema apresenta as opções de extratos disponíveis: extrato de aposentadoria mensal, extrato anual de imposto de renda e extrato anual de empréstimo.<br>3. Usuário seleciona o tipo de extrato que deseja consultar.<br>4. O sistema solicita que o usuário especifique o período do extrato.<br>5. Usuário insere o período desejado e confirma.<br>6. O sistema gera e exibe o extrato para o período especificado. |
|<strong>Fluxos alternativos|1. Usuário escolhe exportar o extrato para um arquivo PDF ou CSV após visualizar o extrato na tela.|
|<strong>Fluxo de exeção|1. Se o sistema estiver indisponível ou houver um erro ao gerar o extrato, o usuário recebe uma mensagem de erro informando que o serviço não está disponível no momento ou que houve um erro ao processar o pedido.|
|<strong>Pré-condições|1. O usuário deve estar autenticado no sistema.<br>2. Deve existir histórico de transações ou benefícios para o período consultado.|
|<strong>Pós-condições|  O usuário obtém as informações desejadas sobre os extratos para o período especificado.|
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade|RE09, RE10, RE11|

<font size="3"><p style="text-align: center">Autor: [Johnny Lopes](https://github.com/JohnnyLopess), 2024</p></font>


### UC09 - Acessar CNIS

<p align="center" > <font><strong>Tabela 11:</strong> Acessar CNIS </font> <br></p>

|<strong>UC08|<strong> Acessar CNIS |
|:--|:--|
|<strong>Descrição|Este caso de uso descreve o processo pelo qual um cidadão acessa seu Extrato de Contribuição (CNIS) no sistema. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico|1. O usuário seleciona a opção para acessar o CNIS.<br>2. O sistema exibe o CNIS do cidadão. |
|<strong>Fluxos alternativos|1. Se o usuário desejar editar o CNIS, ele pode optar por “Editar CNIS”.|
|<strong>Fluxo de exeção|1. Se o sistema não conseguir carregar dados do usuário sobre o CNIS, o sistema informará ao usuário que ocorreu um erro.|
|<strong>Pré-condições| O usuário deve estar autenticado no sistema.|
|<strong>Pós-condições|   O cidadão visualiza seu CNIS após a execução bem-sucedida do caso de uso.|
|<strong>Data da criação|19/05/2024|
|<strong>Rastreabilidade| RE13, RE15 |

<font size="3"><p style="text-align: center">Autor: [Vitor Feijó](https://github.com/vitorfleonardo), 2024</p></font>

### UC10 - Solicitar Empréstimo

<p align="center" > <font><strong>Tabela 12:</strong> Solicitar Empréstimo</font> <br></p>

|<strong>UC08|<strong> Solicitar Empréstimo |
|:--|:--|
|<strong>Descrição|Este caso de uso descreve o processo pelo qual um usuário pode solicitar um empréstimo no sistema. |
|<strong>Ator|Usuário|
|<strong>Fluxo básico|1. O usuário seleciona a opção para solicitar empréstimo.<br>2. O sistema apresenta as opções de empréstimo disponíveis.<br>3. O usuário escolhe a opção desejada e insere as informações necessárias.<br>4. O usuário submete a solicitação de empréstimo.<br>5. O sistema valida a solicitação e, se aprovada, processa o empréstimo. |
|<strong>Fluxos alternativos|1. Caso de uso “Bloquear Empréstimo”: Se o usuário tiver um empréstimo pendente ou se o sistema detectar alguma irregularidade, o usuário pode ser impedido de solicitar um novo empréstimo.|
|<strong>Fluxo de exeção|1. Se a solicitação de empréstimo não for aprovada, o sistema informa ao usuário sobre a rejeição e fornece o motivo, se aplicável.|
|<strong>Pré-condições|O usuário deve estar autenticado no sistema e não deve ter empréstimos pendentes.|
|<strong>Pós-condições|  Se aprovado, o empréstimo é processado e os fundos são transferidos para a conta do usuário.|
|<strong>Data da criação|16/05/2024|
|<strong>Rastreabilidade| RE11, RE18, RE19|

<font size="3"><p style="text-align: center">Autor: [Filipi](https://github.com/JoseFilipi), 2024</p></font>

### UC11 - Simular contribuição

<p align="center" > <font><strong>Tabela 13:</strong> Solicitar benefício</font> <br></p>

| <strong>UC11 | <strong>Simular contribuição |
|:--|:--|
|<strong>Descrição| Permite que o usuário simular as contribuições no sistema MeuINSS. |
| <strong>Ator | Usuário |
| <strong>Fluxo básico | 1. Usuário acessa a opção "Simular contribuição" na tela inicial do aplicativo.<br>2. O usuário é direcionado para a página de Simular contribuição.<br>3. Usuário seleciona de simular para obter o resulltado desejado.<br>4. O sistema processa as informações e calcula o tempo total de contribuição e uma estimativa dos benefícios de aposentadoria.<br>5.O sistema exibe o resultado da simulação, incluindo o tempo de contribuição e a estimativa dos valores de aposentadoria. |
| <strong>Fluxos alternativos | 1. O usuário opta por importar so dados diretamente do CNIS, com isso o sistema solicita a permissão do usuário para acessar esses dados.|
| <strong>Fluxo de exceção | 1. Caso o sistema não consiga acessar os dados do CNIS, o sistema deve apresentar uma mensagem de erro e permitir que o usuário tente enviar novamente. |
| <strong>Pré-condições | 1. Usuário deve estar autenticado no sistema MeuINSS com uma conta GOV.br regular.<br> 2. Usuário deve ter pelo menos 1 ano de contribuição.<br> 3. O aplicativo MeuINSS deve estar instalado e o dispositivo conectado à internet.
| <strong>pós-condições | O usuário obtém uma estimativa do tempo de contribuição e dos benefícios de aposentadoria com base nos dados fornecidos. |
| <strong>Data da criação | 19/05/2024 |
| <strong>Rastreabilidade | RE08 |

<font size="3"><p style="text-align: center">Autor: [Vitor Feijó](https://github.com/vitorfleonardo), 2024</p></font>

### UC012 - Acesso de Processos do Cliente

<p align="center" > <font><strong>Tabela 4:</strong> Solicitar benefício</font> <br></p>

| <strong>UC12 | <strong>Acesso de Processos do Cliente |
|:--|:--|
|<strong>Descrição| Permitir que um advogado acesse os processos dos seus clientes com a autorização destes e possa solicitar e fornecer documentos necessários ao processo diretamente pelo sistema. |
| <strong>Ator | Usuário |
| <strong>Fluxo básico | 1. O advogado acessa a opção "Processos" na tela inicial do aplicativo.<br>2. O usuário é direcionado para uma página de Simular contribuição.<br>3. O advogado seleciona um cliente específico e solicita acesso ao processo do cliente.<br>4. O sistema verifica se há uma autorização prévia do cliente para o advogado acessar o processo.<br>5.O sistema exibe os detalhes do processo do cliente, incluindo documentos e informações relevantes. |
| <strong>Fluxos alternativos | 1. O usuário opta por importar so dados diretamente do CNIS, com isso o sistema solicita a permissão do usuário para acessar esses dados.|
| <strong>Fluxo de exceção | 1. O sistema informa que as credenciais são inválidas e solicita uma nova tentativa de login. |
| <strong>Pré-condições | 1. O advogado deve estar autenticado no sistema MeuINSS com uma conta GOV.br regular.<br> 2. O advogado deve ter a permissão do cliente para poder acessar os proessos.<br> 3. O aplicativo MeuINSS deve estar instalado e o dispositivo conectado à internet. |
| <strong>pós-condições | O advogado acessa e visualiza os processos dos clientes autorizados e pode solicitar e enviar documentos necessários diretamente pelo sistema. |
| <strong>Data da criação | 19/05/2024 |
| <strong>Rastreabilidade | RE26, RE27 |

<font size="3"><p style="text-align: center">Autor: [Paulo Borba](https://github.com/paulohborba), 2024</p></font>

## Referências Bibliográficas

> <a id="ref1" href="#back1">1.</a> SERRANO, M. SERRANO, M (s.d.). Requisitos - Aula 13. UnB GAMA. 

> <a id="ref2" href="#back2">2.</a> DEV MEDIA. O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML. Disponível em: [https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408](https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408). Acesso em: 16 Mai. 2024.

> <a id="ref3" href="#back3">3.</a> Requisitos de Software. Economia DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/#introducao](https://requisitos-de-software.github.io/2023.2-Economia-DF/modelagem/casos-de-uso/#introducao). Acesso em: 16 Mai. 2024.

## Bibliografia
> </a> Requisitos de Software. Economia DF (2023.2). Disponível em: [https://requisitos-de-software.github.io/2023.2-Economia-DF/](https://requisitos-de-software.github.io/2023.2-Economia-DF/). Acesso em: 16 Mai. 2024.

> </a> Pimentel, Andrey Ricardo. Projeto de Software Usando a UML. Apostila para Curso de Projeto de Sistemas Orientado a Objetos Usando a UML. Disponível em: [https://aprender3.unb.br/mod/resource/view.php?id=1218850](https://aprender3.unb.br/mod/resource/view.php?id=1218850). Acesso em: 16 Mai. 2024.</a>


## Histórico de Versão
| Versão | Data | Descrição | Autor(es) | Data de revisão | Revisor(es) |
| :-: | :-: | :-: | :-: | :-: | :-: |
| `1.0` | 13/05/2024 | Versão inicial da pagina de Casos de Uso. | [Vitor Feijó](https://github.com/vitorfleonardo) & [Johnny Lopes](https://github.com/JohnnyLopess) & [José Filipi](https://github.com/JoseFilipi) | 15/05/2024| [Paulo Borba](https://github.com/paulohborba) | 
| `1.1` | 16/05/2024 | Adição de conteúdo à página. | [Johnny Lopes](https://github.com/JohnnyLopess) | 17/05/2024 | [José Filipi](https://github.com/JoseFilipi) | 
| `1.2` | 17/05/2024 | Adição de caso de uso 3. | [José Filipi](https://github.com/JoseFilipi) | 18/05/2024 | [Paulo Borba](https://github.com/paulohborba) | 
| `1.3` | 19/05/2024 | Adição de caso de casos de novos casos de uso. | [José Filipi](https://github.com/JoseFilipi) & [Vitor Feijó](https://github.com/vitorfleonardo) & [Johnny Lopes](https://github.com/JohnnyLopess) & [Paulo Borba](https://github.com/paulohborba)| 19/05/2024 | [Amanda Campos](https://github.com/acamposs) | 