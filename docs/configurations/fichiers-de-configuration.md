---
hide:
  - toc
---

# Installation des fichiers de configuration

Cette étape permet de mettre en place les fichiers de configuration de votre imprimante et les différentes macros.


- Téléchargez la dernière version du Pack

- Rendez-vous sur l'interface Web de Mainsail via votre navigateur Web en saisissant l'adresse IP de votre Raspberry Pi.

- Rendez-vous dans les paramètres (roue dentée en haut à droite) :

![Paramètres](../assets/img/configurations/settings-1.png){ width="400" }

- Puis dans l’onglet **GÉNÉRAL** définissez un nom à l’imprimante, passez la langue en Français et fermez les paramètres :

![Paramètres](../assets/img/configurations/settings-2.png){ width="600" }

{==

:octicons-info-16: Vous pouvez passer en revue les différents paramètres et les configurer à votre convenance.

==}

- Rendez-vous dans l'onglet **Machine** sur la gauche puis importez les fichiers suivants situés dans le dossier **Configurations** du Pack :

  *	KlipperScreen.conf
  * printer.cfg
  * neopixels.cfg
  * macros.cfg
  * adxl345.cfg
  
{==

:octicons-info-16: Vous pouvez faire glisser les fichiers directement sur l’interface de Mainsail afin de les importer ou vous pouvez cliquer sur l’icône d’importation.

==}

![Importer](../assets/img/configurations/importer.png){ width="600" }

<br />

Vous pouvez ensuite continuer vers la section :material-arrow-right-box: [Changement du GCode de Début / Fin](../configurations/gcode-de-debut-fin.md).
