# Dat255_main_project
En test av maskinlæring innenfor patologi

# Prosjekt beskrivelse

I dette prosjektet har vi valgt å utforske maskinlæring i patologi. Patologi betyr sykdomslære, men det de hovedsakelig jobber med er å se etter diverse sykdommer og feil i bilder av vevsprøver. Disse bildene kalles for WSI (Whole Slide Images), og er mikroskopiske bilder av vevet som er farget og kuttet i tynne skiver. Det er dermed mulig for de å se etter kreft, fibrose og mer i forskjellig vev.

Problemet i dag er at antallet patologer synker og arbeidet de gjør blir ganske repetitivt, det å ha et verktøy som maskinlæring til å bruke hadde vært veldig nyttig og gjort arbeidet mer effektivt.

Målet med denne oppgaven er dermed å utforske litt for vår egen del hva maskinlæring kan klare bare med et bilde som input.

Vi har dermed tenkt å trene litt forskjellige modeller med litt forskjellige datasett, og gi disse modellene litt forskjellige oppgaver med forskjellige vanskelighetsgrader.

Til den første testen valgte vi å gå utfra en konkurranse i Kaggle hvor målet var å se etter kreft ved hjelp av disse bildene.

Den andre testen er et nytt datasett, hvor en del av informasjonen vi hadde var hvor mange måneder pasienten levde etter testen var tatt. Dette var nok den vanskeligste oppgaven vi gav til modellene, og vi hadde ikke så mye håp om at dette kom til å  fungere.

Den tredje og siste testen brukte samme datasettet som test nummer 2, men denne gangen ville vi trene modellen på hvilken molekylær subtype vevet hadde, vi testet faktisk to forkjellige, både på molekylær subtype og på histomolekylær subtype (som har en mer subtype i dette datasettet). Denne informasjonen kan brukes til prognose og behandling av brystkreft. Dette er ikke noe som er synlig på bildene og vi regner med dette egentlig var ment som tilleggs informasjon i datasettet til å trene modellen til noe annet, men det var likevel interessant for oss å se om modellen klarte å finne en kobling. Om den hadde klart det ville vi sett på dette som nyttig.


Vi var veldig begrenset til hva vi kunne gjøre i forhold til hvilke datasett vi kunne finne.  Vi brukte noen av de som var vedlagt i oppgaven, men ellers fant vi lite på nett som virket relevant for hva vi ville gjøre i oppgaven. Men likevel har vi fått eksperimentert litt og kommet frem til at for noen oppgaver så kan maskinlæring være veldig nyttig, men enkelte oppgaver er ikke egnet for dette.


