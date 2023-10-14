# DEV5 portfolio ZAHRA

| Task name                    | GitHub     | CodeSandBox   |
| ---------------------------- | ---------- | ------------  |
| `'Lab 1 - GIT to work'`      | https://github.com/JarneSimons/lab1_Jarne_Zahra | https://7xp5r7.csb.app/ |      | 
| `'Lab 2 - Islands'`          | https://github.com/zzahraJ/Lab2-Islands/tree/main           | https://gmk22m.csb.app/# |

Samenvatting Dynamic Import

Ik heb in mijn code gebruik gemaakt van Dynamic Import. 
Dit gaat ervoor zorgen dat je eigenlijk pas modules of code gaat laden op het moment dat je deze daadwerkelijk npdig gaat hebben. Op deze manier gaat de laadtijd an je pagina geoptimaliseerd worden. 

Een voorbeeld hiervan is: 

import('./classes/World.js')
  .then(({ default: World }) => {
    const world = new World();
  })

Wanneer ge module is geladen, wordt de 'then'-blok uitgevoerd, waarin je toegang hebt tot de geïmporteerde 'World'-klasse. Hierdoor wordt deze module pas geladen wanneer je ze daadwerkelijk echt nodig hebt, in plaats van aan het begin van het script.




| `'Lab 3 - Weather Based Ad'` |            |               |
| `'Lab 4 - NodeJS'`           |            |               |
| `'Lab 5 - VueJS'`            |            |               |
| `'Lab 6 - Web Sockets'`      |            |               |