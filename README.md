##### CSS to the Rescue @cmda-minor-web 2020 - 2021

![Badge stating project is licensed under MIT license](https://img.shields.io/github/license/ralfz123/css-to-the-rescue-2021) ![Badge stating amount of issues open](https://img.shields.io/github/issues/ralfz123/css-to-the-rescue-2021) [![](https://img.shields.io/badge/site--status-up-success)](https://ralfz123.github.io/css-to-the-rescue-2021) [![Badges via shields.io](https://img.shields.io/badge/badges%20via-shields.io-brightgreen)](shields.io)

### Table of Contents
<table style="margin-left: auto; margin-right: auto;">
    <tr>
        <td align="center"><a href="#rocket-purpose-of-project">🚀 Purpose of Project<a></td>
        <td align="center"><a href="#week-1">Week 1 👋<a></td>
        <td align="center"><a href="#week-2">Week 2 💻<a></td>
        <td align="center"><a href="#week-3">Week 3 💻<a></td>
        <td align="center"><a href="#week-4">Week 4 🚨<a></td>
        <td align="center"><a href="#gear-installation">⚙️ Installation<a></td>
        <td align="center"><a href="#file_folder-sources">📁 Sources<a></td>
        <td align="center"><a href="#cop-license">👮 License<a></td>
    </tr> 
</table>

Deze README is een procesboek van afgelopen 4 spectaculaire CSS weken :sparkles: . Ik heb veel geleerd en erg veel geëxperimenteerd; dus neem een kijkje in mijn procesboek! :rocket:
# Week 1

## Kickoff
Ik heb onderzoek gedaan naar selectoren en toen heb ik een loginpage gemaakt daarover. Die is [hier](https://ralfz123.github.io/css-to-the-rescue-2021/kickoff) te vinden. Wanneer je ingelogd bent, zie je hetgeen wat Shabier en Sjors gemaakt hebben.

Ik heb hier gebruik gemaakt en research gedaan naar de selectors **(parent selectors)** `:valid`, `:invalid`, `:focus-within` , maar ook pseudo selectors als `:hover`, `:focus` en pseudo elements als `:after`. Hierdoor kwam ik achter de kracht van CSS.

Screenshot van hoe het login scherm eruit ziet:
<img src="assets/kickoff/images/login-page.png" />

## Concept eindbeoordeling
Ik heb het het volgende concept bedacht:  
Ik wil de HTML content van het menu pakken en daar een bepaalde huisstijl aan toevoegen. Mijn ideëen gaan nu uit naar een Swiss style design en die wil ik helemaal uitspitten en vervolgens wil ik de gerechten op de kaartjes weergeven en wanneer je er overheen hovert, dan draait hij om en zie je de ingrediënten erop staan. Overigens wil ik ook nog een soort functie aan kunnen zetten dat het van het rustige swiss design omtovert naar een erg druk design.

## Context
Mijn keuze voor context is de **`prefers-color-scheme`**, omdat ik het uitdagend vind om 2 verschillende kleurthema's toe te passen. Overigens heb ik dit nog nooit gedaan, maar het lijkt mij zeker een uitdaging om dit een keer te doen. Dit brengt zeker ook wat bij aan de UX. Ik heb al een [resource](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) gevonden van MDN waarin ze alles over dit principe uitleggen.

## Requirements
De eisen waar mijn product zich aan moet houden zijn*:
- SVG toepassen in shapes, masks én filters
- Twee kleuren

*Later ben ik zo diep in de materie gedoken dat ik me er helemaal niet meer aan gehouden heb

## Inspiratie

Voor de layout en design heb ik een Pinterest bord gemaakt waarop ik al mijn inspiraties pin. Het bord is [hier](https://nl.pinterest.com/ralfzonneveld/css-to-the-rescue-design-research/) te vinden.

De verschillende onderdelen wil ik op deze manier verwerken, dat als je op een gekleurde pagina drukt, dat hij dan zichbaar wordt (zie hieronder). ([Bron afbeelding](https://www.behance.net/gallery/61153051/One-Night-Only))

<img src="https://i.pinimg.com/564x/a7/37/70/a73770947a4b5792d05752ec1d6553f5.jpg" width="400px">

De manier waarop ik de cards wil laten zien staat hieronder ([Bron afbeelding](https://davisonpro.dev/)):
<img src="https://davisonpro.dev/wp-content/uploads/2019/09/Flipping-Card-HTML-CSS.gif"  width="400px">

## Sketch
<img src="assets/week1/sketch-concept-v1.jpg"  width="500px">

<img src="assets/week1/sketch-concept-v2.jpg"  width="800px">

### Ideëen voor het ontwikkelen
- CSS programming for `:hover` over page and then `z-index`?
- Gridbox
- Animation (`@keyframes`)


# Week 2
<!-- #### New Ideas: -->
#### Nieuwe ideëen
- Slider/carousel in plaats van paper-magazine
- Randomness color subjects
    - Media queries
- Header/titel applicatie
- Roteren van menu's

##### To-Do:
- [x] Label for input
- [x] Background image flip/animation.
- [ ] Dish cards flip -> uiteindelijk heb ik hier niet meer voor gekozen, omdat dat lelijk werd in het design.

<!-- #### New sketches: -->
#### Nieuwe schetsen
<img src="assets/week2/sketch_wk2.JPG" width="600px" />


## Stiekem programmeren met CSS
Het is me eindelijk gelukt om door middel van radio buttons een navigatie te maken en de cards te laten zien. Daarmee was ik erg aan het strugglen, maar nadat Vasilis zei dat ik de inputs in de root van de HTML moet zetten, konden de CSS selectors er wel bij en zo werkte de feature wel! Zie screenshots hieronder.

#### Before
<img src="assets/week2/before.png" width="600px" />

#### After
<img src="assets/week2/after.png" width="600px" />
<img src="assets/week2/after-2.png" width="600px" />

Ook heb ik leren werken met radial-gradient, maar dat heb ik weer verwijderd, omdat dat niet aansloot en paste bij mijn design.

# Week 3
<!-- labels andere plek want zijn door IDs gelink met hun input. -->

### Nieuwe ideëen
- Intro scherm met de titel van het restaurant [uitgewerkt]
- Background image gradient met een animation. Gaaf effect. [uitgewerkt]
- animatie maken [uitgewerkt] --> als raket en dan hover over h1 en dan zal raket verschijnen en weggaan
- header interactie met animaties
- `prefers-color-scheme` - Dark mode [uitgewerkt]:
    - Background dark gradient (custom properties veranderd)
    - Text color light (white)
- extra: media print (helaas niet uitgewerkt)

#### Header/titel zo breed als window

<img src="assets/week3/app-header.png" width="600px">

#### Random effect
Er gebeurt een nice random effect als je op een card hebt geklikt en daarna op een andere. Ze hebben dan allemaal een andere skew effect/richting. Daardoor gaan ze allemaal anders bewegen. Te gek!

<img src="assets/week3/raar-effect-skew.png" width="600px">


#### Prefers-color-scheme
##### Darkmode header
<img src="assets/week3/darkmode-header.png" width="600px">

##### Darkmode main
<img src="assets/week3/darkmode-main.png" width="600px">

### Screenshots tijdens het developen in chronologische volgorde

<img src="assets/week3/dev-1.png" width="600px">
<img src="assets/week3/dev-2.png" width="600px">
<img src="assets/week3/dev-3.png" width="600px">
<img src="assets/week3/dev-4.png" width="600px">
<img src="assets/week3/dev-5.png" width="600px">

# Week 4
### Raket maken en animeren :rocket:
Het is gelukt om een vorm te maken  (een rakte) en te laten bewegen over het scherm. Op het moment dat je over de titel van website hovert, zal de titel verdwijnen en de raket verschijnen.

<img src="assets/week4/rocket.png" width="600px">


## :gear: Installation
1. Clone the repository:  
```
git clone https://github.com/ralfz123/css-to-the-rescue-2021.git
```

2. To run the app   
```
python -m SimpleHTTPServer 8000  
```

3. Go to [localhost](http://localhost:8000/) in the browser
```
http://localhost:8000/
```

## :file_folder: Sources
Credits to [Sanne 't Hooft](https://github.com/shooft), Vasilis van Gemert, Thijs Spijker and Leonie Smits for giving interesting lectures about CSS and how to deal with it.


### LOREM sources
- **example** Lorem. (n.d.). Documentation Lorem. - Lorem Inc. Retrieved 28 December 2020, from https://Lorem.com/

### Other sources
<!-- - Stackoverflow (n.d.). Searching for answers on dev questions - Stackoverflow. Retrieved 02 February 2021 from https://www.stackoverflow.com -->

## :cop: License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
This project from [Ralf](https://github.com/ralfz123) has a [MIT © License](https://github.com/ralfz123/css-to-the-rescue-2021/blob/main/LICENSE)
