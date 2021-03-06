# Les 6: After Effects

## 1. Introductie

### 1.1. Wat is After Effects

#### Kort

"De Photoshop van video editing"

Special effects, motion design & animation.

#### Lang

After Effects wordt in de film- en televisie-industrie gebruikt om special effects, titels en andere objecten aan beeldmateriaal toe te voegen. Alhoewel het mogelijk is, wordt het pure monteren en knippen van beeldmateriaal meestal gedaan in een ander programma.

After Effects maakt net als het Adobe-programma Photoshop gebruik van een "lagensysteem" in combinatie met een tijdlijn. Elke laag bestaat uit beeldmateriaal of effecten. De positie van deze effecten kan exact worden vastgesteld per laag. Zo kan met "keyframes" een effect per frame gepositioneerd en ingesteld worden. De tijdlijn geeft deze instellingen chronologisch weer.

De bediening van het programma werkt voornamelijk via drie panelen, het "Composition"-paneel, het "Project"-paneel en het "Timeline"-paneel (oftewel de tijdlijn waarover eerder werd gesproken). Beeldmateriaal en effecten van buiten het programma zelf worden geïmporteerd in het programma via het "Project"-paneel. Vanuit het "Project"-paneel kan het gewenste beeldmateriaal naar de tijdlijn gesleept worden, waarna er daar effecten aan toegevoegd kunnen worden. Op het "Composition"-paneel wordt weergegeven hoe het beeldmateriaal op de tijdlijn eruitziet, in zijn geheel of per laag.

### 1.2. Wat is After Effects

Wat kan je bijvoorbeeld doen met After Effects?

Zeer veel op vlak van video / beeld manipulatie, maar voor bepaalde taken gebruik je beter externe programma's:

- 3D beelden animeren (dit doe je in een andere programma: Blender of 3DS Max)
- montage van video (dit kan perfect in After Effects maar gaat vlotter in Adobe Premiere)
- vectoriële beelden op een efficiënte manier aanpassen (beter in Illustrator)
- Afbeeldingen / Design / Fotomanipulaties op een efficiënte manier aanpassen (beter in Photoshop)

Om zelf een beter gevoel te krijgen voor motion design is het goed om geregeld bepaalde inspiratie sites te bekijken. Natuurlijk kijken de meeste van ons al vrij veel naar video's dus iedereen heeft automatisch daar al een gevoel voor maar het blijft een goed idee om het kaf van het koren te kunnen onderscheiden.

Inspiratie:

