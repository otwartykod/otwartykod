# [About Opensource licenses - Otwarty Kod](https://www.otwartykod.pl/)


Wybór odpowiedniej licencji:


Poniżej znajudje się krótkie podsumowanie najpopularniejszych licencji Open Source, to obraz pozwalający na podjęcie decyzji biznesowych co do wykorzystania poszczególnych licencji w projektach komercyjnych.


Licencje oznaczone jako liberalne z zasady nadają się do zastosowania w projektach biznesowych, natomiast te oznaczone jako „copyleft” – o ile nie jest to wyraźnym założeniem projektu – skutkują koniecznością uwolnienia kodu źródłowego.

Niemniej jednak w niektórych przypadkach możliwe jest łączenie kodu „copyleft” z kodem komercyjnym bez uszczerbku dla tego drugiego, choć wymaga to pewnej wirtuozerii zarówno po stronie deweloperów, jak i obsługujących ich prawników. 

[The Legal Side of Open Source | Open Source Guides](https://opensource.guide/legal/)

## Licencje
 
-   X11 (MIT)
-   ISC

-   GNU General Public License
-   GNU Lesser General Public License
-   GNU Affero General Public License
-   Apache 2.0

-   BSD 2-klauzulowa (FreeBSD)
-   BSD 3-klauzulowa

-   Eclipse Public License 2.0 (EPL)
-   Mozilla Public License 2.0 (MPL)
-   Microsoft Public License (Ms-PL)

-   Do What The F\*ck You Want To Public License 2.0 (WTFPL)
-   SIL Open Font License 1.1 (OFL)
-   Creative Commons Uznanie autorstwa 4.0 (CC BY 4.0)
 
## Co grozi za nieprawidłowe użycie otwartego oprogramowania?


[The Legal Side of Open Source | Open Source Guides](https://opensource.guide/legal/)

> **If you’re open sourcing a project for your company,** then definitely let them know. Your legal team probably already has policies for what open source license (and maybe additional contributor agreement) to use based on the company’s business requirements and expertise around ensuring your project complies with the licenses of its dependencies. If not, you and they are in luck! Your legal team should be eager to work with you to figure this stuff out. Some things to think about:
> 
> -   **Third party material:** Does your project have dependencies created by others or otherwise include or use others’ code? If these are open source, you’ll need to comply with the materials’ open source licenses. That starts with choosing a license that works with the third party open source licenses (see above). If your project modifies or distributes third party open source material, then your legal team will also want to know that you’re meeting other conditions of the third party open source licenses such as retaining copyright notices. If your project uses others’ code that doesn’t have an open source license, you’ll probably have to ask the third party maintainers to [add an open source license](https://choosealicense.com/no-license/#for-users), and if you can’t get one, stop using their code in your project.
>     
> -   **Trade secrets:** Consider whether there is anything in the project that the company does not want to make available to the general public. If so, you could open source the rest of your project, after extracting the material you want to keep private.
>     
> -   **Patents:** Is your company applying for a patent of which open sourcing your project would constitute [public disclosure](https://en.wikipedia.org/wiki/Public_disclosure)? Sadly, you might be asked to wait (or maybe the company will reconsider the wisdom of the application). If you’re expecting contributions to your project from employees of companies with large patent portfolios, your legal team may want you to use a license with an express patent grant from contributors (such as Apache 2.0 or GPLv3), or an additional contributor agreement (see above).
>     
> -   **Trademarks:** Double check that your project’s name [does not conflict with any existing trademarks](https://opensource.guide/starting-a-project/#avoiding-name-conflicts). If you use your own company trademarks in the project, check that it does not cause any conflicts. [FOSSmarks](http://fossmarks.org/) is a practical guide to understanding trademarks in the context of free and open source projects.
>     
> -   **Privacy:** Does your project collect data on users? “Phone home” to company servers? Your legal team can help you comply with company policies and external regulations.

+ [Choose an open source license | Choose a License](https://choosealicense.com/)




## [9 open source license best practices | Opensource.com](https://opensource.com/article/17/9/9-open-source-software-rules-startups)

Misuse of open source software can delay or derail investment and corporate exit opportunities. But you can easily comply with open source licenses if you follow these simple rules.

1.  **Don't use software without license terms.** 
Some software on the internet doesn't contain licensing notices, but that doesn't mean that it can be used freely. The people posting the software may not have complied with upstream licensing terms. Or the author of the software may not yet have applied a license to the software—open source or otherwise. "No license terms" means no license: You should either avoid using the software or ask the author to apply a permissive license.

2.  **Don't violate open source licenses.** 
Open source software use may be difficult for a software owner to track, but that does not mean use and noncompliance go unnoticed. Violating open source licenses can expose a startup to legal liability and public embarrassment, and can even compromise investments or acquisitions. It can also cause potential customers to refuse to buy your products out of fear of downstream liability. Developers have taken great effort to make their software open source—including foregoing licensing fees. Misuse of the software is unfair to those developers and harms the innovation they hoped to facilitate.

3.  **Keep track of what software you are using.** 
Someday you will have to provide a list of the open source software you are using. Potential investors and acquirers will ask for the list, and maintaining an up-to-date list will save you considerable time and effort when that request comes. Most open source software downloads include a "license.txt" or "copying.txt" file. Keep a copy of that license and note what software it covers. Most startups track licensed software in a simple spreadsheet.

4.  **Understand permissive and copyleft licenses.** 
Open source licenses fall broadly into two types: permissive (BSD, MIT, and Apache) and copyleft (GPL, LGPL, Eclipse Public License, Mozilla Public License, and Common Development and Distribution License). Most companies—and their customers—have no legal concerns over using software under permissive licenses. Complying with copyleft licenses takes more care, however, and may be inconsistent with certain plans for keeping software proprietary.

5.  **Comply with notice requirements.** 
Whether permissive or copyleft, all open source licenses have notice requirements. 
Typically, this means you need to include a copy of the applicable license when distributing open source software. It's generally not sufficient to merely include a link to or short form of the license. It's important to develop a license notice delivery strategy that complies with most open source licenses without confusing or alienating your customers.

6.  **Understand which open source licenses work with distributed software.** 
Most open source licenses—other than the Affero GPL—have no conditions for software-as-a-service (SaaS). For distributed elements of SaaS and cloud systems (like JavaScript) or distributed software (including mobile apps and beta tests), you can use software under permissive licenses, but you will need to be especially careful before using software under copyleft licenses. Use GPL software only if it executes 100% in its own process with no linked code—don't believe myths about compliance by dynamically linking to the GPL code or making the customer download the GPL software. Use LGPL software only as a dynamically linked library. And use other copyleft software only if you have not modified the API. Distribution in compliance with the rules of mobile app marketplaces may be incompatible with compliance with certain copyleft licenses (like the GPL or LGPL).

7.  **Do not contribute to or release open source software before consulting an attorney.** 
Contributing to and releasing open source software can be a boon for the public, but it may not be the right choice for your business. Once you make a contribution or release, any intellectual property rights you had in the software will be unlikely to form the basis for valuation of your company. Your lawyer can help you understand your choices between degrees of proprietary and open source software and guide this important business decision.

8.  **Ensure your employees and third-party developers follow these rules.** 
Whether an open source violation is caused by your employee or a third-party contractor, the resulting legal and publicity issues will fall in your lap. You can avoid these issues through proper training and tracking of open source software.

9.  **Plan for the future.** 
Startup business models can change rapidly, and a SaaS model can quickly become a distributed software model. Following the rules for distributed software, regardless of your current model, can provide flexibility for shifting to a distributed software model without having to remove certain open source software and change associated functionalities.

## Licencja MIT
[Open Source - trochę dłuższa analiza (część pierwsza) | LinkedIn](https://www.linkedin.com/pulse/open-source-troch%C4%99-d%C5%82u%C5%BCsza-analiza-cz%C4%99%C5%9B%C4%87-pierwsza-marcin-maruta/)

Non-copyleft - MIT, BSD, Apache 2.0 - licencja wymaga zachowania praw autorskich i informacji o licencji, ale pozwala na dystrybucję na innych warunkach bez ujawniania kodu źródłowego.

Licencja ta stała się wzorem dla udostępniania oprogramowania w środowiskach akademickich, w późniejszym okresie pojawiło się zresztą wiele bardzo zbliżonych licencji (np. MIT)[1].
 
Podsumowując – wykorzystanie komponentów na tzw. "permisywnych" licencjach Open Source (MIT, BSD, Apache) wiąże się głównie tylko z podaniem w dokumentacji odpowiedniej informacji o zastosowanym oprogramowaniu i licencji, która je obejmuje. Więcej uwagi należy poświęcić wykorzystaniu oprogramowania Open Source na licencjach typu copyleft. W tym przypadku istotny staje się sposób połączenia takiego oprogramowania z innymi elementami produktu, opisany poniżej. Ryzykowne może okazać się stosowanie komponentów na "egzotycznych" (rzadko spotykanych) licencjach, zwłaszcza jeśli nie zostały one poddane ocenie przez organizacje takie jak Free Software Foundation czy Open Source Initiative.

Licencje "non-copyleft" (znane również jako "permisywne") nie mają podobnych ograniczeń. Z reguły nie ma więc przeciwwskazań do łączenia rozwiązań "własnościowych" i "otwartych", w tym udostępniania rozwoju "otwartego" programu na licencji "zamkniętej". Najpopularniejsze przykłady to MIT, BSD (wszystkie wersje) oraz Apache. Licencje te nie nakładają obowiązku udostępniania kodu źródłowego. Oznacza to, że program objęty taką licencją może być udostępniony zarówno w postaci binarnej, jak i źródłowej, niezależnie od tego, czy został zmodyfikowany, czy nie.



## Linki

https://legalgeek.pl/wp-content/uploads/2019/09/Przewodnik-prawny-licencje.pdf

[Oprogramowanie Open Source – pułapki w wykorzystaniu komercyjnym - Biznes, Finanse i Prawo](http://di.com.pl/oprogramowanie-open-source---pulapki-w-wykorzystaniu-komercyjnym-64618)

[Oprogramowanie Open Source - pułapki w wykorzystaniu komercyjnym | Legal Geek](https://legalgeek.pl/oprogramowanie-open-source-pulapki-w-wykorzystaniu-komercyjnym/)

Urzędowy bełkot:
[Licencje Open Source i ich znaczenie dla działalności przedsiębiorstw. Unijny projekt audytowy EU-FOSSA - PARP - Centrum Rozwoju MŚP](https://www.parp.gov.pl/component/content/article/56985:licencje-open-source-i-ich-znaczenie-dla-dzialalnosci-przedsiebiorstw-unijny-projekt-audytowy-eu-fossa)

## licence:

https://opensource.org/licenses

https://choosealicense.com/

+ simple
https://choosealicense.com/licenses/mit/

+ more conditions
https://choosealicense.com/licenses/gpl-3.0/



amazon examples
firecracker
https://aws.amazon.com/de/opensource/

https://github.com/firecracker-microvm/firecracker


##  https://www.freertos.org/
+ MIT open source license text
+
Real-time operating system for microcontrollers

Developed in partnership with the world’s leading chip companies over a 15-year period, and now downloaded every 170 seconds, FreeRTOS is a market-leading real-time operating system (RTOS) for microcontrollers and small microprocessors. Distributed freely under the MIT open source license, FreeRTOS includes a kernel and a growing set of IoT libraries suitable for use across all industry sectors. FreeRTOS is built with an emphasis on reliability and ease of use.

## Definitions




## Inne tematy:

+ [Zaplanuj Biznes](https://www.zaplanujbiznes.pl/)
+ [Dlaczego warto robić biznes w Niemczech? dlaczego.de](https://www.dlaczego.de)
+ [Dlaczeo warto i jak zostać rezydentem niemieckim? rezydent.de](https://www.rezydent.de)
+ [Jak zostać nierezydentem polskim? nierezydent.pl](https://www.nierezydent.pl/)


---

## Tom Sapletta
+ [Kontakt na linkedin](https://www.linkedin.com/in/tom-sapletta-com/)
+ [Blog Tom Sapletta ' Embedded System Software & Hardware Developer, Germany Essen](https://tom.sapletta.pl/)
+ [Firma Softreck - Leadership Through Software Development](https://softreck.pl/)

---


+ [edit](https://github.com/otwartykod/otwartykod/edit/main/README.md)

```
https://github.com/otwartykod/otwartykod.git
```
