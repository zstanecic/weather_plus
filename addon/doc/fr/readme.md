# Weather Plus #

* Auteur : Adriano Barbieri
* Compatibilité NVDA : 2017.3 à 2019.3
* Télécharger : [Version stable][1]

# À propos de Weather Plus : #

* Cette extension ajoute à NVDA la température locale, les prévisions météo
  à 24 heures et les prévisions jusqu'à 9 jours supplémentaires.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Publié sous la GNU GPL (General Public License) v2
* Weather Plus fonctionne grâce à l'utilisation et la présence des services
  suivants :
* [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)
* [http://woeid.rosselliot.co.nz/lookup/](http://woeid.rosselliot.co.nz/lookup/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# UTILISATION : #

* Appuyez sur NVDA+w pour obtenir les informations sur la température
  actuelle et les conditions météo.
* Appuyez sur NVDA +maj+W pour obtenir les prévisions à 24 heures et à 9
  jours au-delà.
* Appuyez sur NVDA+maj+contrôle+w pour définir une ville temporaire.
* Appuyez sur NVDA+maj+contrôle+alt+w pour ouvrir le dialogue Paramètres
  Weather Plus.
* Appuyez sur NVDA+alt+w pour obtenir la date et l'heure de la dernière mise
  à jour du bulletin météo.
* Appuyez sur Contrôle+maj+w pour basculer entre les échelles de température
  Fahrenheit, Celsius ou Kelvin.

# Configuration de Weather Plus : #

* Vous devez configurer l'extension Weather Plus avant sa première utilisation ! Allez dans le sous-menu Préférences, sous-menu Paramètres Weather Plus et choisissez l'une des options suivantes :
 * Définir et gérer vos villes... - Afficher ou définir la ville courante depuis une liste.
 * Documentation - Ouvrir le fichier d'aide pour la langue en cours.
 * Rechercher une mise à jour... - Signaler si une nouvelle version est disponible.

Pour ajouter une nouvelle ville : appuyer sur l'élément suivant :

* Définir et gérer vos villes... - Afficher ou définir la ville en cours
  depuis une liste.
* Le message suivant est affiché seulement la première fois ! Paramètres
  Prédéfinis Aucun F1: aide à la localisation, F2: dernière sélection avec
  TAB, F3: liste et zone d'édition, F4: contrôle de la durée des Prévisions
  Météo, F5: contrôles du volume.
* Dans la zone d'édition, saisissez une ville, un weoID ou choisissez-en une
  dans la liste, si disponible. Remarque : La touche f5 est disponible si
  les effets sonores sont activés.
* Une fois appuyé sur Entrée sur l'élément "Définir et Gérer Vos Villes...",
  vous trouverez d'autres boutons comme suit :
* Tester - Test de la validité du woeID de ville saisi et recherche du nom
  de la ville assignée, ou viceversa.
* Ajouter - Ajoute la ville en cours dans votre liste. Ce bouton est activé
  si vous sélectionnez une ville dans la liste, et qu'elle a passé le test.
* Détails - Affiche les informations sur la ville en cours. Ce bouton est
  activé si vous sélectionnez une ville dans la liste, et qu'elle a passé le
  test.
* Définir - Vous permet de définir la région, afin d'adapter les effets
  sonores. Ce bouton est activé si les effets sonores sont installés et
  activés, et si vous sélectionnez une ville dans la liste.
* Prédéfini - Définit une ville par défaut, qui sera utilisée à chaque
  redémarrage de l'extension. Ce bouton est activé si vous sélectionnez une
  ville préalablement insérée dans la liste et non prédéfinie, ou si elle a
  passé le test.
* Supprimer - Supprimer la ville courante de votre liste. Ce bouton est
  activé si vous sélectionnez une ville préalablement insérée dans votre
  liste.
* Renommer - Renommer la vile en cours. Ce bouton est activé si vous
  sélectionnez une ville préalablement insérée dans votre liste.
* Importer de nouvelles villes... - Ce bouton vous permet d'importer des
  villes d'une autre liste de viles avec l'extension *.zipcodes ; vous
  pouvez choisir la ville que vous souhaitez importer, en activant la case à
  cocher associée.
* Exporter vos villes... - Vous permet d'enregistrer des villes dans le
  fichier spécifié avec l'extension * .zipcodes. Ce bouton est activé si
  vous avez ajouté et enregistré au moins une ville dans la liste.
* Échelle de mesure de la température : Utiliser le bouton radio pour
  choisir entre Celsius (par défaut), Fahrenheit et Kelvin.
* Degrés affichés comme : Utiliser le bouton radio pour choisir entre :
  Celsius `-` Fahrenheit `-` Kelvin (par défaut) C `-` F `-` K ou Non
  spécifié.
* Liste déroulante : Prévisions Météo jusqu'à jours : 3; choisissez une
  valeur entre 1 et 10 (3 jours par défaut)
* Pour effectuer les actions suivantes, activer ou désactiver les cases à
  cocher suivantes :
* Copier le Bulletin météo et les prévisions météo, ainsi que les détails de
  la ville dans le presse-papiers; case à cocher non cochée (par défaut)
* Activer les effets sonores (seulement pour les conditions météo en cours);
  cette case à cocher vous permet également de gérer l'installation des
  effets sonores; si les effets sonores sont installés et que la case à
  cocher est activée, la touche F5 et les paramètres de volume deviennent
  disponibles.
* Une case à cocher supplémentaire sera également disponible : "N'utiliser
  que des effets météo".
* Vous pouvez modifier le volume général ou modifier le dernier effet sonore
  entendu et filtrer les autres sons de votre environnement. Cette case à
  cocher est non cochée par défaut.
* N'utiliser que des effets météo - Cette option est disponible si les
  effets sonores sont activés; s'il est activé, permet de n'entendre que les
  effets tels que pluie, vent, tonnerre, etc., filtrant tous les effets
  environnementaux. (non cochée par défaut)
* Activer la lecture de l'heure au format 24-heures. - Si cette case à
  cocher est désactivée, l'heure est annoncée au format 12-heures, exemple :
  12 AM - 12 PM. Cette case à cocher est cochée (par défaut)
* Activer le bouton aide dans la fenêtre de paramètres; case à cocher cochée
  (par défaut)
* Lire les informations sur le vent; case à cocher non cochée (par
  défaut). Si activée, vous pouvez également cocher les cases à cocher
  suivantes :
* Ajouter la direction du vent; indique la provenance du vent. Case à cocher
  cochée (par défaut)
* Ajouter la vitesse du vent; indique la vitesse en kilomètres ou milles par
  heure. Case à cocher cochée (par défaut)
* Ajouter la vitesse du vent en mètres par seconde; case à cocher cochée
  (par défaut)
* Ajouter la température ressentie; case à cocher cochée (par défaut)
* Lire les informations atmosphériques; case à cocher non cochée (par
  défaut). Si activée, vous pouvez également cocher les cases à cocher
  suivantes :
* Ajouter le taux d'humidité; indique le taux d'humidité. Case à cocher
  cochée (par défaut)
* Ajouter la valeur de visibilité; indique en kilomètres ou milles la
  distance de visibilité. Case à cocher cochée (par défaut)
* Ajouter la valeur de la pression atmosphérique; indique la valeur de la
  pression atmosphérique en millibars ou pouces de mercure. Si cochée,
  ajoute une case à cocher qui vous permet d'indiquer la pression
  atmosphériques en millimètres de mercure. Case à cocher cochée (par
  défaut)
* Ajouter l'état de la pression barométrique; case à cocher cochée (par
  défaut)
