Diretrizes para solicitações legais de dados do usuário - GitHub Docs

[Skip to main content](#main-content)

[](/pt)[GitHub Docs](/pt)

Publicamos atualizações frequentes em nossa documentação, e a tradução desta página ainda pode estar em andamento. Para obter as informações mais recentes, acesse a [documentação em inglês](/en). Se houver problemas com a tradução desta página, [entre em contato conosco](https://github.com/contact?form[subject]=translation%20issue%20on%20docs.github.com&form[comments]=).

Diretrizes para solicitações legais de dados do usuário
==========

[Neste artigo](/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data#in-this-article)
----------

* [Sobre estas diretrizes](#about-these-guidelines)

* [Terminologia GitHub](#github-terminology)

* [Dados do usuário no GitHub.com](#user-data-on-githubcom)

* [Notificaremos qualquer proprietário de conta afetado](#we-will-notify-any-affected-account-owners)

* [Compartilhamento de informações não públicas](#disclosure-of-non-public-information)

* [Reembolso de custos](#cost-reimbursement)

* [Conservação de dados](#data-preservation)

* [Envio de solicitação](#submitting-requests)

* [Pedidos de aplicação de lei estrangeira](#requests-from-foreign-law-enforcement)

* [Perguntas](#questions)

Você é um oficial da lei que está conduzindo uma investigação envolvendo o conteúdo de usuário hospedado no GitHub? Ou talvez você seja uma pessoa consciente de privacidade que gostaria de saber quais informações compartilhamos com um oficial da lei e sob quais circunstâncias. De qualquer forma, você está na página certa.

Nessas diretrizes, informamos quem é o GitHub, os tipos de dados que temos, e as condições em que divulgaremos as informações privadas do usuário. Antes de entrarmos nos detalhes, aqui estão alguns dados importantes que você pode querer saber:

* Vamos [**notificar os usuários afetados**](#we-will-notify-any-affected-account-owners) sobre quaisquer solicitações sobre suas informações de conta, a menos que seja proibido fazê-lo por lei ou por decisão judicial.
* Não divulgaremos **dados de rastreamento de localização**, tais como registros de endereços IP, sem uma [ordem judicial válida ou mandado de busca](#with-a-court-order-or-a-search-warrant).
* Não divulgaremos nenhum **conteúdo privado do usuário**, incluindo o conteúdo de repositórios privados, sem um [mandado de busca válido](#only-with-a-search-warrant).

[](#about-these-guidelines)Sobre estas diretrizes
----------

Nossos usuários nos confiam seus projetos e códigos de software — muitas vezes, alguns dos seus negócios ou ativos pessoais mais valiosos. Manter essa confiança é essencial para nós, o que significa manter os dados do usuário protegidos, seguros e privados.

Embora a esmagadora maioria de nossos usuários use os serviços do GitHub para criar novos negócios, construir novas tecnologias e melhorar a humanidade em geral, reconhecemos que, com milhões de usuários espalhados por todo o mundo, haverá certamente algumas maçãs podres. Nesses casos, queremos ajudar no cumprimento da lei e proteger nosso público.

Ao estabelecer diretrizes para os responsáveis pela aplicação da lei, esperamos encontrar um equilíbrio entre os interesses frequentemente concorrentes da privacidade do usuário e da justiça. Esperamos que essas diretrizes ajudem a definir expectativas para ambos os lados, e acrescente transparência aos processos internos do GitHub. Nossos usuários devem saber que valorizamos suas informações privadas e que fazemos tudo o que estiver ao nosso alcance para protegê-las. No mínimo, isso significa transmitir dados a terceiros somente quando os requisitos legais adequados tiverem sido cumpridos. Da mesma forma, também esperamos educar os responsáveis pela aplicação da lei sobre os sistemas do GitHub, para que eles possam adaptar de forma mais eficiente suas solicitações de dados e solicitar apenas as informações necessárias para realizar suas investigações.

[](#github-terminology)Terminologia GitHub
----------

Antes de nos pedir para divulgar dados, pode ser útil entender como nosso sistema é implementado. O GitHub hospeda milhões de repositórios de dados usando o [sistema de controle de versões do Git](https://git-scm.com/video/what-is-version-control). Os repositórios no GitHub, que podem ser públicos ou privados, são mais comumente usados para projetos de desenvolvimento de software, mas também são frequentemente usados para trabalhar em conteúdos de todos os tipos.

* [**Usuários**](/pt/articles/github-glossary#user) — Os usuários estão representados em nosso sistema como contas pessoais do GitHub. Cada usuário tem um perfil pessoal e pode possuir vários repositórios. Os usuários podem criar ou serem convidados a integrar organizações ou a colaborar com repositórios de outro usuário.

* [**Colaboradores**](/pt/articles/github-glossary#collaborator) - Um colaborador é um usuário com acesso de leitura e escrita em um repositório, que foi convidado pelo proprietário do repositório a contribuir.

* [**Organizações**](/pt/articles/github-glossary#organization) — Organizações são um grupo de dois ou mais usuários que, normalmente, espelham organizações do mundo real, como empresas ou projetos. Elas são administradas por usuários e podem conter repositórios e equipes de usuários.

* [**Repositórios**](/pt/articles/github-glossary#repository) — Um repositório é um dos elementos mais básicos do GitHub. Imagine-o como a pasta de um projeto. Um repositório contém todos os arquivos de projeto (incluindo a documentação) e armazena o histórico de revisão de cada arquivo. Os repositórios podem ter vários colaboradores e, a critério dos seus administradores, podem estar publicamente visíveis ou não.

* [**Páginas**](/pt/articles/what-is-github-pages) — GitHub Pages são páginas públicas na web, hospedadas gratuitamente pelo GitHub, que os usuários podem facilmente publicar através de código armazenado em seus repositórios. Se um usuário ou uma organização tem uma GitHub Page, geralmente, ela pode ser encontrada em uma URL como `https://username. ithub.io` ou pode ter a página da web mapeada para seu próprio nome de domínio personalizado.

* [**Gist**](/pt/articles/creating-gists) — Gists são snippets de código-fonte ou outro texto que os usuários podem usar para armazenar ideias ou compartilhar com amigos. Como repositórios regulares do GitHub, os Gists são criados com o Git, por isso são automaticamente versionados, bifurcáveis e podem ser baixados. Os Gists podem ser públicos ou secretos (acessíveis apenas através de uma URL conhecida). Os Gists Públicos não podem ser convertidos em Gists secretos.

[](#user-data-on-githubcom)Dados do usuário no GitHub.com
----------

Aqui está uma lista não exaustiva dos tipos de dados que mantemos a respeito dos usuários e projetos no GitHub.

* []()**Dados públicos da conta** — Há uma variedade de informações publicamente disponíveis no GitHub sobre os usuários e seus repositórios. Perfis de usuário podem ser encontrados em uma URL, tais como `https://github.com/username`. Perfis de usuário exibem informações sobre quando o usuário criou sua conta e suas atividades públicas no GitHub.com, além de interações sociais. Perfis públicos de usuários também podem incluir informações adicionais que um usuário pode ter escolhido compartilhar publicamente. Todos os perfis públicos de usuário mostram:

  * Nome de usuário

  * Os repositórios que o usuário marcou com estrela

  * Os outros usuários do GitHub que o usuário segue

  * Os usuários que o seguem

    Opcionalmente, um usuário também pode optar por compartilhar publicamente as seguintes informações:

  * Seu nome real

  * Um avatar

  * Uma empresa afiliada

  * Sua localização

  * Um endereço de e-mail público

  * Sua página da web pessoal

  * Organizações das quais o usuário é membro (*dependendo das preferências da organização ou dos usuários*)

* []()**Dados privados da conta** — O GitHub também coleta e mantém certas informações privadas sobre os usuários, conforme descrito em nossa [Política de Privacidade](/pt/articles/github-privacy-statement). Isso pode incluir:

  * Endereço de e-mail privado

  * Dados de pagamento

  * Logs de acesso de segurança

  * Dados sobre interações com repositórios privados

    Para ter uma noção do tipo de informações privadas da conta que o GitHub coleta, você pode visitar seu [painel pessoal](https://github.com/dashboard) e navegar pelas seções do menu à esquerda.

* []()**Dados da conta da organização** — Informações sobre organizações, seus usuários administrativos e repositórios estão publicamente disponíveis no GitHub. Perfis da organização podem ser encontrados em uma URL, tais como `https://github.com/organization`. Os perfis públicos da organização também podem incluir informações adicionais que os proprietários optaram por compartilhar publicamente. Todos os perfis públicos de organizações mostram:

  * Nome da organização

  * Os repositórios que os proprietários marcaram com estrela

  * Todos os usuários GitHub que são proprietários da organização

    Opcionalmente, um usuário administrador também pode optar por compartilhar publicamente as seguintes informações:

  * Um avatar

  * Uma empresa afiliada

  * Sua localização

  * Membros e equipes diretas

  * Colaboradores

* []()**Dados de repositórios públicos** — O GitHub abriga milhões de projetos de software públicos e de código aberto. Você pode navegar por quase qualquer repositório público (por exemplo, o [Atom Project](https://github.com/atom/atom)) para saber o tipo de informação que o GitHub coleta e mantém sobre repositórios. Isso pode incluir:

  * O código em si
  * Versões anteriores do código
  * Versões lançadas e estáveis do projeto
  * Informações sobre colaboradores, contribuidores e membros do repositório
  * Registros de operações do Git como commits, ramificação, push, pull, bifurcação e clonagem
  * Conversas relacionadas a operações do Git, como comentários em pull requests ou commits
  * Documentação do projeto, como problemas e páginas Wiki
  * Estatísticas e gráficos mostrando contribuições para o projeto e a rede de colaboradores

* []()**Dados de repositórios privados** — O GitHub coleta e mantém o mesmo tipo de dados para repositórios privados e públicos. No entanto, apenas usuários convidados especificamente podem acessar dados privados do repositório.

* []()**Outros dados** — Adicionalmente, o GitHub coleta dados analíticos como visitas de página e informações ocasionalmente voluntárias pelos nossos usuários (como comunicações com a nossa equipe de suporte, informações da pesquisa e/ou registros de sites).

[](#we-will-notify-any-affected-account-owners)Notificaremos qualquer proprietário de conta afetado
----------

É nossa política notificar os usuários sobre quaisquer pedidos pendentes relativos a suas contas ou seus repositórios, a não ser que sejamos proibidos por lei ou por decisão judicial. Antes de divulgar informações do usuário, faremos um esforço razoável para notificar qualquer proprietário da conta afetada enviando uma mensagem para seu endereço de e-mail verificado, fornecendo a ele uma cópia da intimação, da ordem judicial, ou do mandado, para que possa ter a oportunidade de contestar o processo judicial, se assim o desejar. Em (raras) circunstâncias exigentes, podemos atrasar a notificação, se determinarmos que os atrasos são necessários para evitar a morte ou danos graves ou devido a uma investigação em curso.

[](#disclosure-of-non-public-information)Compartilhamento de informações não públicas
----------

É nossa política divulgar informações de usuário não públicas que estejam relacionadas com uma investigação civil ou criminal, somente mediante consentimento do usuário ou após o recebimento de uma intimação válida, de uma demanda de investigação civil, ordem judicial, mandado de busca ou outro processo legal válido similar. Em certas circunstâncias (veja abaixo), também podemos compartilhar informações limitadas, mas apenas correspondentes à natureza das circunstâncias, e será necessário processo judicial para qualquer coisa além disso. O GitHub reserva-se o direito de se opor a quaisquer solicitações de informações não públicas. Quando o GitHub concordar em produzir informações não públicas em resposta a uma solicitação legal, realizaremos uma pesquisa razoável a respeito das informações solicitadas. Aqui estão os tipos de informações que concordamos em produzir, dependendo do tipo de processo judicial com o qual estivermos lidando:

* []()**Com o consentimento do usuário** — O GitHub fornecerá informações privadas da conta, caso solicitado, diretamente ao usuário (ou a um proprietário, no caso de uma conta de organização), ou para uma terceira pessoa designada com o consentimento por escrito do usuário, desde que estejamos confiantes de que o usuário teve sua identidade verificada.

* []()**Com uma intimação** — De posse de uma intimação válida, uma demanda de investigação civil, ou um ato jurídico semelhante emitido em relação a uma investigação civil ou criminal oficial, podemos fornecer certas informações não públicas sobre a conta, que podem incluir:

  * Nome(s) associado(s) com a conta
  * Endereço(s) de e-mail associado(s) com a conta
  * Informações de cobrança
  * Data de cadastro e término
  * Endereço IP, data e hora no momento do registro da conta
  * Endereço(s) IP(s) usado(s) para acessar a conta em um momento ou evento especificado relevante à investigação

No caso das contas da organização, podemos fornecer o(s) nome(s) e endereço(s) de e-mail do(s) proprietário(s) da conta, bem como a data e o endereço IP no momento da criação da conta da organização. Não vamos produzir informações sobre outros membros ou colaboradores, se houver, da conta da organização ou qualquer informação adicional sobre o(s) proprietário(s) identificado(s) da conta sem uma solicitação de acompanhamento para esses usuários específicos.

Por favor, note que a informação disponível varia de caso a caso. Algumas das informações são opcionais para os usuários fornecerem. Noutros casos, podemos não ter recolhido ou mantido a informação.

* []()**Com uma ordem judicial *ou* um mandado de busca** — Não divulgaremos os logs de acesso à conta, a menos que sejamos obrigados a fazê-lo por (i) uma ordem judicial emitida conforme 18 U.S.C. Seção 2703(d), sobre a demonstração de fatos específicos e articuláveis que mostrem que há razões razoáveis para acreditar que a informação solicitada é relevante e material para uma investigação criminal em curso; ou (ii) um mandado de busca emitido nos termos dos procedimentos descritos nas Regras Federais de Processo Penal ou procedimentos de autorização estatal equivalentes, mediante demonstração de uma causa provável. Seção 2703(d), após a demonstração de fatos específicos e articuláveis que mostrem que há razões razoáveis para acreditar que a informação solicitada é relevante e material para uma investigação criminal em curso; ou (ii) um mandado de busca emitido de acordo com os procedimentos descritos no Regimento Federal de Assuntos Penal ou procedimentos de mandado de Estado equivalente, após a demonstração de uma causa provável. In addition to the non-public account information listed above, we can provide account access logs in response to a court order or search warrant, which may include:

  * Quaisquer logs que revelaria os movimentos de um usuário ao longo de um período de tempo
  * Configurações de conta ou repositório privado (por exemplo, quais usuários têm certas permissões, etc.)
  * Dados analíticos específicos do usuário ou IP, como histórico de navegação
  * Logs de segurança de acesso além da criação de conta ou para um horário e data específicos

* []()**Only with a search warrant** — We will not disclose the private contents of any account unless compelled to do so under a search warrant issued under the procedures described in the Federal Rules of Criminal Procedure or equivalent state warrant procedures upon a showing of probable cause. In addition to the non-public account information and account access logs mentioned above, we will also provide private account contents in response to a search warrant, which may include:

  * Conteúdos de Gists secretos
  * Código fonte ou outro conteúdo em repositórios privados
  * Registros de colaboração e contribuição para repositórios privados
  * Comunicações ou documentação (como problemas ou Wikis) em repositórios privados
  * Qualquer chave de segurança usada para autenticação ou criptografia

* []()**Sob circunstâncias críticas** — Se recebermos uma solicitação de informações sob certas circunstâncias críticas (onde acreditamos que a divulgação é necessária para evitar uma situação emergencial que envolva risco de morte ou graves lesões físicas para uma pessoa), podemos divulgar informações limitadas que determinarmos necessárias para permitir que a aplicação da lei responda à emergência da situação. Para qualquer informação além disso, precisaríamos de uma intimação, um mandado de busca ou ordem judicial, conforme descrito acima. Por exemplo, não divulgaremos o conteúdo de repositórios privados sem um mandado de busca. Antes de divulgar informações, confirmamos que o pedido veio de um agente de aplicação da lei, que uma autoridade enviou uma notificação oficial resumindo a situação emergencial, e a forma como as informações solicitadas ajudarão a responder à emergência.

[](#cost-reimbursement)Reembolso de custos
----------

Nos termos das leis estadual e federal, o GitHub pode pedir reembolso por custos associados à conformidade com uma demanda legal válida, como uma intimação, ordem de tribunal ou mandado de busca. Só cobramos a recuperação de alguns custos, e estes reembolsos cobrem apenas uma parte dos custos que efetivamente incorremos para cumprir as disposições legais.

Embora não cobremos em situações de emergência ou em outras circunstâncias exigentes, buscamos o reembolso para todas as outras solicitações legais, de acordo com o cronograma a seguir, a menos que exigido de outra forma por lei:

* Pesquisa inicial de até 25 identificadores: livre
* Produção de informação/dados de assinantes para até 5 contas: grátis
* Produção de informação/dados de assinante para mais de 5 contas: US$ 20 por conta
* Pesquisas secundárias: US$ 10 por pesquisa

[](#data-preservation)Conservação de dados
----------

Vamos tomar medidas para preservar os registros das conta por até 90 dias mediante solicitação formal dos EUA. aplicação da lei relacionada a investigações criminais oficiais e aguardando a emissão de uma decisão judicial ou outro processo.

[](#submitting-requests)Envio de solicitação
----------

Por favor, envie solicitações para:

```
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N Sacramento, CA 95833-3505

```

Cópias de cortesia podem ser enviadas para [legal@support.github.com](mailto:legal@support.github.com).

Por favor, faça suas solicitações da forma mais específica e breve quanto for possível, incluindo as seguintes informações:

* Informações completas sobre a autoridade emissora do pedido de informações
* O nome e o registro/ID do agente responsável
* Um endereço de e-mail oficial e número de telefone de contato
* Nome do usuário, da organização, do repositório de interesse
* As URLs de qualquer página, gists ou arquivos de interesse
* A descrição dos tipos de registros de que você precisa

Por favor, conceda-nos pelo menos duas semanas para que possamos analisar o seu pedido.

[](#requests-from-foreign-law-enforcement)Pedidos de aplicação de lei estrangeira
----------

Como empresa dos Estados Unidos sediada na Califórnia, o GitHub não é obrigado a fornecer dados a governos estrangeiros em resposta a processo judicial emitido por autoridades estrangeiras. As autoridades responsáveis pela aplicação da lei estrangeira que desejem solicitar informações ao GitHub deverão entrar em contato com o Gabinete de Assuntos Internacionais da Divisão Penal do Departamento de Justiça dos Estados Unidos. O GitHub responderá prontamente às solicitações que forem emitidas via tribunal dos EUA, por meio de um contrato de assistência jurídica mútua (“MLAT”) ou carta rogatória. tribunal por meio de um tratado de assistência jurídica mútua (“MLAT”) ou de uma rogatória.

[](#questions)Perguntas
----------

Você tem alguma pergunta, comentário ou sugestão? Entre em contato com o [GitHub Support](https://support.github.com/contact?tags=docs-generic).