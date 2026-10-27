# Product Brief: AI Study Buddy

## Executive Summary
AI Study Buddy er en intelligent og interaktiv studiestøtteplattform utviklet for å hjelpe studenter med å bearbeide, oppsummere og repetere lærestoff på en mer effektiv måte. Ved å laste opp sine egne forelesningsnotater, lysbilder og pensumtekster (i PDF- eller tekstformat), får studentene automatisk generert skreddersydde sammendrag, interaktive flashcards og eksamensrelevante quiz-spørsmål.

Løsningen fyller et viktig behov i studiehverdagen ved å redusere tiden studenter bruker på manuell strukturering og renskriving av notater, slik at de i stedet kan fokusere på dypere forståelse og aktiv repetisjon. Samtidig gir applikasjonen studentene praktisk erfaring med hvordan kunstig intelligens og store språkmodeller (LLM) kan benyttes som et verktøy for tekstbehandling og læring.

Løsningen bygges som en moderne webapplikasjon med et brukervennlig grensesnitt og en sikker ryggrad som ivaretar personvern og opphavsrett for opplastet studiemateriale.

## The Problem
Studenter ved universiteter og høyskoler står overfor en stadig voksende mengde pensum, forelesningsnotater og presentasjoner. Å prosessere dette materialet krever betydelig tid og innsats, og mange studenter opplever følgende utfordringer:

* **Tidskrevende notatarbeid:** Studenter bruker uforholdsmessig mye tid på å strukturere, forkorte og omskrive lange notater manuelt fremfor å øve aktivt på stoffet.
* **Passiv lesing fremfor aktiv repetisjon:** Mange tyder til passiv gjennomlesing av foiler og tekst, noe forskning viser gir lav læringseffekt sammenlignet med aktiv gjenkalling (som flashcards og quizer).
* **Vanskelig å identifisere kjernebegreper:** Det kan være krevende å skille ut de viktigste nøkkelbegrepene og sammenhengene i omfangsrike emner.
* **Informasjonsoverflod og stress:** Store mengder ustrukturerte notater før eksamen fører til uoversiktlighet og økt eksamensstress.

## The Solution
AI Study Buddy løser disse utfordringene ved å automatisere de mest tidkrevende delene av studieprosessen. Applikasjonen fungerer som en personlig KI-assistent gjennom følgende opplevelse:

1. **Enkel opplasting:** Studenten laster opp sine notater eller forelesningslysbildefiler (PDF/TXT), oppgir kurskode/emne og velger ønsket detaljnivå samt språk.
2. **Automatisk bearbeiding:** Applikasjonen analyserer dokumentet og oppretter strukturerte sammendrag, en liste med viktige nøkkelbegreper og definisjoner, samt genererer automatisk interaktive flashcards og flervalgsquizer med fasit.
3. **Interaktiv læringsflate:** Studenten kan øve direkte på flashcards i appen, ta quizer for å teste egen kunnskap, og få umiddelbar tilbakemelding med referanser tilbake til de opplastede kildene.
4. **Trygg lagring:** Brukerens studiemateriale og genererte studiesett lagres trygt under brukerens egen profil for enkel tilgang gjennom hele semesteret.

## What Makes This Different
Selv om generelle KI-verktøy som ChatGPT kan oppsummere tekst, er AI Study Buddy spesifikt utformet for studiekonteksten og skiller seg ut på følgende måter:

* **Eksamens- og fagfokusert:** Genererer ferdige studieverktøy (flashcards og quizer) direkte tilpasset pensum og emnekode, i stedet for kun å gi ren tekst.
* **Kildereferanser:** Løsningen gir referansepekere tilbake til de spesifikke sidene eller avsnittene i det opplastede materialet der informasjonen ble hentet fra, noe som minimerer risikoen for feiltolkning eller "hallusinasjoner".
* **Sømløs arbeidsflyt:** Samler opplasting, sammendrag, begrepslister og øvingsquizer i én helhetlig prosess, uten at studenten må skrive kompliserte prompter selv.
* **Personvern i sentrum:** Brukerens opplastede forelesningsnotater behandles konfidensielt og deles ikke med eksterne uten tillatelse.

## Who This Serves
**Primærbrukere:**
* **Høyskole- og universitetsstudenter:** Studenter som ønsker en mer effektiv måte å bearbeide store mengder notater, forberede seg til forelesninger og øve til eksamen.

**Suksesskriterier for brukeren:**
* Rask konvertering fra rånotater til ferdige øvingssett (sammendrag, flashcards og quiz).
* Bedre oversikt over fagtekster og økt faglig mestring før eksamen.

## Success Criteria
* **Funksjonelle kriterier:** 
  * Brukeren kan opprette en konto, logge inn trygt og laste opp filer i PDF- og TXT-format.
  * Systemet genererer korrekte sammendrag, minst 10 flashcards og en quiz med svarforklaringer per opplastet dokument.
  * Brukeren kan gjennomføre en interaktiv quiz og få umiddelbar score og fasit.
* **Tekniske kriterier:** 
  * Behandlingstid for opplasting og generering av studiemateriale er under 15 sekunder for standard dokumenter.
  * Trygg håndtering av innlogging og brukerdata.
  * Responsivt og rent brukergrensesnitt som fungerer godt på både PC og nettbrett.
* **Kvalitetsmessige kriterier:** 
  * Genererte quiz-spørsmål og sammendrag skal ha høy faglig relevans og lav feilrate i henhold til opplastet kildemateriale.

## Scope

### In for Version 1 (MVP)
* Brukerregistrering og sikker innlogging.
* Filopplasting av forelesningsnotater og pensummateriale i PDF- og TXT-format.
* Valg av emnekode, språk (norsk/engelsk) og ønsket detaljnivå.
* Automatisk generering av:
  * Overordnet sammendrag og nøkkelbegreper.
  * Interaktive flashcards (kort med spørsmål/begrep på forsiden og svar/definisjon på baksiden).
  * Flervalgsquiz med fasit og korte forklaringer.
* Kildepekere som viser hvilken del av notatene informasjonen er hentet fra.
* Oversiktlig dashbord der brukeren kan se, administrere og ta fram tidligere opprettede studiesett.

### Explicitly Out of Scope for Version 1
* Direkte integrasjon med Canvas eller Feide (utsettes til fremtidige versjoner).
* Generering og håndtering av avanserte tabeller, matematiske formler eller kompleks grafikkanalyse fra PDF-er.
* Støtte for lyd- og videoopptak av forelesninger (kun tekst og PDF i v1).
* Mobilapp for iOS/Android (kun nettsideskjermer tilpasset skrivebord og nettbrett i v1).
* Kjøp/salg og deling av studienotater på tvers av brukere.

## Vision
Visjonen for AI Study Buddy er å bli studentenes foretrukne digital læringsassistent gjennom hele utdanningsløpet. På sikt skal plattformen utvikles til å tilby mer tilpasset og adaptiv læring, der KI-en identifiserer hvilke temaer studenten strever med og automatisk tilpasser vanskelighetsgraden på quizer og repetisjonsintervaller (Spaced Repetition). 

I fremtidige versjoner ser vi for oss sømløs integrasjon mot utdanningsinstitusjonenes plattformer (som Canvas og Teams), slik at forelesningsmateriale kan synkroniseres automatisk, samt mulighet for at studenter kan samarbeide i virtuelle skippertak-grupper støttet av KI.
