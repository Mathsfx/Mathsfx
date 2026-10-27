# Maths.Fx — prototype de site éducatif

## Aperçu
Site responsive en français avec :
- page d'accueil et présentation de la méthode ;
- trois parcours pédagogiques avec tarifs à définir ;
- calculateur interactif d'espérance mathématique ;
- résumés d'articles pédagogiques ;
- formulaire d'intérêt en mode démo ;
- modale d'espace étudiant en mode démo ;
- boutons d'inscription et d'abonnement non reliés à un paiement ;
- FAQ et emplacements pour mentions légales / confidentialité.

## Voir le site en local
Ouvrir `index.html` dans un navigateur. Une connexion internet est nécessaire pour charger les polices Google ; le reste est local.

## Important avant toute publication
Cette version est un prototype frontend. Elle n'a pas de backend, n'envoie ni ne stocke les formulaires, ne crée pas de comptes, ne protège pas de contenu privé et ne prend aucun paiement.

Pour passer en production, il faut notamment :
1. Valider les offres, les prix, le contenu exact et les modalités d'accompagnement.
2. Choisir et configurer un backend sécurisé (par exemple Supabase ou un service équivalent) pour authentification, base de données et autorisations.
3. Choisir un prestataire de paiement (par exemple Stripe) et configurer les webhooks côté serveur ; ne jamais collecter les numéros de carte dans un formulaire maison.
4. Ajouter une politique de confidentialité, mentions légales, CGV/CGU et informations requises selon le statut et l'offre.
5. Configurer protection anti-spam, validation serveur, sauvegardes, gestion des erreurs et tests mobiles/accessibilité.
6. Tester toutes les fonctions avant d'accepter des inscriptions ou paiements.

## Publication gratuite possible
Cloudflare Pages peut héberger les fichiers statiques. Déployer le dossier contenant `index.html` (ou le dépôt Git connecté). Le sous-domaine demandé est soumis à disponibilité. Les fonctionnalités privées et paiements nécessitent des services complémentaires.
