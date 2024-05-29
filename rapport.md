# Rapport

## Forside (inkl. eventuelle formkrav)
## Introduktion
Introduktionen til rapporten indeholder noget omkring problemområdet. Det er i særdeleshed vigtigt, hvis du arbejder med et emne i din rapport som ikke er et emne indenfor undervisningen, således at underviser og censor får en god forståelse af emnet. Hvis dette projekt er udarbejdet sammen med en virksomhed er det også her man vil give en introduktion til virksomheden, deres overordnede interesse i dette og hvilke områder virksomheden arbejder indenfor.

## Krav
Dette afsnit indeholder en beskrivelse af kravene til arbejdsopgaven. Her skal det bemærkes at der mange gange beskrives ud fra hvordan verden ser ud i dag og de problemer som en virksomhed oplever. Det kan være svært at trække krav ud fra et problemområde og man bør altid bruge en struktureret process til at gøre det med, så man ikke bare "gætter" på krav, men faktisk er struktureret og systematisk omkring det. Metoder til at udtrække krav med kan være `FURPS+` eller `MoSCoW` - der er flere måder at gøre det på.

### Problemformulering
Som en del af kravene vil man beskrive det problem man vil løse - altså en problemformulering. Problemformuleringen er svær at skrive og man må acceptere at man kommer til at rette den til eller helt ændre den undervejs i projektet. Husk på at man arbejder agilt og iterativt og som projektet skrider fremad får man mange gange mere information omkring projektet som gør at man vil opdatere sin problemformulering.

Problemformuleringen består typisk af et overordnet problem og måske et eller flere undersøgelsesspørgsmål. Husk på at problemformuleringen skal beskrive et _problem_ ikke et ønske til læring.

## Analyse
Analysen er den del af udviklingen som prøver at kortlægge hvordan verden ser ud i dag. Det vil sige man vil analysere problemdomænet, forstå brugerne og begynder en dybere analyse for at finde ud af hvordan man skal designe mod fremtiden, med forbedringerne til systemet. Man skal huske at dette handler ikke omkring hvilket system man vil bygge, men det handler om at klarlægge problemet som er beskrevet i problemformuleringen ud fra en analyse.

Her vil man måske kigge på organisationen, økonomien, nuværende udviklingsmetode, nuværende teknologier eller andet som kan være med til at tegne et billede af de problemer der er i dag.

Her kan man forestille sig at man tager en lommelygte og lyser på problemet, man må kun beskrive det man ser i sin analyse. Man må ikke træffe beslutninger eller begynde implementationen i analysen.

* **Input:** Vigtigt at man forholder sig til problemet og problemformuleringen og holder sig indenfor rammerne af det man har skrevet. Analysen skal have en _rød tråd_ tilbage til problemet og til problemformuleringen.
* **Output:** Det er vigtigt at efter Analysen har man et overblik over de problemer, der er i projektet og hvilken indflydelse de har på virksomheden, mennesker eller omverden (aktører). Dette gør det muligt for næste afsnit at adressere disse problemer. Hvis man skal bruge en sportsmetafor så skal dette afsnit i rapporten _lægge op til_ næste afsnit.
* **Længde:** Dette er et af de store og vigtige afsnit i rapporten. Der er som sådan ikke noget krav til længden, men de fleste analyseafsnit fylder omkring 10 sider.

## Design
Dette afsnit handler omkring fremtiden, hvordan vil dette system løse de problemer vi har fundet i vores analyse fase og hvordan designer vi den somtware som skal understøtte dette? Her handler det om at designe software, i dette afsnit vil der mange gange være et valg af arkitektur (valgene af arkitektur skal understøtte de krav man har kortlagt i kravsafsnittet). Det er også her man mange gange vil træffe valg omkring platform (database, programmeringssprog, servicebus, protokoller og meget mere).

## Implementering
Implementeringen handler om at eksekvere på sit design. Populært sagt skal man "bare oversætte designet til kode". I praksis er der typisk mere i dette, dette i særdeleshed ud fra et agilt perspektiv.

I implementeringsfasen skal man også træffe et valg omkring sin applikationsarkitektur. Det vil sige man skal kigge på `tre-lagsarkitektur` eller `clean arkitektur`(eller noget helt andet), man skal kigge på kodeprincipper som `Don't repeat yourself (DRY)`, `Descriptive And Meaningfull Phrases (DAMP)`, `S.O.L.I.D Principper`, `CQRS` og meget andet. Man kan sige at man skal finde sin "implementeringsstil" for dette projekt. Det kan eksempelvis være at man vil kode meget defensivt og have guard clauses i hver metode, eller noget helt andet. Dette hører hjemme i dette afsnit og beslutningerne man træffer omkring det skal pege bagud til designet, analysen og de krav man har fremsat. Der skal hele tiden være denne "røde tråd".

## Test
Det er typisk lidt misvisende at man har et særskilt afsnit med test i sin rapport, i særdeleshed, hvis man arbejder agilt. Grunden til at have det er at man præsenterer en rapport i en sekventiel metode, mens man udvikler mere agilt. Det vil sige at strukturen på ens rapport ikke nødvendigvis afspejler den måde man har arbejdet på. I en agil udviklingsmodel laver man test hele tiden, i alle faser af sin udvikling. Test er også mange gange lidt et misvisende ord, det handler måske mere omkring kvalitetssikring - det vil sige, hvordan sikrer du at det software du leverer er at høj kvalitet. Det vil være en god ide at redegøre for hvorledes man vil sikre kvaliteten af sin software tidligt i rapporten og hvilke handlinger man udfører for at få det hele til at gå op.

Kvalitetssikring omfatter også tests, det vil sige at man tidligt skal tage stilling til hvordan man vil styrke kvaliteten af sit software. Dette er alt fra at forstå kunden til at lave User Stories og til at lave Unit Tests. Mange gange bruger man `Agile Test Quadrants` modellen til at strukturere sit kvalitetsarbejde efter.

## Overdragelse / drift
## Konklusion
Konklusionen er opsamlingen af hele rapporten. Den skal adressere de forskellige punkter man har arbejdet med undervejs i rapporten og i særdeleshed den problemformulering man har skrevet. I princippet skal man kunne læse problemformuleringen og få svar på sine spørgsmål / problemer i selve konklusionen.

* **Længde:** Ingen faste krav om længde, men min. en halv side - afhængig af hvor kompleks problemformuleringen er
## Bilag
