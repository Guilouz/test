---
hide:
  - toc
---

# Connexion SSH sous MacOS

- Afin d’obtenir l’adresse IP de votre Raspberry Pi sur votre réseau, téléchargez **LanScan** ici : <a href="https://apps.apple.com/fr/app/lanscan/id472226235?mt=12" target="_blank">https://apps.apple.com/fr/app/lanscan/id472226235?mt=12</a>

- Lancez l'application et cliquez sur **Config** :

![01](../../assets/img/installation/ssh/macos/01.png){ width="600" }

- Sélectionnez la bonne interface réseau utilisée par votre MAC dans la partie **Select interface** puis cliquez sur **Scan** :

![02](../../assets/img/installation/ssh/macos/02.png){ width="600" }

- Récupérez ensuite l’adresse IP correspondante à votre Raspberry Pi (il porte le même nom que le nom d’hôte renseigné dans **Raspberry Pi Imager**) :

![03](../../assets/img/installation/ssh/macos/03.png){ width="600" }

- Lancez ensuite l'application **Terminal** et saisissez la commande suivante :

```
ssh pi@adresse_ip_du_raspberry # (1)!
```

1.  :warning: Remplacez le champ 'adresse_ip_du_raspberry' par l'adresse IP obtenue précédemment.

``` yaml
content.code.annotate # (1)
```

1.  :warning: Remplacez le champ 'adresse_ip_du_raspberry' par l'adresse IP obtenue précédemment.


![04](../../assets/img/installation/ssh/macos/04.png){ width="600" }

- Puis saisissez votre mot de passe précédemment défini dans **Raspberry Pi Imager** (il ne s'affiche pas à la saisie, cela est normal) :

![05](../../assets/img/installation/ssh/macos/05.png){ width="600" }

- Vous êtes désormais connecté :

![06](../../assets/img/installation/ssh/macos/06.png){ width="600" }



<br />

Vous pouvez ensuite continuer vers la section :material-arrow-right-box: [Installation des dépendances](../dependances.md) 