* Lire les informations astronomiques; indique les heures de lever et de
  coucher du soleil. Case à cocher non cochée (par défaut)
* Utiliser la virgule pour séparer les décimales; si activée, utilise la
  virgule pour séparer les décimales, sinon utilise le point. Case à cocher
  non cochée (par défaut)
* Recherche d'une mise à jour; si activée, alerte en cas de mise à jour de
  l'extension. Case à cocher cochée (par défaut)
* Presser le bouton OK pour confirmer l'action ou le bouton Annuler pour
  l'annuler.
* Si vous avez modifié la liste des villes, en pressant "Annuler", vous
  serez averti et vous pourrez quand-même sauvegarder la liste. Note : Vos
  paramètres seront sauvegardés dans le fichier nommé :
* "Weather.ini" : paramètres de démarrage de Weather Plus.
* "Weather.volumes" : niveaux de volume audio personnalisés, indépendant du
  volume général.
* "Weather.zipcodes" : liste des villes avec leur zip code et leur
  définition.
* "Weather_searchkey": mots-clés de recherche enregistrées.

--------------------------------------------------------------------------------

# Quoi de neuf : #

# Version 7.4 #

* Correction d'un bug dans une fonction de recherche de la ville.

# Version 7.3 #

* Correction d'un bug inattendu lorsque la page n'a pas été trouvé lors de
  la recherche des mises à jour.

# Version 7.2 #

* Correction d'un bug après avoir ajouté la première ville, lorsque vous
  appuyez sur le bouton OK et redémarrez l'extension.
* Maintenant, la boîte de dialogue de progression affiche à nouveau le temps
  restant et le temps écoulé.
* Traduction correcte en Italien dans l'aide du bouton Renommer.

# Version 7.1 #

* Correction de bogue de mise à jour.

# Version 7.0 #

* Fenêtre de recherche améliorée. Vous pouvez maintenant gérer tous les
  mots-clés insérés, les ajouter, les supprimer et les enregistrer à partir
  du menu contextuel.
* Amélioration du contrôle d’ouverture des fenêtres.
* Correction de quelques bugs mineurs.

# Version 6.9 #

* La recherche de ville récursive a été implémentée avec le système valide
  précédemment utilisé dans la version Weather Plus pour Apixu.
* Appuyez sur f1 dans la fenêtre des options pour afficher une explication
  des commandes disponibles.

