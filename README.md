# Learn-Home

## User Stories

### Login

| # | User Story | Critères d'acception |
|--|:----------|:----------|
| L1 | En tant que nouvel utilisateur, <br />je veux pouvoir m'inscrire <br />afin d'accéder à mon espace Learn@Home | Etant donné que je suis sur la page de connexion, <br />lorsque je clique sur le lien "inscris-toi !", <br />alors je suis redirigé vers le formulaire d'inscription.<br />---<br />Etant donné que je suis sur la page d'inscription, <br />lorsque je renseigne correctement tous les champs et que je valide le formulaire, <br />alors mon inscription est validée et je reçois un mail de confirmation. |
| L2 | En tant que [étudiant/tuteur], <br />je veux pouvoir m'identifier <br />afin d'accéder à mon espace Learn@Home | Etant donné que je suis sur la page de connexion, <br />lorsque je renseigne mon identifiant/mdp, <br />alors je suis connecté et redirigé vers ma page Dashboard |
| L3 | En tant que [étudiant/tuteur], <br />je veux pouvoir retrouver mon mot de passe <br />afin de pouvoir m'identifier | Etant donné que je suis sur la page de connexion, <br />lorsque je clique sur le lien "mot de passe oublié, <br />alors je suis redirigé vers le formulaire de mot de passe perdu<br />---<br />Etant donné que je suis sur la page de mot de passe perdu, <br />lorsque je renseigne mon identifiant et que je valide le formulaire, <br />alors je reçois un mail me permettant de changer mon mot de passe. |

### Dashboard
| # | User Story | Critères d'acception |
|--|:----------|:----------|
| D1 | En tant que [étudiant/tuteur], <br />je veux voir le nombre de messages non lus <br />afin de pouvoir aller les lire | Etant donné que je suis sur la page de dashboard, <br />lorsque je consulte la partie "messagerie", <br />alors je vois le nombre de messages non lus et la date/heure du dernier message.<br />---<br />Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur le lien "Accéder à la messagerie", <br />alors je suis redirigé vers la page de chat. |
| D2 | En tant que [étudiant/tuteur], <br />je veux voir mes prochains rendez-vous <br />afin de pouvoir organiser ma journée | Etant donné que je suis sur la page de dashboard, <br />lorsque je consulte la partie "événements", <br />alors je vois les événements du jour à venir.<br />---<br />Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur le lien "Accéder au calendrier", <br />alors je suis redirigé vers la page celendrier.<br />---<br />Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur un événement, <br />alors je suis redirigé vers la page celendrier, avec le détail de l'événement visible. |
| D3 | En tant que [étudiant/tuteur], <br />je veux voir mes prochaines tâches à faire <br />afin de pouvoir organiser ma journée | Etant donné que je suis sur la page de dashboard, <br />lorsque je consulte la partie "gestion des tâches", <br />alors je vois les tâches à faire.<br />---<br />Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur le lien "Accéder au gestionnaire de tâches", <br />alors je suis redirigé vers la page du gestionnaire.<br />---<br />Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur une tâche, <br />alors je suis redirigé vers la page du gestionnaire des tâches, avec le détail de la tâche visible. |
| D4 | En tant que [étudiant/tuteur], <br />je veux accéder à ma page de profil <br />afin de pouvoir modifier mes informations personnelles | Etant donné que je suis sur la page de dashboard, <br />lorsque je consulte la partie "mon compte" dans le header et que je clique sur "mon profil", <br />alors je suis redirigé vers la page d'édition de mon profil. |
| D5 | En tant que [étudiant/tuteur], <br />je veux pouvoir me déconnecter <br />afin de ne pas laisser mon compte ouvert | Etant donné que je suis sur la page de dashboard, <br />lorsque je consulte la partie "mon compte" dans le header et que je clique sur "me déconnecter", <br />alors je suis déconnecté et redirigé vers la page de login. |
| D6 | En tant que [tuteur], <br />je veux pouvoir consulter la liste de mes étudiants <br />afin de pouvoir consulter leur progression | Etant donné que je suis sur la page de dashboard, <br />lorsque je clique sur le lien "Mes étudiants" du menu princpal, <br />alors je suis redirigé vers la page "mes étudiants". |

### Messagerie
| # | User Story | Critères d'acception |
|--|:----------|:----------|
| M1 | En tant que [étudiant/tuteur], <br />je veux voir la liste de mes contacts <br />afin de pouvoir discuter avec eux | Etant donné que je suis sur la page de messagerie, <br />lorsque je clique sur un contact (partie de gauche), <br />alors la conversation avec ce contact s'affiche (partie de droite) avec la totalité de l'historique. |
| M2 | En tant que [étudiant/tuteur], <br />je veux pouvoir ajouter un contact <br />afin de pouvoir discuter avec lui | Etant donné que je suis sur la page de messagerie, <br />lorsque je clique sur "ajouter un contact" (partie de gauche), <br />alors une nouvelle conversation (vierge) avec ce contact s'affiche (partie de droite). |
| M3 | En tant que [étudiant/tuteur], <br />je veux pouvoir ajouter un contact en favoris <br />afin de pouvoir accéder à notre conversation rapidement | Etant donné que je suis sur la page de messagerie, <br />lorsque je clique sur "ajouter au favoris" en haut d'une conversation (partie de droite), <br />alors le contact apparaît  dans la section "favoris" (partie de gauche). |
| M4 | En tant que [étudiant/tuteur], <br />je veux pouvoir envoyer un message instantané à un contact <br />afin de pouvoir échanger rapidement | Etant donné que je suis sur la page de messagerie et que j'ai sélectionné un contact, <br />lorsque j'écris un message et que je clique sur "envoyer" (partie de droite), <br />alors le message est envoyé au contact et je suis averti du statut du message (envoyé, reçu ou lu). |

