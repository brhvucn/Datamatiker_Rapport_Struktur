# Rapport

## Forside (inkl. eventuelle formkrav)
## Introduktion
Introduktionen til rapporten indeholder noget omkring problemområdet. Det er i særdeleshed vigtigt, hvis du arbejder med et emne i din rapport som ikke er et emne indenfor undervisningen, således at underviser og censor får en god forståelse af emnet. Hvis dette projekt er udarbejdet sammen med en virksomhed er det også her man vil give en introduktion til virksomheden, deres overordnede interesse i dette og hvilke områder virksomheden arbejder indenfor.

## Krav
Dette afsnit indeholder en beskrivelse af kravene til arbejdsopgaven. Her skal det bemærkes at der mange gange beskrives ud fra hvordan verden ser ud i dag og de problemer som en virksomhed oplever. Det kan være svært at trække krav ud fra et problemområde og man bør altid bruge en struktureret process til at gøre det med, så man ikke bare "gætter" på krav, men faktisk er struktureret og systematisk omkring det. Metoder til at udtrække krav med kan være `FURPS+` eller `MoSCoW` - der er flere måder at gøre det på.

Som en del af kravene vil man beskrive det problem man vil løse - altså en problemformulering.

## Analyse
Analysen er den del af udviklingen som prøver at kortlægge hvordan verden ser ud i dag. Det vil sige man vil analysere problemdomænet, forstå brugerne og begynder en dybere analyse for at finde ud af hvordan man skal designe mod fremtiden, med forbedringerne til systemet. Man skal huske at dette handler ikke omkring hvilket system man vil bygge, men det handler om at klarlægge problemet som er beskrevet i problemformuleringen ud fra en analyse.

Her vil man måske kigge på organisationen, økonomien, nuværende udviklingsmetode, nuværende teknologier eller andet som kan være med til at tegne et billede af de problemer der er i dag.

## Design
Dette afsnit handler omkring fremtiden, hvordan vil dette system løse de problemer vi har fundet i vores analyse fase og hvordan designer vi den somtware som skal understøtte dette? Her handler det om at designe software, i dette afsnit vil der mange gange være et valg af arkitektur (valgene af arkitektur skal understøtte de krav man har kortlagt i kravsafsnittet). Det er også her man mange gange vil træffe valg omkring platform (database, programmeringssprog, servicebus, protokoller og meget mere).

## Implementering
Implementeringen handler om at eksekvere på sit design. Populært sagt skal man "bare oversætte designet til kode". I praksis er der typisk mere i dette, dette i særdeleshed ud fra et agilt perspektiv.

I implementeringsfasen skal man også træffe et valg omkring sin applikationsarkitektur. Det vil sige man skal kigge på `tre-lagsarkitektur` eller `clean arkitektur`(eller noget helt andet), man skal kigge på kodeprincipper som `Don't repeat yourself (DRY)`, `Descriptive And Meaningfull Phrases (DAMP)`, `S.O.L.I.D Principper`, `CQRS` og meget andet. Man kan sige at man skal finde sin "implementeringsstil" for dette projekt. Det kan eksempelvis være at man vil kode meget defensivt og have guard clauses i hver metode, eller noget helt andet. Dette hører hjemme i dette afsnit og beslutningerne man træffer omkring det skal pege bagud til designet, analysen og de krav man har fremsat. Der skal hele tiden være denne "røde tråd".

## Test
## Overdragelse / drift
## Konklusion
## Bilag