# Version 6.8 #

* Compatibilité mise à jour pour Python 3.

# Version 6.7 #

* Correction d'un bug survenant lors du test d'une nouvelle ville et de
  l'utiliser en mode temporaire en appuyant simplement sur "Entrée" et en
  essayant de l'ajouter plus tard en utilisant le bouton "Ajouter".
* Les abréviations pour la Géorgie du Sud et les îles Sandwich du Sud ont
  été ajoutés à la base de données. Malheureusement, à l'heure actuelle, il
  semble que les villes de ces États ne fonctionnent pas ou disposent de
  données incomplètes. Nous espérons que cela sera bientôt résolu.

# Version 6.5 #

* Correction de quelques bugs dans la reproduction des effets sonores;
  quelques cycles "for" avec des valeurs maximales incorrectes ont provoqué
  l'appel d'un effet sonore inexistant.
* Correction d'un bogue d'heure locale dans "Détails"; La conversion au
  format 12-heures donnait une erreur.
* Correction d'un bug dans le rapport Yahoo Weather Forecast; dans certaines
  villes, les prévisions partent de la veille et non de la date actuelle. La
  correction de ces villes entraîne la perte des derniers jours de prévision
  proportionnelle au décalage des dates (si les jours de prévision sont
  définis à 10).

# Version 6.4 #

* Heure d'été supprimée dans la fonction "Détails".
* Amélioration de la reproduction des effets sonores; maintenant, ils se
  mettent à jour régulièrement si les conditions météorologiques changent.

# Version 6.3 #

* Correction des problèmes de l'encodage.

# Version 6.2 #

* Correction d'un bug dans la fonction "Ajouter une ville".
* Correction d'un bogue qui n'assignait pas la variable "_volume" au
  démarrage de l'extension.
* Ajout de code manquant de la version 6.0; maintenant vous pouvez récupérer
  les villes sauvegardées de la version utilisant l'API Apixu; les boutons
  "Test" et "Supprimer" et les villes non compatibles sont disponibles dans
  le format : "Ferrara, iter 44.83,11.58 0" (ville, coordonnées
  géographiques, définition de zone).

# Version 6.1 #

* Correction de 2 bogues.

# Version 6.0 #

* Weather Plus utilise à nouveau l'API Yahoo Weather.
* Virtuellement, toutes les fonctionnalités de la version 4.8 sont de retour
  et le bouton "Renommer" est conservé.
* Compatibilité avec Python 3.

# Version 5.0.1 #

* Correction d'un bogue qui retournait une chaîne vide si la vitesse du vent
  en mph était égale à 0.
* Correction d'un bogue faisant que les effets sonores n'étaient pas
  cohérents avec avec la zone horaire à reproduire.
* Ajustement du nombre de jours de la prévision de 9 à 6 dans le fichier
  readme.

# Version 5.0 #

* Weather Plus utilise maintenant l'API APIXU.

# Changements dans la fenêtre de paramètres Weather Plus #

* Suppression de l'ancienne case à cocher "état de la pression
  barométrique". Remplacée par la nouvelle case à cocher "Ajouter la valeur
  de nébulosité";
* Cela vous donne le pourcentage de nébulosité.
* Ajout d'une nouvelle case à cocher "Ajouter la valeur de
  précipitations". Cela vous donne le niveau de précipitations en
  millimètres.
* Suppression de l'ancienne case à cocher "Indiquer l'attente par des bips
  durant la recherche du dernier bulletin"; laissé actif par défaut.
* Ajouté les informations astronomiques;
* Heure du lever et coucher de lune.
* Ajout d'un nouveau bouton "Renommer" ; pour renommer les villes plus
  facilement.
* Amélioration de la fonction du bouton "Test"; accepte maintenant quelques
  commandes pour faciliter la recherche d'une ville; ces nouvelles commandes
  sont décrites dans la fonction d'aide appelée en pressant F1.

# Version 4.8 #

# Changements dans la fenêtre de paramètres Weather Plus #

* Ajout d'une nouvelle case à cocher; "N'utiliser que des effets météo";
  cela vous permet de supprimer tous les autres effets environnementaux.
* Amélioration des effets sonores aléatoires et ajout de 71 nouveaux effets
  sonores; vous devrez les mettre à jour en cliquant deux fois dans la case
  à cocher "activer les effets sonores".
* Le type de volume assigné par l'utilisateur, entre volume général et
  volume courant, est maintenant conservé quand la configuration est
  sauvegardée.
* Suppression d'un son inutile durant la sélection de texte dans la zone
  d'édition en pressant contrôle+a.
* Amélioration de la lisibilité dans la fenêtre d'aide invoquable par la
  touche de fonction F1.
* Ajout d'un nouvel indicateur de compatibilité pour NVDA 2019.1, et les
  versions alpha courantes.

# Version 4.7.7 #

* Suppression de la notification inutile de fin de téléchargement durant la
  mise à jour de Weather Plus.