- [https://motionographer.com/](https://motionographer.com/)
- [https://vimeo.com/channels/staffpicks](https://vimeo.com/channels/staffpicks)
- [https://www.behance.net/](https://www.behance.net/)
- [https://abduzeedo.com/](https://abduzeedo.com/)
- [https://www.artofthetitle.com/](https://www.artofthetitle.com/)
- [https://theinspirationgrid.com//](https://theinspirationgrid.com/)
- [https://2017.motionawards.com/winners/](https://2017.motionawards.com/winners/)

Wat maakt een geanimeerde video goed? Probeer geregeld te tijd te nemen om een antwoord voor jezelf te vinden op die vraag.
### 1.3 Enkele begrippen in After Effects

#### Composition (compositie)

Een compositie (composition) kan je het best vergelijken met een soort van PSD bestand gelijkaardig aan Photoshop.  Een compositie heeft een bepaalde resolutie & frames per second. Een compositie bestaat ook uit verschillende lagen.  Die lagen kunnen bestaan uit zowel video materiaal als beelden.


### 1.3. Overzicht After Effects interface

Gelieve onderstaande video te bekijken (gebruik hoofdtelefoon):

[Nederlandstalige overzicht van After Effects](https://www.youtube.com/watch?v=onfbyShe52U)

![Overzicht After Effects interface](ae-basic-overview.png)

#### Project panel

Hierin plaats je alle bronbestanden zoals afbeeldingen (png, jpeg, gif, etc.), Photoshop .PSD, Illustrator .AI, video's, geluidsbestanden etc.

Je vind hier ook de compositie (of verschillende composities) terug van je huidig project.

#### Composition panel

Dit is het paneel waarin je de huidige compositie in kan bekijken. Gelijkaardig aan het canvas in Photoshop. Je kan hier ook bewerkingen uitvoeren.

#### Timeline panel

De tijdslijn of timeline panel, is het paneel waarin je kan kiezen welke lagen wanneer zichtbaar zijn. Je kan hier ook verschillende effecten en manipulaties in toepassen.

De timeline panel heeft links een lagen / layer paneel (gelijkaardig aan photoshop) waarin je de verschillende lagen terugvind. Net zoals in photoshop is de bovenste laag de meest zichtbare laag.

In het rechtse gedeelte, zie je over de tijd van je compositie, welke lagen op welk moment zichtbaar zijn.

#### Effects panel

Hierin kan je verschillende effecten en tools selecteren om toe te passen op je gekozen lagen.

### 1.4 Troubleshooting (Algemene Problemen)

Het zal zeker en vast gebeuren dat je in problemen komt bij het uitvoeren van opdrachten

#### Anker punt standaard centreren

Voor je er aan begint, zeer belangrijk dat je deze setting goed zet; het is belangrijk wanneer je een vorm gaat animeren en je de rotatie wil aanpassen, dat het ankerpunt (anchor point) van het object in het midden staat. Enkel dan kan de basisvorm roteren rond zijn middelpunt.

![center-anchor-point](center-anchor-point.gif)


#### Purge Cache

Het kan zijn dat af en toe je After Effects programma traag werkt of begint te crashen. In dat geval moet je de cache purgen, dat doe je op volgende manier:

![purge-cache](purge-cache.gif)

## 2. Oefening Basis Animatie

In deze oefening leren we hoe we een basis animatie kunnen maken in After Effects en hoe we verschillende aanpassingen kunnen doen.

### Nieuwe Compositie maken

We beginnen eerst met een nieuwe compositie te maken.

Belangrijkste instelingen om je compositie te maken:

- Width & Height: Breedte & Hoogte, in principe hoeveel pixels breed & hoog je de compositie wil
- Start Timecode: tijdspunt waarop compositie begint, we laten dit op standaardwaarde staan (0:00:00:00 - uren:minuten:seconden:frames)
- Duration: we laten het hier beginnen vanaf 3 seconde, dus 0:00:03:00
- Frame rate (of FPS = Frames per second), staat voor hoeveel frames per seconde er te zien zijn. Hoe hoger, hoe vloeiender. Standaard staat dit rond de 30 maar voor deze oefening zetten we het op 60

Op de afbeelding hieronder zie je ze nog allemaal eens op een rijtje:
![ ](comp-start.PNG)

Hieronder zie je hoe je er aan begint:

![ ](create-comp.gif)

### Basisvorm aanmaken

We hebben natuurlijk iets nodig om te animeren. We kiezen om te beginnen een basisvorm, met name een vierkant. Een basisvorm noemt een "solid". Hieronder zie 2 manieren om een solid te maken.

Een manier: Layer > New > Solid

Zorg dat je de kleur kiest vooraleer je op confirm drukt.

![](create-solid.gif)

### Eigenschappen (properties) opzoeken

Eenmaal je layers (lagen) in je layer panel hebt kan je die openklikken om de verschillende eigenschappen te bekijken, maar je kan er ook op zoeken (zie onderstaande gif).

![](search-property.gif)

### Basis animatie in een richting

Om een basis animatie te maken, moeten we de "stopwatch" activeren. Dit zorgt ervoor dat er op het gekozen tijdstip een keyframe wordt aangemaakt. Om dan de animatie te vervolledigen moet je het tijdstip verplaatsen en en een aanpassing maken voor de gekozen eigenschap.

In ons geval, gaan we bij het beginpunt de stopwatch drukken, en dan op een later punt (seconde 2) de X coordinaat aanpassen.

![ ](basic-animation.gif)

### Basis animatie als rotatie

Je kan hetzelfde doen om een rotatie te maken door de rotation property aan te passen.

![ ](basic-animation-rot2.gif)

Kan je het verschil zien tussen volgende 2 animaties. Bij de eerste is de animatie zonder easing, dat wel zeggen dat te constant op de zelfde snelheid beweegt.

### Easing

No easing:

![ ](anim-norm-exx.gif)

Easing:

![ ](anim-ease-ex.gif)

De 2e afbeelding werd er "easing" toegepast, in de animatie wereld wil dit zeggen dat de snelheid een beetje creatiever wordt gemaakt bv het begin trager te laten bewegen, dan sneller, en dan weer te eindigen met tragere beweging.

Als je meer in detail wil weten wat easing precies is, kan je deze link openen en bekijken [After Effects Tutorial - Easing (Motion Design Techniques)
](https://www.youtube.com/watch?v=AlXEzbhfZJM)

---

Om easing toe te passen selecteer je de 2e keyframes en dan rechterklik je op 1 van 2. Dan kies je "Keyframe Assistant" en dan kies je vervolgens "Easy Ease", experimenteer gerust eens met de andere opties.

![ ](basic-ease.gif)

## 3. Video opslaan (renderen)

Zo'n After Effects compositie is natuurlijk niet zo handig om je video te tonen of te delen met anderen.

Er zijn verschillende manieren om een video te experteren. Een ervan is met de Render Queue, dat is een manier binnen After Effects om de video te exporteren, maar er gebeurt geen compressie/encoding dus het bestand zal groot zijn.

![ render-queue ](render-queue.gif)

Als dit programma ook geïnstalleerd is, is het ook beter om het met de Adobe Media Encoder te doen. Dan gaat het ook veel kleiner worden en correct gecomprimeerd / encoded worden.

![ adobe-media-encoder ](adobe-media-encoder.gif)

## 4. Oefeningen

### 4.1 Enkel kleur overlaten

We maken een nieuwe compositie met het filmpje bboy.mp4.

Download [ hier ](bboy.mp4)

![ ](bboy-newcomp.gif)

Vervolgens voeg je een effect toe;

Effects > Color Correction > Leave Color

En dan kies je de kleur van de broek.

![ ](bboy-leavecolor.gif)

### 4.2 Time Remapping

Af en toe, afhankelijk van hetgeen je moet doen, zal het interessant zijn / handig om het verloop van de tijd van verschillende lagen te manipuleren.

Dit kan je op volgende manier:

![ ](bboy-timeremap.gif)

## 5. OPDRACHT - Eerste (eigen) Animatie maken

Probeer nu eens een animatie naar keuze te maken.

Idëeen (kies 1 of meerdere):
- Je kan gerust Illustrator of Photoshop bestanden gebruiken. Probeer verschillende elementen te animeren door de technieken in vorige hoofdstukken te gebruiken.
- je kan ook bijvoorbeeld de opdracht Bewegend Beeld opnieuw ophalen en proberen je animatie te maken in After Effects door de verschillende lagen daar te gebruiken
- Gebruik de basis oefening vierkant en probeer die uit te breiden

Vereisten:
- Gebruik op zijn minst 1 foto in de opdracht
- Animeer op zijn minst 3 verschillende objecten
- Je naam moet duidelijk zichtbaar zijn ergens in het filmpje, liefst met een bepaalde animatie
- Exporteer het filmpje naar een bestand kleiner dan 100 MB (megabyte) - ik wil dus enkel het video bestand.

Probeer die animatie dan op te slaan en up te loaden in de map met naam "Eerste Animatie".

Als iets niet duidelijk is of je hebt vragen, aarzel niet om, om hulp te vragen.

## 6. OPDRACHT Squirrel titles

In deze opdracht gaan we iets gelijkaardig maken als de Brooklyn 99 intro, maar dan met dieren.

Bekijk eens de intro hieronder;

[Brooklyn 99 intro](https://www.youtube.com/watch?v=v0QTdCHX_-c)

![](brooklyn99-intro.PNG)

Je mag beginnen met de video squirrel.mp4 te downloaden van het bron materiaal voor de les van 2020-10-20.

Vervolgens ga je die importeren op volgende wijze en maken we een nieuwe compositie door die te slepen in het compositie icoontje:

![](new-comp-from-footage.gif)

Vervolgens kiezen gaan we de werkruimte (work area) aanpassen zodat we enkel werken met de eerste 10 seconden. Zoals in de afbeelding kan je het gedeelte waarin je werkt verkleinen naar enkel de tijd die je wil door de balk juist onder de tijdsaanduiding te verkleinen. Dan, wanneer je de gewenste periode hebt gekozen, rechterklik je op die balk en kies je: "Trim Comp to Work Area".

![](trimp-comp.gif)

Vervolgens gaan we de frame waarbij we willen dat die stilstaat en Hiervoor selecteren we een frame uit de video. Je kan naar de seconde gaan die je wil; best kies je 1 waar de eekhoorn duidelijk zichtbaar is. Dan klik je op Composition > Save Frame > as Photoshop Layers

![](save-frame.gif)

Vervolgens begin je de eekhoorn uit te knippen in Photoshop.

Eenmaal je de eekhoorn hebt uitgeknipt breng je die terug in After Effects.

![](use-photoshop-layer-in-ae.gif)

Nu zet je daar een gekleurde laag achter en animeer je een naam (bv je eigen naam) voor de eekhoorn.


### 2 extra tutorials

Ik heb nog 2 extra tutorials toegevoegd voor de squirrel intro opdracht.
Ik denk dat het duidelijker moet zijn eenmaal je die hebt bekeken:

[Eerste video vind je hier](https://youtu.be/vaI3_itE16c)
[Tweede video vind je hier](https://youtu.be/kCrUcCn4ojs)

Daarin leg ik uit:

- hoe een solid / kleur achtergrond te maken
- hoe een marker te gebruiken
- hoe time remapping toe te passen (video laten pauzeren en verder laten lopen)
- hoe je animatie kan maken
- hoe je zichtbaarheid kan maken
- hoe met verschillende lagen te werken
- hoe je photoshop laag best importeert als die bestaat uit een frame
- enkele idëeen om je opdracht tot een goed einde te brengen

aarzel niet extra vragen te stellen als iets niet duidelijk is!




#### Stock Video's gratis

[https://www.pexels.com/nl-nl/zoeken/videos](https://www.pexels.com/nl-nl/zoeken/videos)

## Afstandsonderwijs zonder software

Als je klaar bent met ALLE opdrachten of heb je het niet de nodige software om de oefeningen te maken, kan je volgend materiaal doornemen. Dit zal dienen als basis om verdere opdrachten uit te voeren.

### Online Lesgevers

#### Ben Marriot

Ben Marriot is een zeer goede youtube lesgevers voor After Effects & Motion Design, weliswaar in het Engels.
Hij heeft op [zijn youtube kanaal (klik hier)](https://www.youtube.com/channel/UCjJk212xU15y_NPYKuCsKQA) heel veel boeiende tutorials waarbij je vaak ook de project files kan downloaden.

[Learn After Effects in 10 Minutes! Beginner Tutorial](https://www.youtube.com/watch?v=hb2bbfiNBXA)

[50 After Effects Tips, Tricks & Secrets for Beginners](https://www.youtube.com/watch?v=LdLdRRWNkNc)

#### Andere

Michael Terny [(klik hier)](https://www.youtube.com/channel/UCqAsrgGkeN92yNu4dmi0PFw) & Peter McKinnon [(klik hier)](https://www.youtube.com/channel/UC3DkFux8Iv-aYnTRWzwaiBA) hebben ook leuke tutorials die je kan bekijken

als je er zelf nog kent, mag je me die gerust geven, dan zet ik ze hierbij

### Basis After Effects in het Nederlands

Het is niet makkelijk om informatie over After Effects te vinden in het Nederlands, maar bij deze;
De basis van After Effects in het Nederlands door een Nederlandse:
[Basis After Effects in het Nederlands](https://www.youtube.com/watch?v=onfbyShe52U)

### Adobe MAX

Voor allerhande onderwerpen, zowel technische, artistiek en creatief, kan het leuk zijn om enkele lezingen mee te pikken op de Adobe MAX conferentie website:

[Adobe MAX](https://www.adobe.com/max.html)

### 12 principes van Animatie

We gaan in deze les niet zo ver gaan in animatie, maar het is zeker interessant als animatie iets is die je interesseert:
[The 12 principles of animation](https://www.youtube.com/watch?v=uDqjIdI4bF4)

### Meer over encoding

[ Video Formats, Codecs and Containers (Explained)
 ](https://www.youtube.com/watch?v=XvoW-bwIeyY)