### Calendrier
| # | User Story | Critères d'acception |
|--|:----------|:----------|
| C1 | En tant que [étudiant/tuteur], <br />je veux consulter mes événements du jour ou de la semaine <br />afin de pouvoir m'organiser et ne pas rater de rendez-vous | Etant donné que je suis sur la page de calendrier, <br />lorsque je consulte les journées, <br />alors je peux voir mes rendez-vous et événements. |
| C2 | En tant que [étudiant/tuteur], <br />je veux consulter le détail d'un rendez-vous/événement <br />afin de connaître l'heure, le lieu et les autres invités | Etant donné que je suis sur la page de calendrier, <br />lorsque je clique sur un rendez-vous/événement, <br />alors le détail s'affiche. |
| C3 | En tant que [étudiant/tuteur], <br />je veux créer un rendez-vous/événement <br />afin de me rappeler de la date | Etant donné que je suis sur la page de calendrier, <br />lorsque je clique sur une case du calendrier (ou sur le bouton "nouvelle tâche"), <br />alors le formulaire de création s'affiche.<br />---<br />Etant donné que je suis sur la page de calendrier et que le formulaire de création est ouvert, <br />lorsque je remplis toutes les informations et que je valide le formulaire, <br />alors le nouveau rendez-vous/événement s'affiche dans le calendrier. |
| C4 | En tant que [étudiant/tuteur], <br />je veux consulter un jour en particulier dans plusieurs semaine <br />afin de réserver la date | Etant donné que je suis sur la page de calendrier, <br />lorsque je me sers de la navigation, <br />alors le calendrier se met à jour. |

### Gestionnaire de tâches
| # | User Story | Critères d'acception |
|--|:----------|:----------|
| T1 | En tant que [étudiant/tuteur], <br />je veux consulter mes tâches <br />afin de pouvoir m'organiser et d'avancer dans mon travail | Etant donné que je suis sur la page du gestionnaire des tâches, <br />lorsque je consulte la colonne "en cours", <br />alors je peux voir mes tâches commencées mais non terminées. |
| T2 | En tant que [étudiant/tuteur], <br />je veux me créer une nouvelle tâche et y ajouter des fichiers et des commentaires<br />afin de ne rien oublier | Etant donné que je suis sur la page du gestionnaire des tâches, <br />lorsque je clique sur le bouton "nouvelle tâche", <br />alors le formulaire de création s'affiche.<br />---<br />Etant donné que je suis sur la page du gestionnaire des tâches et que le formulaire de création est ouvert, <br />lorsque je remplis toutes les informations et que je valide le formulaire, <br />alors la nouvelle tâche s'affiche dans la colonne "A faire". |
| T3 | En tant que [étudiant/tuteur], <br />je veux modifier une tâche <br />afin de pouvoir y ajouter un fichier, une TODO list ou un commentaire | Etant donné que je suis sur la page du gestionnaire des tâches, <br />lorsque je clique sur une tâche, <br />alors le détail s'affiche.<br />---<br />Etant donné que je suis sur la page du gestionnaire des tâches et que le détail d'une tâche est affiché, <br />lorsque je remplis le formulaire d'ajout d'un document et que je valide, <br />alors le détail de la tâche se ferme et l'icône "pièce jointe" est visible sur la tâche. |
| T4 | En tant que [tuteur], <br />je veux créer une nouvelle tâche <br />afin de l'affecter à un étudiant | Etant donné que je suis sur la page du gestionnaire des tâches connecté avec un compte tuteur et que le formulaire de création est ouvert, <br />lorsque je renseigne les informations de la tâche, <br />alors je peux sélectionner un de mes étudiants comme destinataire de la tâche.<br />---<br />Etant donné que je suis sur la page du gestionnaire des tâches connecté avec un compte tuteur et que le formulaire de création est ouvert, <br />lorsque je valide la création en ayant sélectionné un étudiant, <br />alors le formulaire se ferme et je reçois une confirmation de création et d'affectation de la tâche. |
| T5 | En tant que [étudiant/tuteur], <br />je veux déplacer une tâche <br />afin de la mettre dans la colonne "terminées" | Etant donné que je suis sur la page du gestionnaire des tâches, <br />lorsque je "drag & drop" ma tâche dans la colonne "terminées", <br />alors le statut de la tâche est modifié. |
| T6 | En tant que [étudiant/tuteur], <br />je veux archiver une tâche terminée <br />afin de ne pas encombrer la colonne "terminées" | Etant donné que je suis sur la page du gestionnaire des tâches, <br />lorsque j'affiche le détail d'une tâche terminée, <br />alors le bouton "archiver" est visible.<br />---<br />Etant donné que je suis sur la page du gestionnaire des tâches et que j'ai ouvert le détail d'une tâche terminée, <br />lorsque je clique sur le bouton "archiver", <br />alors le détail se ferme et la tâche est retirée de la liste. |

## Kanban

Le Kanban se situe dans le projet lié [Learn@Home](https://github.com/users/gcorbelin/projects/1)
