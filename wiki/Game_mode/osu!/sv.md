
---

# osu! (spelläge)

*För andra användningar av ordet, se [osu! (disambiguation)](/wiki/Disambiguation/osu!).*

![Gameplay av osu!](/wiki/shared/osu-gameplay.jpg "osu! Interface")

Det första spelläget, med gameplay [baserat på ouendan-serien](#inspiration).

## ![](/wiki/shared/mode/osu.png)Gameplay

*Introduktion: [new beginnings (Bundled with osu!)](https://osu.ppy.sh/beatmapsets/1011011).*

### Låtväljaren

För att komma åt osu! spelläget, tryck `Ctrl`+`1` samtidigt.

Alternativt kan man klicka på `Mode` knappen och välja `osu!`.

### Grundläggande spelmekaniker

#### Spelfältet

![osu! spelfält](/wiki/shared/osu-gameplay.jpg "osu! playfield")

Den ifyllda linjen i det övre vänstra hörnet visar hälsan, som stadigt minskar (i en fart beroende på beatmappens svårighetsinställning), men kan fyllas på genom att träffa noter vid rätt tillfälle eller genom att snurra på spinnern. En perfekt träff (en 300 eller Geki) ger mer hälsa än en för sen eller tidig träff (50). En miss tar bort en bit av hälsan.

Till höger om hälsan syns totala antalet poäng. Nedanför det visas träffsäkerhet. Cirkeln bredvid träffsäkerheten (dvs. under poängtalet) är en timer för låtens längd. I det nedre vänstra hörnet visas kombo/poängfaktor.

#### Hit-Cirklar

![Hit-cirklar](/wiki/shared/osu_hitcircles.jpg "osu! hit circles")

Färgade cirklar med nummer på kallas för hit-cirklar. Hit-cirklar kommer att dyka upp på spelfältet under kartans gång. En tunn [Approach-cirkel](/wiki/Gameplay/Hit_object/Approach_circle) med liknande färg kryper ständigt med tiden. Tryck på hit-cirkeln precis när approach-cirkeln rör hit-cirkelns vita kant. Hit-cirklarna ska tryckas på i samma ordning som siffrorna på hit-cirklarna indikerar.

Efter att en hit-cirkel har tryckts på kommer ett nummer synas. Numret är en [Bedömning](/wiki/Gameplay/Judgement/osu!) av hur noggrant timeat trycket var. 

#### Sliders

![Sliders](/wiki/shared/osu_slider.jpg "osu! sliders")

Börja med att trycka på cirkeln i början av slidern vid rätt tillfälle. Cirkeln på en slider kallas för en [slider head](/wiki/Gameplay/Hit_object/Slider/Sliderhead). När en sliderhead trycks kommer en boll att börja röra sig längs med slidern. Den orangea cirkeln, som kallas för en följecirkel, kommer att dyka upp när man håller i slider-bollen. Följecirkeln kommer däremot att försvinna när muspekaren är utanför cirkeln, eller när knappen släpps. Tryck och håll mus/tangentbordsknappen (eller håll pennan mot ritplattan) och följ bollen innanför följecirkeln medan den rör på sig.

Ibland, som i bilden ovan, kan bollen ändra riktning när den når sliderns slut. Spelaren måste då följa bollen tillbaka till början av slidern, eller vice versa. Detta representeras genom en pil som pekar tillbaka på slutet av slidern.

#### Spinners

![Spinner](/wiki/shared/osu_spinner.jpg "osu! spinners")

Tryck och håll in musknappen eller tangenten (eller tryck på ritplattan med pennan). Använd sedan musen (eller pennan) för att rotera muspekaren runt spinnerns mittpunkt åt valfritt håll tills spinner-cirkeln har växt till fullständig storlek. En *Clear*-notis dyker då upp för att indikera att spinnern är avklarad. Ifall spinnern blev avklarad tidigt, fortsätt snurra för att få bonuspoäng och hälsa.

Den yttre vita cirkeln visar hur mycket tid det finns kvar för att klara av spinnern. Cirkeln blir röd när tiden börjar rinna ut. Äldre skins, [skin version](/wiki/Skinning/skin.ini#versions) 1.0, har en mätare som visar hur nära spinnern är att bli avklarad.

Den lilla rutan nedanför spinnern visar spelares spin-hastighet, mätt i antal varv per minut.

## Spelstilar

*Se [Play Styles page under osu!](/wiki/Gameplay/Play_style).*

## Kontroller

Standardkontrollerna för osu! är följande:

| Mus | Tangenbord | Ritplatta/Pekskärm |
| :-- | :-- | :-- |
| Vänsterklick(M1) / Högerklick(M2) | `Z`(K1) / `X`(K2) | Skärmtryck(M1) |


Hitobjekt i osu! registrerar träffar från alla knappar på enheten, så länge varje hitobjekt är tryckta i tid.

Om [Relax](/wiki/Gameplay/Game_modifier/Relax)-modifikatationen används fungerar bara muspekaren. Använd muspekaren för att följa hitobjekten som istället trycks automatiskt. Spinners måste fortfarande avklaras.

Om [Auto Pilot](/wiki/Gameplay/Game_modifier/Autopilot)-modifikatationen används fungerar endast knapparna. Muspekaren rör sig automatiskt till varje hitobjekt, som behövs bara tryckas i tid. Spinners kommer att automatiskt snurras i samma fart som [Spun Out](/wiki/Gameplay/Game_modifier/Spun_Out)-modifikatationen.

## Score

[Score i osu!](/wiki/Gameplay/Score/ScoreV1/osu!) är en summa av flera olika delar av gameplay. Score beror på följande: 

- [Bedömning](/wiki/Gameplay/Judgement/osu!) bedömer mängden score ett hit-objekt ger (300, 100, 50, eller 0 för en miss). För [hit-cirklar](/wiki/Gameplay/Hit_object/Hit_circle) värderas tryck med bra timing högre, både vad gäller score och träffsäkerhet. [Sliders](/wiki/Gameplay/Hit_object/Slider) och [spinners](/wiki/Gameplay/Hit_object/Spinner) har inte en scorebedömning på samma sätt, men om slidern missas eller inte klaras av ordentligt kommer spelaren att tappa sin kombo. En bra timead träff kommer även att ge mer liv.
- [Träffsäkerhet](/wiki/Gameplay/Accuracy#osu!) beror på bedömningen och hur precisa trycken är. För tidiga eller för sena tryck, samt missar, sänker den totala träffsäkerheten.
- [Kombo](/wiki/Gameplay/Combo_(score_multiplier)) är en score-multiplikator. Ett objekt ger mer totala poäng när det avklaras om kombon är hög, och tvärtom. Kombo kan [tappas](/wiki/Gameplay/Judgement/Combobreak) genom en miss eller en [slider break](/wiki/Gameplay/Judgement/Slider_break).

Den totala mängden score ökar exponentiellt i takt med att spelaren "håller" kombo. Objekt närmare slutet av mappen är värda många gånger fler poäng än objekten i början (förutsatt att kombon inte tappas), vilket innebär att spelaren kan tappa mycket potentiella poäng i slutet av kartan när objekten inte trycks med rätt timing. Detta innebär att det är möjligt, och relativt vanligt, att scores med lägre träffsäkerhet kan ha mer poäng än scores med högre träffsäkerhet.

Efter att en karta har avklarats ges ett [betyg](/wiki/Gameplay/Grade#osu!), vilket är en kort träffsäkerhetspresentation i form av en bokstav. Ett guldigt eller silvrigt SS innebär 100% träffsäkerhet, medan allting annat, från S till D, beror på antalet 300s, 50s och missar.

## Skins

*Se [Skinning page of osu!](/wiki/Skinning/osu!) för fullständig information.*

## Beatmapping

*Se [Beatmapping page](/wiki/Beatmapping) för fullständig information.*

## Trivia

### Inspiration

Gameplayen i osu! är baserad på *[Osu! Tatakae! Ouendan](https://en.wikipedia.org/wiki/Osu!_Tatakae!_Ouendan)*, ett rytmspel för Nintendo DS. Precis som osu! består gameplayen av tre delar: Trycka på cirklar på skärmen, dra en boll längs med en bana, och snurra en spinner snabbt. Dessa tre delar kombineras och är timeade till covers av populära japanska låtar. Såhär ser det ut på DS:

![Exempel på gameplay i Osu! Tatakae! Ouendan in Nintendo DS](/wiki/shared/Ouendan.jpg "Gameplay example of Osu! Tatakae! Ouendan in Nintendo DS")

Gameplay-cirklarna syns på den nedre skärmen, medan berättelsen syns på den övre skärmen. Varje bana är en berättelse om en person med någon form av problem. Det är här *Ouendan* kommer in i bilden. Genom den magiska kraften av manlig cheerleading hjälper spelaren personen med problemen.

### Gameplay

![osu! smoke-effekt](/wiki/shared/osu_smoke.jpg "Smoke Usage")

![osu! smoke-inställningar](/wiki/shared/osu_smoke_set.jpg "Smoke in key bindings")

- Beroende på kartans svårighetsgradsinställningar och hur strikt inställningen för timing är kan *väldigt tidiga* klick på objekt göra att objektet vibrerar istället för att räknas som en miss.

- Om sliderbollen släpps på en tom sliderbana utan gömda eller synliga sliderticks kommer det inte resultera i en miss eller något score. Sliderns bedömning räknar endast ett par saker: Om slidercirkeln klickades, om sliderticksen följdes, samt om slutcirkeln i slidern avklarades.

- På Nintendo DS är spinners ett enkelt sätt att få rispor på skärmen, speciellt på svårare svårighetsgrader. I osu! har spinners gjorts enklare, för att de inte ska vara onödigt svåra att klara av. Det maximala antalet spins per minut är 477, vilket också är hur snabbt [Auto](/wiki/Gameplay/Game_modifier/Auto) modifikationen snurrar spinners. Modifikationen [Spun Out](/wiki/Gameplay/Game_modifier/Spun_Out) spinnar i ett långsammare tempo, 287 spins per minut.

- Om spelaren byter riktning på spinnern (motsols till medsols, eller vice versa) kommer spinnern att sakta ner (Spins per minut kommer gå ner till 0 för att nollställa spin-rikningen), och sedan kommer spinnern att börja spinna åt rätt håll igen. Framstegen på spinnern kommer inte att förloras när spinnern ändrar håll (framstegen kommer däremot inte att öka medan spinnern ändrar håll). Framstegen kommer att fortsätta när spinnern snurrar åt motsatt håll.

- Skulle spelaren inte snurra spinnern runt dess mittpunkt kommer spinnen **inte** att räknas som en godkänd spin.

- Smoke-effekten varar längre än spelets default markörspår. Använd smoke-effekten konservativt för att förhindra att gamla smoke-effekter försvinner för snabbt.

- Maskoten för osu! är [pippi](/wiki/Mascots#pippi).

- När [Auto](/wiki/Gameplay/Game_modifier/Auto) modifikationen är aktiv kommer spelarnamnet vara osu!.

### Historia

- Äldre versioner av osu! brukade emulera gamla beteenden från *Ouendan* serien innan beteendena  antingen togs bort eller byttes ut:
  - [Kombo fire](/wiki/Gameplay/Combo_fire) när nya kombo milestones uppnåddes.
  - Den första versionen av standardskinnet, vilket var *osu!default av peppy*, gav en näst intill identisk kopia av *Ouendan* interfacen.
    - Detta byttes sedan ut mot nuvarande standardskin, med v2 skin beteende.
  - Den mest märkbara skillnaden mellan v1 och v2 skin beteenden är spinnern.
    - Spinnern i v1 skinnet hade en mätare som fylldes från botten till toppen tills den var helt fylld, som i *Ouendan* serien.
      - Timern är en cirkel inuti spinnern som minskar inåt till mitten av spinnern. Spinnern tar slut när timer-cirkeln når mitten av spinners.
    - En spinnercirkel i v2 skinnet  expanderar långsamt tills den når sin fulla storlek. Spinnercirkeln börjar då lysa för att indikera att spinnern är avklarad.
      - Timern är den yttre cirkeln av spinnern som ändrar färg. Spinnern tar slut när timercirkelns färg har ändrats helt.
- De tre första kartorna som rankades på samma dag (07 October 2007, 2007-10-07) när online topplistan släpptes var följande:
  - [Kenji Ninuma - DISCO PRINCE (peppy)](https://osu.ppy.sh/beatmapsets/1), eller `discoprince`; som tydligen skapades (mappades?!?!?!) på ungefär en timme.
  - [Ni-Ni - 1,2,3,4, 007 \[Wipeout Series\] (MCXD)](https://osu.ppy.sh/beatmapsets/3 ) , eller `Ni-Ni - 1,2,3,4, 007 [Wipeout Series]`.
  - [Brandy - Love Fighter (FFFanatic)](https://osu.ppy.sh/beatmapsets/16), eller `Brandy - Love Fighter`.
- De äldre mapparna har ett eget namnformat (mappnamnen kan bara hittas i *uråldriga* beatmap packs) och följer inte strikt det numera upprätthållna `{BeatmapSetID} {ArtistNamn} - {BeatmapNamn}` formatet.
  - Laddar man ner beatmaps direkt från osu!webbsidans beatmaplista följs det nuvarande namnformatet.
