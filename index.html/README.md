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

- Kanban en 4 colonnes (glisser-deposer les cartes entre colonnes, ou fleches), vue liste, ou vue calendrier mensuel des deadlines
- Tri des commandes par deadline, prix ou client
- Montant en Robux ou en Euros par commande, avec taux de conversion personnalise (bouton "Sauvegarde" > "Modifier le taux") ; les totaux sont toujours affiches en RBX
- Graphique des revenus encaisses par mois
- Graphique de repartition des commandes par type
- Delai moyen de livraison par type de commande
- Comparaison du revenu du mois vs le mois precedent (%)
- Recherche par client / description et filtre par type
- Alerte visuelle si une deadline est depassee ou arrive dans moins de 3 jours
- Champ acompte : suit le reste a payer par commande
- Historique clients : total de commandes et revenu encaisse par client
- Objectif de revenu mensuel avec barre de progression qui change de couleur (gris vers dore) en approchant de 100%
- Mode sombre (bouton en haut a droite, la preference est memorisee)
- Petite animation de confettis quand une commande passe en "Livre / paye"
- Badge "livrees ce mois" a cote du logo
- Message d'accueil et petit indicateur meteo ironique selon le nombre de commandes actives
- Widget "Records perso" : plus grosse commande, livraison la plus rapide, client le plus fidele
- Heatmap d'activite des 12 dernieres semaines, façon GitHub
- Frise chronologique de toutes tes commandes
- Section "A surveiller cette semaine" avec les deadlines proches
- Titre d'onglet et icone qui indiquent le nombre de commandes en retard
- Bouton "Copier le recap" et "Generer un devis" (impression / PDF) dans une commande
- Notes libres (bouton "Notes") pour tes rappels et idees
- Sauvegarde automatique des 5 dernieres versions de tes donnees, restaurable en un clic
- Export et import CSV, avec la devise (bouton "Sauvegarde")
- Clique sur une commande pour la modifier ou la supprimer
