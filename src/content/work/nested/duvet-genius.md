---
title: Musical'Mandingue
publishDate: 2023-09-09 00:00:00
img: /assets/Image.jpg
img_alt: Images du site de Musical'Mandingue
description: |
  Développement d'une applcation web pour l'inscriprtion et la gestion d'une association.
tags:
  - Python(Django)
  - Html 
  - Bootstrap & Css
  - Java-Script
---

L'application est développée du côté front pour permettre aux visiteur de créer un compte afin de pouvoir adhérer à l'association et de pouvoir accéder à des informations supplémentaires une fois connecté.

- Les inscriptions aux stages (adhésion automatique si le visiteur n'a pas d'adhésion)
- L'affichage ou les modifications du profil utilisateur.
- L'accès aux tutos des stages précédents.

Si le visiteur n'est pas connecté, il n'aura pas accès aux pages ci-dessus mais il aura accès :

- A la liste des stages (pas de possibilité de s'inscrire).
- A la page d'accueil (avec les informations sur les manifestations).
- A la page de contact (Envoyer un mail à l'association).
- A la page des tarifs.
- A la page de story.
- A la page Festidingue (présentaion du festival de l'association)
- Et la possibilité de se connecter ou de créer un compte.

La gestion de l'administrateur :

L'administrateur a un accès à la création des stages, à l'ajout de nouveaux évènements et à l'impression des inscrits (aux stages et la liste des adhérents) en PDF.
Cette accès est soumis à une authentification spéciale.
L'administrateur peut aussi envoyer un mail directement de l'application.

L'authentification :

Pour l'inscription sur le site, le visiteur doit remplir un formulaire sipmple:
- Nom d'utilisteur.
- Adresse mail (envoie d'une confirmation par mail).
- Mot de passe.

- L'utilisateur peut redéfinir son mot de passe en cas d'oublie (authorisation envoyée par mail).

vous pouvez visiter le site en cliquant sur le lien : www.musicalmandingue.fr

L'application est responsive.