* Ajout de 6 nouveaux effets sonores; il sera nécessaire de les mettre à
  jour depuis les paramètres de l'extension.

# Version 4.7.6 #

* Version de correction d'un bug.

# Version 4.7.5 #

* Version de correction d'un bug.

# Version 4.7.3 #

* Pour plus de facilité la fonction dans "Détails" a été mis à jour;
  l'information concernant l'altitude est maintenant fournie par
  veloroutes.org. Cela amène à de petites différences de peu d'importance.

# Version 4.7.2 #

* Correction d'un petit bogue d'encodage.

# Version 4.7.1 #

* Correction d'un bug lors de l'obtention des informations sur la zone
  horaire.

# Version 4.7 #

* Section de mise à jour simplifiée; maintenant au démarrage, si une mise à
  jour est disponible, il sera possible de l'installer directement via une
  simple boîte de dialogue.
* Suppression de la sélection de fichier dans la section de mise à jour;
  maintenant, le fichier de mise à jour est sauvegardé dans le dossier
  temporaire, il ouvre la possibilité d'installer la mise à jour
  automatiquement, bon pour les débutants.

# Version 4.6.9 #

* Ajout de la localisation en Arabe (Grâce à Wafik Immaculate).

# Version 4.6.8 #

* Mise à jour des localisations Portugais Brésilien et Portugais Européen
  (Grâce à Alberto Mendonça).

# Version 4.6.7 #

* Amélioration de la lecture de l'heure courante; pour certaines villes,
  elle était incorrecte. Ajout de l'heure d'été/hiver aux détails;
  disponible seulement pour les pays l'ayant adoptée.

# Version 4.6.5 #

* Correction d'un petit bogue à la lecture de l'heure.

# Version 4.6.4 #

* Amélioration de la lecture de l'heure locale; Les touches de recherches
  sont plus appropriées.

# Version 4.6.2 #

* Bogue corrigé : Après une vérification de mise à jour, le menu "définir
  une ville temporaire..." était activé même si aucune liste de villes
  n'était disponible.
* Bogue corrigé; Impossible de configurer WP quand le fichier weather.ini
  n'a pas encore été créé.

# Version 4.6 #

* Ajout de l'élément de menu "définir une ville temporaire..."; pour être
  complet, vous pouvez maintenant ouvrir la liste des villes temporaires
  aussi depuis le menu.
* Amélioration de la gestion des échelles de température; maintenant la
  fenêtre de paramètres renverra toujours la valeur par défaut.
* Amélioration de la protection contre des ouvertures multiples de la
  fenêtre principale; si l'une d'entre elles est déjà ouverte, en plus de
  l'alerte sonore, elle sera mise en avant-plan.
* Amélioration des effets sonores; ils sont maintenant basés sur l'heure
  locale de la ville en cours.

# Changements dans la fonction du bouton détails dans la fenêtre de paramètres #

* Ajout de l'heure locale courante.
* Correction de la valeur d'altitude; elle retourne maintenant l'altitude
  quand sa valeur est inférieure ou égale à 0.

# Version 4.5.5 #

* Correction de la localisation et de la documentation en Serbe.
* Correction de la localisation en Allemand.

# Changements dans la fenêtre de paramètres Weather Plus #

* Ajout d'une nouvelle case à cocher; vous pouvez utiliser la virgule comme
  séparateur décimal, sinon le séparateur sera le point.

# Version 4.5.3 #

* Correction de deux chaînes dans les localisations Russes et Ukrainiennes.
* Correction du titre de la fenêtre Recherche d'une mise à jour.
* Amélioration de l'algorithme de mise à jour.

# Version 4.5 #

* Ajout du raccourci NVDA+maj+contrôle+alt+w; Il ouvre le dialogue
  paramètres de Weather Plus.
* Correction de quelques chaînes en Anglais.

# Changements dans la fenêtre de paramètres Weather Plus #

* Ajout de 8 nouvelles cases à cocher; il est maintenant possible de
  personnaliser davantage le rapport :
* Direction du vent.
* Vitesse du vent.
* Température ressentie.
* Taux d'humidité.
* Visibilité.
* Pression atmosphérique.
* Indication de la pression atmosphérique en millimètres de mercure (mmHg).
* Etat de la pression barométrique.

# Version 4.4.8 #

* Ajout de la traduction Polonaise (grâce à Zvonimir Staneczyć).
* Compatibilité avec wx python version 4.

# Version 4.4.1 #

* Ajout du support SSL.

# Version 4.4 #

* Correction d'un bogue à la lecture de la nouvelle chaîne de version,
  durant un dépassement du temps de connexion.
* Amélioration de la section de mise à jour; maintenant le dialogue
  n'interfère plus avec le menu NVDA.
* Localisation Russe revue et corrigée.
* Ajout de la traduction Ukrainienne (grâce à Alex Yeshanu).

# Version 4.3.4 #

* Localisation Allemande revue et corrigée.

# Version 4.3.3 #

* Ajout de la localisation en Allemand (grâce à Karl Eick).

# Version 4.3.2 #

