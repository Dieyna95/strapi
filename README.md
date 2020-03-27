# Strapi application
Dieynaba Ndour Master 2 Télécoms Réseaux


Ajouter une page à notre projet qui va permettre à l’administrateur d’ajouter un plat (page créée depuis Ionic cli avec la commande 'ionic generate' )


Créer une page pour pouvoir modifier les informations sur un plat; pour cela après avoir générer la page avec la commande ionic generate, nous allons enregistrer la page au niveau du routing


Ajouter un bouton au niveau de la page:
Sur chaque ligne au niveau de la liste des plats ajouter un événement au clic de la ligne afin de rediriger l’utilisateur vers la page de modification. Pour cela, nous allons ajouter la directive click sur les items de liste au niveau de la page d’affichage des plats. La fonction "modifierPlat" prend en entrée l’identifiant du plat et devra rediriger l’utilisateur vers la page de modification


Pour la création du formulaire, l’importation du module doit être faite au niveau du fichier ajouter.module dans le dossier plat
Une fois le module importé, on peut maintenant définir notre formulaire au niveau de la page ajouter.page.html


Quand le formulaire est soumis par l’utilisateur, la méthode ajouterPlat sera appelée. Le binding étant effectué les données
saisies par l’utilisateur sont présentes au niveau de l’objet plat.
Nous devons tout d'abord importer le module ReactiveFormsModule au niveau du fichier modifier.module.ts
Dans le code Typescript, nous pouvons commencer par définir des formControl pour chaque champ du formulaire (nom, prix, description)


Créer la classe Utilisateur pour mapper les informations sur le compte de l’utilisateur
Le service AuthService sera créé via la commande ionic generate service
Ajouter à l’intérieur de notre service les deux méthodes
Créer nos deux pages de connexion et d’inscription

Nous pouvons ainsi:
Permettre à l’administrateur de définir le menu du jour en précisant les plats du jour
Permettre aux employés de passer leur commande et à l’administrateur de voir les commandes du jour

