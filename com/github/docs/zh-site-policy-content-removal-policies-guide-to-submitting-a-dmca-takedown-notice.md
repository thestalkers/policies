DMCA 下架通知提交指南 - GitHub 文档

[Skip to main content](#main-content)

[主页](/zh)

[Site policy](/zh/site-policy)
----------

* [站点政策](/zh/site-policy)/
* [内容删除政策](/zh/site-policy/content-removal-policies)/
* [DMCA 下架通知提交指南](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-takedown-notice)

DMCA 下架通知提交指南
==========

本文内容
----------

* [开始前](#before-you-start)
* [您的投诉必须...](#your-complaint-must-)
* [有关反规避技术的投诉](#complaints-about-anti-circumvention-technology)
* [如何提交投诉](#how-to-submit-your-complaint)

本指南说明了 GitHub 处理 DMCA 下架请求所需的信息。 如果您对 DMCA 是什么或 GitHub 如何处理 DMCA 下架请求有更多常规问题，请参阅我们的 [DMCA 下架政策](/zh/site-policy/content-removal-policies/dmca-takedown-policy)。

鉴于 GitHub 托管内容的类型（主要是软件代码）以及管理内容的方式（使用 Git），我们需要投诉内容尽可能具体。 这些准则旨在尽可能简单明了地处理指控侵权的通知。 下述通知形式与 DMCA 法规建议的形式一致，您可以登录美国版权局官方网站<https://www.copyright.gov> 查看该法规。

与所有法律事务一样，就您的具体问题或情况咨询专业人员始终是最好的方式。 我们强烈建议您在采取任何可能影响您权利的行动之前这样做。 本指南不是法律意见，不应被视为法律意见。

[开始前](#before-you-start)
----------

***说实话。*** DMCA 要求您对自己的版权投诉内容宣誓，如有不实会受到伪证处罚。 在宣誓声明中故意说谎是一种联邦罪行。 （*请参阅*[美国法典，第 18 章，第 1621 条](https://www.gpo.gov/fdsys/pkg/USCODE-2011-title18/html/USCODE-2011-title18-partI-chap79-sec1621.htm)。）提交虚假信息还可能导致民事责任，即可能被诉提供经济赔偿。 DMCA 本身对任何故意严重歪曲材料或活动侵权的人[规定了赔偿条款](https://en.wikipedia.org/wiki/Online_Copyright_Infringement_Liability_Limitation_Act#%C2%A7_512(f)_Misrepresentations)。

调查。 数百万用户为自己在 GitHub 上创建和参与的项目倾注了心血。 针对此类项目提出 DMCA 投诉是一种严重的法律指控，会对项目背后真实的人造成真正的后果。 因此，我们要求您在提交下架通知之前进行彻底的调查并咨询律师，以确保您所投诉的使用没有经过许可。

***先礼貌问清。*** 向我们发送下架通知之前，最好先尝试直接联系用户。 他们可能在其公开的个人资料页面上或存储库的自述文件中列出了联系信息，您也可以通过在存储库中打开议题或拉取请求，与他们取得联系。 这不是强制要求，但却是一种很好的做法。

***发送正确的请求。*** 我们只接受针对受版权保护的作品并且标识出具体版权作品的 DMCA 下架通知。 如果您要投诉商标滥用行为，请参阅我们的[商标政策](/zh/site-policy/content-removal-policies/github-trademark-policy)。 如果您要删除密码等敏感数据，请参阅我们的[敏感数据政策](/zh/site-policy/content-removal-policies/github-private-information-removal-policy)。 如果您要处理诽谤或其他辱骂行为，请参阅我们的[社区准则](/zh/site-policy/github-terms/github-community-guidelines)。

***代码不同于其他创意内容。*** GitHub 专为软件代码协作而构建。 因此，识别有效版权侵犯行为比识别照片、音乐或视频方面的版权侵犯行为要复杂得多。

代码不同于其他创意内容的原因有很多。 例如：

* 存储库可能包含来自许多不同用户的零碎代码，但可能只有一个文件甚至文件中的一个子例程侵犯了您的版权。
* 代码结合了功能和创意表达，但版权只保护表达元素，而不保护功能部分。
* 通常要考虑许可。 仅仅是一段代码有版权声明，并不一定意味着侵权。 因为该代码有可能是在开源许可下使用的。
* 如果特定使用符合以下条件，可能属于[合理使用](https://www.lumendatabase.org/topics/22)：只使用少量版权内容、以变换方式使用内容、用于教育目的或以上条件的某些组合。 由于代码本身适合于这些用途，但每个用例都有所不同，因此必须单独考虑。
* 代码可能被控以许多不同的方式侵权，因此需要对作品进行详细的说明和标识。

此列表并不详尽，因此在提出针对代码的投诉之前，请咨询法律专业人士，这一点特别重要。

***不要使用自动程序。*** 应该让训练有素的专业人员来评估你发送的每个删除通知中的事实。 如果您将工作外包给第三方，请务必了解他们的运作方式，确保他们不使用自动程序来批量提交投诉。 这些投诉往往是无效的，并且处理它们会对项目造成不必要的中断！

***版权问题难以确定。*** 确定特定作品是否受版权保护可能很难。 例如，事实（包括数据）通常不受版权保护。 字词短语通常不受版权保护。 URL 和域名通常不受版权保护。 由于您只能使用 DMCA 流程来处理受版权保护的内容，因此，如果您对内容是否受保护存有疑问，应咨询律师。

***您可能会收到抗辩通知。*** 任何受您的下架通知影响的用户可自行决定提交[抗辩通知](/zh/site-policy/content-removal-policies/guide-to-submitting-a-dmca-counter-notice)。 如果他们这样做，我们将在 10-14 天内重新启用其内容，除非您通知我们您已发起法律诉讼以求制止用户从事与 GitHub 上的内容有关的侵权活动。

***您的投诉将被公布。*** 如我们的 [DMCA 删除政策](/zh/site-policy/content-removal-policies/dmca-takedown-policy#d-transparency)所述，在删除个人信息后，我们将在 <https://github.com/github/dmca> 上发布所有完整、可诉的下架通知。

***GitHub 不是法官。*** 除了确定通知是否符合 DMCA 的最低要求外，GitHub 在此过程中几乎不行使酌处权。 当事方（及其律师）应负责评估其投诉的合理性，并注意，此类通知受伪证处罚条款约束。

[您的投诉必须...](#your-complaint-must-)
----------

1. **包括以下声明：“我已阅读并理解 GitHub 的《DMCA 通知提交指南》。** 如果您的投诉未包括此声明，但其他内容完整，我们不会拒绝处理。 但我们知道您尚未阅读这些准则后，可能会要求您先完成这一步。

2. **标识您认为被侵犯版权的作品。** 此信息很重要，因为它有助于受影响的用户评估您的主张，使他们能够将您的作品与他们的作品进行比较。 标识的具体性将取决于您认为被侵权的作品的性质。 如果您已发布自己的作品，则只需链接到其所在的网页。 如果它是尚未发布的专有信息，您可以对其进行描述并说明它是专有信息。 如果您已在版权局对它进行注册，则应提供注册号。 如果您声称托管内容完全直接复制您的作品，您也可以只阐述这一事实。

3. **标识您声称侵犯了上述第 2 条中所列版权作品的材料。** 您的标识应尽可能具体，这非常重要。 此标识必须足以让 GitHub 找到所指材料。 这意味着至少应包括涉嫌侵犯版权的材料的 URL。 如果您声称并非整个存储库侵权，则应标识涉嫌侵权的具体文件或文件中的具体行号。 如果您声称 URL 上的所有内容都侵权，也请明确说明。

   * 请注意，GitHub 禁用父存储库时 *不会* 自动禁用[复刻](/zh/site-policy/content-removal-policies/dmca-takedown-policy#b-what-about-forks-or-whats-a-fork)。 如果您已调查和分析了存储库的复刻，并且认为它们也涉嫌侵权，请明确标识每个涉嫌侵权的复刻。 另请确认，您已逐个调查每个所标识的复刻，并且您的宣誓声明适用于每个所标识的复刻。 在极少数情况下，您可能会指控正在被复刻的完整存储库中存在侵权。 如果您在提交通知时发现该存储库的所有现有复刻涉嫌侵权，我们将在处理通知时处理对该网络中所有复刻的有效索赔。 我们这样做是考虑到所有新建复刻都可能包含相同的内容。 此外，如果所报告的包含涉嫌侵权内容的网络大于一百 (100) 个存储库，从而很难全面审查，并且您在通知中指出，“根据您审查的代表性复刻数量，我相信所有或大多数复刻的侵权程度与父存储库相同”，则我们可能会考虑禁用整个网络。 您的宣誓声明将适用于该声明。

4. **说明受影响用户需要采取哪些侵权补救措施。** 同样，具体性很重要。 我们将您的投诉传达给用户时，这些说明将告诉他们需要采取哪些措施以避免其余内容被禁用。 用户是否只需要添加归属声明？ 他们是否需要删除代码中的某些行，或者需要删除整个文件？ 当然，我们明白在某些情况下，用户的所有内容都涉嫌侵权，除了全部删除之外，别无他法。 如果是这种情况，也请明确说明。

5. **提供您的联系信息。** 包括您的电子邮件地址、姓名、电话号码和实际地址。

6. **提供涉嫌侵权者的联系信息（如果您知道）。** 通常可以提供与涉嫌侵权内容相关联的 GitHub 用户名来满足这一要求。 但在某些情况下，您可能对涉嫌侵权者有更多了解。 如果是，请与我们分享这些信息。

7. **包括以下声明：“我有足够理由相信，在侵权网页中对上述受版权保护材料的使用并未得到版权所有者、其代理人或法律的授权。我已考虑合理使用的情况。”**

8. **还应包括以下声明：“我宣誓，本通知中的信息是准确的，我是商标所有者，或者我被授权代表专有权涉嫌受到侵犯的所有者行事。”**

9. **包括您的纸质或电子签名。**

[有关反规避技术的投诉](#complaints-about-anti-circumvention-technology)
----------

著作权法还禁止规避用于有效控制受版权保护作品的访问权限的技术措施。 如果您认为 GitHub 上托管的内容违反了此禁令，请通过我们的 [版权声明表](https://github.com/contact/dmca) 向我们发送报告。 规避索赔必须包括以下有关现有技术措施以及被指控项目如何规避这些措施的详细信息。 具体来说，发送给 GitHub 的通知必须包含详细的说明，描述：

1. 技术措施是什么；
2. 它们如何有效控制对受版权保护材料的访问；以及
3. 被指控项目如何设计来规避前面所述的技术保护措施。

[如何提交投诉](#how-to-submit-your-complaint)
----------

得到回复的最快方式是在我们的[版权声明表](https://github.com/contact/dmca)中输入您的信息并回答所有问题。

你也可以发送电子邮件通知到 [copyright@github.com](mailto:copyright@github.com)。 您可以包含附件（如果您愿意），但在邮件正文中也应包含邮件的纯文本版本。

如果必须通过邮政邮件发送通知，也可以，但我们接收和回复通知的时间会 *大大* 延长。 接收纯文本电子邮件通知比接收 PDF 附件或邮政邮件要快得多。 如果您仍希望通过邮寄方式发送通知，我们的邮寄地址是：

```
GitHub, Inc
Attn: DMCA Agent
88 Colin P Kelly Jr St
San Francisco, CA. 94107

```

{"resolvedServerColorMode":"day"}