* Ajout de la localisation en Roumain (Grâce à Florian Ionașcu).

# Version 4.3.1 #

* Correction d'un bogue mineur dans la fonction "détails"; les chaînes
  "latitude" et "longitude" étaient inversées par rapport aux valeurs.

# Version 4.3 #

* Weather Plus déplacé sur "nvda.it" comme il est son fournisseur
  d'hébergement par défaut.

# Version 4.2.4 #

* Correction d'un bogue mineur quand la connexion n'a pas été active.

# Version 4.2.3 #

* Maintenant Weather Plus est capable de tenter plusieurs connexions avant
  de notifier un mauvais fonctionnement du WoeId en cours d'utilisation, il
  émet un bip à chaque tentative; ce bip peut être désactivé au moyen d'une
  case à cocher dans les paramètres de Weather Plus.

# Version 4.2.2 #

* Correction d'un bogue dans les chaînes de traduction pour l'échelle de
  mesure. Dans certaines langues, Kelvin, Celsius et Fahrenheit n'ont pas
  été traduits.

# Version 4.2.1 #

* Correction de la notification de mise à jour de Weather Plus durant le
  démarrage de Windows; ceci arrive quand le bouton "Utilisez les paramètres
  actuellement sauvegardés sur l'écran de démarrage de Windows" des
  paramètres généraux de NVDA a été utilisé, ce qui copie la configuration,
  et toutes les extensions dans le dossier systemConfig, mais celles-ci ne
  sont pas synchronisés avec les mises à jour ultérieures des extensions. Si
  vous avez utilisé cette option au moins une fois, Vous devrez l'utiliser
  une dernière fois juste après avoir mis à jour Weather Plus.

# Version 4.2 #

* Ajout de 5 nouveaux effets sonores; il sera nécessaire de les mettre à
  jour depuis les paramètres de l'extension.
* Correction d'un bogue dans la fonction d'import; la liste de villes
  n'était pas triée par ordre alphabétique.
* Ajout du mode d'importation dans la fonction d'import; vous pouvez décider
  de complètement remplacer votre liste, ou simplement d'y ajouter de
  nouvelles villes.
* Mise à jour de la lecture du bulletin météo, bulletin en cours; ajout de
  la température ressentie (wind chill).
* Ajout de nouvelles chaînes à la liste bulletin météo.

# Version 4.1 #

* Correction d'un bogue dans la prévision à 10 jours; maintenant si le
  nombre de jours reçu est inférieur à la requête de l'utilisateur, les
  jours manquants sont annoncés comme inconnus.
* Correction de la chaîne de l'entrée aide sur la commande nvda+maj+w.
* Documentation revue et mise à jour.

# Version 4.0 #

* Mise à jour de certaines parties du code et remplacé toutes les
  instructions eval().

# Version 3.9.7 #

* Correction d'un bogue durant la lecture des bulletins météos; maintenant,
  les températures sont lues correctement.

# Version 3.9.6 #

* Changement de l'arrondi dans la conversion de la pression atmosphérique de
  mbar en pouces de mercure; maintenant la valeur est calculée en défaut,
  alors qu'avant elle l'était en excès.

# Version 3.9.5 #

* Ajout de deux nouvelles chaînes à la liste bulletin météo.
* Correction de 2 bogues.
* Mise à jour de l'effet sonore en cours d'exécution de condition de vent
  seul; maintenant le son du vent peut varier aléatoirement.

# Version 3.9.4 #

* Documentations, localisations pour la langue Croate et l'Allemand ont été
  supprimées; parce qu'elles ne sont plus supportées par les traducteurs
  respectifs.
* Correction d'un bogue dans la localisation Serbe.
* Mise à jour de la localisation Tchèque.
* Mise à jour de la documentation et de la localisation en Gallicien.

# Version 3.9 #

* Changé à nouveau de service API; Weather Plus utilise maintenant la
  nouvelle API Yahoo Weather avec language Yahoo!Query et JQuery:
* La clé API n'est plus requise.
* Réintroduction de la recherche de villes homonymes; il sera possible de
  choisir exactement la ville désirée depuis une liste.
* Optimisation de la sortie des sons généraux; ils sont maintenant
  synchronisés avec la synthèse vocale et sont plus rapides.
* Amélioration du cache des données hors-ligne; il est remis à 0 seulement
  toutes les 10 minutes ou lors d'un changement de ville.
* Pression barométrique mesurée en bars ou pouces de mercure (si réglé sur
  Fahrenheit).

# Version 3.8 #

* Corrections de précision des données.
* Ajout du choix automatique de la langue; maintenant l'API renvoie les
  données des conditions météo dans la langue définie pour NVDA.
* Ajout d'un cache pour le bulletin et les prévisions météo; si vous n'avez
  pas changé de ville, d'échelle de degrés ou le nombre de jours pour la
  prévision, vous pourrez lire la prévision pendant 10 minutes même si vous
  êtes hors-ligne. Le cache est réinitialisé à chaque changement décrit
  ci-dessus. C'est parce que les bulletins ne changent pas sur une telle
  période et pour réduire la fréquence des appels à l'API, peut-être en
  jouant avec les effets sonores.
