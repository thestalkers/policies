Política de eliminación de DMCA - Documentación de GitHub

[Skip to main content](#main-content)

[Home](/es)

[Site policy](/es/site-policy)
----------

* [Política del sitio](/es/site-policy)/
* [Políticas de eliminación de contenido](/es/site-policy/content-removal-policies)/
* [Política de eliminación de DMCA](/es/site-policy/content-removal-policies/dmca-takedown-policy)

Política de eliminación de DMCA
==========

Ver página como Markdown

En este artículo
----------

* [¿Qué son los Derechos de Uso de los Productos (DMCA)?](#what-is-the-dmca)
* [Avisos de DMCA en pocas palabras](#dmca-notices-in-a-nutshell)
* [A. ¿Cómo funciona esto realmente?](#a-how-does-this-actually-work)
* [B. ¿Qué pasa con las horquillas? (o ¿Qué es un tenedor?)](#b-what-about-forks-or-whats-a-fork)
* [C. ¿Qué pasa con las reclamaciones por elusión?](#c-what-about-circumvention-claims)
* [D. ¿Qué pasa si sin darme cuenta perdí la ventana para hacer cambios?](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)
* [E. Transparencia](#e-transparency)
* [F. Infracción Repetida](#f-repeated-infringement)
* [G. Envío de avisos](#g-submitting-notices)
* [Obtenga más información y hable](#learn-more-and-speak-up)

Bienvenido a la Guía de GitHub para la Ley de derechos de autor del milenio digital, comúnmente conocida como "DMCA". Esta página no pretende ser un manual completo del estatuto. Sin embargo, si recibió un aviso de eliminación de DMCA dirigido al contenido que publicó en GitHub o si es un titular de derechos que busca emitir dicho aviso, esperamos que esta página ayude a desmitificar un poco la ley, así como nuestra políticas para su cumplimiento.

(Si solo desea enviar una notificación, puede ir directamente al apartado [G. Envío de Notificaciones](#g-submitting-notices)).

Como con todos los asuntos legales, siempre es mejor consultar con un profesional acerca de sus preguntas o situaciones específicas. Le recomendamos encarecidamente que lo haga antes de emprender cualquier acción que pueda afectar a sus derechos. Esta guía no es un consejo legal y no debe tomarse como tal.

[¿Qué son los Derechos de Uso de los Productos (DMCA)?](#what-is-the-dmca)
----------

Para comprender la DMCA y algunas de las líneas de política que traza, tal vez sea útil considerar la vida antes de que se promulgara.

La DMCA proporciona un puerto seguro para los proveedores de servicios que alojan contenido generado por el usuario. Dado que incluso un solo reclamo de infracción de derechos de autor puede acarrear daños legales de hasta $150,000, la posibilidad de ser considerado responsable por el contenido generado por el usuario podría ser muy perjudicial para los proveedores de servicios. Si tenemos en cuenta que los posibles daños y perjuicios podrían multiplicarse por millones de usuarios, la informática en la nube y los sitios de contenido generado por el usuario, como YouTube, Facebook o GitHub, probablemente [nunca habrían existido](https://arstechnica.com/tech-policy/2015/04/how-the-dmca-made-youtube/) sin la DMCA (al menos, no sin transferir una parte de ese coste a sus usuarios).

La DMCA aborda este problema mediante la creación de un [marco de seguridad de la responsabilidad de los derechos de autor](https://www.copyright.gov/title17/92chap5.html#512) para los proveedores de servicios de Internet que hospedan contenido generado por el usuario supuestamente infractor. Esencialmente, siempre que un proveedor de servicios siga las reglas de notificación y eliminación de la DMCA, no será responsable de la infracción de derechos de autor basada en el contenido generado por el usuario. Debido a esto, es importante que GitHub mantenga su estado de puerto seguro de DMCA.

La DMCA también prohíbe [eludir las medidas técnicas](https://www.copyright.gov/title17/92chap12.html) que controlan de forma eficiente el acceso a las obras protegidas por derechos de autor.

[Avisos de DMCA en pocas palabras](#dmca-notices-in-a-nutshell)
----------

La DMCA proporciona dos procedimientos simples y directos que todos los usuarios de GitHub deben conocer: (i) un procedimiento de [notificación de eliminación](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) que permite a los titulares de los derechos de autor solicitar que se retire un contenido; y (ii) un procedimiento de [contranotificación](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) para que los usuarios puedan rehabilitar el contenido cuando éste se haya retirado por error o por una identificación incorrecta.

Los titulares de los derechos de autor utilizan las [notificaciones de eliminación](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) en virtud de la DMCA para solicitar a GitHub que retire un contenido que consideran infractor. Si es diseñador o desarrollador de software, crea contenido protegido por derechos de autor todos los días. Si alguien más está utilizando su contenido protegido por derechos de autor de manera no autorizada en GitHub, puede enviarnos un aviso de eliminación de DMCA para solicitar que se cambie o elimine el contenido infractor.

Por otro lado, las [contranotificaciones](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice) se pueden usar para corregir errores. Tal vez la persona que envía el aviso de eliminación no posee los derechos de autor o no se dio cuenta de que tiene una licencia o cometió algún otro error en su aviso de eliminación. Dado que GitHub generalmente no puede saber si ha habido un error, la contranotificación de DMCA le permite informarnos y solicitar que volvamos a colocar el contenido.

El aviso de DMCA y el proceso de eliminación solo deben usarse para quejas sobre infracciones de derechos de autor. Los avisos enviados a través de nuestro proceso de DMCA deben identificar el trabajo con derechos de autor o los trabajos que presuntamente se están infringiendo. El proceso no se puede utilizar para otras reclamaciones, tales como reclamaciones por supuestas [infracciones de marcas comerciales](/es/site-policy/content-removal-policies/github-trademark-policy) o relacionadas con [datos confidenciales](/es/site-policy/content-removal-policies/github-private-information-removal-policy); para estas situaciones, ofrecemos procesos independientes.

[A. ¿Cómo funciona esto realmente?](#a-how-does-this-actually-work)
----------

El marco DMCA es un poco como pasar notas en clase. El propietario de los derechos de autor entrega a GitHub una queja sobre un usuario. Si está escrito correctamente, pasamos la queja al usuario. Si el usuario disputa la queja, puede devolver una nota para decirlo. GitHub ejerce poca discreción en el proceso aparte de determinar si los avisos cumplen con los requisitos mínimos de la DMCA. Corresponde a las partes (y sus abogados) evaluar el mérito de sus reclamaciones, teniendo en cuenta que las notificaciones deben hacerse bajo pena de perjurio.

Estos son los pasos básicos del proceso.

1. **El propietario de los derechos de autor realiza una investigación.** El propietario de los derechos de autor siempre debe realizar una investigación inicial para confirmar (a) que posee los derechos de autor de un trabajo original y (b) que el contenido de GitHub no está autorizado y es infractor. Esto incluye confirmar que el uso no esté protegido por la doctrina de [uso justo](https://www.lumendatabase.org/topics/22). Un uso particular puede ser justo si solo usa una pequeña cantidad de contenido protegido por derechos de autor, usa ese contenido de una manera transformadora, lo usa con fines educativos o alguna combinación de los anteriores. Debido a que el código se presta naturalmente a tales usos, cada caso de uso es diferente y debe considerarse por separado.

   >
   >
   > **Ejemplo:** Un empleado de Acme Web Company encuentra parte del código de la empresa en un repositorio de GitHub. Acme Web Company otorga licencias de su código fuente a varios socios de confianza. Antes de enviar un aviso de eliminación, Acme debe revisar esas licencias y sus acuerdos para confirmar que el código en GitHub no está autorizado bajo ninguna de ellas.
   >
   >

2. **El propietario de los derechos de autor envía una notificación.** Tras llevar a cabo la investigación, el propietario de los derechos de autor elabora y envía una [notificación de eliminación](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice) a GitHub. Suponiendo que la notificación de eliminación contenga los detalles suficientes de conformidad con los requisitos legales (según se explica en la [guía](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)), [publicaremos la notificación](#e-transparency) en nuestro [repositorio público](https://github.com/github/dmca) y transmitiremos el enlace al usuario afectado.

3. **GitHub solicita al usuario que realice cambios.** Si el aviso alega que todo el contenido de un repositorio infringe, o un paquete infringe, pasaremos al Paso 6 y deshabilitaremos todo el repositorio o paquete de manera expedita. De lo contrario, debido a que GitHub no puede deshabilitar el acceso a archivos específicos dentro de un repositorio, nos comunicaremos con el usuario que creó el repositorio y le daremos aproximadamente 1 día hábil para eliminar o modificar el contenido especificado en el aviso. Notificaremos al propietario de los derechos de autor cuando le demos al usuario la oportunidad de realizar cambios. Debido a que los paquetes son inmutables, si solo una parte de un paquete está infringiendo, GitHub necesitaría deshabilitar todo el paquete, pero permitimos la restauración una vez que se elimine la parte infractora.

4. **El usuario notifica a GitHub los cambios.** Si el usuario decide llevar a cabo los cambios especificados, nos los *debe* indicar dentro del plazo de aproximadamente un (1) día hábil. Si no lo hacen, deshabilitaremos el repositorio (como se describe en el Paso 6). Si el usuario nos notifica que realizó cambios, verificaremos que los cambios se hayan realizado y luego notificaremos al propietario de los derechos de autor.

5. **El propietario de los derechos de autor revisa o revoca la notificación.** Si el usuario realiza cambios, el propietario de los derechos de autor debe revisarlos y renovar o revisar su aviso de eliminación si los cambios son insuficientes. GitHub no tomará ninguna otra medida a menos que el propietario de los derechos de autor se comunique con nosotros para renovar el aviso de eliminación original o enviar uno revisado. Si el propietario de los derechos de autor está satisfecho con los cambios, puede enviar una retractación formal o no hacer nada. GitHub interpretará el silencio de más de dos semanas como una retractación implícita del aviso de eliminación.

6. **GitHub puede deshabilitar el acceso al contenido.** GitHub deshabilitará el contenido de un usuario si: (i) el propietario de los derechos de autor ha alegado derechos de autor sobre todo el repositorio o paquete del usuario (como se indica en el paso 3); (ii) el usuario no ha realizado ningún cambio después de haber tenido la oportunidad de hacerlo (como se indica en el paso 4); o (iii) el propietario de los derechos de autor ha renovado su notificación de eliminación después de que el usuario haya tenido la oportunidad de realizar cambios. Si, en cambio, el propietario de los derechos de autor opta por *revisar* la notificación, volveremos al paso 2 y repetiremos el proceso como si la notificación revisada fuese una notificación nueva.

7. **El usuario puede enviar una contranotificación.** Alentamos a los usuarios a quienes se les ha deshabilitado el contenido a que consulten con un abogado acerca de sus opciones. Si un usuario considera que su contenido se ha deshabilitado a consecuencia de un error o de una identificación errónea, puede enviarnos una [contranotificación](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice). Al igual que sucede con la notificación original, nos aseguraremos de que la contranotificación esté lo suficientemente detallada (como se explica en la [guía](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)). En caso afirmativo, la [publicaremos](#e-transparency) en nuestro [repositorio público](https://github.com/github/dmca) y pasaremos la contranotificación al propietario de los derechos de autor enviándole el enlace.

8. **El propietario de los derechos de autor puede incoar una acción legal.** Si un propietario de derechos de autor desea mantener el contenido deshabilitado después de recibir una contranotificación, deberá iniciar una acción legal en busca de una orden judicial para impedir que el usuario participe en actividades infractoras relacionadas con el contenido en GitHub. En otras palabras, podría ser demandado. Si el propietario de los derechos de autor no notifica a GitHub dentro de los 10 a 14 días, mediante el envío de una copia de una demanda legal válida presentada en un tribunal de jurisdicción competente, GitHub volverá a habilitar el contenido deshabilitado.

[B. ¿Qué pasa con las horquillas? (o ¿Qué es un tenedor?)](#b-what-about-forks-or-whats-a-fork)
----------

Una de las mejores características de GitHub es la capacidad de los usuarios de "bifurcar" los repositorios de los demás. ¿Qué significa eso? En esencia, significa que los usuarios pueden hacer una copia de un proyecto en GitHub en sus propios repositorios. Según lo permita la licencia o la ley, los usuarios pueden realizar cambios en esa bifurcación para retroceder al proyecto principal o simplemente mantener su propia variación de un proyecto. Cada una de estas copias es un [Glosario de GitHub](/es/get-started/learning-about-github/github-glossary#fork) del repositorio original, que a su vez también puede llamarse «matriz» de la bifurcación.

GitHub *no* deshabilitará automáticamente las bifurcaciones cuando deshabilite un repositorio matriz. Esto se debe a que las bifurcaciones pertenecen a diferentes usuarios, pueden haber sido alteradas de manera significativa y pueden tener licencia o usarse de una manera diferente que esté protegida por la doctrina del uso justo. GitHub no realiza ninguna investigación independiente sobre las bifurcaciones. Esperamos que los propietarios de los derechos de autor lleven a cabo esa investigación y, si creen que las bifurcaciones también están infringiendo, incluyan expresamente las bifurcaciones en su aviso de eliminación.

En casos excepcionales, es posible que esté alegando una infracción de derechos de autor en un repositorio completo que se está bifurcando activamente. Si en el momento en que envió su notificación, identificó todas las bifurcaciones existentes de ese repositorio como presuntamente infractoras, procesaríamos un reclamo válido contra todas las bifurcaciones en esa red en el momento en que procesemos la notificación. Haríamos esto dada la probabilidad de que todas las bifurcaciones recién creadas tuvieran el mismo contenido. Además, si la red denunciada que contiene el contenido presuntamente infractor tiene más de cien (100) repositorios y, por lo tanto, sería difícil revisarla en su totalidad, podemos considerar deshabilitar toda la red si indica en su aviso que, "Basado sobre el número representativo de bifurcaciones que he revisado, creo que todas o la mayoría de las bifurcaciones están infringiendo en la misma medida que el repositorio principal". Su declaración jurada se aplicaría a esta declaración.

[C. ¿Qué pasa con las reclamaciones por elusión?](#c-what-about-circumvention-claims)
----------

La DMCA prohíbe [eludir las medidas técnicas](https://www.copyright.gov/title17/92chap12.html) que controlan de forma eficiente el acceso a las obras protegidas por derechos de autor. Dado que estas reclamaciones suelen ser de naturaleza muy técnica, GitHub requiere a los demandantes que proporcionen [información detallada sobre estas reclamaciones](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice#complaints-about-anti-circumvention-technology) para llevar a cabo una revisión más extensa.

Un reclamo de elusión debe incluir los siguientes detalles sobre las medidas técnicas implementadas y la forma en que el proyecto acusado las elude. Específicamente, el aviso a GitHub debe incluir declaraciones detalladas que describan:

1. Cuáles son las medidas técnicas;
2. Cómo controlan efectivamente el acceso al material protegido por derechos de autor; y
3. Cómo el proyecto acusado está diseñado para eludir sus medidas tecnológicas de protección descritas anteriormente.

GitHub revisará de cerca los reclamos de elusión, incluso por parte de expertos técnicos y legales. En la revisión técnica, buscaremos validar los detalles sobre la forma en que operan las medidas técnicas de protección y la forma en que el proyecto supuestamente las elude. En la revisión legal, buscaremos asegurarnos de que los reclamos no se extiendan más allá de los límites de la DMCA. En los casos en los que no podamos determinar si un reclamo es válido, nos equivocaremos del lado del desarrollador y dejaremos el contenido. Si el reclamante desea hacer un seguimiento con detalles adicionales, comenzaríamos el proceso de revisión nuevamente para evaluar las reclamaciones revisadas.

Cuando nuestros expertos determinen que un reclamo es completo, legal y técnicamente legítimo, nos comunicaremos con el propietario del repositorio y le daremos la oportunidad de responder al reclamo o realizar cambios en el repositorio para evitar una eliminación. Si no responde, intentaremos comunicarnos con el propietario del repositorio nuevamente antes de tomar más medidas. En otras palabras, no deshabilitaremos un repositorio basándonos en una reclamación de uso de tecnología de elusión sin intentar ponernos en contacto con el propietario del repositorio para darle la oportunidad de responder o realizar cambios primero. Si no podemos resolver el problema comunicándonos primero con el propietario del repositorio, siempre estaremos encantados de considerar una respuesta del propietario del repositorio, incluso después de que el contenido haya sido deshabilitado, si desea tener la oportunidad de disputar el reclamo, presentarnos hechos adicionales, o realice cambios para restaurar el contenido. Cuando necesitemos deshabilitar contenido, nos aseguraremos de que los propietarios del repositorio puedan exportar sus problemas y solicitudes de extracción y otros datos del repositorio que no contengan el supuesto código de elusión en la medida de lo legalmente posible.

Tenga en cuenta que nuestro proceso de revisión de la tecnología de elusión no se aplica al contenido que, de lo contrario, violaría las restricciones de nuestra Política de uso aceptable contra el intercambio de claves de licencia de productos no autorizados, software para generar claves de licencia de productos no autorizadas o software para eludir las comprobaciones de claves de licencia de productos. Aunque este tipo de reclamos también pueden violar las disposiciones de la DMCA sobre tecnología de elusión, generalmente son sencillos y no requieren una revisión técnica y legal adicional. No obstante, cuando una reclamación no es sencilla, por ejemplo, en el caso de fugas, se aplicaría el proceso de revisión de reclamaciones de tecnología de elusión.

Cuando GitHub procese una eliminación en virtud de la DMCA en virtud de nuestro proceso de revisión de reclamaciones de tecnología de elusión, ofreceremos al propietario del repositorio una referencia para recibir una consulta legal independiente a través del [Fondo de Defensa para Desarrolladores de GitHub](https://github.blog/2021-07-27-github-developer-rights-fellowship-stanford-law-school/) sin coste alguno para él.

[D. ¿Qué pasa si sin darme cuenta perdí la ventana para hacer cambios?](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)
----------

Reconocemos que hay muchas razones válidas por las que es posible que no pueda realizar cambios dentro de la ventana de aproximadamente 1 día hábil que proporcionamos antes de que se deshabilite su repositorio. Tal vez nuestro mensaje se marcó como spam, tal vez estabas de vacaciones, tal vez no revisas esa cuenta de correo electrónico regularmente o tal vez simplemente estabas ocupado. Lo entendemos. Si responde para informarnos que le hubiera gustado realizar los cambios, pero de alguna manera perdió la primera oportunidad, volveremos a habilitar el repositorio una vez más durante aproximadamente 1 día hábil para permitirle realizar los cambios. En este caso, también debe notificarnos que ha realizado los cambios para mantener el repositorio habilitado una vez transcurrido ese periodo de aproximadamente un (1) día hábil, como se ha indicado anteriormente en el [paso A.4](#a-how-does-this-actually-work). Tenga en cuenta que solo proporcionaremos esta oportunidad adicional.

[E. Transparencia](#e-transparency)
----------

Creemos que la transparencia es una virtud. El público debe saber qué contenido se elimina de GitHub y por qué. Un público informado puede notar y sacar a la luz problemas potenciales que de otro modo pasarían desapercibidos en un sistema opaco. Publicamos copias editadas de todas las notificaciones legales que recibimos (incluidas las notificaciones originales, las contranotificaciones y las revocaciones) en <https://github.com/github/dmca>. No publicaremos públicamente su información de contacto personal; eliminaremos la información personal (excepto los nombres de usuario en las URL) antes de publicar avisos. Sin embargo, no eliminaremos ninguna otra información de su notificación a menos que usted nos lo solicite específicamente. Aquí tiene ejemplos de una [notificación](https://github.com/github/dmca/blob/master/2014/2014-05-28-Delicious-Brains.md) y de una [contranotificación](https://github.com/github/dmca/blob/master/2014/2014-05-01-Pushwoosh-SDK-counternotice.md) publicadas para que pueda ver qué aspecto tienen. Cuando eliminemos contenido, publicaremos un enlace al aviso relacionado en su lugar.

Tenga en cuenta también que, si bien no publicaremos públicamente avisos no editados, podemos proporcionar una copia completa no editada de cualquier aviso que recibamos directamente a cualquier parte cuyos derechos se verían afectados por ello.

[F. Infracción Repetida](#f-repeated-infringement)
----------

Es política de GitHub, en las circunstancias apropiadas ya su exclusivo criterio, deshabilitar y cancelar las cuentas de los usuarios que puedan infringir los derechos de autor u otros derechos de propiedad intelectual de GitHub u otros.

[G. Envío de avisos](#g-submitting-notices)
----------

Si está listo para enviar una notificación o una contranotificación:

* [Guía para enviar una notificación de DMCA](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)
* [Guía para enviar una contranotificación de DMCA](/es/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)

[Obtenga más información y hable](#learn-more-and-speak-up)
----------

Si hurgas en Internet, no es demasiado difícil encontrar comentarios y críticas sobre el sistema de derechos de autor en general y la DMCA en particular. Si bien GitHub reconoce y aprecia el importante papel que ha desempeñado la DMCA en la promoción de la innovación en línea, creemos que las leyes de derechos de autor probablemente podrían usar un parche o dos, si no una versión completamente nueva. En software, estamos constantemente mejorando y actualizando nuestro código. Piense en cuánto ha cambiado la tecnología desde 1998, cuando se escribió la DMCA. ¿No tiene sentido actualizar estas leyes que se aplican al software?

No pretendemos tener todas las respuestas. Pero si tiene curiosidad, aquí hay algunos enlaces a artículos académicos y publicaciones de blog que hemos encontrado con opiniones y propuestas de reforma:

* [Consecuencias imprevistas: doce años bajo la DMCA](https://www.eff.org/wp/unintended-consequences-under-dmca) (Electronic Frontier Foundation)
* [Daños y perjuicios en la Ley de derechos de autor: un recurso que necesita reformas](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1375604) (Revista de Derecho William & Mary)
* [¿Es demasiado largo el plazo de protección de los derechos de autor?](https://the1709blog.blogspot.com/2012/11/is-term-of-protection-of-copyright-too.html) (El blog de 1709)
* [Si vamos a cambiar la "Notificación y eliminación" de la DMCA, centrémonos en la amplitud de su abuso](https://www.techdirt.com/articles/20140314/11350426579/if-were-going-to-change-dmcas-notice-takedown-lets-focus-how-widely-its-abused.shtml) (TechDirt)
* [Oportunidades para la reforma de los derechos de autor](https://www.cato-unbound.org/issues/january-2013/opportunities-copyright-reform) (Cato Unbound)
* [La doctrina del uso razonable y la Ley de derechos de autor del milenio digital: ¿Existe el uso legítimo en Internet según la DMCA?](https://digitalcommons.law.scu.edu/lawreview/vol42/iss1/6/) (Revisión de la Ley de Santa Clara)

GitHub no respalda necesariamente ninguno de los puntos de vista de esos artículos. Proporcionamos los enlaces para alentarlo a obtener más información, formarse sus propias opiniones y, después, ponerse en contacto con sus representantes electos (por ejemplo, en el [Congreso de los EE. UU.](https://www.govtrack.us/congress/members) o en el [Parlamento de la UE](https://www.europarl.europa.eu/meps/en/home)), para solicitar que se introduzcan aquellos cambios que considere oportunos.

{"resolvedServerColorMode":"day"}
