# Cahier des charges

## Qui est la cible ?

FACE Rennes (Fondation Agir Contre l'Exclusion) est une association spécialisée dans l'insertion professionnelle. Elle fait partie d'un réseau plus dense d'associations présentes sur tout le territoire.

### Détail sur l'entreprise ?
Cette association à une 4  employées à son actif, qui s'occupe chaqu'un d'une dizaine de flux par ans.
Sont désigné entant que flux les personnes mise en marge du monde du travail.
Ces personne represente une bonne partie des missions pour chaque employé de la fondation.

###### Particularité du flux
- Present sans ou sous rendez-vous.
- Représent une grande partie des missions de face.

###### Les service proposer par la cible au flux.

- Création d'une lettre de motivation
- Création/amélioration d'un CV
- Proposition d'offres.
- Préparation aux entretiens.
- Et bien d'autres ateliers encore.

###### Contexte actuel.

Un suivis des flux après l’insertion pro (3 - 6 - 9 mois).
Suivie jusqu’à ce que son statuts situation professionnelle soit stable, ou qu’il n’ai plus besoin de face.

Etat des lieux de la situation actuelle:
	-> Présence d’une base de données peu organisée.
	-> Absence de soft de gestion lié à la base de données.
		-> conséquence:
1. Manque de réactivité lors de la recherche des données (Interface non existante).
2. Absence de mise en lien des profiles aux offres susceptibles . (Façon Pôle emploi)


###### Besoin exprimé par la cible:

- Appli destinée principalement aux employés de Face.
- Une fonction de recherche efficace et rapide qui permet de retrouver une page descriptive sur toutes les actions menées pour le flux et le suivi.

- Un suivis des flux après l’insertion pro (3 - 6 - 9 mois).

- Un agenda centralisé pour les employés de FACE (de façon que chacun connaisse les disponibilités de l'autres pour lui assigner un flux)
- Un suivi des actions menées par l'employé sur une période donnée
- Un système de mailing intégré avec envoi automatique aux dates de suivi.
- Un système de messagerie interne.
- Un système de reminder (notifications) pour les différents rendez-vous.
- Un système de gestion des fichiers et des offres d'emplois.
- Prévoir un usage à grande échelle (Face France 64 utilisateur).
- Compte supérieur (corps de direction) avec des privilèges supplémentaire et une possibilité d’avoir une vision globale des flux.


 	#Quels sont ces privilège et qui a le droit de faire quoi:
	CRUD -> Création d’un compte
		-> Suppr d’un compte après démission ou fin de contrat
			-> répartition des flux vers d’autre employé
			->  possibilité d’annuler les rendez-vous.








Copier - coller des premiers besoins dégagés (voir exemple)


* D'un agenda personnel et un autre plus global.
* Un système de mailing automatisé à la création d'un rendez-vous.
* Une messagerie interne pour demander l'autorisation à ses collègues.




1. D'une fonction de recherche par nom du flux.
2. Une interface qui comprend :
    1. Un historique lié à ce flux (rendez-vous, fichiers, actions menées).
    2. Une possibilité de consulter les fichiers liées à ce flux et d'en associer de nouveaux
    3. Une photo du flux
    4. Un résumé de sa situation (status, cours brief).




* D'une interface récapitulative des employés avec une présentation très visuelle des éléments cités plus haut.
* La possibilité de mettre des notes personnelles sur ses employés pour préparer la réunion d'équipe.
* La possibilité d'accéder à une interface plus détaillée des actions menées par l'employé.

 				<-- Hypothèse -->

1# Agenda
 	-> Un agenda deux en un voir charte graphique de Face.
2-Consulter la disponibilité de ses collègues en cas de surcharge.


	Techno utilisé google agenda.


2# Compte avec privilège en plus gestion des comptes employés.


-> CRUD  pour la gestion des comptes “employé”.
-> Accessibilité des données et fichiers dans leurs ensemble.
-> suivis de l’avancée de l’employé.
-> Mise en place d’un système de note ou rappel qui servira par la suite lors de chaque réunion.


Interface:


Une interface plus détaillé que celle de l’employé ( en terme d’infos) et des fonctionnalitées supplémentaires.


Détail sur les infos:
{{ À établir après. }}


3# Interface didactique:

	-> Faire les recherches sur les flux (à travers une barre de recherche);


		1# Profil du flux qui doit contenir:
* afficher les infos personnelles
* pouvoir faire un compte rendu et voir un récapitulatif sur le parcours pro.
			Création d’un compte pour flux CRUD
			Stockage des fichiers relatifs au flux.
			2# Parcourir les offres anciennes ou récentes.
			3# Peut être associer les offres aux profils potentiels et dispo.

-> Pouvoir ajouter de nouvelle offre.
-> Proposition de profils type par rapport à la nouvelle offre.
-> Peut-être par le biais de mot clé.
-> la  disponibilité du flux


#### Messagerie interne.
	Dispositif en intranet.
	Permet échange entre employé
-> implique une notification des nouveaux messages.  
-> consultation via une interface de message privé.
-> Rédaction et envoie des message via cette espace grâce à un formulaire d’enregistrement.


Annexes.
>##Charte graphique de Face :
	Couleur:
			#24888F -> Vrai bleu présent sur logo de face.
			#FF9966 -> Vrai orange clair présent sur logo de face.
      #1693A5 ->  cyan
			#FBB829 -> orange clair
	Logo:


>## Hébergement de l'application.
  Pour un fonctionnement optimal de l'application, la configuration requise sera:
	 Intranet.
   Nginx.
   PHP 7.

## Supportable sur différent type de média?
  L'application sera supportable par des écrans compris en tre 360px460px jusqu'à 1920x900px. Au delà de ces dimensions, il ne sera pas supportable.

## La charte graphique.
  Une charge graphique est imposée par l'association face. Elle devra être transmisse dès l'élaboration du projet, à fin devoir maquetter l'application.

## Prèstation service àprès vente.

  L'association est pleinnement consciente que la code académie, ne sera en mesure de lui proposer un services après ventes après livraison de l'application. Toutefois, il lui sera fournie en annexe:

    Une notice d'installation
    Une spécification fonctionnelle
    Une spécification technique
    Un guide d'administration

    #### Document d’installation et d’usage de l’application.
    Ces document contiendrons toutes les marches à suivre, pour que l'usager puisse être autonome dans le déploiement de l'application et lors de son usage.

Présentation du projet en 200 mot
  comprehesion de besoin et des différents


Les exigence projet