* Amélioration de la recherche de mises à jour; maintenant, une fois
  téléchargé, l'installation sera activée, ou, dans le cas d'une version
  portable de NVDA, le dossier où vous avez sauvegardé la mise à jour sera
  ouvert.
* Mise à jour pour tous les sons; maintenant, les sons sont au format wav.

# Version 3.7 #

* Ajout de la possibilité de désactiver la conversion en mètres par seconde
  de la vitesse du vent.
* Ajout de la possibilité d'utiliser des unités de mesure en livres par
  pouce carré. 
* Correction de 2 bogues.

# Version 3.6 #

* Changement de service API (application programming interface); maintenant
  WP utilise le service offert par OpenWeatherMap.org au lieu de Yahoo
  Weather.com.
* Ajout de la classification du vent dans le bulletin courant.
* Ajout du pourcentage de nébulosité dans le bulletin courant.
* Adoption de l'unité de mesure de la pression en hectopascal dans le
  bulletin courant.

# Changements dans la fenêtre de paramètres de Weather Plus #

* Changement de l'insertion/recherche de yahoo zipcode/woeId vers ID number,
  identifieur de la ville; les ID numbers city sont similaires aux woeid,
  mais le woeId ne fonctionnera plus, même l'ancien zipcode. Vous pourrez
  retrouver une grande partie des villes en tapant son nom ou une partie de
  son nom.
* Ajout de la recherche/insertion pour les coordonnées géographiques.
* Ajout de la recherche/insertion par code postal.
* Amélioration de la fonction "details".
* L'entrée/recherche de l'aide a été assignée à la touche F1.
* Le contrôle des prévisions de 1 à 16 jours a été assigné à la touche
  F4. Attention, si vous choisissez de copier dans le presse-papiers une
  valeur supérieure à 10, elle ne sera pas lue !
* Le contrôle audio a été assigné à la touche F5.
* Ajout de la mesure en degrés Kelvin.
* Ajout de la recherche de mises à jour; vous pouvez activer la recherche
  dans les paramètres ou vérifier manuellement depuis le menu.
* Réaffecté le bouton "Trouver votre ville" dans "Gérer votre clé API...";
  cela vous permet d'entrer ou modifier votre clé API.

# Version 3.5 #

* Ajout de la traduction en Croate (grâce à Gordan Radić).
* Ajout d'un contrôle des woeIds et zip codes trouvés sur le réseau et qui
  ne sont plus valides; il y a eu des rapports de codes ayant cessé de
  fonctionner d'un jour à l'autre, maintenant WP signale si l'un d'entre eux
  a été inséré depuis les fenêtres de recherche sur le net. Si cela arrive
  en utilisant la fonction "Trouver votre ville...", veuillez me le signaler
  pour que je puisse mettre à jour Weather_buffer et les retirer de la
  liste.
* Correction d'un bogue d'encodage dans la fonction de recherche.
* Mise à jour de la fenêtre pour définir un zip code temporaire; ajout de la
  fonction "Trouver" comme dans les autres fenêtres de Weather Plus:
  Contrôle+F3 = Trouver..., F3 = Trouver suivant, Maj+F3 = Trouver
  précédent.

# Version 3.4 #

* Ajout de la traduction en Galicien (grâce à Iván Novegil).
* Ajout de la traduction en Portugais (grâce à Ângelo Miguel Abrantes).
* Ajout de la traduction en Allemand (incomplète)

# Version 3.3 #

* Ajout de la mesure de la vitesse du vent en mètres par seconde.
* Corrections d'encodage.

# Version 3.2 #

* Mise à jour de la lecture des prévisions météo, bulletin météo en cours et
  lecture de la date du bulletin météo en cours; Yahoo weather forecast,
  ddepuis un peu de temps et en quantités aléatoires, permet de passer d'un
  historique de -10 à -5 jours pour les prévisions météo qui doivent être
  insérés entre les données mises à jour que nous voulons lire; il a été
  ajouté un filtre qui permet de lire uniquement la dernière mise à jour des
  données météorologiques, et un discret bip des alertes lorsque ceci
  intervient; ce bip, Si vous le souhaitez, peut être désactivée à l'aide
  d'une case à cocher dans les paramètres de Weather Plus. Évidemment, le
  filtrage des données parfois implique un léger retard dans la réponse,
  mais ceci est toujours acceptable.
* Prévisions météo étendue jusq'à 10 jours.

# Version 3.1 #

* Ajout de la traduction en Serbe (grâce à l'aimable coopération de Dejan
  Gasic).
* Correction de la commande insert+alt+w; ni la validité du code postal en
  cours d'utilisation ni la validité de la connexion n'étaient vérifiées
  comme le font les autres commandes.
* Mise à jour de la fonction de lecture des effets audio; le format mp3 est
  maintenant utilisé. Maintenant, les fichiers seront beaucoup plus petits.
