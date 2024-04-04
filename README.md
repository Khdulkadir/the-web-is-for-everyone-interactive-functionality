> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)

# Red Pers
Omzetten van nieuwssite gemaakt met elementor naar ejs en node.
<!-- Geef je project een titel en schrijf in één zin wat het is -->
![image](https://github.com/Khdulkadir/server-side-rendering-server-side-website/assets/144004145/1dba716c-aed1-4173-ac49-902bd3bdcd5f)


## Beschrijving

Red Pers is een toegankelijk en inclusief opleidingsplatform voor jonge, aspirerende journalisten. Bij ons kunnen zij zich ontwikkelen, workshops volgen, producties publiceren en zich klaarstomen voor een journalistieke carrière. Door samen te werken met redacties en onderwijsinstellingen, verbinden we een brede groep studenten met de journalistieke wereld. Dit levert meer diversiteit en vakinhoudelijke kennis op bij mediabedrijven. Zo vormen wij een springplank voor de journalisten van de toekomst.

De originele website van Red Pers werkte niet naar behoren. Ik heb daarom deze website omgezet van een Wordpress naar een met de hand gecodeerde website voor een betere snelheid en toegankelijkheid.

## Gebruik
<!--Bij Gebruik staat hoe je project er uit ziet, hoe het werkt en wat je er mee kan. -->
Met behulp van EJS en NodeJS is deze website gemaakt. De website haalt data op van de API van Wordpress en de API van Directus. Gebruikers kunnen artikelen lezen en artikelen liken.

## Kenmerken
<!-- Bij Kenmerken staat welke technieken zijn gebruikt en hoe. Wat is de HTML structuur? Wat zijn de belangrijkste dingen in CSS? Wat is er met Javascript gedaan en hoe? Misschien heb je een framwork of library gebruikt? -->
Progressive enhancement

Ik heb mijn article.ejs pagina, waarop de POST interactie voorkomt, getest aan de hand van de Progressive Enhancement methode. Ik heb getest op de desktop en mobile browsers van Chrome, Edge en Firefox. Ook heb ik getest op Safari op een Ipod Touch. Ik heb gelet op de drie lagen die aan bod komen bij progressive enhancement:

<pre>
Laag 1: De functionaliteit is aanwezig en heeft de pagina een goede basis.
Laag 2: De huisstijl en gebruikersfeedback zijn toegevoegd.
Laag 3: Eventuele complexere en nieuwere codeermethoden worden gebruikt.
Chrome, Edge en Firefox bleken meteen de website zoals bedoeld te renderen. Alle drie de lagen kwamen met succes uit de verf. Op de Ipod Touch was het een ander verhaal. Daar bleken 'laag 2' en 'laag 3' niet correct te werken. Door het gebruik van modernere CSS properties en CSS nesting werd deze CSS code genegeerd. Caniuse.com geeft ook aan dat nesting, gap en scale nog redelijk recent zijn. Gelukkig bestaat mijn 1e laag uit goede en semantische HTML, waardoor de functionaliteit van de website zelfs op dit oude apparaat niet verloren ging.
</pre>

## Installatie
<!-- Bij Instalatie staat hoe een andere developer aan jouw repo kan werken -->
Na het forken van de repo heb ik eerst ik alle vereiste bestanden aangemaakt in VS Code. Server.js voor de backend, /views voor de ejs code, /public voor alle assets. Daarna heb ik npm install ingevoerd in de console om Node modules te installeren. Alle backend code heb ik overgenomen van de vorige sprint voor zover dat mogelijk was.

## Bronnen

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
