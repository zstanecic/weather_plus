# Weather Plus #

* Auteur : Adriano Barbieri
* Compatibilité NVDA : 2017.3 au-delà
* Télécharger : [Version stable][1]

# À propos de Weather Plus : #

* Cette extension ajoute à NVDA la température locale, les prévisions météo
  à 24 heures et les prévisions jusqu'à 2 jours supplémentaires et les
  prévisions horaires.
* Copyright (C) [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Publié sous la GNU GPL (General Public License) v2
* Weather Plus fonctionne grâce à l'utilisation et la présence des services
  suivants :
* [https://www.weatherapi.com/](https://www.weatherapi.com/)
* [http://www.geonames.org/](http://www.geonames.org/)
* [http://veloroutes.org/elevation/](http://veloroutes.org/elevation/)
* [http://www.nvda.it/](http://www.nvda.it/)

# UTILISATION : #

* Appuyez sur NVDA+w pour obtenir les informations sur la température
  actuelle et les conditions météo.
* Appuyez sur NVDA +maj+W pour obtenir les prévisions à 24 heures et à 2
  jours au-delà.
* Appuyez sur NVDA +maj+W deux fois pour obtenir la température horaire et
  les conditions atmosphériques.
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
 * Définir une ville temporaire... - Affiche et permet de définir une ville temporaire depuis une liste si disponible.
 * Documentation - Ouvrir le fichier d'aide pour la langue en cours.
 * Rechercher une mise à jour... - Signaler si une nouvelle version est disponible.

Pour ajouter une nouvelle ville : appuyer sur l'élément suivant :

* Définir et gérer vos villes... - Afficher ou définir la ville en cours
  depuis une liste.
* Le message suivant est affiché seulement la première fois ! Paramètres
  Prédéfinis Aucun F1: aide à la localisation, F2: dernière sélection avec
  TAB, F3: liste et zone d'édition, F4: contrôle de la durée des Prévisions
  Météo, F5: contrôles du volume.
* Dans la zone d'édition, saisissez une ville ou choisissez-en une dans la
  liste, si disponible. Remarque : La touche f5 est disponible si les effets
  sonores sont activés.
* Une fois appuyé sur Entrée sur l'élément "Définir et Gérer Vos Villes...",
  vous trouverez d'autres boutons comme suit :
* Tester - Testez la validité de la ville et trouvez les données de
  celle-ci.
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
* Réglage des prévisions horaires... - Ce bouton vous permet de choisir le
  contenu du bulletin des prévisions horaires.
* Échelle de mesure de la température : Utiliser le bouton radio pour
  choisir entre Celsius (par défaut), Fahrenheit et Kelvin.
* Degrés affichés comme : Utiliser le bouton radio pour choisir entre :
  Celsius `-` Fahrenheit `-` Kelvin (par défaut) C `-` F `-` K ou Non
  spécifié.
* Liste déroulante : Prévisions Météo jusqu'à jours : 1; choisissez une
  valeur entre 1 et 3 (1 jours par défaut)
* Liste déroulante : Langue de réponse de l'API : English, en; Vous pouvez
  choisir la langue du texte des conditions météorologiques.
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
* Ajouter la vitesse rafale de vent"; case à cocher cochée (par défaut)
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
* Ajouter la valeur de nébulosité"; case à cocher cochée (par défaut)
* Ajouter la valeur de précipitation; case à cocher cochée (par défaut)
* Ajouter la valeur du rayonnement ultraviolet; case à cocher cochée (par
  défaut)
* Lire les informations astronomiques; indique les heures de lever et de
  coucher du soleil et les heures de lever et de coucher de la lune. Case à
  cocher non cochée (par défaut)
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
* "Weather.default": Votre ville par défaut.
* "Weather_searchkey": mots-clés de recherche enregistrées.

--------------------------------------------------------------------------------

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=wetp
