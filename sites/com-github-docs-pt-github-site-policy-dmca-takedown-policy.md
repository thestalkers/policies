DMCA Takedown Policy - GitHub Docs

[Skip to main content](#main-content)

[](/pt)[GitHub Docs](/pt)

Publicamos atualizações frequentes em nossa documentação, e a tradução desta página ainda pode estar em andamento. Para obter as informações mais recentes, acesse a [documentação em inglês](/en). Se houver problemas com a tradução desta página, [entre em contato conosco](https://github.com/contact?form[subject]=translation%20issue%20on%20docs.github.com&form[comments]=).

DMCA Takedown Policy
==========

[Neste artigo](/site-policy/content-removal-policies/dmca-takedown-policy#in-this-article)
----------

* [What Is the DMCA?](#what-is-the-dmca)

* [DMCA Notices In a Nutshell](#dmca-notices-in-a-nutshell)

* [A. Como realmente funciona?](#a-how-does-this-actually-work)

* [B. O que significa Bifurcação? (ou O que é uma Bifurcação?)](#b-what-about-forks-or-whats-a-fork)

* [C. What about Circumvention Claims?](#c-what-about-circumvention-claims)

* [D. What If I Inadvertently Missed the Window to Make Changes?](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)

* [E. Transparency](#e-transparency)

* [F. Repeated Infringement](#f-repeated-infringement)

* [G. Submitting Notices](#g-submitting-notices)

* [Learn More and Speak Up](#learn-more-and-speak-up)

Welcome to GitHub's Guide to the Digital Millennium Copyright Act, commonly known as the "DMCA." This page is not meant as a comprehensive primer to the statute. However, if you've received a DMCA takedown notice targeting content you've posted on GitHub or if you're a rights-holder looking to issue such a notice, this page will hopefully help to demystify the law a bit as well as our policies for complying with it.

(If you just want to submit a notice, you can skip to "[G. Submitting Notices](#g-submitting-notices).")

Como em todas as questões jurídicas, é sempre melhor consultar um profissional sobre suas dúvidas ou situação específica. Incentivamos a fazê-lo antes de tomar quaisquer medidas que possam impactar seus direitos. Este guia não é um aconselhamento jurídico e não deve ser tomado como tal.

[](#what-is-the-dmca)What Is the DMCA?
----------

In order to understand the DMCA and some of the policy lines it draws, it's perhaps helpful to consider life before it was enacted.

The DMCA provides a safe harbor for service providers that host user-generated content. Since even a single claim of copyright infringement can carry statutory damages of up to $150,000, the possibility of being held liable for user-generated content could be very harmful for service providers. With potential damages multiplied across millions of users, cloud-computing and user-generated content sites like YouTube, Facebook, or GitHub probably [never would have existed](https://arstechnica.com/tech-policy/2015/04/how-the-dmca-made-youtube/) without the DMCA (or at least not without passing some of that cost downstream to their users).

The DMCA addresses this issue by creating a [copyright liability safe harbor](https://www.copyright.gov/title17/92chap5.html#512) for internet service providers hosting allegedly infringing user-generated content. Essentially, so long as a service provider follows the DMCA's notice-and-takedown rules, it won't be liable for copyright infringement based on user-generated content. Because of this, it is important for GitHub to maintain its DMCA safe-harbor status.

The DMCA also prohibits the [circumvention of technical measures](https://www.copyright.gov/title17/92chap12.html) that effectively control access to works protected by copyright.

[](#dmca-notices-in-a-nutshell)DMCA Notices In a Nutshell
----------

The DMCA provides two simple, straightforward procedures that all GitHub users should know about: (i) a [takedown-notice](/pt/articles/guide-to-submitting-a-dmca-takedown-notice) procedure for copyright holders to request that content be removed; and (ii) a [counter-notice](/pt/articles/guide-to-submitting-a-dmca-counter-notice) procedure for users to get content re-enabled when content is taken down by mistake or misidentification.

DMCA [takedown notices](/pt/articles/guide-to-submitting-a-dmca-takedown-notice) are used by copyright owners to ask GitHub to take down content they believe to be infringing. If you are a software designer or developer, you create copyrighted content every day. If someone else is using your copyrighted content in an unauthorized manner on GitHub, you can send us a DMCA takedown notice to request that the infringing content be changed or removed.

On the other hand, [counter notices](/pt/articles/guide-to-submitting-a-dmca-counter-notice) can be used to correct mistakes. Maybe the person sending the takedown notice does not hold the copyright or did not realize that you have a license or made some other mistake in their takedown notice. Since GitHub usually cannot know if there has been a mistake, the DMCA counter notice allows you to let us know and ask that we put the content back up.

The DMCA notice and takedown process should be used only for complaints about copyright infringement. Notices sent through our DMCA process must identify copyrighted work or works that are allegedly being infringed. The process cannot be used for other complaints, such as complaints about alleged [trademark infringement](/pt/articles/github-trademark-policy) or [sensitive data](/pt/articles/github-sensitive-data-removal-policy); we offer separate processes for those situations.

[](#a-how-does-this-actually-work)A. Como realmente funciona?
----------

The DMCA framework is a bit like passing notes in class. The copyright owner hands GitHub a complaint about a user. If it's written correctly, we pass the complaint along to the user. If the user disputes the complaint, they can pass a note back saying so. GitHub exercises little discretion in the process other than determining whether the notices meet the minimum requirements of the DMCA. Cabe às partes (e aos seus advogados) avaliar o mérito das suas reivindicações, tendo em conta que os avisos devem ser feitos corretamente sob pena de perjúrio.

Here are the basic steps in the process.

1. **Copyright Owner Investigates.** A copyright owner should always conduct an initial investigation to confirm both (a) that they own the copyright to an original work and (b) that the content on GitHub is unauthorized and infringing. This includes confirming that the use is not protected as [fair use](https://www.lumendatabase.org/topics/22). A particular use may be fair if it only uses a small amount of copyrighted content, uses that content in a transformative way, uses it for educational purposes, or some combination of the above. Como o código se presta naturalmente a tais usos, cada caso de utilização é diferente, e deve ser considerado separadamente.

   >
   >
   > **Example:** An employee of Acme Web Company finds some of the company's code in a GitHub repository. Acme Web Company licenses its source code out to several trusted partners. Before sending in a take-down notice, Acme should review those licenses and its agreements to confirm that the code on GitHub is not authorized under any of them.
   >
   >

2. **Copyright Owner Sends A Notice.** After conducting an investigation, a copyright owner prepares and sends a [takedown notice](/pt/articles/guide-to-submitting-a-dmca-takedown-notice) to GitHub. Assuming the takedown notice is sufficiently detailed according to the statutory requirements (as explained in the [how-to guide](/pt/articles/guide-to-submitting-a-dmca-takedown-notice)), we will [post the notice](#d-transparency) to our [public repository](https://github.com/github/dmca) and pass the link along to the affected user.

3. **GitHub Asks User to Make Changes.** If the notice alleges that the entire contents of a repository infringe, or a package infringes, we will skip to Step 6 and disable the entire repository or package expeditiously. Otherwise, because GitHub cannot disable access to specific files within a repository, we will contact the user who created the repository and give them approximately 1 business day to delete or modify the content specified in the notice. We'll notify the copyright owner if and when we give the user a chance to make changes. Because packages are immutable, if only part of a package is infringing, GitHub would need to disable the entire package, but we permit reinstatement once the infringing portion is removed.

4. **User Notifies GitHub of Changes.** If the user chooses to make the specified changes, they *must* tell us so within the window of approximately 1 business day. If they don't, we will disable the repository (as described in Step 6). If the user notifies us that they made changes, we will verify that the changes have been made and then notify the copyright owner.

5. **Copyright Owner Revises or Retracts the Notice.** If the user makes changes, the copyright owner must review them and renew or revise their takedown notice if the changes are insufficient. GitHub will not take any further action unless the copyright owner contacts us to either renew the original takedown notice or submit a revised one. If the copyright owner is satisfied with the changes, they may either submit a formal retraction or else do nothing. GitHub will interpret silence longer than two weeks as an implied retraction of the takedown notice.

6. **GitHub May Disable Access to the Content.** GitHub will disable a user's content if: (i) the copyright owner has alleged copyright over the user's entire repository or package (as noted in Step 3); (ii) the user has not made any changes after being given an opportunity to do so (as noted in Step 4); or (iii) the copyright owner has renewed their takedown notice after the user had a chance to make changes. If the copyright owner chooses instead to *revise* the notice, we will go back to Step 2 and repeat the process as if the revised notice were a new notice.

7. **User May Send A Counter Notice.** We encourage users who have had content disabled to consult with a lawyer about their options. If a user believes that their content was disabled as a result of a mistake or misidentification, they may send us a [counter notice](/pt/articles/guide-to-submitting-a-dmca-counter-notice). As with the original notice, we will make sure that the counter notice is sufficiently detailed (as explained in the [how-to guide](/pt/articles/guide-to-submitting-a-dmca-counter-notice)). If it is, we will [post it](#d-transparency) to our [public repository](https://github.com/github/dmca) and pass the notice back to the copyright owner by sending them the link.

8. **Copyright Owner May File a Legal Action.** If a copyright owner wishes to keep the content disabled after receiving a counter notice, they will need to initiate a legal action seeking a court order to restrain the user from engaging in infringing activity relating to the content on GitHub. In other words, you might get sued. If the copyright owner does not give GitHub notice within 10-14 days, by sending a copy of a valid legal complaint filed in a court of competent jurisdiction, GitHub will re-enable the disabled content.

[](#b-what-about-forks-or-whats-a-fork)B. O que significa Bifurcação? (ou O que é uma Bifurcação?)
----------

Um dos melhores recursos do GitHub é a possibilidade de os usuários "bifurcarem" repositórios uns dos outros. O que isso significa? Basicamente, isso significa que os usuários podem fazer uma cópia de um projeto no GitHub em seus próprios repositórios. Conforme a licença ou a lei permitirem, os usuários podem fazer alterações nessa bifurcação para ou fazer push de volta para o projeto principal ou simplesmente manter como sua própria variação de um projeto. Each of these copies is a "[fork](/pt/articles/github-glossary#fork)" of the original repository, which in turn may also be called the "parent" of the fork.

GitHub *will not* automatically disable forks when disabling a parent repository. This is because forks belong to different users, may have been altered in significant ways, and may be licensed or used in a different way that is protected by the fair-use doctrine. O GitHub não realiza nenhuma investigação independente sobre as bifurcações. We expect copyright owners to conduct that investigation and, if they believe that the forks are also infringing, expressly include forks in their takedown notice.

Em casos raros, você pode estar alegando a violação de direitos autorais em um repositório completo que está sendo ativamente bifurcado. Se, no momento em que você enviou a notificação, você identificou todas as bifurcações existentes do repositório como supostamente violadas, nós processaríamos uma reivindicação válida contra todas as bifurcações dessa rede no momento em que processamos a notificação. Nós faríamos isso tendo em conta a probabilidade de todas as novas bifurcações criadas conterem o mesmo conteúdo. In addition, if the reported network that contains the allegedly infringing content is larger than one hundred (100) repositories and thus would be difficult to review in its entirety, we may consider disabling the entire network if you state in your notice that, "Based on the representative number of forks I have reviewed, I believe that all or most of the forks are infringing to the same extent as the parent repository." A sua declaração juramentada será aplicada a esta declaração.

[](#c-what-about-circumvention-claims)C. What about Circumvention Claims?
----------

The DMCA prohibits the [circumvention of technical measures](https://www.copyright.gov/title17/92chap12.html) that effectively control access to works protected by copyright. Given that these types of claims are often highly technical in nature, GitHub requires claimants to provide [detailed information about these claims](/pt/github/site-policy/guide-to-submitting-a-dmca-takedown-notice#complaints-about-anti-circumvention-technology), and we undertake a more extensive review.

Uma alegação de circunvenção deve incluir os pormenores a seguir sobre as medidas técnicas em vigor e a forma como o projeto acusado as contorna. Principalmente, o aviso ao GitHub deve incluir declarações detalhadas que descrevem:

1. Quais são as medidas técnicas;
2. Como controlam, de forma eficaz, o acesso ao material protegido por direitos autorais; e
3. O modo como o projecto acusado foi concebido para contornar as medidas de proteção tecnológica anteriormente descritas.

GitHub will review circumvention claims closely, including by both technical and legal experts. In the technical review, we will seek to validate the details about the manner in which the technical protection measures operate and the way the project allegedly circumvents them. In the legal review, we will seek to ensure that the claims do not extend beyond the boundaries of the DMCA. In cases where we are unable to determine whether a claim is valid, we will err on the side of the developer, and leave the content up. If the claimant wishes to follow up with additional detail, we would start the review process again to evaluate the revised claims.

Where our experts determine that a claim is complete, legal, and technically legitimate, we will contact the repository owner and give them a chance to respond to the claim or make changes to the repo to avoid a takedown. If they do not respond, we will attempt to contact the repository owner again before taking any further steps. In other words, we will not disable a repository based on a claim of circumvention technology without attempting to contact a repository owner to give them a chance to respond or make changes first. If we are unable to resolve the issue by reaching out to the repository owner first, we will always be happy to consider a response from the repository owner even after the content has been disabled if they would like an opportunity to dispute the claim, present us with additional facts, or make changes to have the content restored. When we need to disable content, we will ensure that repository owners can export their issues and pull requests and other repository data that do not contain the alleged circumvention code to the extent legally possible.

Please note, our review process for circumvention technology does not apply to content that would otherwise violate our Acceptable Use Policy restrictions against sharing unauthorized product licensing keys, software for generating unauthorized product licensing keys, or software for bypassing checks for product licensing keys. Although these types of claims may also violate the DMCA provisions on circumvention technology, these are typically straightforward and do not warrant additional technical and legal review. Nonetheless, where a claim is not straightforward, for example in the case of jailbreaks, the circumvention technology claim review process would apply.

When GitHub processes a DMCA takedown under our circumvention technology claim review process, we will offer the repository owner a referral to receive independent legal consultation through [GitHub’s Developer Defense Fund](https://github.blog/2021-07-27-github-developer-rights-fellowship-stanford-law-school/) at no cost to them.

[](#d-what-if-i-inadvertently-missed-the-window-to-make-changes)D. What If I Inadvertently Missed the Window to Make Changes?
----------

We recognize that there are many valid reasons that you may not be able to make changes within the window of approximately 1 business day we provide before your repository gets disabled. Maybe our message got flagged as spam, maybe you were on vacation, maybe you don't check that email account regularly, or maybe you were just busy. We get it. If you respond to let us know that you would have liked to make the changes, but somehow missed the first opportunity, we will re-enable the repository one additional time for approximately 1 business day to allow you to make the changes. Again, you must notify us that you have made the changes in order to keep the repository enabled after that window of approximately 1 business day, as noted above in [Step A.4](#a-how-does-this-actually-work). Please note that we will only provide this one additional chance.

[](#e-transparency)E. Transparency
----------

We believe that transparency is a virtue. The public should know what content is being removed from GitHub and why. An informed public can notice and surface potential issues that would otherwise go unnoticed in an opaque system. We post redacted copies of any legal notices we receive (including original notices, counter notices or retractions) at <https://github.com/github/dmca>. We will not publicly publish your personal contact information; we will remove personal information (except for usernames in URLs) before publishing notices. We will not, however, redact any other information from your notice unless you specifically ask us to. Here are some examples of a published [notice](https://github.com/github/dmca/blob/master/2014/2014-05-28-Delicious-Brains.md) and [counter notice](https://github.com/github/dmca/blob/master/2014/2014-05-01-Pushwoosh-SDK-counternotice.md) for you to see what they look like. When we remove content, we will post a link to the related notice in its place.

Please also note that, although we will not publicly publish unredacted notices, we may provide a complete unredacted copy of any notices we receive directly to any party whose rights would be affected by it.

[](#f-repeated-infringement)F. Repeated Infringement
----------

It is the policy of GitHub, in appropriate circumstances and in its sole discretion, to disable and terminate the accounts of users who may infringe upon the copyrights or other intellectual property rights of GitHub or others.

[](#g-submitting-notices)G. Submitting Notices
----------

If you are ready to submit a notice or a counter notice:

* [How to Submit a DMCA Notice](/pt/articles/guide-to-submitting-a-dmca-takedown-notice)
* [How to Submit a DMCA Counter Notice](/pt/articles/guide-to-submitting-a-dmca-counter-notice)

[](#learn-more-and-speak-up)Learn More and Speak Up
----------

If you poke around the Internet, it is not too hard to find commentary and criticism about the copyright system in general and the DMCA in particular. While GitHub acknowledges and appreciates the important role that the DMCA has played in promoting innovation online, we believe that the copyright laws could probably use a patch or two—if not a whole new release. In software, we are constantly improving and updating our code. Think about how much technology has changed since 1998 when the DMCA was written. Doesn't it just make sense to update these laws that apply to software?

We don't presume to have all the answers. But if you are curious, here are a few links to scholarly articles and blog posts we have found with opinions and proposals for reform:

* [Unintended Consequences: Twelve Years Under the DMCA](https://www.eff.org/wp/unintended-consequences-under-dmca) (Electronic Frontier Foundation)
* [Statutory Damages in Copyright Law: A Remedy in Need of Reform](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=1375604) (William & Mary Law Review)
* [Is the Term of Protection of Copyright Too Long?](https://the1709blog.blogspot.com/2012/11/is-term-of-protection-of-copyright-too.html) (The 1709 Blog)
* [If We're Going to Change DMCA's 'Notice & Takedown,' Let's Focus on How Widely It's Abused](https://www.techdirt.com/articles/20140314/11350426579/if-were-going-to-change-dmcas-notice-takedown-lets-focus-how-widely-its-abused.shtml) (TechDirt)
* [Opportunities for Copyright Reform](https://www.cato-unbound.org/issues/january-2013/opportunities-copyright-reform) (Cato Unbound)
* [Fair Use Doctrine and the Digital Millennium Copyright Act: Does Fair Use Exist on the Internet Under the DMCA?](https://digitalcommons.law.scu.edu/lawreview/vol42/iss1/6/) (Santa Clara Law Review)

GitHub doesn't necessarily endorse any of the viewpoints in those articles. We provide the links to encourage you to learn more, form your own opinions, and then reach out to your elected representative(s) (e.g, in the [U.S. Congress](https://www.govtrack.us/congress/members) or [E.U. Parliament](https://www.europarl.europa.eu/meps/en/home)) to seek whatever changes you think should be made.
