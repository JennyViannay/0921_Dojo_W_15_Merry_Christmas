# Noël App (bdd/back/front)

C’est bientôt Noël et le père Noël demande une application pour que les enfants (nom, prénom, niveau de sagesse) puissent ajouter des cadeaux(nom) à leur liste. Si un enfant n'est pas sage, le père Noël pourra supprimer ces cadeaux.

## Bonus

Plus noël approche, plus les timings deviennent serrés, il va bientôt commencer l'exploitation de centaines de lutins(nom,prénom). Un lutin travaille seul sur chaque cadeau et quand il a finis il passe au cadeau suivant. Attention il faudra surement rajouter un statut todo/doing/done aux cadeaux.

## Modélisation BDD 
- Création BDD (Vous ajouterez manuellement des enfants/cadeaux/bonus-lutin dans la base)

## Server
- Initialisation projet Node(express/mysql)
- Création des routes express
- Récupérer une liste d’enfants avec leurs cadeaux
- Ajouter un cadeau
- Supprimer la liste d'un enfant bonus
- Associer un lutin à un cadeau
- Valider la fabrication du cadeau (statut table cadeau ok)

## Client
- Initialiser un projet react
- Connecter le front au back (fetch/axios)
- Afficher la liste d'enfant et leurs cadeaux
- Bouton de suppression de la liste d'un enfant
- Formulaire d'ajout de cadeaux pour un enfant bonus
- Afficher la liste de lutin
- Associer un lutin à un cadeaux