* Ajout de 55 nouveaux effets sonores; il sera nécessaire de les mettre à
  jour depuis les paramètres de l'extension.

# Changements dans la fenêtre de paramètres de Weather Plus #

* Correction de l'affichage de l'aide sur les boutons; maintenant
  l'extension désactive / active en temps réel via la case à cocher
  correspondante.
* Ajout de 3 raccourcis claviers pour naviguer plus rapidement dans la
  fenêtre:
* F1 saute dans la liste et la zone d'édition du code postal.
* F2 renvoie à la dernière sélection réalisé avec TAB.
* F3 saute dans les contrôles du volume (si les effets sonores sont
  installés et activés).
* Ajout d'un raccourcis clavier pour toutes les cases à cocher et les
  boutons; omis des deux boutons radio car ils sont présents dans la
  succession et le premier est accessible avec la commande contrôle+maj+w.
* Modifié, le bouton "Définir" est maintenant désactivé si les effets
  sonores ne sont pas installés et activés.
* Ajout du Contrôles du volume; vous pouvez régler le volume général et le
  dernier effet sonore entendue; cette option est activée si les effets
  sonores sont installés et activés.
* Ajout de la possibilité de définir l'heure du système au format 12 heures
  (12:30 AM - 12:30 PM) , ou le système 24 heures(12:30 - 00:30).

# Version 3.0 #

* Ajout de la traduction en Slovaque (grâce à l'aimable coopération de Vitek
  Jirasek).
