# Bloemenveld Frankendael - Prototype 1
Welkom bij de README van het eerste prototype voor **Bloemenveld Frankendael**! Dit project is ontwikkeld voor het bewonersinitiatief Bloemenveld Frankendael (Buurtcampus Oost / HvA) om bezoekers van Park Frankendael op een laagdrempelige, visuele manier bewust te maken van de tuin, planten en biodiversiteit.

## Inhoudsopgave Readme

  * [Beschrijving](#beschrijving)
  * [Kenmerken](#kenmerken)
  * [Bronnen](#bronnen)
  * [Licentie](#licentie)

## Beschrijving
In dit project bouwen we voort op het eerdere prototype dat vorig jaar is ontworpen door een CMD-student. Waar dat prototype de basis legde, hebben wij ons gericht op het verder ontwikkelen en verbeteren van de functionaliteit van de kaart.

- **Eigen illustratie/plattegrond:** Om het veld nauwkeurig en sfeervol weer te geven, is er eerst een illustratie gemaakt in Adobe Illustrator met de juiste grenzen en huisstijlkleuren.   

- **Interactieve pins & pop-ups:** Op de kaart staan pins voor elke plant. Wie scrolt en klikt op een pin, krijgt direct een pop-up te zien met de belangrijkste plantinformatie en een optie om door te klikken naar de volledige verzameling.
<img width="400" height="auto" alt="Bloemenveld_kaart" src="https://github.com/user-attachments/assets/63118179-58ee-4920-a74f-e0c50b8c9ae6" /> <img width="200" height="200" alt="icon_nav-02" src="https://github.com/user-attachments/assets/6c74b645-c7ed-4e5a-bede-b3435b8ba76d" />


## Kenmerken
Voor deze opdracht heb ik me sterk gericht op het schrijven van schone, gestructureerde code en moderne stylingtechnieken. 
* **Semantische HTML:** Er is gewerkt met schone code en semantische elementen zoals `<ul>` en `<li>` lijsten om plantenoverzichten netjes en toegankelijk in te richten.


```html
<ul class="tabs">
                    <li><button class="tab active">Kaart Overzicht</button></li>
                    <li> <button class="tab">Plantencollectie</button></li>
                </ul>
```             



* **CSS `:root` variabelen:** Ik heb geleerd en gewerkt met `:root` in CSS om kleuren en instellingen globaal en overzichtelijk vast te leggen.

```css
:root{
    --primary-color: #a38c75;
    --card-background: #ffffff;
    --text-dark: #5c4033;
    --font-family: montserrat;
}
```

* **Flexbox & Layout:** Moderne layout-technieken zijn toegepast om elementen flexibel en responsief in te delen.

```css
.app-container {
    width: 100%;
    max-width: 412px;
    height: 100vh;
    max-height: 847px;
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    overflow: hidden;
    box-shadow: 0 10px 25px rgba(0,0,0,0.5);
    background-color: #222; 
}
```

## Licentie

This project is licensed under the terms of the [MIT license](./LICENSE).
