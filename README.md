# GroceryApp sprint2 

Gitflow Workflow

Voor dit project word er gebruik gemaakt van de Gitflow methode om de ontwikkeling gestructureerd en overzichtelijk te houden.

Binnen Gitflow worden de volgende branches gebruikt:


## main
Bevat de stabiele, productierijpe code. Alles in deze branch is getest en klaar om in productie te gebruiken.


## develop
De integratiebranch waarin alle nieuwe features samengevoegd worden. Hier staat altijd de laatste werkende ontwikkelversie.


## feature/…
Voor iedere nieuwe user case of functionaliteit wordt een aparte feature branch aangemaakt.

- feature/UC5 → voor de uitwerking van Use Case 5.
- feature/UC6 → voor de uitwerking van Use Case 6.


Zodra een feature klaar is, wordt deze terug samengevoegd in de develop branch.


## release/…
Wanneer een nieuwe versie bijna klaar is, wordt er een release branch aangemaakt vanuit develop. Hierin worden enkel nog documentatie-updates gedaan, zodat de release stabiel wordt.


## hotfix/…
 Voor dringende fouten in de main branch die snel opgelost moeten worden, zonder te wachten op een nieuwe release.
