# RAPPORT GRUPPE 2B #

Denne markdown filen vil inneholde en beskrivelse av fremgangsmåten vår, FS-ANALYSE, FS-SYSTEM, FS-SYSTEM-STEG og FS-TESTER. Resten, som er GR-KUNN-FERD og GITHUB-SAMARBEID leverer vi som pdf i canvas. Dette er for å gjøre oppgaven oversiktelig og inkludere det innholdet som er mest relevant til oppgaven i repositoryen. 


<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#fs-analyse">FS-ANALYSE</a>
    <li><a href="#fs-system">FS-SYSTEM</a></li>
    <ul>
        <li><a href="#fs-system-steg">FS-SYSTEM-STEG</a></li>
      </ul>
    </li>
    <li><a href="#fs-tester">FS-TESTER</a></li>
    <li><a href="#kilder">Kilder</a></li>
  </ol>
</details>


<!-- FS-ANALYSE -->
## FS-ANALYSE
How We Roll - Fellesskapet var hoved brukerhistorien og prioriteringen vår. Når den var helt ferdig fortsatte vi å lage andre ekstra brukerhsitorier vi som gruppe tenkte var relevant og artig. 

__How we roll brukerhistorie med eksempel:__

Som et team vil vi ha en undersøkelse hvor hvert spørsmål har to motsatte personlige preferanser og deltakere får muligheten til å gi sin meningen ved å dra en slider frem og tilbake innenfor en bestemt linje, slik at vi kan hente dataen fra undersøkelsen og bestemme hvordan vi skal jobbe.
Slik at jeg kan hente denne dataen for å lage et rapport, vil jeg som en deltaker at mine svar lagres i et eksternt server med en url.

Akseptansekriterier : Vi må ha minst 10 range sliders i rapporten som gir informasjon om alle i gruppen. Deretter må de samles og det blir lettere å se gjennomsnittsverdier.
F.eks Mie er gruppe lederen av gruppe 2B og hun ville ha en ekstra møte med medlemmer for å planlegge 114 oppgaven. Hun sjekker how we roll rapporten og ser at mest av medlemmene foretrekker å ha møte på morgen og på discord. Da kan Mie invitere folken til gruppesmøte søndag morgen via discord.

How We Roll vil hjelpe oss med å skaffe mye informasjon om medlemmene våre. Alle spørreundersøkelser vil bli lagt til kunnskapen vi tidligere har fått om våre medlemmer gjennom en samarbeidsprosess. Dette vil hjelpe oss i å lære mer om vaner til medlemmer og lære hvordan vi kan fikse uvaner. Som et resultat vil vi kunne overkomme utfordringer som gjør at vi misforstår, mangler kommunikasjon og ikke klarer å fullføre oppgavene i tide.


__Ekstra brukerhistorier:__
1. Som sagt ovenfor er How We Woll hoved brukerhistorien vår. Den har en egen side både for sliderne/innhenting av informasjon, denne heter "How We Roll". Vi har også en egen side for resultatene og rapporten som heter "Resultater" - begge finnes i navigation baren og utgjør vår besvarelse på How We Roll brukerhistorien. 
2. Vi har laget en hjemmeside for webaplikasjonen vår. På hjemmesiden har vi laget en gruppe CV der alle gruppemedlemmene står med bilde, navn, studie, interesse og en knapp med link til hvert medlems github bruker. 
3. En annnen ekstra brukerhistorie er siden "Prosjektets prosess" som er i navigation baren og er en egen side med informasjon om prosessen vår i dette prosjektet.
4. Siste brukerhistorie er en egen side til denne rapporten, som tillater folk å både se den og laste den ned som pdf. 

Dette er den prioriterte rekkefølgen på våre brukerhistorier. Vi valgte denne prioriteringen utifra hva vi mente var vitkigst å få med, og hva som var bonus poeng om vi rakk. Da den obligatoriske delen var første prioritert, deretter gruppe CV som er nyttig for lærerene å se hvem som deltok i prosjektet, til slutt var det eksta brukerhistorier som ikke var like kritisk. 

<!-- FS-SYSTEM -->
## FS-SYSTEM 

Html attributene fikk navn i forhold til funksjonen til elementene. Disse navnene ble valgt slik at andre som ser på koden kan forstå hva elementen inneholder. Siden disse elementene har fått navn som klasser, fikk vi muligheten til å kalle disse fra css filen og samtidig script elementet som inneholder funksjonelle javascript kode. 
I css kalte vi “slider”,  “slidercontainer”, “button” og samtidig andre globale elementene (sånn som body) for å gi stil til FS-SYSTEM. I script kalte vi “form” og “submit” elementene for å kunne hente dataene fra html. “Form” elementen inneholder dataen og “submit” elementen kobler knappen til script funksjonen. 
På denne måten har vi gjort prosessen fra html input til json output.

