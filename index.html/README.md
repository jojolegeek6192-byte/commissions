# Commissions

Site perso pour suivre tes commandes de commissions Roblox. Noir et blanc, minimaliste.
Un seul fichier `index.html`, rien a installer, rien a configurer.

Tes commandes sont enregistrees directement dans ton navigateur (localStorage) : elles restent
si tu fermes l'onglet ou eteins ton ordi, tant que tu utilises le meme navigateur sur le meme
appareil et que tu ne vides pas les donnees du site.

## Mise en ligne (GitHub Pages)

1. Cree un repo GitHub, mets-y ce fichier `index.html`
2. Va dans Settings > Pages > Source > choisis la branche `main` et le dossier `/ (root)` > Save
3. Attends une minute, ton site est en ligne a l'adresse indiquee en haut de cette page Pages

C'est tout. Chaque fois que tu modifies `index.html` et que tu push sur GitHub, le site se
met a jour tout seul, sans rien reconfigurer.

## Fonctionnalites

- Kanban en 4 colonnes avec navigation par fleches
- Graphique des revenus encaisses par mois
- Graphique de repartition des commandes par type
- Recherche par client / description et filtre par type
- Alerte visuelle (bordure + badge) si une deadline est depassee ou arrive dans moins de 3 jours
- Clique sur une commande pour la modifier ou la supprimer
- Export CSV de toutes les commandes (bouton en haut a droite)
