GitHub 附加产品和功能条款 - GitHub 文档

[Skip to main content](#main-content)

[主页](/zh)

[Site policy](/zh/site-policy)

* [站点政策](/zh/site-policy)/
* [GitHub 条款](/zh/site-policy/github-terms)/
* [GitHub 附加产品和功能条款](/zh/site-policy/github-terms/github-terms-for-additional-products-and-features)

GitHub 附加产品和功能条款
==========

本文内容
----------

* [操作](#actions)
* [Advanced Security](#advanced-security)
* [Advisory Database](#advisory-database)
* [Codespaces](#codespaces)
* [竞争基准分析](#competitive-benchmarking)
* [连接](#connect)
* [GitHub Copilot](#github-copilot)
* [GitHub Enterprise Importer](#github-enterprise-importer)
* [npm](#npm)
* [服务包](#packages)
* [Pages](#pages)
* [预览版](#previews)
* [赞助商计划](#sponsors-program)
* [SQL Server Images](#sql-server-images)
* [GitHub 模型](#github-models)

版本生效日期：2025 年 4 月 1 日

当您使用 GitHub 时，您可以访问大量附加产品和功能（“附加产品和功能”）。 由于许多附加产品和功能具有不同的作用，您与我们之间的协议包含针对该产品或功能的具体条款以及您与我们的主要协议（GitHub 服务条款、GitHub 客户协议、GitHub 企业服务条款、其他旧版 GitHub 合同或微软批量许可协议）。 下面列出了这些产品和功能，以及适用于您对它们的使用的相应附加条款。

使用附加产品和功能，即表示您也同意下面列出的适用的 GitHub 附加产品和功能条款。 违反这些 GitHub 附加产品和功能条款即为违反协议。 此处未定义的术语与协议中规定的含义相同。

**对于企业用户**

* GitHub Enterprise Cloud 用户可以访问以下附加产品和功能：Actions、Advanced Security（包括 Code Security 和 Secret Protection）、Advisory Database、Codespaces、Dependabot、GitHub Enterprise Importer、Packages 和 Pages。\*\*\*\*

* GitHub Enterprise Server 用户可以访问以下附加产品和功能：Actions、Advanced Security（包括 Code Security 和 Secret Protection）、Advisory Database、Connect、Dependabot、GitHub Enterprise Importer、Packages、Pages 和 SQL Server Images。\*\*\*\*

[操作](#actions)
----------

GitHub Actions 使你能够直接在 GitHub 存储库中创建自定义软件开发生命周期工作流程。 Actions 按使用情况计费。 [Actions 文档](/zh/actions)包含详细信息，包括计算和存储量（取决于您的帐户计划）以及如何监控您的 Actions 分钟使用情况和设置使用限制。

对 Actions 以及任何 Actions 产品或服务元素的使用不得违反协议、[GitHub 可接受的使用政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)或 [Actions 文档](/zh/actions/learn-github-actions/usage-limits-billing-and-administration)规定的 GitHub Actions 服务限制。 此外，无论操作是否使用自托管运行器，Actions 都不应用于：

* 加密货币挖矿；
* 破坏、获取或试图未经授权而访问任何服务、设备、数据、帐户或网络（[GitHub Bug 赏金计划](https://bounty.github.com)授权的除外）；
* 出于商业目的提供独立或集成的应用程序或服务，其中提供 Actions 产品或服务或者 Actions 产品或服务的任何元素；
* 给我们的服务器带来负担且这种负担与提供给用户的权益不成比例的活动（例如，不要将 Actions 用作内容分发网络或作为无服务器应用程序的一部分，但低权益、低负担的操作可能没有问题）；
* 与软件项目（与使用 GitHub Actions 的存储库关联）的生产、测试、部署或发布无关的任何其他活动（如果使用 GitHub 托管的运行器）。

为防止违反这些限制和滥用 GitHub Actions，GitHub 可能会监视您对 GitHub Actions 的使用。 滥用 GitHub Actions 可能会导致作业终止、限制您使用 GitHub Actions 的能力、禁用为了以违反这些条款的方式运行 Actions 而创建的存储库，或者在某些情况下，暂停或终止您的 GitHub 帐户。

*用于开发和测试*

您只能访问和使用 GitHub Actions 来开发和测试您的应用程序。 任何时候都只能由一位许可用户访问 Actions 提供的虚拟机。

*授权开发人员*

对于 Actions 中包含的 Apple 软件，您指定 GitHub 作为您的授权开发商。 GitHub 有责任遵守 Actions 中包含的任何此类软件的条款，并对作为 Actions 的一部分访问的任何 Apple 机密信息进行保密。

*第三方存储库服务访问*

如果您授权 GitHub 访问您的第三方存储库服务帐户，即表示您授权 GitHub 扫描这些帐户（包括您的公共和私有存储库的内容）以便提供 GitHub Actions。

*GitHub Actions 上的自托管运行器*

如果您使用自托管运行器，则可以关闭自动更新，但 GitHub 保留覆盖您选择的重要安全更新的权利。

[Advanced Security](#advanced-security)
----------

GitHub 根据 Advanced Security 许可证下为客户提供额外的安全功能。 从 2025 年 4 月 1 日开始，以前仅在单个 GitHub Advanced Security 许可证下可用的功能也可在下面两个单独的许可证下使用：GitHub Code Security（代码扫描和依赖项扫描功能）和 GitHub Secret Protection（机密扫描功能）。 [Advanced Security 文档](/zh/get-started/learning-about-github/about-github-advanced-security)提供更多详细信息。

Advanced Security 功能按“唯一提交者”许可。 “唯一提交者”是指过去 90 天内在激活了任何 GitHub Advanced Security 功能的任何存储库中进行过提交的 GitHub Team、GitHub Enterprise、GitHub Enterprise Cloud 或 GitHub Enterprise Server 许可用户。 您必须为每个唯一提交者获取相应的 GitHub Advanced Security 用户许可。 您只能在由您开发或为您开发的代码库上使用 GitHub Advanced Security 功能。 对于 GitHub Team 和 GitHub Enterprise Cloud 用户，一些高级安全功能也可能需要使用 GitHub Actions。

若要使用 GitHub Advanced Security 或 GitHub Secret Protection 进行机密扫描，如果选择自动验证合作伙伴模式，可能会与相关合作伙伴共享公开的第三方令牌，以便提供有关令牌有效性的详细信息。 并非所有合作伙伴都位于美国。 [机密扫描模式文档](/zh/enterprise-cloud@latest/code-security/secret-scanning/introduction/supported-secret-scanning-patterns)提供了更多详细信息，介绍哪些合作伙伴支持有效性检查。

[Advisory Database](#advisory-database)
----------

GitHub Advisory Database 允许您浏览或搜索影响 GitHub 上开源项目的漏洞。

*向我们授予许可*

我们需要合法权利才能将您对 GitHub Advisory Database 的贡献提交到公共域数据集，例如[国家漏洞数据库](https://nvd.nist.gov/)，并在明文条款下许可 GitHub Advisory Database，以供安全研究人员、开源社区、行业和公众使用。 您同意根据[知识共享零许可](https://creativecommons.org/publicdomain/zero/1.0/)发布您对 GitHub Advisory Database 的贡献。

*GitHub Advisory Database 的许可*

GitHub Advisory Database 根据[知识共享署名 4.0 许可](https://creativecommons.org/licenses/by/4.0/)获得许可。 要履行署名条款，可链接至 <https://github.com/advisories> 上的 GitHub Advisory Database，或者所使用的单独 GitHub Advisory Database 记录（以 <https://github.com/advisories> 为前缀）。

[Codespaces](#codespaces)
----------

*注意：可在存储库上按下“.”或直接导航到 github.dev 来使用 github.dev 服务，此服务受 GitHub 试用版服务条款约束。*

GitHub Codespaces 使您能够直接从浏览器中使用 GitHub 存储库中的代码来开发代码。 使用 Codespaces 和 Codespaces 服务的任何元素时不得违反协议或可接受使用政策。 此外，Codespaces 不得用于：

* 加密货币挖矿；
* 使用我们的服务器破坏、获取或试图未经授权而访问任何服务、设备、数据、帐户或网络（GitHub Bug 赏金计划授权的除外）；
* 出于商业目的提供独立或集成的应用程序或服务，其中提供 Codespaces 或者 Codespaces 的任何元素；
* 给我们的服务器带来负担且这种负担与提供给用户的权益不成比例的活动（例如，不要将 Codespaces 用作内容分发网络、作为无服务器应用程序的一部分或托管任何类型的面向生产的应用程序）；
* 与软件项目（与启动 GitHub Codespaces 的存储库关联）的开发或测试无关的任何其他活动。

为防止违反这些限制和滥用 GitHub Codespaces，GitHub 可能会监视您对 GitHub Codespaces 的使用。 滥用 GitHub Codespaces 可能会导致终止您对 Codespaces 的访问、限制您使用 GitHub Codespaces 的能力，或禁用为了以违反这些条款的方式运行 Codespaces 而创建的存储库。

Codespaces 允许您从 Microsoft Visual Studio Marketplace 加载扩展（“Marketplace Extensions”）以在开发环境中使用，例如，用于处理编写代码所使用的编程语言。 Marketplace Extensions 根据其自己的单独使用条款（如 Visual Studio Marketplace 中所述）以及位于 <https://aka.ms/vsmarketplace-ToU> 的使用条款进行许可。 GitHub 对 Marketplace Extensions 不作任何形式的保证，对于有权访问您的内容的 Marketplace Extensions 的第三方作者的行为也概不负责。 Codespaces 还允许您通过 devcontainer 功能将软件加载到您的环境中。 此类软件根据其随附的单独使用条款提供。 您使用任何第三方应用程序由您自行承担风险。

Codespaces 的通用版本当前不适用于美国政府客户。 美国政府客户可以在单独条款下继续使用 Codespaces Beta 预览版。 请参阅 [Beta 预览版条款](/zh/site-policy/github-terms/github-terms-of-service#j-beta-previews)。

[竞争基准分析](#competitive-benchmarking)
----------

如果您提供的产品或服务与任何 GitHub 产品或服务存在竞争关系，那么使用该 GitHub 产品或服务，即表示您同意并特此放弃适用于您的竞争产品或服务的条款中对 GitHub 的竞争性使用和基准测试的任何限制。 如果您无意放弃您的使用条款中的此类限制，则无权使用该 GitHub 产品或服务。

[连接](#connect)
----------

使用 GitHub Connect，您可以在 GitHub Enterprise Server 部署与您的 GitHub Enterprise Cloud 组织或 GitHub.com 上的企业帐户之间共享特定功能和数据。 要启用 GitHub Connect，您必须在 GitHub Enterprise Cloud 或 GitHub.com 上至少有一 (1) 个帐户，以及一 (1) 个许可的 GitHub Enterprise Server 部署。 您通过 Connect 对 GitHub Enterprise Cloud 或 GitHub.com 的使用受您许可 GitHub Enterprise Cloud 或 GitHub.com 所依据的条款管理。 对个人数据的使用受 [GitHub 隐私声明](/zh/site-policy/privacy-policies/github-privacy-statement)管理。

[GitHub Copilot](#github-copilot)
----------

GitHub Copilot Business 和 Copilot Enterprise 许可证持有者对 GitHub Copilot 的使用受 [GitHub Copilot 产品特定条款](https://github.com/customer-terms/github-copilot-product-specific-terms)约束。

对于其他 GitHub Copilot 许可证持有者，对 GitHub Copilot 的使用受以下条款的约束：若要在代码编辑器中使用 GitHub Copilot，需要将 GitHub Copilot 扩展安装到该编辑器。 要在 CLI（命令行接口）中使用 GitHub Copilot，则需要安装 GitHub Copilot CLI 扩展。 要在 GitHub Mobile 上使用 GitHub Copilot 聊天，则需要安装 GitHub Mobile 应用程序。 若要在 GitHub.com 使用 GitHub Copilot，则必须访问该网站。

如果自定义 GitHub Copilot，包括使用 GitHub Copilot 扩展（扩展），则使用可能会受到适用于该自定义的使用条款和隐私策略的约束。

根据协议，你使用 GitHub Copilot编写的代码在你将其上传到 GitHub.com 前不是“内容”。 GitHub Copilot 返回给你的代码、函数和其他输出称为“建议”。 GitHub 不对建议主张任何权利， 你对你的代码（包括你的代码中包含的建议）具有所有权和责任。 是否使用 GitHub Copilot 生成的建议完全由你决定。 如果你使用建议，GitHub 强烈建议制定合理的策略和做法，以避免在使用建议时侵犯他人权利。

*可接受的使用方式*

你对 GitHub Copilot 的使用受 GitHub [可接受的使用方式政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)约束。 例如，不得向 GitHub Copilot 提示非法或 GitHub.com 上的 GitHub 可接受的使用方式政策禁止的内容。 如果选择“允许”Copilot 提供[与公共代码匹配的建议](/zh/enterprise-cloud@latest/copilot/using-github-copilot/finding-public-code-that-matches-github-copilot-suggestions?tool=vscode)，则必须符合引用的许可证。

*数据*

GitHub Copilot：(i) 可能会根据你的设置以及你使用的特定 GitHub Copilot 服务收集和处理数据 - 这可能包括提示、建议和代码片段，并且 (ii) 将通过你使用的与帐户绑定的 GitHub Copilot 服务收集其他使用信息 - 这可能包括服务使用信息、网站使用数据和反馈数据。 我们可能根据你的指示与第三方应用程序（例如 [GitHub Marketplace](https://github.com/marketplace) 中的应用程序）或你选择的第三方 AI 模型共享此类数据。 这可能包括个人数据，如 [GitHub 隐私声明](/zh/site-policy/privacy-policies/github-privacy-statement)中所述。 可以通过 [GitHub Copilot 信任中心](https://resources.github.com/copilot-trust-center/)详细了解 GitHub Copilot 数据的收集和使用。

对于 GitHub Copilot 免费版用户，GitHub Copilot 收集的数据可能用于 AI 模型训练（在允许的场景下并且如果你的设置中允许这样做）。

[GitHub Enterprise Importer](#github-enterprise-importer)
----------

Importer 是将数据从其他源导出到 GitHub 平台的框架。 Importer“按原样”提供。

[npm](#npm)
----------

npm 是一种软件包托管服务，允许您以私有方式或公开方式托管软件包，并将软件包用作项目中的依赖项。 npm 是 JavaScript 生态系统的记录注册表。 npm 公共注册表可以免费使用，但客户如果想要发布私有包或使用团队管理私有包，则需收取费用。 [npm 文档](https://docs.npmjs.com/)包含有关帐户类型限制以及如何管理[私有包](https://docs.npmjs.com/about-private-packages)和[组织](https://docs.npmjs.com/organizations)的详细信息。 [开源条款](https://www.npmjs.com/policies/open-source-terms)概述了可接受的 npm 注册表使用。 npm [solo](https://www.npmjs.com/policies/solo-plan) 和 [org](https://www.npmjs.com/policies/orgs-plan) 计划都有补充条款。 npm [使用条款](https://www.npmjs.com/policies/terms)适用于您对 npm 的使用。

[服务包](#packages)
----------

GitHub Packages 是一种软件包托管服务，允许您以私有方式或公开方式托管软件包，并将软件包用作项目中的依赖项。 GitHub Packages 按使用情况计费。 [Packages 文档](/zh/packages/learn-github-packages/introduction-to-github-packages)包含详细信息，包括带宽和存储量（取决于您的帐户计划）以及如何监控您的 Packages 使用和设置使用限制。 Packages Bandwidth 使用情况受 [GitHub 可接受的使用政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)的限制。

[Pages](#pages)
----------

每个帐户都可以访问 [GitHub Pages 静态托管服务](/zh/pages/getting-started-with-github-pages/about-github-pages)。 GitHub Pages 旨在托管静态网页，但主要用作个人和组织项目的展示。

GitHub Pages 并非旨在用于或允许用作免费的 Web 托管服务来运行您的在线业务、电子商务站点或主要针对促进商业交易或提供商业软件即服务 (SaaS) 的任何其他网站。 用户可在 Pages 上进行一些与货币有关的工作，如捐款按钮和筹款链接。

*带宽和使用限制*

GitHub Pages 受某些特定带宽和使用限制的约束，可能不适用于某些高带宽用途。 请参阅我们的 [GitHub Pages 限制](/zh/pages/getting-started-with-github-pages/about-github-pages)，了解更多信息。

*禁止的使用情形*

对 GitHub Pages 的使用不得违反协议、GitHub [可接受使用政策](/zh/site-policy/acceptable-use-policies/github-acceptable-use-policies)或 [Pages 文档](/zh/pages/getting-started-with-github-pages/about-github-pages#guidelines-for-using-github-pages)规定的 GitHub Pages 服务限制。

如果您对用途或预期用途是否归入这些类别有疑问，请通过 [GitHub 支持门户](https://support.github.com/)联系我们。 GitHub 保留随时收回任何 GitHub 子域而不承担任何责任的权利。

*学习练习*

允许使用 GitHub Pages 创建现有网站的副本以进行学习练习。 但是，必须自行编写代码，网站不得收集任何用户数据，并且网站必须提供明确的免责声明，表明项目与原始项目无关，且仅用于学习目的。

[预览版](#previews)
----------

预览版是指为预览、评估、演示或试用目的而提供的软件、在线服务以及附加产品和功能或者它们的预发布版本，如 Alpha 版、Beta 版或抢先体验版。 如果协议不包含涉及预览版的条款和条件，则以下条款适用。 GitHub 授予使用预览版非生产实例的有限权限。 预览版按“原样”、“可能存在各种缺陷”和“可用”的形式提供。 GitHub 可能随时更改或终止预览版，恕不另行通知。 我们提供的有关私人预览版的任何信息都将被视为 GitHub 的机密信息。 如果您选择提供有关预览版的评论或建议，我们可能会出于任何目的使用该反馈，而无需承担任何义务。 GitHub 的最高赔偿责任仅限于直接损害赔偿，最高 500 美元。 对于因您对预览版的使用而导致第三方提出的索赔，GitHub 没有义务为您辩护、赔偿或使您免受损害。

[赞助商计划](#sponsors-program)
----------

GitHub 赞助商计划允许开发人员社区直接在 GitHub 上为设计、构建和维护自身所依赖的开源项目的人员及组织提供经济支持。 要成为受赞助开发人员，您必须同意 [GitHub 赞助商计划附加条款](/zh/site-policy/github-terms/github-sponsors-additional-terms)。

[SQL Server Images](#sql-server-images)
----------

您可以下载适用于 Linux 文件的 Microsoft SQL Server 标准版容器映像（“SQL Server Images”）。 当您对该软件的使用权利终止时，您必须卸载 SQL Server Images。 Microsoft Corporation 可随时禁用 SQL Server Images。

[GitHub 模型](#github-models)
----------

GitHub 模型是一项功能，可用于在 GitHub.com 上学习、试用和测试人工智能模型。 可以通过 [GitHub Marketplace](https://github.com/marketplace) 访问 GitHub 模型。 通过访问 [AI 模型的原型制作](/zh/github-models/prototyping-with-ai-models)，详细了解 GitHub 模型。

此功能的使用受托管模型和模型许可证的公司条款的约束。

{"resolvedServerColorMode":"day"}
