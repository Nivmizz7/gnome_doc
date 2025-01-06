# GNOME 0.0  
## Date de sortie : août 1997  

**GNOME 0.0**, la toute première version de **GNOME**, lancée en août 1997, marque le début d’un projet ambitieux visant à créer un environnement de bureau libre et convivial, principalement destiné aux systèmes *Unix* et *Linux*.  

Cette version était principalement un point de départ et ne ressemblait pas à ce que **GNOME** est devenu aujourd’hui. En fait, **GNOME 0.0** était encore un ensemble de projets et d’idées sans une structure définie.  

---

## **Caractéristiques de GNOME 0.0**  

### **Objectif Principal**  
GNOME a été lancé pour fournir une alternative libre et open-source aux bureaux propriétaires comme **CDE** (**C**ommon **D**esktop **E**nvironment) et les solutions similaires d’alors.  
Il visait à intégrer un environnement de bureau facilement utilisable pour les utilisateurs de *GNU*/*Linux*.  

### **Technologies**  
- Modèle objet basé sur le langage **C**.  
- Utilisation de la bibliothèque **GTK+** (**GIMP Toolkit**), choisie comme fondation pour remplacer **Motif**, qui était *payante* et *non libre*.  

### **Interface Utilisateur**  
- **Simplicité** : Interface basique avec un gestionnaire de fenêtres rudimentaire, ne permettant pas une expérience cohérente.  
- **Pas de gestion de sessions** : Nécessité de lancer manuellement les applications à chaque démarrage du bureau.  
- **Composants restreints** : Pas de gestionnaire de fichiers complet comme **Nautilus** (introduit plus tard). GNOME 0.0 se composait uniquement d’utilitaires simples et expérimentaux.  
- **Écosystème d’applications limité** : Pas encore d’applications dédiées. La priorité était de poser les bases pour un développement futur.  

En résumé, **GNOME 0.0** était une version embryonnaire, avec une structure encore expérimentale et des outils limités.  

---

## **Compatibilité avec les distributions**  

Bien que **GNOME 0.0** soit une version expérimentale, il a été conçu dès le départ pour être compatible avec des distributions GNU/Linux et d'autres systèmes Unix-like.  

### **1. Compatibilité avec GNU/Linux**  
- Les premières distributions compatibles incluaient **Red Hat**, **Debian**, et **Slackware**.  
- **Installation manuelle** : GNOME 0.0 devait être compilé à partir des sources, car il n'était pas intégré par défaut.  

### **2. Compatibilité avec Unix et autres systèmes**  
- **Portabilité** : GNOME 0.0 visait une compatibilité avec Solaris, BSD, ou AIX grâce à GTK+.  
- **Problèmes de stabilité** : Les performances et la stabilité sur ces systèmes restaient limitées à ce stade.  

### **3. Absence de distributions GNOME spécifiques**  
- À l’époque, il n’existait pas de distribution dédiée à GNOME. L’environnement était installé manuellement sur des systèmes existants.  

### **4. Défis d’installation**  
- **Dépendances complexes** : Les bibliothèques nécessaires, comme **GTK+**, devaient être installées manuellement.  
- **Stabilité limitée** : GNOME 0.0 souffrait d’erreurs fréquentes et de plantages, rendant son utilisation difficile pour les non-techniciens.  

### **5. Utilisateurs ciblés**  
- Principalement destiné aux développeurs et contributeurs techniques.  
- Les utilisateurs non techniques préféraient des environnements de bureau plus stables, comme **FVWM** ou **CDE**.  

---

## **Conclusion sur la compatibilité des distributions**  
**GNOME 0.0** était compatible avec des distributions comme **Red Hat**, **Debian**, et **Slackware**, mais cette compatibilité était expérimentale.  

- **Installation complexe** : Les utilisateurs devaient compiler GNOME à partir des sources, sans assistance de packages précompilés.  
- **Stabilité limitée** : GNOME 0.0 n'était pas adapté à un usage quotidien et nécessitait des ajustements manuels.  
- **Support communautaire** : L’aide provenait essentiellement des développeurs et contributeurs de la communauté GNOME.  

Ce n’est qu’avec les versions suivantes que GNOME a atteint une maturité suffisante pour être intégré de manière fluide dans les distributions GNU/Linux.  

---  


## Installation :

  

### Dépendances :

 
## 1. **GCC** (**G**NU **C**ompiler **C**ollection)

  ***Vérification :***
`gcc --version`

Si GCC est installé, cette commande renverra la version du compilateur.

***Installation si nécessaire :***
	
 - Sur **Ubuntu**/**Debian** :
		`sudo apt-get install build-essential`    	
 - Sur **Fedora** :
		`sudo dnf install gcc`
 - Sur **Arch Linux** :
	    `sudo pacman -S gcc`

 

 
## 2. **GTK+**

### _Vérification :_
`gtk-config --version`

Si **GTK+** est installé, cette commande renverra la version de **GTK+**.

### _Installation si nécessaire :_

- Sur **Ubuntu**/**Debian** :  
  `sudo apt-get install libgtk2.0-dev`  
- Sur **Fedora** :  
  `sudo dnf install gtk2-devel`  
- Sur **Arch Linux** :  
  `sudo pacman -S gtk2`  

---

## 3. **Make**

### _Vérification :_
`make --version`

Si **Make** est installé, cette commande renverra la version de **Make**.

### _Installation si nécessaire :_

- Sur **Ubuntu**/**Debian** :  
  `sudo apt-get install make`  
- Sur **Fedora** :  
  `sudo dnf install make`  
- Sur **Arch Linux** :  
  `sudo pacman -S make`  

---

## 4. **Autoconf**

### _Vérification :_
`autoconf --version`

Si **Autoconf** est installé, cette commande renverra la version de **Autoconf**.

### _Installation si nécessaire :_

- Sur **Ubuntu**/**Debian** :  
  `sudo apt-get install autoconf`  
- Sur **Fedora** :  
  `sudo dnf install autoconf`  
- Sur **Arch Linux** :  
  `sudo pacman -S autoconf`  

---

## 5. **Automake**

### _Vérification :_
`automake --version`

Si **Automake** est installé, cette commande renverra la version de **Automake**.

### _Installation si nécessaire :_

- Sur **Ubuntu**/**Debian** :  
  `sudo apt-get install automake`  
- Sur **Fedora** :  
  `sudo dnf install automake`  
- Sur **Arch Linux** :  
  `sudo pacman -S automake`  

---

## 6. **Libtool**

### _Vérification :_
`libtool --version`

Si **Libtool** est installé, cette commande renverra la version de **Libtool**.

### _Installation si nécessaire :_

- Sur **Ubuntu**/**Debian** :  
  `sudo apt-get install libtool`  
- Sur **Fedora** :  
  `sudo dnf install libtool`  
- Sur **Arch Linux** :  
  `sudo pacman -S libtool`  

---

## Une fois toutes les dépendances installées, on peut passer à l'installation de GNOME 0.0.

### _Commandes pour installer GNOME 0.0 :_

1. **Télécharger les sources :**  
   `wget https://download.gnome.org/desktop/0.x/gnome-0.0.tar.gz`

2. **Extraire l'archive :**  
   `tar -xvzf gnome-0.0.tar.gz`

3. **Se déplacer dans le répertoire extrait :**  
   `cd gnome-0.0`

4. **Lancer le script de configuration :**  
   `./configure`

5. **Compiler le code source :**  
   `make`

6. **Installer GNOME :**  
   `sudo make install`

---

Et voilà, redémarrez et votre machine aura **GNOME 0.0** installé ! 
