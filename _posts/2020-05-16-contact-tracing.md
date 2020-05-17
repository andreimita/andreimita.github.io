---
layout: post
title: Despre aplicațiile de contact tracing, cu preambul
---

## Preambul

Tocmai a trecut cinșpe' mai și-am așteptat dramatic momentul. N-am o idee foarte clară cum o să evolueze lucrurile. N-am avut nici până acum, doar am urmărit și-am încercat să-mi explic și să provoc la dezbatere prin diverse postări. Rolul unei analize, [cred eu](https://stiri.plus/andrei-mita-la-scoala-plus-mandatul-analistilor-de-date-este-sa-descopere-lucruri-interesante-sa-descurajeze-certitudinile-si-sa-invite-la-cercetare/), este să înlăture certitudinile, să provoace polemici (dezbateri, nu scandaluri).

Mai 15, ziua 80, suntem pe coama valului și o luăm în jos. Dacă e primul sau singurul val, nu știm. În egală măsură putem avea mai multe și mici sau încă unul mai mare prin toamnă. Balanța zilnică e constant negativă, adică se însănătoșesc (și mor) mai mulți oameni decât se infectează.

Noi vedem zilnic, cu mai puțină pasiune decât la început, trei cifre: infectați, recuperați, decedați. Am câteva mantre și una dintre ele este că în spatele cifrelor sunt oameni. Am repetat peste tot asta. Pe Andrei Balint nu-l cunosc, dar am dat peste [o postare](https://www.facebook.com/andrei.balint/posts/10220265195972408) care arată durerea din spatele unui singur număr. 1 din 16 mii. Și ne mai arată magnitudinea informațiilor, a datelor pe care nu le avem. Un singur exemplu din postarea lui, la care sunt mai sensibil: din 10 teste, 2 au fost fals negative[^1]. Adică era încă infectat, dar testul nu a arătat asta. RTC făcut la spital, nu test prin poștă. 20%. N-am încredere că administrația colectează despre fiecare caz tot ce Andrei a publicat, n-am încredere nici că folosesc datele astea așa cum trebuie. Nu este o neîncredere consiprațională ci una bazată pe experiența lucrurlui cu instituțiile statului ca cetățean normal.

Guvernanții sigur au mai mult decât cele trei cifre pe care le primim noi, altfel nu s-ar explica panica instaurării lock-down-ului la 159 de cazuri active (0 decese) și relaxare totală când avem peste 6.000 de cazuri active și peste 1.000 de decese. Cu cât știu acum, eu nu m-am relaxat.



## Aplicațiile de *contact tracing*

Aplicațiile de contact tracing[^2] au ca scop înregistrarea interacțiunilor tale fizice cu alte persoane făra ca tu să faci ceva. Practic, telefonul tău ține un jurnal al întâlnirilor cu alte telefoane. O întâlnire înseamna, de fapt, aproprierea ta fizică cam la 2 metri de o altă persoană pentru mai mult de câteva minute, chiar dacă nu o cunoști, chiar dacă nu vorbești cu ea. O întâlnire în contact tracing este atunci când te duci să duci gunoiul și te oprești să vorbești cu un vecin, sau atunci când stai la coadă la magazin. Scopul este ca dacă ești testat pozitiv să poți afla cu cine ai fost în contact în ultimele doua săptămâni.

Pentru ca aplicațiile ăstea să funcționeze este nevoie ca ele să fie folosite de **cel puțin 60% din populație**.



##### I. Ai nevoie nevoie de o țără profund digitalizată și mobile-ready

În România nivelul de penetrare al telefoanelor mobile smart este de ~50%[^3]. Adică doar jumătate din populația țării, indiferent de vârstă, are telefon mobil smart. Deci și dacă ne-am pune cu toții aplicația pe mobil și tot n-ar fi suficient.

Singapore, Coreea de Sud sau Islanda, țările care conduc topul adopției unor astfel de tehnologii nu se aproprie nici ele de prag de 60%[^4]. Singapore, care nu echiar o țară, eu un singur oraș (nu are rual, nu are mii de administrații, nu au discrepanțele noastre sociale) abia a ajuns la 20% din populație în condițiile în care [9 din 10 persoane au smartphone](https://www.todayonline.com/singapore/smartphone-penetration-singapore-highest-globally-survey). Islanda, cu doar 370 mii locuitori, e la 38%. Coreea de Sud a folosit aplicația doar ca punct de plecare, din cauza adopției scăzute, și a corelat informațiile cu tranzacțiile de pe card sau camere video instalate public. Pentru noi și pentru Europa ar funcționa și mai puțin[^5], adică deloc.

Despre China, Israel sau India nu are rost să vorbim căci acolo este mass-surveilance. În Israel, spre exemplu, au folosit tehnologie militară în aplicație[^6], tehnologie de spionaj pentru combaterea terorismului.

Apoi vine problema colaborării, din motive tehnice[^7], cu Google și Apple[^8] pentru ca o astfel de aplicație să devină funcțională. Oricât de fan-boy Apple sunt, nu am niciun motiv să am încredere oarbă în a-mi deschide viața în fața lor în măsura asta incontrolabilă. Și este incontrolabilă atâta timp cât noi, cetățenii, nu avem absolut niciun mecanism prin care să validăm ce se întâmplă cu informațiile strânse de telefon în buzunar. Nu cred că vor profita de datele noastre, dar nici nu pot să fiu sigur.



##### II. Contact tracing-ul este o soluție reactivă

Și dacă am ajunge să avem adopția necesară, aplicațiile oferă o soluție care răspunde infectărilor, nu le previne. Adică te pot ajuta pe tine și ce ceilalți doar după ce esti testat și identificat pozitiv.

Ori scopul nostru principal este să împiedicăm infectările, nu să le identificăm. Știm că limitarea interacțiunilor neesențiale încetinește foarte mult răspândirea. Știm asta din evoluția de până acum și din faptul că noul coronavirus se răspândește comunitar. Chiar și acolo unde n-a fost lock-down complet numărul cazurilor noi a scăzut mult. În fond, asta au făcut ordonanțele militare, ne-au blocat pe loc.



##### III. O soluție alternativă

Câteva lucruri trebuie spuse foarte clar despre cum trebuie făcută o colaborare digitală între stat și cetățeni, indiferent de aplicație sau soluție:

1. datele colectate prin orice aplicație de către stat trebuie să fie complet anonimizate

2. datele trebuie colectate participativ, adică noi să alegem să le dăm (*anonim!*), nu să ne fie luate

3. datele colectate public trebuie să fie date înapoi publicului (adică să vedem și noi ce vede statul)

Și desigur, fără discuție, orice aplicația trebuie să fie deschisă (*open-source*) și auditată public, adică oricine cu skill-urile necesare se poate uite să vadă daca aplicația face ceea ce spune că face. Slavă Domnului, suntem suficienți în România care putem face asta.

Aplicații de contact tracing se bazeaza pe numere absolute, pe indivizi. Propunerea mea și a colegilor mei se bazează pe estimări statistice, adică pe sondaj, ca la alegeri. Aplicația nu încearcă să identifice cine ar putea fi bonlav, ci ne permite fiecăruia să decidem singuri cât de mult ne expunem riscului de îmbolnăvire.

**Adică o soluție proactivă care pune accent pe reducerea riscului de infectare.**

Pentru București, spre exemplu, o aplicație de contact tracing are nevoie de 1 milion de utilizatori ca să fie eficientă. Aplicația pe care o propunem noi începe să dea rezultate bune cu doar 2.000 de utilizatori (cu un interval de încredere de 99% și o marjă de eroare de +/- 3%) și rezultate fantastice cu 20.000 utilizatori (cu un interval de încredere de 99% și o marjă de eroare de +/- 1%).

Cu mai puțin de 1% din populația orașului am putea avea rezultate care se ridică la standarde de teste clinice medicale.



##### IV. Aplicația urmărește să nu fiu urmărit

Aplicația nu urmărește să determine dacă ai trecut la un moment dat pe lângă cineva cu COVID-19, ci te-ar ajuta să decizi singur dacă într-un anumit interval orar e sigur, după recomandări medicale, *dar mai ales după propriile tale standarde*, să te duci acolo unde vrei estimând gradul de aglomerare pentru zona respectivă.

*50 de oameni într-un Mega Image nu e tot una cu 50 de oameni într-un Auchan și nici cu 50 de oameni în Herăstrău.*

Cred că declarația pentru deplasare a fost o idee bună, dar foarte prost implementată și s-a urmărit pedepsirea în loc de informarea noastră. N-am fost parteneri, am fost subiecți[^9].

Modul în care ne mișcăm, orele la care o facem și zonele pe care le frecventăm sunt factori pentru răspândirea COVID-19, sau, în egală măsură, pentru combarea pandemiei.



> Au băgat la Lidl tricouri de ălea simple din bumbac și vreu neaparat să-mi iau. Scot telefonul, completez ora și magazinul. Informatiile complete rămân la mine, iar spre stat se duce doar o notificare cum că încă o persoană merge în Lidl la ora respectivă. În acealași timp și eu văd că alte persoane vor să vină la Lidl *meu*, la aceeași oră. Suntem 70 în total cei care ne-am anunțat. Pentru mine, sunt prea mulți. N-or vrea toți tricouri și n-or vrea toți mărimea M. Caut să mă duc mai târziu.



Dacă tu ai fi în situația asta, te-ai mai duce? Sau ți-ai căuta altă oră? Te simți în siguranță când ești vânat cu amendă sau când ai libertatea de a te proteja singur de virus?

Nu spun că statul ar trebuii să știe cum mă mișc eu. Nu, statul ar avea nevoie să știe cum ne mișcăm noi ca un tot, nu ca indivizi. Și nu doar statul, ci și noi trebuie să știm cum ne mișcăm noi ca să putem lua singuri decizii.

Parcurile ar fi putut fi deschise mai devreme, sau să nu fie închise de la bun început. Restaurantele care acum se zbat să nu închidă de tot și-ar putea limita numărul de clienți la mese, iar firmele ar putea chemea angajații la ore diferite (deja o fac). Dar pentru a-ți planifica în siguranță ziua nu trebuie să știi doar ce ai tu de gând să faci, ai nevoie ca noi cu toții să impărtășim asta.

**Cum ar ajuta informațiile ăstea statul?** La fel ca noi și statul are nevoie de o imagine clară a ceea ce se întâmplă în jurul lui. Nu are un ochi magic și nici nu suntem urmăriți (încă) fără acordul nostru. As spune chiar că statul este mai rupt de realitate decât noi. Fără informații reale, decidenții transformă părerei personale, de multe ori subiective, în decizii care ne afectează doar pe noi. Fără informații reale, soluțiile pe care le adoptă nu sunt doar ineficiente, dar uneori sunt chiar dispoporționate (cred că ai șanse mai mari să te imbolnăvești într-un supermarket decât la o plimbare printr-un parc mai mult gol).



##### V. Am ratat prima ocazie, dar mai avem de câștigat

Imaginațivă dacă captam toate motivele de deplasare și toate intervalurile orare, anonim, în prima lună de pandemie, imediat după prima ordonanță militară, pentru doar un sfert dintre cei care au ieșit din casă. Am fi stat pe un munte de informații acum care ar fi ajutat guvernanții să decidă forme de relaxare coerente, pe baza nevoilor din luna a doua. Și le-ar fi putut readapta constant pe măsură ce tot mai mulți oameni ar fi ales, de bună voie, să folosescă aplicatia. Cred că n-am mai fi stat 80 de zile izolați complet.

Încă e timp. Suntem pe o pantă descendentă, însă nimic nu ne poate garanta că un nou val nu e pe vine sau, mai rău, un nouă pandemie. Am putea începe acum să lucrăm și să ne adaptăm pentru ca la toamnă, dacă e cazul, să fim pregătiți.

Poate ajunge până sus la PNL căci eu n-am linie directă cu ei. Știu însă oameni mișto care să o dezvolte. Trebuie doar folosită.



*Materialele de mai jos nu sunt notate doar ca research făcut pentru articol (și pentru care care trebuie să mulțumesc echipei). Sunt surse surse credibile și sănătoase de informare pe care recomand să le parcurgeți.*

[^1]:Un test **RTC** poate avea 4 rezultate: pozitiv (și persoana chiar este infectată), negativ (și persoana chiar nu are virusul), fals pozitiv (testul iese pozitiv, dar persoana este sănătoasă), fals negativ (testul este negativ, dar persoana este, de fapt, infectată). Dintre cele 4, două sunt erori: [de tip I și de tip II](https://en.wikipedia.org/wiki/Type_I_and_type_II_errors#Error_rate). Erorile de tip II, în cazul nostru fals negativ, sunt cele mai grave, cele care au repercursiuni severe. Un exemplu care poate e mai clar, sentința de vinovat dată unui om nevinovat.
[^2]:Wikipedia: [COVID-19 apps](https://en.wikipedia.org/wiki/COVID-19_apps)
[^3]:[Forecast of the smartphone user penetration rate in Romania from 2015 to 2022](https://www.statista.com/statistics/568223/predicted-smartphone-user-penetration-rate-in-romania/)
[^4]:[Who Wants to Be a Contact Tracer?](https://www.citylab.com/solutions/2020/05/contact-tracing-coronavirus-cases-data-jobs-technology-apps/611119/)

[^5]:[Countries Rolling Out Coronavirus Tracking Apps Show Why They Can’t Work](https://foreignpolicy.com/2020/05/12/coronavirus-tracking-tracing-apps-cant-work-south-korea-singapore-australia/)
[^6]: [Yuval Noah Harari: the world after coronavirus](https://www.ft.com/content/19d90308-6858-11ea-a3c9-1fe6fedcca75)
[^7]: [NHS in standoff with Apple and Google over coronavirus tracing](https://www.theguardian.com/technology/2020/apr/16/nhs-in-standoff-with-apple-and-google-over-coronavirus-tracing)
[^8]: Despre [coloborare Apple și Google](https://covid19-static.cdn-apple.com/applications/covid19/current/static/contact-tracing/pdf/ExposureNotification-FAQv1.1.pdf) pentru o soluție de contact tracing
[^9]: O notă personală: am remarcat în discursurile publice la noi că îndemnurile primite au fost de genul *"stați în casă"*, *"vă doresc"*, *"respectați indicațiile"*. Adică voi. În comparație, discursul Regeni Marii Britanii a fost plin de *"we will"*. Adică noi toți. 
