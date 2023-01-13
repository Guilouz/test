---
hide:
  - toc
---

# Connexion SSH sous MacOS

- Afin d’obtenir l’adresse IP de votre Raspberry Pi sur votre réseau, téléchargez **LanScan** ici : <a href="https://www.advanced-ip-scanner.com/fr/" target="_blank">[https://www.advanced-ip-scanner.com/fr/](https://apps.apple.com/fr/app/lanscan/id472226235?mt=12)</a>

- Lancez l'application et cliquez sur **Config** :

![01](../../assets/img/installation/ssh/macos/01.png){ width="600" }

- Sélectionnez la bonne interface réseau utilisée par votre MAC sans la partie **Select interface** puis cliquez sur **Scan** :

![02](../../assets/img/installation/ssh/macos/02.png){ width="600" }

- Récupérez ensuite l’adresse IP correspondante à votre Raspberry Pi (il porte le même nom que le nom d’hôte renseigné dans **Raspberry Pi Imager**) :

![03](../../assets/img/installation/ssh/macos/03.png){ width="600" }

- Lancez ensuite l'application **Terminal** et saisissez la commande suivante :

```
ssh pi@`#!python adresse_ip_du_raspberry` # (1)
```
1. :warning: Remplacez le champ 'adresse_ip_du_raspberry' par l'adresse IP obtenue précédemment.



<br />

Vous pouvez ensuite continuer vers la section :material-arrow-right-box: [Installation des dépendances](../dependances.md) 
