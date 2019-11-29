# People around the world

## De opdracht
Deze 2 weken bedenken we een interactief concept voor het museum Wereldculturen. Hierin moet de data van het museum terug te vinden zijn, bewerkt kunnen worden door middel van interactie en het programma moet gebouwd zijn met D3.

## Het concept

<img width="466" alt="Schermafbeelding 2019-11-29 om 09 45 12" src="https://user-images.githubusercontent.com/43657951/69856043-03b36a80-128d-11ea-8cca-362c737bfa1d.png">
Ik werd geinspireerd door de foto's van Jimmy Nelson die tentoongesteld staan bij het Volkenkunde Museum Leiden.
Op een kaart geef ik weer waar volken leven. Je kan filteren op cultuur/regio door te klikken op een foto van de persoon. Daarna krijg je de punten op de kaart te zien waar de objecten van deze cultuur zich bevinden. Door te hoveren over een punt wordt het object zichtbaar met een foto.

## Features
* Filter
* Zoomen
* Geef de objectfoto bij hover

## Onderzoek
Bekijk hoe ik op dit idee gekomen ben en zie het onderzoek in de [Wiki](https://github.com/marissaverdonck/frontend-data/wiki)

## Installatie
1. Open de terminal

2. Navigeer in de CLI naar de map waar de applicatie geinstaleerd kan worden

3. Type <br/>
```
Git clone https://github.com/marissaverdonck/frontend-data.git
```

4. Installeer NPM en de dependencies<br/>
```
npm install
```

## Data
Data wordt opgehaald uit de [collectie wereldculturen](https://collectie.wereldculturen.nl). De Data is opgebouwd als een thesaurus. Via SPARQL kan data worden opgevraagd. Ik zoek op regio en haal daarvan de link, plaatsnaam, type, imagelink, categorielabel, titel, longitude en latitude op.

<img width="560" alt="Schermafbeelding 2019-11-29 om 09 25 04" src="https://user-images.githubusercontent.com/43657951/69854764-2f812100-128a-11ea-87cb-06915a84a716.png">

<img width="1155" alt="Schermafbeelding 2019-11-29 om 09 37 27" src="https://user-images.githubusercontent.com/43657951/69855469-e29e4a00-128b-11ea-942b-5a60ee5f4240.png">

## Tools

• NPM

• D3

• SPARQL

## Credits

• Curran Kelleher - making a World Map. Bron: https://www.youtube.com/watch?v=Qw6uAg3EO64

• Jimmy Nelson - Inspiratie door de prachtige foto's Bron: https://www.jimmynelson.com

## License
[MIT License](https://github.com/marissaverdonck/functional-programming/blob/master/license)
