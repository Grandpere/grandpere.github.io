---
pid: o-children
title: "O'Children"
type: "formation"

start: "2019-05"
end: "2019-05"
year: "2019"
period: "Mai"

cover: "/assets/images/projects/ochildren/ochildren.png"
links:
  - value: "Voir le dépot Github (back)"
    url: "https://github.com/Grandpere/O-Children-API"
    title: "Accéder au dépôt Back-End sur Github"
  - value: "Voir le dépot Github (front)"
    url: "https://github.com/Grandpere/O-Children"
    title: "Accéder au dépôt Front-End sur Github"
  - value: "Vidéo de Présentation"
    url: "https://youtu.be/i4v-851tBPo?t=596"
    title: "Accéder à la vidéo (notre démo se termine à 30min)"
media:
  - title: "homepage"
    url: "/assets/images/projects/ochildren/ochildren.png"
    alt: "homepage"
---
Ce projet de fin de formation a été réalisé en équipe. Le but était de mener un miniprojet d'un mois à terme en mode agile.

L'équipe était composé de 3 développeurs React et d'un développeur PHP Symfony donc j'ai développé seul pendant les sprints de développement.

Ce projet a été découpé en 4 sprints d'une semaine :
- Sprint de documentation, de réalisation du cahier des charges, des documents de conceptions (MCD, MLD, wireframes, users stories, workflow git, etc...)
- Sprint de développement du MVP (Minimum Viable Product) afin de coder les principales fonctionnalités prévues et validées dans le cahier des charges
- Sprint deux de développement pour finaliser nos fonctionnalités.
- Sprint de débug et mise en ligne afin de corriger et finaliser notre MVP, aucune features ne devaient être codé pendant ce sprint.

La partie API et le backend ont été développé en PHP via le framework Symfony (version 4). L'API a été développé sans l'utilisation de bundle comme API Platform ou FOSRestBundle.

L'API a été documenté grâce au bundle NelmioAPIDocBundle. La partie front non présente dans ce dépôt a été développé en Javascript avec React. La communication entre les deux a été faite via des requêtes Axios et JWT a été utilisé pour protéger certaines ressources de l'API.

L'équipe n'a pas poursuivi le développement du projet donc il est resté au stade v1.

Présentation du projet sur YouTube : https://youtu.be/i4v-851tBPo?t=596 (Fin de notre projet à 30 min)
