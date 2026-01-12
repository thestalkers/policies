Directrices para solicitudes legales de datos de usuario - Documentación de GitHub

[Skip to main content](#main-content)

[Home](/es)

[Site policy](/es/site-policy)
----------

* [Política del sitio](/es/site-policy)/
* [Otras políticas del sitio](/es/site-policy/other-site-policies)/
* [Directrices para solicitudes legales de datos de usuario](/es/site-policy/other-site-policies/guidelines-for-legal-requests-of-user-data)

Directrices para solicitudes legales de datos de usuario
==========

Ver página como Markdown

En este artículo
----------

* [Acerca de estas pautas](#about-these-guidelines)
* [Terminología de GitHub](#github-terminology)
* [Datos de usuario en GitHub.com](#user-data-on-githubcom)
* [Notificaremos a los propietarios de cuentas afectados.](#we-will-notify-any-affected-account-owners)
* [Divulgación de información no pública](#disclosure-of-non-public-information)
* [Reembolso de los gastos](#cost-reimbursement)
* [Conservación de datos](#data-preservation)
* [Envío de solicitudes](#submitting-requests)
* [Solicitudes de fuerzas del orden extranjeras](#requests-from-foreign-law-enforcement)
* [Preguntas](#questions)

¿Eres un agente de la ley que realiza una investigación que puede involucrar contenido de usuario alojado en GitHub?
O tal vez sea una persona preocupada por la privacidad a la que le gustaría saber qué información compartimos con las fuerzas del orden y en qué circunstancias.
De cualquier manera, estás en la página correcta.

En estas pautas, proporcionamos un poco de información sobre qué es GitHub, los tipos de datos que tenemos y las condiciones bajo las cuales divulgaremos la información privada de los usuarios.
Sin embargo, antes de entrar en detalles, aquí hay algunos detalles importantes que quizás desee saber:

* [**Notificaremos a los usuarios afectados**](#we-will-notify-any-affected-account-owners) sobre cualquier solicitud de información de su cuenta, a menos que la ley o una orden judicial lo prohíban.
* No revelaremos **datos de seguimiento de la ubicación**, como registros de direcciones IP, sin una [orden judicial válida o una orden de registro](#with-a-court-order-or-a-search-warrant).
* No revelaremos ningún **contenido de usuario privado**, incluido el contenido de repositorios privados, sin una [orden de registro](#only-with-a-search-warrant) válida.

[Acerca de estas pautas](#about-these-guidelines)
----------

Nuestros usuarios nos confían sus proyectos y códigos de software, a menudo algunos de sus activos comerciales o personales más valiosos.
Mantener esa confianza es esencial para nosotros, lo que significa mantener los datos de los usuarios seguros, protegidos y privados.

Si bien la gran mayoría de nuestros usuarios utilizan los servicios de GitHub para crear nuevos negocios, desarrollar nuevas tecnologías y para el mejoramiento general de la humanidad, reconocemos que con millones de usuarios repartidos por todo el mundo, seguramente habrá algunas manzanas podridas en el grupo
En esos casos, queremos ayudar a las fuerzas del orden público a cumplir su interés legítimo de proteger al público.

Al proporcionar pautas para el personal encargado de hacer cumplir la ley, esperamos lograr un equilibrio entre los intereses a menudo contrapuestos de la privacidad y la justicia del usuario.
Esperamos que estas pautas ayuden a establecer expectativas en ambos lados, así como a agregar transparencia a los procesos internos de GitHub.
Nuestros usuarios deben saber que valoramos su información privada y que hacemos todo lo posible para protegerla.
Como mínimo, esto significa solo divulgar datos a terceros cuando se hayan cumplido los requisitos legales correspondientes.
Del mismo modo, también esperamos educar a los profesionales encargados de hacer cumplir la ley sobre los sistemas de GitHub para que puedan adaptar de manera más eficiente sus solicitudes de datos y enfocarse solo en la información necesaria para realizar su investigación.

[Terminología de GitHub](#github-terminology)
----------

Antes de pedirnos que divulguemos datos, puede ser útil comprender cómo se implementa nuestro sistema.
GitHub aloja millones de repositorios de datos con el [sistema de control de versiones Git](https://git-scm.com/video/what-is-version-control).
Los repositorios en GitHub, que pueden ser públicos o privados, se usan más comúnmente para proyectos de desarrollo de software, pero también se usan a menudo para trabajar en contenido de todo tipo.

* [**Usuarios**](/es/get-started/learning-about-github/github-glossary#user): los usuarios están representados en nuestro sistema como cuentas personales de GitHub.
  Cada usuario tiene un perfil personal y puede poseer varios repositorios.
  Los usuarios pueden crear o ser invitados a unirse a organizaciones o colaborar en el repositorio de otro usuario.

* [**Colaboradores**](/es/get-started/learning-about-github/github-glossary#collaborator): un colaborador es un usuario con acceso de lectura y escritura a un repositorio al que el propietario le ha invitado a colaborar.

* [**Organizaciones**](/es/get-started/learning-about-github/github-glossary#organization): las organizaciones son un grupo de dos o más usuarios que normalmente reflejan organizaciones del mundo real, como negocios o proyectos.
  Son administrados por usuarios y pueden contener tanto repositorios como equipos de usuarios.

* [**Repositorios**](/es/get-started/learning-about-github/github-glossary#repository): un repositorio es uno de los elementos más básicos de GitHub.
  Pueden ser más fáciles de imaginar como la carpeta de un proyecto.
  Un repositorio contiene todos los archivos del proyecto (incluida la documentación) y almacena el historial de revisión de cada archivo.
  Los repositorios pueden tener múltiples colaboradores y, a discreción de sus administradores, pueden ser visibles públicamente o no.

* [**Pages**](/es/pages/getting-started-with-github-pages/about-github-pages): GitHub Pages son páginas web públicas alojadas gratuitamente por GitHub que los usuarios pueden publicar fácilmente a través del código almacenado en sus repositorios.
  Si un usuario u organización tiene una página de GitHub, esta se suele encontrar en una URL como `https://username.github.io` o podría tener la página web asignada a su propio nombre de dominio personalizado.

* [**Gists**](/es/get-started/writing-on-github/editing-and-sharing-content-with-gists/creating-gists): los Gists son fragmentos de código fuente u otro texto que los usuarios pueden usar para almacenar ideas o compartir con amigos.
  Al igual que los repositorios normales de GitHub, los Gists se crean con Git, por lo que se versionan, bifurcan y descargan automáticamente.
  Los gists pueden ser públicos o secretos (accesibles solo a través de una URL conocida). Los Gists públicos no se pueden convertir en Gists secretos.

[Datos de usuario en GitHub.com](#user-data-on-githubcom)
----------

Aquí hay una lista no exhaustiva de los tipos de datos que mantenemos sobre usuarios y proyectos en GitHub.

* <a name="public-account-data"></a>**Datos de cuentas públicas**: en GitHub hay una gran variedad de información disponible públicamente sobre los usuarios y sus repositorios.
  Los perfiles de usuario se pueden encontrar en una URL como `https://github.com/username`.
  Los perfiles de usuario muestran información sobre cuándo el usuario creó su cuenta, así como su actividad pública en GitHub.com e interacciones sociales.
  Los perfiles de usuario públicos también pueden incluir información adicional que un usuario puede haber elegido compartir públicamente.
  Todos los perfiles públicos de usuario muestran:

  * Nombre de usuario

  * Los repositorios que el usuario ha destacado

  * Los otros usuarios de GitHub que el usuario sigue

  * Los usuarios que los siguen

    Opcionalmente, un usuario también puede optar por compartir públicamente la siguiente información:

  * Su verdadero nombre

  * Un avatar

  * Una empresa afiliada

  * Su ubicación

  * Una dirección de correo electrónico pública

  * Su página web personal

  * Organizaciones a las que pertenece el usuario (*dependiendo de las preferencias de las organizaciones o de los usuarios*)

* <a name="private-account-data"></a>**Datos de cuentas privadas**: GitHub también recopila y mantiene determinada información privada sobre los usuarios de la forma en que se describe en nuestra [directiva de privacidad](/es/site-policy/privacy-policies/github-privacy-statement).
  Esto puede incluir:

  * Direcciones de correo electrónico privadas

  * Detalles del pago

  * Registros de acceso de seguridad

  * Datos sobre interacciones con repositorios privados

    Para hacerse una idea del tipo de información de cuentas privadas que recopila GitHub, puede visitar su [panel personal](https://github.com/dashboard) y navegar por los apartados de la barra de menús de la izquierda.

* <a name="organization-account-data"></a>**Datos de cuentas de organizaciones**: en GitHub, la información sobre las organizaciones, sus usuarios administrativos y los repositorios está disponible públicamente.
  Los perfiles de organización se pueden encontrar en una URL como `https://github.com/organization`.
  Los perfiles de organizaciones públicas también pueden incluir información adicional que los propietarios han decidido compartir públicamente.
  Todos los perfiles públicos de la organización muestran:

  * El nombre de la organización

  * Los repositorios que han protagonizado los propietarios

  * Todos los usuarios de GitHub que son propietarios de la organización

    Opcionalmente, los usuarios administrativos también pueden optar por compartir públicamente la siguiente información:

  * Un avatar

  * Una empresa afiliada

  * Su ubicación

  * Miembros Directos y Equipos

  * Colaboradores

* <a name="public-repository-data"></a>**Datos de repositorios públicos**: GitHub alberga millones de proyectos de software de código abierto públicos.
  Puede examinar casi cualquier repositorio público (por ejemplo, [GitHub Docs](https://github.com/github/docs)) para tener una idea de la información que GitHub recopila y mantiene sobre los repositorios.
  Esto puede incluir:

  * El código en sí
  * Versiones anteriores del código
  * Versiones de lanzamiento estables del proyecto
  * Información sobre colaboradores, contribuidores y miembros del repositorio
  * Registros de operaciones de Git, como confirmaciones, bifurcaciones, inserción, extracción, bifurcación y clonación
  * Conversaciones relacionadas con operaciones de Git, como comentarios sobre solicitudes de incorporación de cambios o confirmaciones
  * Documentación del proyecto, como problemas y páginas wiki
  * Estadísticas y gráficos que muestran las contribuciones al proyecto y la red de contribuyentes.

* <a name="private-repository-data"></a>**Datos de repositorios privados**: GitHub recopila y mantiene el mismo tipo de datos para los repositorios privados que se pueden ver en los repositorios públicos, excepto que los usuarios invitados de forma específica pueden acceder a los datos del repositorio privado.

* <a name="other-data"></a>**Otros datos**: además, GitHub recopila datos analíticos, como visitas a páginas e información que ocasionalmente nos ofrecen voluntariamente nuestros usuarios (como comunicaciones con nuestro equipo de soporte, información de encuestas y/o registros en el sitio).

[Notificaremos a los propietarios de cuentas afectados.](#we-will-notify-any-affected-account-owners)
----------

Nuestra política es notificar a los usuarios sobre cualquier solicitud pendiente con respecto a sus cuentas o repositorios, a menos que la ley o una orden judicial nos lo prohíba. Antes de divulgar la información del usuario, haremos un esfuerzo razonable para notificar a los propietarios de cuentas afectados mediante el envío de un mensaje a su dirección de correo electrónico verificada brindándoles una copia de la citación, orden judicial o orden judicial para que puedan tener la oportunidad de impugnar la proceso legal si así lo desean. En circunstancias exigentes (raras), podemos retrasar la notificación si determinamos que la demora es necesaria para evitar la muerte o daños graves o debido a una investigación en curso.

[Divulgación de información no pública](#disclosure-of-non-public-information)
----------

Es nuestra política divulgar información de usuario no pública en relación con una investigación civil o penal solo con el consentimiento del usuario o al recibir una citación válida, demanda de investigación civil, orden judicial, orden de allanamiento u otro proceso legal válido similar. En ciertas circunstancias exigentes (ver a continuación), también podemos compartir información limitada pero solo correspondiente a la naturaleza de las circunstancias, y requeriríamos un proceso legal para cualquier cosa más allá de eso.
GitHub se reserva el derecho de oponerse a cualquier solicitud de información no pública.
Cuando GitHub acepte producir información no pública en respuesta a una solicitud legal, realizaremos una búsqueda razonable de la información solicitada.
Estos son los tipos de información que aceptaremos producir, según el tipo de proceso legal que recibamos:

* <a name="with-user-consent"></a>**Con consentimiento del usuario**: GitHub proporciona información de cuentas privadas, si se solicita, directamente al usuario (o a un propietario, en el caso de que sea una cuenta de organización) o a un tercero designado con el consentimiento por escrito del usuario una vez que GitHub concluya que el usuario ha verificado su identidad.

* <a name="with-a-subpoena"></a>**Con una citación**: si se presenta una citación válida, una demanda de investigación civil o un procedimiento legal similar en relación con una investigación penal o civil oficial, podemos proporcionar determinada información de las cuentas no públicas, que podría incluir:

  * Nombres asociados a la cuenta
  * Dirección(es) de correo electrónico asociadas con la cuenta
  * Información de facturación
  * Fecha de registro y fecha de terminación
  * Dirección IP, fecha y hora en el momento del registro de la cuenta
  * Dirección(es) IP utilizada(s) para acceder a la cuenta en un momento específico o evento relevante para la investigación

En el caso de las cuentas de la organización, podemos proporcionar los nombres y las direcciones de correo electrónico de los propietarios de la cuenta, así como la fecha y la dirección IP en el momento de la creación de la cuenta de la organización. No produciremos información sobre otros miembros o contribuyentes, si los hay, a la cuenta de la organización o cualquier información adicional sobre los propietarios de la cuenta identificados sin una solicitud de seguimiento para esos usuarios específicos.

Tenga en cuenta que la información disponible variará de un caso a otro. Parte de la información es opcional para los usuarios. En otros casos, es posible que no hayamos recopilado o retenido la información.

* <a name="with-a-court-order-or-a-search-warrant"></a>**Con una orden judicial *o* una orden de registro**: no revelaremos los registros de acceso a la cuenta a menos que se nos obligue a hacerlo por medio de (i) una orden judicial emitida en virtud del título 18 del USC. La Sección 2703(d), cuando se muestren hechos específicos y articulables que demuestren que existen motivos razonables para creer que la información solicitada es relevante y material para una investigación penal en curso; o (ii) una orden de allanamiento emitida conforme a los procedimientos descritos en las Reglas Federales de Procedimiento Penal o procedimientos de orden estatal equivalentes, previa demostración de causa probable.
  Además de la información de la cuenta no pública mencionada anteriormente, podemos proporcionar registros de acceso a la cuenta en respuesta a una orden judicial o una orden de allanamiento, que pueden incluir:

  * Cualquier registro que revele los movimientos de un usuario durante un período de tiempo
  * La configuración de la cuenta o del repositorio privado (por ejemplo, qué usuarios tienen ciertos permisos, etc.)
  * Datos analíticos específicos del usuario o de la IP, como el historial de navegación
  * Registros de acceso de seguridad distintos de la creación de cuentas o para una hora y fecha específicas

* <a name="only-with-a-search-warrant"></a>**Solo con orden de registro**: no revelaremos el contenido privado de ninguna cuenta a menos que se nos obligue a hacerlo en virtud de una orden de registro emitida conforme a los procedimientos descritos en las Reglas Federales de Procedimientos Penales o los procedimientos de órdenes de registro estatales equivalentes, previa demostración de que existe una causa probable.
  Además de la información no pública de la cuenta y los registros de acceso a la cuenta mencionados anteriormente, también proporcionaremos contenido privado de la cuenta en respuesta a una orden de registro, que puede incluir:

  * Contenido de Gists secretos
  * Código fuente u otro contenido en repositorios privados
  * Registros de contribuciones y colaboraciones para repositorios privados
  * Comunicaciones o documentación (como Issues o Wikis) en repositorios privados
  * Cualquier clave de seguridad utilizada para la autenticación o el cifrado

* <a name="in-exigent-circumstances"></a>**En circunstancias extremas**: si recibimos una solicitud de información bajo ciertas circunstancias extremas (cuando creamos que es necesario divulgarla para evitar una emergencia que implique un peligro mortal o lesiones físicas graves para una persona), podemos divulgar la información limitada que determinemos necesaria para permitir que las fuerzas del orden atiendan la emergencia. Para cualquier información más allá de eso, requeriríamos una citación, una orden de allanamiento o una orden judicial, como se describe anteriormente. Por ejemplo, no divulgaremos contenidos de depósitos privados sin una orden de registro. Antes de divulgar información, confirmamos que la solicitud provino de una agencia del orden público, una autoridad envió un aviso oficial que resume la emergencia y cómo la información solicitada ayudará a abordar la emergencia.

[Reembolso de los gastos](#cost-reimbursement)
----------

Según la ley estatal y federal, GitHub puede solicitar el reembolso de los costos asociados con el cumplimiento de una demanda legal válida, como una citación, una orden judicial o una orden de allanamiento. Solo cobramos para recuperar algunos costos, y estos reembolsos cubren solo una parte de los costos en los que realmente incurrimos para cumplir con las órdenes legales.

Si bien no cobramos en situaciones de emergencia o en otras circunstancias exigentes, buscamos el reembolso de todas las demás solicitudes legales de acuerdo con el siguiente programa, a menos que la ley exija lo contrario:

* Búsqueda inicial de hasta 25 identificadores: gratis
* Entrega de información/datos de suscriptores de hasta cinco (5) cuentas: gratis
* Entrega de información/datos de suscriptores de más de cinco (5) cuentas: 20 USD por cuenta
* Búsquedas secundarias: 10 USD por búsqueda

[Conservación de datos](#data-preservation)
----------

Tomaremos medidas para conservar los registros de la cuenta hasta por 90 días a pedido formal de las fuerzas del orden de los EE. UU. en relación con investigaciones criminales oficiales y en espera de la emisión de una orden judicial u otro proceso.

[Envío de solicitudes](#submitting-requests)
----------

Sirva las solicitudes a:

```
GitHub, Inc.
c/o Corporation Service Company
2710 Gateway Oaks Drive, Suite 150N
Sacramento, CA 95833-3505

```

Como cortesía, se pueden enviar copias por correo electrónico a [legal-support@github.com](mailto:legal-support@github.com)

Haga sus solicitudes lo más específicas y restringidas posible, incluyendo la siguiente información:

* Información completa sobre la autoridad que emite la solicitud de información
* El nombre y credencial/ID del agente responsable
* Una dirección de correo electrónico oficial y un número de teléfono de contacto.
* Los nombres de usuario, organización y repositorio de interés
* Las URL de cualquier página, resumen o archivo de interés.
* La descripción de los tipos de registros que necesita

Espere al menos dos semanas para que podamos investigar su solicitud.

### [Aviso sobre el proyecto de ley 1242 de la Asamblea de California](#california-assembly-bill-1242-notice) ###

Al enviar un proceso legal a GitHub, declara que el proceso legal no está relacionado con la violación de ninguna ley que genere responsabilidad por una conducta relacionada con el aborto que sea legal en California.

[Solicitudes de fuerzas del orden extranjeras](#requests-from-foreign-law-enforcement)
----------

Como empresa estadounidense con sede en California, GitHub no está obligado a proporcionar datos a gobiernos extranjeros en respuesta a procesos legales emitidos por autoridades extranjeras.
Los funcionarios encargados de hacer cumplir la ley extranjeros que deseen solicitar información de GitHub deben comunicarse con la Oficina de Asuntos Internacionales de la División Criminal del Departamento de Justicia de los Estados Unidos.
GitHub responderá de inmediato a las solicitudes que se emitan a través de un tribunal de los EE. UU. mediante un tratado de asistencia legal mutua ("MLAT") o carta rogatoria.

[Preguntas](#questions)
----------

¿Tienes otras preguntas, comentarios o sugerencias? Póngase en contacto con con nosotros a través del [Soporte técnico de GitHub](https://support.github.com).

{"resolvedServerColorMode":"day"}
