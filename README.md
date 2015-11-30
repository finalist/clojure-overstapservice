
![Clojure](http://clojure-conj.org/images/clojure.png)

# De Clojure overstapservice

Deze overstapservice is samengesteld voor programmeurs die eens iets anders willen. 

Clojure is dan een prima, volwassen alternatief, want:

* Clojure is simpel
* Clojure is data-georiënteerd
* Clojure vereist minder regels code
* Clojure ondersteunt meerdere platformen
* Clojure is interactief
* Clojure is full stack
* Clojure voorkomt callback hell
* Clojure ... etc

Als je daadwerkelijk die overstap wil maken, dan zijn hier wat pointers die je daarbij zouden kunnen helpen.

## Tools

Je kunt Clojure direct uitproberen, via [Try Clojure](http://www.tryclj.com).

<a href="http://www.tryclj.com"><img src="http://learn-clojure.com/images/try_clojure.png"/></a>

Maar als Clojure op je eigen machine wil draaien, dan heb je een editor en een build tool nodig.

### Editors

#### [Emacs](https://www.gnu.org/software/emacs/)

Onder Clojure-ontwikkelaars is Emacs [het meest populair](https://cognitect.wufoo.com/reports/state-of-clojure-2014-results/), waarschijnlijk omdat het de meest krachtige editor is voor Lisp-achtige talen. Je hebt in de vorm van [CIDER](https://github.com/clojure-emacs/cider) een ingebouwde REPL en debugger, en via [ParEdit](http://www.emacswiki.org/emacs/ParEdit) beschik je over de mogelijkheid van _structural editing_. 

Echter, als Emacs nieuw voor je is, hou dan wel rekening met een steile leercurve. Maar voor de dapperen onder ons: op de [Clojure for the Brave and True](http://www.braveclojure.com/basic-emacs/) website staan prima aanwijzingen om  met Emacs aan de slag te gaan.

<img src="http://www.braveclojure.com/assets/images/cftbat/basic-emacs/emacs-fresh.png" width=200/>

#### [vim-fireplace](https://github.com/tpope/vim-fireplace)

Voor vim-adepten bestaat bovendien de [Spacemacs](https://github.com/syl20bnr/spacemacs) distributie, maar als je liever voor de 'echte' vim gaat, dan kun je [fireplace](https://github.com/tpope/vim-fireplace) gebruiken, dat ook letterlijk 'REPL' bevat.


#### [Cursive](https://cursiveclojure.com)

Cursive is een Clojure-plugin voor IntelliJ. Het heeft een ingebouwde REPL,  biedt ondersteuning voor debugging en structural editing, en daarnaast natuurlijk alle features die de IDE van IntelliJ je biedt. Het is een commercieel product, maar onder bepaalde voorwaarden mag je 'm gratis gebruiken.

<img src="https://cursiveclojure.com/images/logo.png" width=200/>

#### [CounterClockwise](http://doc.ccw-ide.org)

Als je meer een fan bent van de Eclipse IDE, dan is wellicht CounterClockwise iets voor jou.

<img src="http://www.eclipse.org/eclipse.org-common/themes/Nova/images/eclipse-800x426.png" width=200/>

#### [Light Table](http://lighttable.com)

Is een IDE te zwaar voor je, dan is de lichtgewicht editor Light Table een prima alternatief. Eén van de opvollende features van Light Table is de instant feedback die je krijgt in de vorm van uitgerekende datawaarden, zodat je kunt zien hoe de data door je programma stroomt.

<img src="http://lighttable.com/images/logo.png" width=100/>

### Build Tools

#### [Leiningen](http://leiningen.org)

Leiningen was lange tijd (en is nog steeds) de de-facto build tool voor Clojure.

<img src="http://leiningen.org/img/leiningen.jpg" width=75/>

#### [boot](http://boot-clj.com)

Tegenwoordig is het niet langer [Leiningen vs. the ants](https://en.wikipedia.org/wiki/Leiningen_Versus_the_Ants), maar Leiningen vs. boot. Zoals de makers het zelf uitdrukken: het is geen build tool, het is build _tooling_, omdat het je in staat stelt om verschillende bouwstappen te combineren tot een _build pipeline_.

<img src="http://boot-clj.com/assets/images/logos/boot-logo-3.png" width=100/>


## Boeken

Een gangbare manier om een programmertaal te leren is door er een boek over te lezen. Inmiddels zijn er al talloze titels verschenen over het onderwerp, waardoor het moeilijk is om er één uit te kiezen. We denken echter dat de volgende drie voor beginners echt de moeite waard zijn.

### [Clojure for the Brave and True](http://www.braveclojure.com)

Dit boek van Daniel Higginbotham ([@nonrecursive](https://twitter.com/nonrecursive)) is volgens velen echt het leukste boek over Clojure voor newbies.

<a href="http://www.braveclojure.com"><img src="https://www.nostarch.com/sites/default/files/imagecache/product_full/clojure_cover-front_final.png" width=150/></a>

### [Clojure Programming](http://shop.oreilly.com/product/0636920013754.do)

Geschreven door Chas Emerick ([@cemerick](https://twitter.com/cemerick)), Brian Carper ([@cdaddr](https://twitter.com/cdaddr)) en Christophe Grand ([@cgrand](https://twitter.com/cgrand)). Goed voor het totaaloverzicht - niet alleen van de taal - maar ook het  ecosysteem van Clojure, waaronder vele libraries en dergelijke.

<a href="http://shop.oreilly.com/product/0636920013754.do"><img src="http://akamaicovers.oreilly.com/images/0636920013754/cat.gif" width=150/></a>

### [The Joy of Clojure](https://www.manning.com/books/the-joy-of-clojure-second-edition)

Dit pareltje van [Michael Fogus](https://twitter.com/fogus) en [Chris Houser](https://twitter.com/chrishouser) gaat meer in op de filosofie achter Clojure. Voor als je de beginselen net onder de knie hebt en meer wil lezen over de kracht van de programmeertaal.

<a href="https://www.manning.com/books/the-joy-of-clojure-second-edition"><img src="http://images.manning.com/255/340/resize/book/5/c0cca9c-4de6-401b-a3d0-91f95bd2b4eb/fogus2.png" width=150/></a>

## Trainingen

In het volgende rijtje vind je diverse manieren om je in Clojure te trainen.

### [Clojure Inside Out](http://shop.oreilly.com/product/0636920030409.do)

Heb je geen zin om een boek te lezen, dan krijg je met Clojure Inside Out keen grondige en uitgebreide videotraining van Stuart Halloway([@stuarthalloway](https://twitter.com/stuarthalloway)) en Neal Ford([@neal4d](https://twitter.com/neal4d)).

<a href="http://shop.oreilly.com/product/0636920030409.do"><img src="http://akamaicovers.oreilly.com/images/0636920030409/cat.gif" width=150/><a>

### [Living Clojure](http://shop.oreilly.com/product/0636920034292.do)

Als je het lezen van een boek wil combineren met het volgen van een cursus, dan is  Living Clojure van Carin Meier ([@gigasquid](https://twitter.com/gigasquid)) ideaal voor jou. Want naast een goede introductietekst bevat het ook een compleet plan om je in zeven weken op een gestructureerde manier Clojure te leren.

<a href=""><img src="http://ecx.images-amazon.com/images/I/519kdAUU-gL._SX258_BO1,204,203,200_.jpg" width=150/></a>

### [Functional Programming with Clojure](http://mooc.fi/courses/2014/clojure/)

De enige [massive open online course](https://en.wikipedia.org/wiki/Massive_open_online_course) (MOOC) die volledig is gewijd aan de programmeertaal Clojure. In het Engels gegeven, door de Universiteit van Helsinki.

<a href="http://mooc.fi/courses/2014/clojure/"><img src="http://mooc.fi/img/logo.png" width=150/></a>

### [Inleiding Functioneel Programmeren met Clojure](http://michielborkent.nl/clojurecursus/)

Collegedictaat van de Nederlandstalige Clojure-cursus, ontwikkeld door Michiel Borkent ([@borkdude](https://twitter.com/borkdude)), voor Hogeschool Utrecht (cursusjaar 2012-2013).

<a href=""><img src="http://www.hu.nl/includes/img/HU-Platform/hu-logo-nl.svg" width=150/></a>

### [Clojure from the Ground Up](http://aphyr.com/tags/Clojure-from-the-ground-up)

Als een complete academische cursus je net iets teveel is: Kyle Kingsbury ([@aphyr](https://twitter.com/aphyr)), onder meer bekend van het (Clojure-gebaseerde) monitoringsysteem [Riemann](http://riemann.io) en de [Jepsen](https://aphyr.com/tags/jepsen) serie over gedistribueerde systemen, biedt je een hands-on tutorial in [tien hapklare brokken](http://aphyr.com/tags/Clojure-from-the-ground-up).

### [4Clojure](https://www.4clojure.com)

Een andere manier om je Clojure skills te testen, is via het oplossen van de programmeerproblemen van 4Clojure.

<a href=""><img src="http://www.4clojure.com/images/4clj-logo-small.png" width=150/></a>

## Meetups

Via meetups kun je in een kleinschalige, informele setting een avondje uithangen met die andere Clojure ontwikkelaars, die hier in Nederlands actief zijn.

### [The Amsterdam Clojure Meetup](http://www.meetup.com/the-amsterdam-clojure-meetup-group/)

De Amsterdamse meetup over Clojure ([@amsclj](https://twitter.com/amsclj)) wordt georganiseerd door Carlo Sciolla ([@skuro](https://twitter.com/skuro)).

### [Functional Rotterdam](http://www.meetup.com/Functional-Rotterdam/)

Rotterdam had ooit een Clojure Meetup, maar organisator Vijay Kiran ([@vijaykiran](https://twitter.com/vijaykiran) heeft met Functional Rotterdam de scope van de meetup verbreed naar ook andere programmeertalen.

## Conferenties

Conferenties helpen om je in een paar dagen tijd helemaal te wentelen is van alles wat maar met Clojure te maken heeft. Daarnaast biedt het je de gelegenheid in contact te treden met ontwikkelaars van over de grens.

De meest conferenties rondom Clojure worden georganiseerd door Cognitect. De enige 'onafhankelijke' Clojure conferentie is een initiatief van Skills Matter.

<img src="http://cognitect-labs.github.io/transducers-js/assets/css/cognitect.jpg" width=150/>

<img src="https://d2rrjv931ezem9.cloudfront.net/assets/logo_proper-ccaff0ec01a9850c84d8bd6d2e488e69.png" width=200/>

### [Clojure/conj](http://clojure-conj.org)

Laatste editie: 16-18 november, 2015 in Philadelphia (Pennsylvania, USA).

### [Euroclojure](http://euroclojure.org)

Laatste editie: 25-26 juni, 2015 in Barcelona (Spanje)

### [Clojure/West](http://clojurewest.org)

Laatste editie: 20-22 april, Portland (Oregon, USA)

### [Clojure eXchange](https://skillsmatter.com/conferences/6861-clojure-exchange-2015)

Volgende editie: 3-4 december, Londen (UK)

## Videos

De meeste conferenties leggen hun talks vast op video, waardoor ze later online zijn te bekijken door een groter publiek. Hieronder hebben een aantal videoregistraties van inmiddels 'legendarische' voordrachten op het gebied van Clojure.

### Rich Hickey: Simple Made Easy

De voordracht die Rich Hickey hield op Strange Loop in 2011. Rich gebruikt de term 'de-complecting', en geeft hiermee een van de belangrijkste drijvende krachten achter het ontwerp van Clojure aan. Clojure is niet zozeer gemakkelijk ('easy'), maar wel eenvoudig ('simple').

[Video](http://www.infoq.com/presentations/Simple-Made-Easy) | [Transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/SimpleMadeEasy.md)

<a href="http://www.infoq.com/presentations/Simple-Made-Easy"><img src="http://cdn.infoq.com/statics_s1_20151125-0108/resource/presentations/Simple-Made-Easy/en/slides/sl1.jpg" width=250/></a>

### Rich Hickey: Are We There Yet?

In deze talk legt Rich Hickey aan de hand van quotes van Whitehead uit wat de waarde is van immutable datastructures, en hoe dit via persistent datastructures werkt in Clojure.

[Video](http://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey) | [Transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/AreWeThereYet.md)

<a href="http://www.infoq.com/presentations/Are-We-There-Yet-Rich-Hickey"><img src="http://image.slidesharecdn.com/hickeyjvmsummit2009-100702080446-phpapp02/95/hickey-jvm-summit2009-1-728.jpg?cb=1278057965" width=250/></a>

### Rich Hickey: Hammock Driven Development

Met een knipoog naar _fads_ zoals Test Driven Development, vertelt Rich Hickey over de waarde van de hangmat bij het oplossen van programmeerproblemen. Want soms helpt het om even niet te coderen, maar om goed na te denken.

[Video](https://www.youtube.com/watch?v=f84n5oFoZBc) | [Transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Hickey_Rich/HammockDrivenDev.md)

<a href="https://www.youtube.com/watch?v=f84n5oFoZBc"><img src="http://incanter.org/images/misc/hammock-driven-dev.png" width=250/></a>

### David Nolen: The Functional Final Frontier

In deze talk helpt David Nolen je om over te stappen van een MVC-architectuur, naar een meer functionele smaak van User Interface design, en hoe de persistent datastructures van Clojure(Script) daarbij helpen.

[Video](https://www.youtube.com/watch?v=DMtwq3QtddY) | [Transcript](https://github.com/matthiasn/talk-transcripts/blob/master/Nolen_David/FunctionalFinalFrontier.md)

<img src="https://github.com/matthiasn/talk-transcripts/raw/master/Nolen_David/FinalFrontier/00.00.00.jpg" width=250/>

## Podcast

### [Cognicast](http://blog.cognitect.com/cognicast/)

Regelmatig verschijnende podcast van Cognitect, gehost door Craig Andera ([@craigandera](https://twitter.com/craigandera)).

<img src="http://cognitect-labs.github.io/transducers-js/assets/css/cognitect.jpg" width=150/>


## Blogs

Er worden talloze blog-artikelen over het onderwerp geschreven, waaronder velen die geschikt zijn voor de beginnende Clojure-programmeur.

### [Planet Clojure](http://planet.clojure.in)

Een metablog over Clojure, bijgehouden door Baishampayan Ghose ([@ghoseb](https://twitter.com/ghoseb) en Alex Ott ([@alexott_en](https://twitter.com/alexott_en)). Op dit moment houdt Planet Clojure ongeveer 839 blogs bij.

### [Clojure Gazette]((http://www.clojuregazette.com)

Je kunt je [hier](http://www.clojuregazette.com) abonneren op Clojure Gazette, de newsletter van Eric Normand ([@ericnormand](https://twitter.com/ericnormand)). Deze verschijnt elke week met een aantal van commentaar voorziene links naar interessante blogartikelen.

Eric houdt zelf ook een blog bij, [LispCast](http://www.lispcast.com), en biedt daarnaast online mentoring via [PurelyFunctional.tv](http://www.purelyfunctional.tv).

<img src="http://www.lispcast.com/img/Logo@2x.png" width=150/>

## Community

De Clojure community is een relatief kleine community. Echter, Clojurians zijn actief en behulpzaam, zoals je zult ondervinden bij onderstaande initiatieven.

### [Google Groups](https://groups.google.com/forum/#!forum/clojure)

Het Clojure forum, gehost door Google Groups.

<img src="http://www.google.com/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" width=150/>

### [Stack Overflow](http://stackoverflow.com/questions/tagged/clojure)

Tagged questions voor Clojure op Stack Overflow.

<img src="http://stackoverflow.com/" width=200/>

### IRC

\#clojure

### [Clojurians](http://clojurians.net) Slack Chat

Met op dit moment 3762 geregistreerde slackers.

<img src="http://slack.com/img/slack_hash_128.v1442100037.png" width=100/>