* Ajout de la traduction en Portugais-Brésilien et en Portugais-Portugal
  (grâce à l'aimable coopération de Adair Knaesel).
* Ajout de nouvelles chaînes à la liste bulletin météo.
* Ajout de 171 nouveaux effets audio, il y en a désormais 213.
* Ajout de la commande insert+alt+w dans le gest, annonce la date de la
  dernière mise à jour du bulletin météo actuel.
* Ajout d'un scriptCategory qui permet de configurer les raccourcis claviers
  de Weather Plus dans les "Gestes de commandes" de NVDA.

# Changements dans la fenêtre de paramètres de Weather Plus #

* Ajout d'un bouton radio pour définir comment il faut indiquer l'échelle de
  température;
* Les différents choix sont:
* Celsius `-` Fahrenheit
* C `-` F
* Aucune indication
* Ajout du bouton "Définir"; il permet de définir la zone d'une ville entre
  :
* Arrière-pays
* Zone maritime
* Zone de désert
* Zone arctique
* Zone de montagne
* Le choix permettra à Weather Plus d'utiliser des effets sonores plus
  appropriés pour chaque ville individuel; voici la raison de l'augmentation
  du nombre de nouveaux effets sonores dans cette version de l'extension;
  beaucoup de nouveaux effets sonores que j'ai obtenu de Tapin, que je
  remercie sincèrement.

# Version 2.9 #

* Ajout d'une option lors de l'importation pour sélectionner le contenu du
  fichier importé.
* Quatre nouveaux effets de sons ont été ajoutés.
* Ajout de la traduction russe (grâce à Alex Yeshanu).
* Ajout de la traduction tchèque (grâce à Jirimu Holzingerovi).

# Version 2.8 #

* Correction d'un bug dans "Détails", il ouvrait la fenêtre des occurrences
  lorsqu'il ne pouvait pas trouver la ville.
* Correction de regexp pour la recherche de l'altitude; il n'acceptait pas
  les paramètres d'un seul chiffre.
* Amélioration de l'analyseur de la zone d'édition; il devrait retrouver
  plus facilement la ville.
* Connexions maintenant gérées par urllib2, Au lieu de urllib; cela devrait
  permettre le fonctionnement de l'extension même sur un ordinateur connecté
  au réseau d'entreprise protégé par un proxy.
* Ajout de la fonction "Trouver"; Contrôle+F3 = Trouver..., F3 = Trouver
  suivant, Maj+F3 = Trouver précédent.

# Version 2.7 #

* Correction d'un nom incorrect d'une chaîne "Motorcycle" en "Motorcycle00"
  ; il a demandé la mise à jour des effets sonores parce qu'il ne pouvait
  pas trouver le fichier.
* Ajout de la possibilité de lire à propos du vent ; direction, vitesse et
  température du vent.
* Ajout de la possibilité de lire les informations atmosphériques ;
  humidité, la visibilité, la pression et l'état de la pression
  barométrique.
* Ajout de la possibilité de lire les informations astronomiques ; heure du
  lever et du coucher du soleil.

# Changements dans la fenêtre de paramètres de Weather Plus #

* Ajout de 3 cases à cocher pour gérer les informations énumérées ci-dessus.
* Ajout du bouton "Détails" ; fournit des informations telles que le vrai
  nom de la ville (assigné par Yahoo Weather Forecast), l'état / région et
  la nation à laquelle il appartien ; avec les coordonnées géographiques et
  la hauteur au-dessus du niveau de la mer.
* Ajout de la reconnaissance des WoeID (codes de localisation, par
  exemple. Bologna correspond à 711080).
* Maintenant, vous pouvez taper le nom de la ville, dans ce cas, si le cas
  se présente, les occurrences seront répertoriés et vous serez en mesure de
  choisir.

# Version 2.6 #

* Les fonctions des boutons "Ajouter" et "Supprimer" ont été optimisées dans
  la gestion de la liste des codes postaux; maintenant les opérations sont
  beaucoup plus rapide !
* La fonction du bouton "Tester" a été optimisé, maintenant jusqu'à 13 Mots
  clés sont utilisés; Maintenant, si il ne trouve pas le nom de la ville,
  c'est une véritable malchance !
* La fonction du bouton "Trouver votre ville...", maintenant trouve
  davantage de pays; un testeur automatique qui reprend les codes postaux
  qui fonctionnent, et permet un affichage rapide grâce à la création d'un
  petit tampon correspondant au nom du pays spécifique a été ajouté.
* Trois nouveaux effets sonores ont été ajoutés; il sera nécessaire de les
  mettre à jour à partir des paramètres de l'extension.

# Version 2.5 #

* Ajout d'une commande dans le geste pour basculer temporairement l'échelle
  de la température de Celsius en Fahrenheit, la commande est également
  effective dans la fenêtre des paramètres.
* Correction d'un bug, si l'utilisateur n'appuie pas sur les boutons
  "Ajouter" ou "Prédéfini" il n'été pas permis de prononcer le nom de la
  ville, puisqu'elle ne figurait pas dans la liste.
* Ajout de nouvelles chaînes à la liste bulletin météo.

# Changements dans la fenêtre de paramètres de Weather Plus #

* Ajout d'un bouton pour ouvrir une page web de recherche afin de vérifier
  dans le monde entier les Codes postaux.
* Ajout de la possibilité d'importer / exporter les Codes Postaux des amis.
* Ajout de la possibilité de copier le bulletin météo ou la prévisions météo
  dans le presse-papiers.
* Ajout de la possibilité d'écouter les effets sonores météorologiques,
  l'option permet également l'installation / mise à jour des effets sonores.
* Ajout d'un boutons d'aide sur la gestion du Code postal.
* Changement du mode d'affichage de la fenêtre, les menus de nvda sont
  débridé lorsqu'il est ouvert.

# Version 2.4.4 #

* Ajout de deux nouvelles chaînes à la liste bulletin météo.
* Ajout de traduction en espagnol et en français (grâce à Pablo Vargas et
  Rémy Ruiz).

# Version 2.4.3 #

* Ajout de la prévisions météo pour les 4 prochains jours.
* Ajout d'une chaîne à la liste bulletin météo.
* La liste Code postal temporaire est maintenant réordonnée à chaque
  nouvelle insertion.

# Version 2.4 #

* Correction d'un bug qui empêchait d'enregistrer et gérer correctement les
  noms de ville contenant des voyelles accentuées.

# Version 2.3 #
* Élimination de la boîte de dialogue pour définir l'échelle de mesure de la
  température, une nouvelle interface graphique qui vous permet de définir
  tous dans une seule fenêtre a été ajoutée.
* Maintenant vous pouvez tester/ajouter/supprimer/prédéfinir comme la valeur
  par défaut le Code Postal recueillies sous forme de liste.
* Modification de la boîte de dialogue pour la saisie lorsque vous avez tapé
  un Code Postal, maintenant en mode temporaire il vous permet de définir un
  Code Postal précédemment ajoutés à la liste dans le menu À partir du menu
  Préférences.
* Maintenant la documentation peut être lu en anglais si le paramètre de
  langue n'est pas inclus dans les documents.

# Version 2.2 #

* Correction d'un bug qui ne permettait pas d'ouvrir la documentation pour
  les versions définitives de NVDA.

# Version 2.1 #

* Correction d'un bug qui n'a pas fermer correctement l'extension, cela a
  empêché la mise à jour de l'icône dans la barre d'état système.

# Version 2.0 #

* Le Menu Paramètres Weather Plus dans le sous-menu préférences a été
  déplacé.
* L'entrée correct n'est plus enregistrée à la volée, il est donc
  temporaire; pour appeler la ville définie dans les préférences, appuyez
  sur NVDA+contrôle+f3.

# Version 1.9 #

* Ajout de la fonction aide a la saisie.
* Ajout d'une nouvelle fonction pour une saisie rapide de Code Postal.
* Ajout de la lecture / écriture pour la configuration weather.ini,
  maintenant, plus besoin d'éditer le fichier source.
* Menu Weather ajouté dans la barre d'état système.
* Ajout du sous-menu Code Postal dans le menu paramètres.
* Ajout dans le sous-menu paramètres l'échelle de la température (Fahrenheit
  ou Celsius).
* Ajout du menu Documentation.
* ajout de la localisation Italienne.

# Première version 1.1 #

* Mis à jour de NVDA-addon.
* Le support de traduction a été ajouté.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