Når det gjelder datamodellen, har vi valgt å bruke to string elementer som er navn og etternavn, tolv nummer elementer som kommer fra html range elementene, og samtidig transaksjons-id og tid-stempel. Disse lagres i en JSON object literal.


### FS-SYSTEM-STEG

__Skisser:__

Som står i GR-KUNN-FERD har vi lært allerede å bruke systemer f.eks. html, css, kanban og github. Først laget vi website template. Og deretter laget vi 12 forslag til data kategorier i websiden fanen, operert folkens egne egenskaper med WEB-FORM. Det betyr data fra brukerne er samlet for rapporten. Dataene som vi lagde er input.  Etter er alle ferdig med å legge inn data, vi laget en forståelig rapport viser at vaner av gruppe medarbeider. Så er dataene fra WEB-FORM behandlet som output i WEB-RAPPORT. 


<img width="595" alt="Skjermbilde 2022-10-28 kl  16 36 14" src="https://user-images.githubusercontent.com/111752047/198653736-95fc4f2e-1d11-4c43-a5c8-0e550521e4e1.png">


Html attributene fikk navn i forhold til funksjonen til elementen. Disse navnene ble valgt slik at andre som ser på koden kan forstå hva elementen inneholder. Siden disse elementene har fått navn som klasser, fikk vi muligheten til å kalle disse fra css filen og samtidig script elementet som inneholder funksjonelle javascript kode. 
I css kalte vi “slider”,  “slidercontainer”, “button” og samtidig andre globale elementene (sånn som body) for å gi stil til FS-SYSTEM. I script kalte vi “form” og “submit” elementene for å kunne hente dataene fra html. “Form” elementen inneholder dataen og “submit” elementen kobler knappen til script funksjonen. På denne måten har vi gjort prosessen fra html input til json output.

<img width="463" alt="Skjermbilde 2022-10-28 kl  16 45 25" src="https://user-images.githubusercontent.com/111752047/198655860-040e0414-53dd-49a3-bc1d-d4d9552fabc5.png">
Forskjellige skisser som viser prosessen fra INPUT til OUTPUT.



<img width="612" alt="Skjermbilde 2022-10-28 kl  16 43 36" src="https://user-images.githubusercontent.com/111752047/198654482-2b6d75a9-1786-43ea-abbd-e0b816ca80be.png">


Skissene fra FS-SYSTEM er en abstrakt skisse til hvordan systemet vårt skal fungere. Med systemet prater vi om å omgjøre brukerens input til brukbar output. Istedenfor at vi går rett på kodingen, blir det mer oversiktlig hvis vi bryter oppgaven ned til mer abstrakte modeller.
Hvordan input dataen skal sendes inn og hvordan output dataen blir hentet vil bli slik:

* Input
    - Brukerens fornavn og etternavn i to forskjellige tekst input bokser.
    - Denne dataen må fylles ut får brukeren kan sende inn sin besvarelse, dette er for å unngå systemfeil.
    
* Slider dataen, brukerens meninger om spørsmålene vi stiller hverandre.
    - Denne dataen blir lagret som talldata.
    - På grunn av at det er flere sliders kunne dette blitt lagret som array, men det kompliserer oppgaven mer og er ikke nødvendig fordi antall sliders er           statisk.
   
* Dato når dataene blir sendt inn.
    - Dette vil egentlig ikke brukeren fylle ut, men heller gjøres automatisk av nettsiden.
    
* En individuell id.
    - Dette kan løses med et veldig stort tilfeldig tall. Tallet kan dobbelsjekkes med de eksisterende tallene i serveren slik at de ikke ‘klasher’.
Denne input dataen vil bli sendt fra nettsiden til EKSTERN-SERVER. Neste steget nå er å kunne hente og lese denne dataen.

* Output - All dataen fra EKSTERN-SERVER vil bli hentet inn når siden lastes ned og den vil bli lagret slik:
  * Class, data satt inn i ei struktur. I klassen må vi ha:
    - Navn
    - Korresponderende id
    - Hver individuell tall verdi til hver slider, som sagt kunne dette være en array men det blir mer komplisert enn nødvendig

I det fjerde siste punktet var “class” nevnt og forklart som strukturert data. Ved å bruke klasser, som blir dannet til objekter, vil gjøre koden mye renere og lese og mye lettere for å samarbeide i koden.

Når det gjelder datamodellen, har vi valgt å bruke to string elementer som er navn og etternavn, tolv nummer elementer som kommer fra html range elementene, og samtidig transaksjons-id og tid-stempel. Disse lagres i en JSON object literal.
<img width="511" alt="Skjermbilde 2022-10-31 kl  14 56 29" src="https://user-images.githubusercontent.com/111752047/199025280-a5b46a1b-e6de-4acd-9bb4-cfbc3a0a6c80.png">
Datamodellen

<!-- FS-TESTER -->
## FS-TESTER
Ved å se på FS-SYSTEM-STEG og funksjonene som hører med stegene vil det være nødvendig, i henhold til kravspesifikasjonen å teste dette.
Her beskriver vi funksjonene som gir oss ønsket output:

