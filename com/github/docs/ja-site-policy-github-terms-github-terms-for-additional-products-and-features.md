追加の製品および機能に適用される GitHub 条件 - GitHub Docs

[Skip to main content](#main-content)

[ホーム](/ja)

[Site policy](/ja/site-policy)

* [サイト ポリシー](/ja/site-policy)/
* [GitHub 条件](/ja/site-policy/github-terms)/
* [追加の製品および機能に適用される GitHub 条件](/ja/site-policy/github-terms/github-terms-for-additional-products-and-features)

追加の製品および機能に適用される GitHub 条件
==========

この記事の内容
----------

* [アクション](#actions)
* [Advanced Security](#advanced-security)
* [Advisory Database](#advisory-database)
* [Codespaces](#codespaces)
* [競合する製品またはサービスのベンチマーク](#competitive-benchmarking)
* [Connect](#connect)
* [GitHub Copilot](#github-copilot)
* [GitHub Enterprise Importer](#github-enterprise-importer)
* [npm](#npm)
* [パッケージ](#packages)
* [ページ](#pages)
* [プレビュー](#previews)
* [Sponsors プログラム](#sponsors-program)
* [SQL Server Images](#sql-server-images)
* [GitHub モデル](#github-models)

バージョンの有効日: 2024 年 9 月 9 日

GitHub を利用する際、数多くの追加製品や機能 (以下「追加の製品および機能」といいます) にもアクセス権を与えられる場合があります。 「追加の製品および機能」の多くはさまざまな機能を提供するため、当社との主な契約、すなわち「GitHub サービス使用条件」、GitHub 顧客契約、「GitHub の企業向けサービス使用条件」、その他「GitHub 一般契約」、または Microsoft ボリューム ライセンス契約 (以下、それぞれを「契約」といいます) に加えて、製品や機能に特定の条件が適用される場合があります。 以下に、これらの製品および機能と、その利用に対して適用される追加の条件を示します。

追加の製品および機能を使用することにより、お客様は、適用される下記の「追加の製品および機能に適用される GitHub 条件」にも同意するものとします。 これらの「追加の製品および機能に適用される GitHub 条件」に対する違反は、本契約の違反になります。 大文字の用語のうちここで定義されていないものについては、本契約における定義が適用されます。

**エンタープライズ ユーザー向け**

* **GitHub Enterprise Cloud** のユーザーは、Actions、Advanced Security、Advisory Database、Codespaces、Dependabot Preview、GitHub Enterprise Importer、Packages、および Pages の追加の製品および機能にアクセスできます。

* **GitHub Enterprise Server** のユーザーは、Actions、Advanced Security、Advisory Database、Connect、Dependabot Preview、GitHub Enterprise Importer、Packages、Pages、および SQL Server Images の追加の製品および機能にアクセスできます。

[アクション](#actions)
----------

GitHub Actions を使用すると、カスタム ソフトウェア開発ライフサイクル ワークフローを GitHub リポジトリに直接作成することができます。 Actions は使用量ベースで請求されます。 [Actions のドキュメント](/ja/actions)には、コンピューティング量とストレージ量 (アカウント プランによって異なります)、Actions の分単位の使用状況を監視し、使用制限を設定する方法などの詳細が含まれています。

Actions および Actions 製品またはサービスの要素は、「契約」、「[GitHub 利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)」、または [Actions ドキュメント](/ja/actions/learn-github-actions/usage-limits-billing-and-administration)に規定されている GitHub Actions サービスの制限に違反して使用することはできません。 さらに、Action が自己ホスト型のランナーを使用しているかどうかに関係なく、Action は次の目的には使用しないでください。

* クリプトマイニング、
* サービス、デバイス、データ、アカウント、またはネットワーク ([GitHub バグ報奨金プログラム](https://bounty.github.com)によって承認されたものを除く) に対する中断、取得、または不正アクセスの試み、
* Actions 製品またはサービス、または Actions 製品またはサービスの要素を商業目的で提供するスタンドアロンまたは統合されたアプリケーションまたはサービスの提供、
* 当社のサーバーに負担をかけるアクティビティで、その負担がユーザーに提供される利益に見合わない場合 (たとえば、Actions をコンテンツ配信ネットワークまたはサーバーレス アプリケーションの一部として使用しないでください。ただし、利益の小さい Action でも負荷が小さければ問題ありません)、または、
* GitHub でホストされるランナーを使用している場合、GitHub Actions が使用されているリポジトリに関連付けられているソフトウェア プロジェクトの運用、テスト、デプロイ、または公開とは無関係のその他のアクティビティ。

これらの制限の違反および GitHub Actions の乱用を防止するために、GitHub はお客様の GitHub Actions の使用を監視する場合があります。 GitHub Actions の不正使用により、ジョブの終了、GitHub Actions の使用能力の制限、本条件に違反する方法で Actions を実行するために作成されたリポジトリの無効化、または場合によっては GitHub アカウントの停止または終了につながる可能性があります。

*開発およびテストを目的とした使用*

お客様は、お客様のアプリケーションの開発およびテストのためにのみ、GitHub Actions にアクセスして使用することができます。 ライセンスを取得した 1 名のユーザーのみが、Actions により提供される仮想マシンにいつでもアクセスすることができます。

*認定開発者*

お客様は、Actions に含まれる Apple ソフトウェアに関して、お客様の認定開発者として GitHub を指名します。 GitHub は、Actions に含まれるかかるソフトウェアの条件を遵守する責任を負い、Actions の一部としてアクセスされる Apple の秘密情報を秘密として保持します。

*第三者リポジトリ サービスへのアクセス*

お客様は、お客様の第三者リポジトリ サービス アカウントへのアクセスを GitHub に許諾した場合、GitHub に対し、GitHub Actions を提供する目的で、お客様のパブリックおよびプライベート リポジトリのコンテンツを含め、お客様のアカウントを精査する権限を付与します。

*GitHub Actions での自己ホスト型のランナー*

自己ホスト型のランナーを使用する場合、自動更新をオフにすることができますが、GitHub は重要なセキュリティ更新の選択を上書きする権利を留保します。

[Advanced Security](#advanced-security)
----------

GitHub では、Advanced Security ライセンスの下で顧客が追加のセキュリティ機能を利用できるようにしています。 これらの機能には、コード スキャン、シークレット スキャン、依存関係のレビューなどがあります。 詳細については、[Advanced Security のドキュメント](/ja/get-started/learning-about-github/about-github-advanced-security)を参照してください。

Advanced Security は、「一意のコミッター」ごとにライセンスされます。 「一意のコミッター」とは、GitHub Enterprise、GitHub Enterprise Cloud、または GitHub Enterprise Server のライセンスを取得し、GitHub Advanced Security 機能を有効にしたリポジトリに直前の 90 日以内にコミットしたユーザーのことです。 お客様は、一意のコミッターごとに 1 つの GitHub Advanced Security User ライセンスを取得しなければなりません。 GitHub Advanced Security は、お客様によって、またはお客様のために開発されたコードベースでのみ使用できます。 GitHub Enterprise Cloud ユーザーの場合、一部の Advanced Security 機能では GitHub Actions の使用も必要です。

GitHub Advanced Security を使用したシークレット スキャンの場合、パートナー パターンの自動有効性チェックをオプトインすると、公開された第三者のトークンが関連するパートナーと共有され、トークンの有効性に関する詳細情報が提供される場合があります。 すべてのパートナーが米国に拠点を置いているわけではありません。 [シークレット スキャン パターンのドキュメント](/ja/enterprise-cloud@latest/code-security/secret-scanning/introduction/supported-secret-scanning-patterns)には、有効性チェックをサポートするパートナーの詳細が記載されています。

[Advisory Database](#advisory-database)
----------

GitHub Advisory Database を使用すると、GitHub のオープン ソース プロジェクトに影響を与える脆弱性を表示または検索できます。

*当社へのライセンス付与*

当社では、GitHub Advisory Database へのお客様の投稿を [National Vulnerability Database](https://nvd.nist.gov/) などのパブリック ドメイン データセットに提出し、セキュリティ リサーチャー、オープン ソース コミュニティ、業界、および一般の人々が使用できるように、オープンな条件の下で GitHub Advisory Database をライセンスする法的権利が必要です。 お客様は、GitHub Advisory Database への投稿を[クリエイティブ コモンズ ゼロ ライセンス](https://creativecommons.org/publicdomain/zero/1.0/)の下でリリースすることに同意するものとします。

*GitHub Advisory Database へのライセンス*

GitHub Advisory Database は [クリエイティブ コモンズ表示 4.0 ライセンス](https://creativecommons.org/licenses/by/4.0/)の下でライセンスされています。 表示の条件は、<https://github.com/advisories> の GitHub Advisory Database、または使用される個々の GitHub Advisory Database 記録にリンクし、<https://github.com/advisories> による接頭辞を付けることで満たすことができます。

[Codespaces](#codespaces)
----------

*注: リポジトリで . を押すか、github.dev に直接移動することで利用できる github.dev サービスには、GitHub のベータ サービス使用条件が適用されます。*

GitHub Codespaces を使用すると、GitHub リポジトリ内のコードを使用して、ブラウザーからコードを直接開発できます。 Codespaces および Codespaces サービスの要素は、本契約または「利用規約」に違反して使用することはできません。 また、Codespaces は次の目的には使用しないでください。

* クリプトマイニング、
* サービス、デバイス、データ、アカウント、またはネットワーク (GitHub バグ報奨金プログラムによって承認されたものを除く) に対する中断、取得、または不正アクセスの試みのために当社のサーバーを使用すること、
* 商用目的で Codespaces または Codespaces の要素を提供するスタンドアロンまたは統合されたアプリケーションまたはサービスの提供、
* 当社のサーバーに負担をかけるアクティビティで、その負担がユーザーに提供される利益に見合わない場合 (たとえば、Codespaces をコンテンツ配信ネットワークとして、サーバーレス アプリケーションの一部として、またはあらゆる種類の本番環境向けアプリケーションをホストするために使用しないでください)、または、
* GitHub Codespaces が開始されたリポジトリに関連付けられているソフトウェア プロジェクトの開発またはテストとは無関係のその他のアクティビティ。

これらの制限の違反および GitHub Codespaces の乱用を防止するために、GitHub はお客様の GitHub Codespaces の使用を監視する場合があります。 GitHub Codespaces の不正使用により、Codespaces へのアクセスが終了したり、GitHub Codespaces を使用する能力が制限されたり、本条件に違反する方法で Codespaces を実行するために作成されたリポジトリが無効になったりする可能性があります。

Codespaces を使用すると、Microsoft Visual Studio Marketplace から拡張機能 (以下「Marketplace 拡張機能」といいます) を読み込んで、開発環境で使用することができます (たとえば、コードが記述されているプログラミング言語を処理する場合など)。 Marketplace 拡張機能は、Visual Studio Marketplace に記載されている独自の個別の使用条件と、<https://aka.ms/vsmarketplace-ToU> にある使用条件に基づいてライセンス供与されます。 GitHub は、Marketplace 拡張機能に関していかなる種類の保証も行わず、「お客様のコンテンツ」へのアクセスを許可された Marketplace 拡張機能の第三者作成者の行為について責任を負いません。 Codespaces では、devcontainer 機能を使用して環境にソフトウェアを読み込むこともできます。 このようなソフトウェアは、それに付随する個別の使用条件に基づいて提供されます。 第三者のアプリケーションの使用は、お客様ご自身の責任において行ってください。

一般に利用可能なバージョンの Codespaces は、現在、米国政府のお客様にはご利用いただけません。 米国政府のお客様は、Codespaces ベータ プレビューを別の条件で引き続き使用することができます。 [ベータ プレビューの条件](/ja/site-policy/github-terms/github-terms-of-service#j-beta-previews)を参照してください。

[競合する製品またはサービスのベンチマーク](#competitive-benchmarking)
----------

GitHub の製品またはサービスと競合する製品またはサービスを提供する場合、その GitHub 製品またはサービスを使用することにより、競合する製品またはサービスに適用される条件に従って、競合する製品またはサービスの使用とベンチマーク テストにおける GitHub に関する制限に同意し、これを放棄するものとします。 使用条件に従ってかかる制限を放棄する意図がない場合、その GitHub 製品またはサービスを使用することはできません。

[Connect](#connect)
----------

GitHub Connect を使用すると、GitHub Enterprise Server デプロイと、GitHub.com 上の GitHub Enterprise Cloud の組織または Enterprise アカウントとの間で特定の機能やデータを共有できます。 GitHub Connect を有効にするには、GitHub Enterprise Cloud または GitHub.com に少なくとも 1 つのアカウントと、GitHub Enterprise Server の 1 つのライセンス デプロイを持っていなければなりません。 Connect を介した GitHub Enterprise Cloud または GitHub.com の使用には、お客様が GitHub Enterprise Cloud または GitHub.com のライセンスを供与する条件が適用されます。 個人データの使用には、「[GitHub のプライバシーに関する声明](/ja/site-policy/privacy-policies/github-privacy-statement)」が適用されます。

[GitHub Copilot](#github-copilot)
----------

GitHub Copilot Business および Copilot エンタープライズライセンスのライセンス所有者の場合、GitHub Copilot の使用には、[GitHub Copilot 製品固有の条件](https://github.com/customer-terms/github-copilot-product-specific-terms)が適用されます。

GitHub Copilot の個々のライセンス所有者の場合、GitHub Copilot の使用は次の条件によって管理されます: コード エディターで GitHub Copilot を使用するには、そのエディターに GitHub Copilot 拡張機能をインストールする必要があります。 CLI (コマンド ライン インターフェイス) で GitHub Copilot を使用するには、GitHub Copilot CLI 拡張機能をインストールする必要があります。 GitHub Mobile で GitHub Copilot チャットを使用するには、GitHub Mobile アプリケーションをインストールする必要があります。 GitHub.com で GitHub Copilot を使用するには、GitHub.com にアクセスする必要があります。 GitHub Copilot 使って書いたコード (「**お客様のコード**」) は、GitHub.com にアップロードするまで、本契約上の「コンテンツ」ではありません。

GitHub Copilot 拡張機能 (拡張機能) を使用して GitHub Copilot をカスタマイズする場合、拡張機能の利用規約とプライバシー ポリシーが適用される場合があります。

GitHub Copilot からお客様に返されるコード、関数およびその他のアウトプットは、「**Suggestions**」と呼ばれます。 GitHub は提案を所有していません。 お客様は、コードの所有権を保持し、コードに含める提案に対する責任を負います。

*許可される使用*

GitHub Copilot の使用は、GitHub [利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)が適用されます。 例えば、GitHub.com 上の GitHub 利用規約で違法または禁止されているコンテンツを GitHub Copilot に促すことはできません。

*データ*

GitHub Copilot は、(i) 設定と使用する GitHub Copilot Service に応じて、コードのスニペットを収集し、(ii) アカウントに関連付けられている使用する GitHub Copilot Service を通じて追加の使用状況に関する情報を収集する場合があります。 これには [GitHub のプライバシーに関する声明](/ja/site-policy/privacy-policies/github-privacy-statement)で言及されているように、個人データが含まれる場合があります。 GitHub Copilot データの収集と使用については、[GitHub Copilotトラスト センター](https://resources.github.com/copilot-trust-center/) で詳しく説明されています。

[GitHub Enterprise Importer](#github-enterprise-importer)
----------

Importer は、GitHub プラットフォームにインポートする他のソースからデータをエクスポートするためのフレームワークです。 Importer は「現状のまま」提供されます。

[npm](#npm)
----------

npm は、ソフトウェア パッケージをプライベートまたはパブリックにホストし、プロジェクトの依存関係としてパッケージを使用できるようにするソフトウェア パッケージ ホスティング サービスです。 npm は JavaScript エコシステムの記録のレジストリです。 npm パブリック レジストリは無料で使用できますが、プライベート パッケージを公開したり、チームを使用してプライベート パッケージを管理したりする場合は、お客様宛に請求されます。 [npm ドキュメント](https://docs.npmjs.com/)には、アカウント タイプの制限と、[プライベート パッケージ](https://docs.npmjs.com/about-private-packages)および[組織](https://docs.npmjs.com/organizations)の管理方法の詳細が記載されています。 npm レジストリの許容可能な使用については、[オープン ソースの条件](https://www.npmjs.com/policies/open-source-terms)で概説されています。 また、npm の [solo](https://www.npmjs.com/policies/solo-plan) と [org](https://www.npmjs.com/policies/orgs-plan) の両方のプランに補足の条件があります。 npm の利用には、npm [使用条件](https://www.npmjs.com/policies/terms)が適用されます。

[パッケージ](#packages)
----------

GitHub Packages は、ソフトウェア パッケージをプライベートまたはパブリックにホストし、プロジェクトの依存関係としてパッケージを使用できるようにするソフトウェア パッケージ ホスティング サービスです。 GitHub Packages は使用量ベースで請求されます。 [Packages のドキュメント](/ja/packages/learn-github-packages/introduction-to-github-packages)には、帯域幅とストレージ量 (アカウント プランによって異なります)、Packages の分単位の使用状況を監視し、使用制限を設定する方法などの詳細が含まれています。 Packages の帯域幅使用量は「[GitHub 利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)」によって制限されます。

[ページ](#pages)
----------

各アカウントには、[GitHub Pages の静的ホスティング サービス](/ja/pages/getting-started-with-github-pages/about-github-pages)へのアクセス権があります。 GitHub Pages は静的な Web ページをホストするためのサービスですが、主に個人および組織のプロジェクトのためのショーケースの役割を担っています。

GitHub Pages は、オンライン ビジネス、e コマース サイト、主に商取引の円滑化または商用のサービスとしてのソフトウェア (SaaS) の提供のいずれかを目的とする、その他の Web サイトを運営するための無料の Web ホスティング サービスとしての使用を意図したものではなく、またそのような使用を許可するものでもありません。 Pages では、寄付のボタンやクラウドファンディングのリンクなど、収益化の行為が一部認められています。

*Bandwidth および使用制限*

GitHub Pages は、特定の帯域幅を対象とし、使用制限が適用されるため、一定以上の高帯域の利用には適していない場合があります。 詳細については、[GitHub Pages の制限](/ja/pages/getting-started-with-github-pages/about-github-pages)を参照してください。

*禁止されている用途*

GitHub Pages は、契約、「GitHub [利用規約](/ja/site-policy/acceptable-use-policies/github-acceptable-use-policies)」、または[Pages ドキュメント](/ja/pages/getting-started-with-github-pages/about-github-pages#guidelines-for-using-github-pages)に規定されている GitHub Pages サービスの制限に違反して使用することはできません。

お客様の使用または使用目的がこれらのカテゴリに分類されるかどうかについてご質問がある場合は、[GitHub Support ポータル](https://support.github.com/)を通じてお問い合わせください。 GitHub はいつでも、責任を負うことなく GitHub の任意のサブドメインを回収する権利を常に留保します。

*教育演習*

GitHub Pages を使用して、学習演習として既存の Web サイトのコピーの作成は禁止されていません。 ただし、自分でコードを記述する必要があります。サイトはユーザー データを収集する必要はありません。また、プロジェクトが元のプロジェクトに関連付けられていないので、教育目的でのみ作成されたものであることを示す目立つ免責事項をサイトに掲載する必要があります。

[プレビュー](#previews)
----------

プレビューとは、下見、評価、デモ、試用などの目的のために提供されているソフトウェア、オンライン サービス、および追加の製品および機能、またはそれらのプレリリース版 (アルファ版、ベータ版、早期アクセス版など) を意味します。 契約にプレビューに関する条件が含まれていない場合は、次の条件が適用されます。 GitHub は、プレビュー版の非稼働インスタンスを使用する限定的な権利を付与します。 プレビューは、「現状有姿」、「瑕疵があってもそれらを含む状態で」、かつ「提供可能な状態で」提供されます。 GitHub は、随時予告なくプレビューを変更または中止することがあります。 プライベート プレビューに関して当社から提供された情報は、GitHub の秘密保持と見なされます。 プレビューに関するコメントや提案を提供することをお客様が選択した場合、当社はいかなる種類の責務も負うことなく、そのフィードバックをいかなる目的にも使用することができます。 GitHub の最大責任限度額は 5,00 米ドルまでの直接損害に制限されます。 GitHub は、お客様のプレビューの使用から生じる第三者による申し立てについて、お客様を防御、補償、または無害に保つ責務を負いません。

[Sponsors プログラム](#sponsors-program)
----------

GitHub Sponsors により、開発者コミュニティは、日々活用しているオープン ソース プロジェクトの設計、構築、維持に携わる人々や組織を、GitHub で直接、経済的に支援できます。 支援対象開発者になるには、[GitHub Sponsors プログラムの追加条件](/ja/site-policy/github-terms/github-sponsors-additional-terms)に同意しなければなりません。

[SQL Server Images](#sql-server-images)
----------

お客様は、Linux ファイル用の Microsoft SQL Server Standard Edition コンテナー イメージ (以下「SQL Server Images」といいます) をダウンロードできます。 お客様の本ソフトウェアの使用権が終了した場合は、SQL Server Images をアンインストールしなければなりません。 また、Microsoft Corporation は、随時 SQL Server Images を無効にすることができます。

[GitHub モデル](#github-models)
----------

GitHub モデルは、GitHub.com で人工知能モデルを学習、試用、テストできる機能です。 GitHub モデルには、[GitHub Marketplace](https://github.com/marketplace) 経由でアクセスできます。 GitHub モデルの詳細については、「[AI モデルを使用したプロトタイプ作成](/ja/github-models/prototyping-with-ai-models)」に関するページを参照してください。

この機能の使用は、モデルとモデル ライセンスをホストしている会社の条件に従います。

{"resolvedServerColorMode":"day"}
