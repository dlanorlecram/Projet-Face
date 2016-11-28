# les spécifications fonctionnelles

1. __JE SUIS UN EMPLOYÉ DE FACE__

  Avant d'accéder au Dashbord l'employé se retouve sur une page lui demandant de s'authentifier à fin d'accéder à sa session.

  __Interaction__

  Dans cette page de connexion se trouve un formulaire  composer de deux champs:
  - Un champs intitulé "Identifiant" permettant de saisir son identifiant en l'occurance son adresse mail.
  - Un autre champs intitulé "Mot de passe" pour la saisie de mot de pass
  - (À en discuter pour ce scénario "Dans le cas, l'employé oublie sont mot de passe doit d'il contacté l'administrateur pour lui divulger un notre mot de passe ou cliquer sur ce lien pour en générer un automatiquement ?")
  Ainsi, qu'un lien lui permettant en cas d'oublie d'obtenir un mot de passe de substitution envoyé à l'adresse mail que la Fondation lui à attribuer.

  * Je souhaite me connecté à ma session pour ce faire je dois:
  rentrer une adresse mail et un mot de passe valide dans les champs prévu à cette effet c'est à dire le champs " Identifiant " pour adresse mail et le champs " Mot de passe " pour le mot de passe.

    * Pour que mon adresse soit valide, je dois saisir 24 caractères en miniscules suivis du signe arobase "@" et du nom du serveur mail exclusive de la Fondation FACE.

    * Pour que mon mot de passe soit valide, il faut qu'il corresponde au mot de passe délivré par l'administrateur. Ce mot de passe doit contenir environs entre 6 - 24 caractères alphanumériques en majuscule et/ou miniscules.

    * Pour faire une vérification de l'identifiant et du mot de passe saisie, l'employé devra cliquer sur le bouton "valider", dans le but de lancer une vérification pour accéder à sa session.

  __Comportement attendu__
    * Dans le cas où la saisie est correct, alors l'employé de la FONDATION FACE se verra redirigé vers sont d'interface de travail.

    * Dans le cas où la saisie est incorret.
      * Si identifiant invalide.
        Un message en surbrillance apparaitra afin d'indiquer que l'identifiant est incorrect.

      * Si mot de passe invalide.
        Un message en surbrillance apparaitra pour spécifier que le mot de passe est incorrect.

# Les spécifications techniques
