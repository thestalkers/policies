Политика удаления личной информации GitHub - Документация по GitHub

[Skip to main content](#main-content)

[Домашняя страница](/ru)

[Site policy](/ru/site-policy)
----------

* [Политика сайта](/ru/site-policy)/
* [Политики удаления контента](/ru/site-policy/content-removal-policies)/
* [Политика удаления личной информации GitHub](/ru/site-policy/content-removal-policies/github-private-information-removal-policy)

Политика удаления личной информации GitHub
==========

В этой статье
----------

* [Что такое личная информация?](#what-is-private-information)
* [Что нужно знать](#things-to-know)
* [Как это на самом деле работает?](#how-does-this-actually-work)
* [Отправка запроса на удаление личной информации](#sending-a-private-information-removal-request)
* [Как отправить запрос](#how-to-submit-your-request)
* [Споры](#disputes)

Мы предлагаем этот процесс удаления личных сведений в качестве исключительной услуги только для содержимого с высоким риском, нарушающего [условия предоставления услуг GitHub](/ru/site-policy/acceptable-use-policies/github-acceptable-use-policies#3-conduct-restrictions), например, когда безопасность подвергается риску в связи с раскрытием учетных данных для доступа. В этом руководстве описана информация, которая нужна GitHub от вас для обработки запроса на удаление личной информации из репозитория.

[Что такое личная информация?](#what-is-private-information)
----------

Для целей данного документа под «личными сведениями» понимается содержимое, которое (i) должно оставаться конфиденциальным *и* (ii) общедоступность которого представляет определенный или целевой риск безопасности для вас или вашей организации.

«Угроза безопасности» относится к ситуации, связанной с физической опасностью, кражей личных данных или повышенной вероятностью несанкционированного доступа к физическим или сетевым объектам.

### [Запросы на удаление личной информации подходят для:](#private-information-removal-requests-are-appropriate-for) ###

* Учетные данные доступа, такие как имена пользователей в сочетании с паролями, токены доступа или другие конфиденциальные секреты, которые могут предоставлять доступ к серверу, сети или домену вашей организации.
* Токены AWS и другие аналогичные учетные данные для доступа, которые предоставляют доступ третьей стороне от вашего имени. Вы должны быть в состоянии показать, что токен действительно принадлежит вам.
* Документация (например, сетевые схемы или архитектура), представляющая определенный риск для безопасности организации.
* Связанной с вами как с физическим лицом и представляющей риск безопасности для вас как для физического лица [информации](/ru/site-policy/acceptable-use-policies/github-doxxing-and-invasion-of-privacy) (например, номера социального страхования или другие правительственные идентификационные номера).

### [Запросы на удаление личных сведений *не* подходят для:](#private-information-removal-requests-are-not-appropriate-for) ###

* Внутренние имена серверов, IP-адреса и URL-адреса сами по себе. Вы должны быть в состоянии показать, что их использование в конкретном файле или фрагменте кода представляет угрозу безопасности.
* Простые упоминания личности, имени, бренда, доменного имени или другие ссылки на вашу компанию в файлах на GitHub. Вы должны быть в состоянии сформулировать, почему использование идентификационных данных вашей компании представляет угрозу безопасности вашей компании.
* Целые файлы или репозитории, которые не представляют особой угрозы безопасности, но, по вашему мнению, нежелательны.
* Запросы на удаление содержимого, который может нарушать ваши авторские права или права вашей организации. Если у вас есть вопросы о том, как GitHub обрабатывает проблемы, связанные с авторским правом, или вы хотите сообщить о потенциально нарушающем авторское право содержимом, ознакомьтесь с нашей [политикой снятия DMCA](/ru/site-policy/content-removal-policies/dmca-takedown-policy). Процесс удаления личной информации, как правило, не предназначен для удаления полных файлов или репозиториев — только для определенных фрагментов личной информации в этих файлах. Хотя могут быть случаи, когда файлы полностью заполнены личной информацией, вы должны обосновать угрозу безопасности для удаления таких файлов, и это может увеличить время, необходимое для обработки вашего запроса.
* Споры о товарных знаках. Если у вас есть вопросы о том, как GitHub обрабатывает проблемы, связанные с товарными знаками, или вы хотите сообщить о содержимом, включающем товарные или служебные знаки вашей организации, ознакомьтесь с нашей [политикой товарных знаков](/ru/site-policy/content-removal-policies/github-trademark-policy).
* Жалобы на конфиденциальность. Если вы хотите получить доступ к своим личным сведениям, а также передать, изменить или удалить их на GitHub, свяжитесь с нами с помощью [контактной формы по вопросам конфиденциальности](https://github.com/contact/privacy).
* Содержимого, на которое распространяется действие [правил сообщества](/ru/site-policy/github-terms/github-community-guidelines), например, вредоносных программ или универсальных инструментов. Если у вас есть вопросы о наших принципах сообщества или вы считаете, что содержимое на GitHub может нарушать наши правила, вы можете связаться с нами через [Портал поддержки GitHub](https://support.github.com/) и сообщить о таком содержимом.

[Что нужно знать](#things-to-know)
----------

**Сначала вежливо попросите.** Отличным первым шагом перед отправкой нам запроса на удаление данных является попытка связаться с пользователем напрямую. Они могли указать контактную информацию на своей общедоступной странице профиля, в README или файле поддержки репозитория, или вы могли связаться с ними, создав проблему или запрос на извлечение в репозитории. Это не является строго обязательным, но приветствуется.

**Никаких ботов.** Вы должны иметь подготовленного специалиста для оценки фактов каждого запроса, который вы отправляете. Если вы передаете свои усилия третьей стороне, убедитесь, что вы знаете, как они работают, и убедитесь, что они не используют автоматических ботов для массовой подачи жалоб. Эти жалобы часто содержат данные, которые не представляют угрозы безопасности, и они не содержат достаточных пояснений, что требует дополнительной обратной связи и приводит к задержкам, даже если жалоба обоснованна.

**Отправьте правильный запрос.** Как отмечалось выше, мы предлагаем этот процесс удаления личной информации в качестве исключительной услуги только для содержимого с высоким уровнем риска. Мы не можем использовать этот процесс для удаления других типов содержимого, например содержимого, потенциально нарушающего авторские права, и мы не можем обрабатывать какие-либо другие типы запросов на удаление одновременно с обработкой запросов на удаление личной информации. Мы сможем помочь вам быстрее, если вы отправите запросы на удаление личной информации отдельно от любых запросов на удаление содержимого, который может нарушать авторские права. Если вы не уверены, касается ли ваш запрос только частной информации или касается и других юридических вопросов, проконсультируйтесь с юристом.

**Время обработки.** Хотя мы обрабатываем запросы на удаление личной информации как можно быстрее, из-за большого количества запросов, которые мы обрабатываем, рассмотрение вашего запроса может занять некоторое время. Дополнительные запросы или несколько запросов от дополнительных контактных лиц могут привести к задержкам.

[Как это на самом деле работает?](#how-does-this-actually-work)
----------

1. **Заявитель проводит расследование.** Именно запрашивающая сторона проводит собственное расследование и предоставляет нам необходимые [сведения](#your-request-must-include) и, что самое главное, объяснение того, каким образом данные представляют угрозу безопасности. GitHub не имеет права искать или принимать первоначальные решения в отношении личной информации от имени какого-либо лица или организации.

2. **Заявитель отправляет запрос на удаление личных сведений.** После проведения расследования заявитель готовит и [отправляет запрос на удаление личных сведений](#sending-a-private-information-removal-request) в GitHub. Если запрос недостаточно подробен, чтобы продемонстрировать угрозу безопасности и чтобы GitHub мог найти данные, мы ответим и запросим дополнительную информацию.

3. **GitHub просит пользователя внести изменения.** В большинстве случаев мы свяжемся с пользователем, создавшим репозиторий, и предоставим ему возможность удалить или изменить личную информацию, указанную в запросе, либо оспорить претензию.

4. **Пользователь уведомляет GitHub об изменениях.** Если пользователь решит внести указанные изменения, он должен сообщить нам об этом в течение отведенного ему периода времени. Если они этого не сделают, мы отключим репозиторий. Если пользователь уведомит нас о внесении изменений, мы проверим, были ли внесены изменения, и уведомим заявителя.

   ИЛИ

5. **Пользователь может оспорить запрос.** Если пользователь считает, что рассматриваемое содержимое не является частной информацией, подпадающей под действие настоящей Политики, он может оспорить его. Если они это сделают, мы, как правило, оставляем заявителю возможность связаться с пользователем и решить вопрос напрямую с ним в разумных пределах.

6. **Заявитель проверяет изменения.** Если пользователь вносит изменения, заявитель должен их просмотреть. Если изменений недостаточно, заявитель должен предоставить GitHub подробную информацию, объясняющую, почему. GitHub может отключить репозиторий или предоставить пользователю дополнительную возможность внести изменения.

7. **Пользователь может запросить дополнительный период времени для внесения изменений.** Если пользователь упустил возможность удалить личную информацию, указанную в уведомлении, мы можем предоставить ему дополнительное окно примерно в 1 рабочий день по запросу для внесения этих изменений. В этом случае GitHub уведомит заявителя.

### [Что насчет вилок? (или Что такое вилка?)](#what-about-forks-or-whats-a-fork) ###

Одной из лучших особенностей GitHub является возможность для пользователей «разветвлять» репозитории друг друга. Что это обозначает? По сути, это означает, что пользователи могут сделать копию проекта на GitHub в свои собственные репозитории. В соответствии с лицензией или законом пользователи могут затем вносить изменения в эту вилку, чтобы либо вернуться к основному проекту, либо просто сохранить как свою собственную вариацию проекта. Каждая из этих копий представляет собой [Глоссарий GitHub](/ru/get-started/learning-about-github/github-glossary#fork) исходного репозитория, который в свою очередь может называться «родительским элементом» вилки.

GitHub не будет автоматически отключать вилки при отключении родительского репозитория. Это связано с тем, что вилки принадлежат разным пользователям и могут быть существенно изменены. GitHub не проводит никаких независимых расследований вилок. Мы ожидаем, что те, кто отправляет запросы на удаление личной информации, проведут это расследование и, если они сочтут, что вилки также содержат личную информацию, прямо включат вилки в свой запрос.

Если на момент отправки уведомления вы определили все существующие ответвления этого репозитория, мы обработаем действительную претензию в отношении всех ответвлений в этой сети на момент обработки уведомления. Мы бы сделали это, учитывая вероятность того, что все вновь созданные вилки будут содержать одно и то же содержимое. Кроме того, если заявленная сеть, содержащая указанное содержимое, превышает сто (100) репозиториев и, таким образом, будет трудно проверить ее целиком, мы можем рассмотреть возможность отключения всей сети, если вы укажете в своем уведомлении, что на основании репрезентативное количество проверенных вами вилок, вы считаете, что все или большинство вилок содержат содержимое, указанное в родительском репозитории.

[Отправка запроса на удаление личной информации](#sending-a-private-information-removal-request)
----------

Из-за типа содержимого, размещенного на GitHub (в основном программный код), и способа управления этим содержимым (с помощью Git) нам нужно, чтобы жалобы были как можно более конкретными. Чтобы мы могли убедиться, что пользователь полностью удалил сообщенную личную информацию, нам нужно точно знать, где искать.

Эти рекомендации предназначены для того, чтобы максимально упростить обработку запросов на удаление личной информации.

### [Ваш запрос должен включать:](#your-request-must-include) ###

1. Рабочая ссылка на каждый файл, содержащий личную информацию. (Обратите внимание, что мы не можем работать с результатами поиска, примерами или снимками экрана.)
2. Конкретные номера строк в каждом файле, содержащем личную информацию.
3. Краткое описание того, как каждый элемент, который вы идентифицировали, представляет угрозу безопасности для вас или вашей организации. ***Важно объяснить, как именно данные представляют риск безопасности, а не просто заявить об этом.***
4. Если вы являетесь третьей стороной, выступающей в качестве агента организации, сталкивающейся с угрозой безопасности, включите заявление о том, что у вас есть законное право действовать от имени этой организации.
5. НЕОБЯЗАТЕЛЬНО: если ваш запрос является срочным, сообщите нам об этом и укажите причину. Мы отвечаем на все запросы на удаление личной информации как можно быстрее. Однако, если этот запрос особенно чувствителен ко времени, например, совсем недавно раскрытие учетных данных, пожалуйста, объясните, почему.

[Как отправить запрос](#how-to-submit-your-request)
----------

Вы можете отправить запрос на удаление личных сведений с помощью [контактной формы](https://support.github.com/contact?tags=docs-private-information). Пожалуйста, включите текстовую версию вашего запроса в текст вашего сообщения. Отправка вашего запроса во вложении может привести к задержке обработки.

[Споры](#disputes)
----------

Если вы получили от нас запрос на удаление личной информации, вы можете оспорить его, ответив на наше электронное письмо и сообщив нам — как можно более подробно — почему вы считаете, что рассматриваемое содержимое не является личной информацией, подпадающей под действие настоящей Политики.

{"resolvedServerColorMode":"day"}