__Tester:__


__Brukerscenario:__ lage en fungerende range slider

__Verktøy:__ HTML 5, CSS

__Egnede funksjoner:__ <input type="range"> (html element, ikke funksjon)

__Testfunksjon som påkaller funksjon:__  .slider (kalles i css men ellers er elementet visst i nettleseren.

__Utfør testfunksjon:__
 <td colspan="3"> <input type="range" name="worktime" id="worktime" min="0" max="100" value="50" class="slider" ></td>
(tabell element er visst i nettleseren med verdier sånn som navn, min, max osv.)

<br>
<br>
<br>

__Brukerscenario:__ Etter å ha fylt inn min informasjon i range slidersene trykker jeg på submit button og får resultatene (hvordan de lagers på ekstern server)

__Verktøy:__ HTML, JavaScript

__Egnede funksjoner:__ function postData(event){}

__Testfunksjon som påkaller funksjon:__ function handleSubmit{}
(postData kalles i handleSubmit funksjonen.)

__Utfør testfunksjon:__
async function postData(url ='https://bacit.info/', data = {}) {
   const response = await fetch(url, {
       method: 'POST',    
    mode: 'cors', value
       cache: 'no-cache', 
       credentials: 'same-origin', {
           'Content-Type': 'application/json'},
       redirect: 'follow', 
       referrerPolicy: 'no-referrer', 
       body: JSON.stringify(data) 
"Content-Type"});
   return response.json();}
(Metoden som kalles for å poste data i bacit.info)
postData('https://bacit.info/', formJSON) 

<br>

__Brukerscenario:__ Deretter må vi kunne hente resultatene i serveren bacit.info

__Verkøy:__ Html, JavaScript

__Egnede funksjoner:__ function handleSubmit(event)

__Testfunksjon som påkaller funksjon:__ data => {}
(denne metoden lar oss hente dataen med en Url som har trxid od tid)
Utfør testfunksjon:  .then(data => {
   let trxid = JSON.stringify(data.trxid, null, 2).replace(/"/g, "");
  let time = JSON.stringify(data.time, null, 2).replace(/"/g, "");  

<br>

__Brukerscenario:__ Tegne en rektangel i nettleserens vindu

__Verktøy:__ html,css, javascript, Canvas API

__Egnede funksjoner:__ function tegnKvadrat() {}

__Testfunksjon som påkaller funksjon:__ function submitButton() {}
Utfør testfunksjon: <button onclick=”submitButton”> </button>
function tegnKvadrat() {“ctx.beginPath(); ctx.rect(x1,y1, x2, y2); ctx.stroke();
”}

<br>

__Brukerscenario:__ Tegne linjer og skrive tekst inni rektangelen

__Verktøy:__ html,css, javascript, Canvas API

__Egnede funksjoner:__ function tegnLinjeOgSkrivTekst() {}

__Testfunksjon som påkaller funksjon:__ function submitButton2() {}

__Utfør testfunksjon:__ <button onclick=”submitButton2”> </button>
function  tegnLinjeOgSkrivTekst() {Linje: ctx.beginPath(); ctx.moveTo(x, y); ctx.lineTo(x, y); ctx.fill(); }

<br>

__Brukerscenario:__ Tegne sirkler i bestemte farger og størrelser

__Verktøy:__ html,css, javascript, Canvas API

__Egnede funksjoner:__ function tegnSirkler() {}

__Testfunksjon som påkaller funksjon:__ function submitButton3() {}

__Utfør testfunksjon:__ <button onclick=”submitButton3”> </button>
function tegnSirkler() {Sirkel: ctx.arc(x, y, 10, 0, 2 * Math.PI, false); ctx.fill();
}



<!-- Kilder -->
## Kilder

Othneildrew, u.å, Best ReadMe Template, ukjent, Source code:
https://github.com/othneildrew/Best-README-Template


W3schools, u.å, How TO - Range Sliders, ukjent, source code:
https://www.w3schools.com/howto/howto_js_rangeslider.asp


Mozilla, u.å, <center>: The Centered Text element, ukjent, source code:
https://developer.mozilla.org/en-US/docs/Web/HTML/Element/center

  
Codingartistweb, u.å, Custom Range Slider, ukjent, source code:
https://codingartistweb.com/2021/07/custom-range-slider-html-css-javascript/

  
W3schools, u.å, Json objects literal, ukjent, source code:
https://www.w3schools.com/js/js_json_objects.asp 

  
SheCodes, u.å, Css Gradient Generator, ukjent, source code:
https://generators.shecodes.io/css-gradient-generator


Àlvaro, u.å, Untitled, ukjent, source code:
https://codepen.io/alvarotrigo/pen/mdBbEPj 

  
Gruppe repo eksempler:
  
https://github.com/theodorUIA/howweroll 
  
https://github.com/stinawest/how-we-roll


