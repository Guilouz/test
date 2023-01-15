---
hide:
  - toc
---

# Utilisation de la Rétraction Firmware

La Rétraction Firmware donne un avantage comparé à la rétraction Slicer, elle peut être modifiée pendant une impression (depuis Mainsail ou KlipperScreen). 

Un même modèle peut donc être imprimé avec des paramètres de rétraction différents sans nécessité d'être reslicé.


## Pour Cura :

- Il est nécessaire d'installer le plugin **Klipper Settings Plugin** disponible dans le Pack (sources : :simple-github: <a href="https://github.com/jjgraphix/KlipperSettingsPlugin" target="_blank">Github</a>).

- Démarrez Cura et allez dans l'onglet **Aide** -> **Afficher le dossier de configuration**.

-	Copiez le dossier **KlipperSettingsPlugin** du Pack (présent dans le dossier Slicers/Cura) dans le dossier **plugins**.

-	Quittez Cura et redémarrez-le.

-	Activez le paramètre **Enable Firmware Retraction** comme cela sans renseigner de valeur :

![Rétraction Cura](../assets/img/configurations/retraction-cura.png){ width="300" }


## PrusaSclicer / SuperSlicer :

- Il est juste nécessaire d'activer le paramètre **Utiliser la rétraction du firmware** depuis l’onglet **Réglages de l’imprimante** --> **Général** comme cela :


![Rétraction PrusaSclicer / SuperSlicer](../assets/img/configurations/retraction-prusaslicer.png){ width="600" }

<br />

L'installation principale est maintenant terminée, vous pouvez continuer vers les sections :

:material-arrow-right-box: [Configuration d'un écran avec KlipperScreen](../configurations/ecran-avec-klipperscreen.md) si vous possédez un écran.

:material-arrow-right-box: [Configuration de l'ADXL](../configurations/adxl.md) si vous utilisez un ADXL pour mesurer les résonances.

:material-arrow-right-box: [Configuration des NeoPixels](../configurations/neopixels.md) si vous possédez des NeoPixels.

:material-arrow-right-box: [Installation du thème Mainsail](../configurations/theme-mainsail.md) si vous désirez installer un thème pour Mainsail.

:material-arrow-right-box: [Fixer l'adresse IP du Raspberry Pi](../configurations/fixer-adresse-ip.md) si vous désirez configurer une adresse IP statique au Rapsberry Pi.
