# GNOME 0.1

## Date de sortie : août 1998

GNOME 0.1, la première version publique du projet GNOME, a été lancée en août 1998.  
Elle marque un tournant important dans l’histoire de GNOME, car elle a permis de présenter un environnement de bureau libre et open-source aux utilisateurs de systèmes Unix et Linux.  
Bien que GNOME 0.1 ait encore été dans une phase expérimentale, elle a jeté les bases pour ce qui allait devenir un environnement de bureau mature et populaire.

---

## Caractéristiques de GNOME 0.1

### Objectif Principal
- Fournir une alternative libre et open-source aux environnements de bureau propriétaires comme **CDE** (*Common Desktop Environment*).  
- Offrir une plateforme unifiée pour les applications de bureau sur les systèmes GNU/Linux et Unix.  
- Poser les bases de GNOME en tant qu’environnement de bureau complet.

### Technologies
- **GTK+** : GNOME 0.1 a été construit sur la bibliothèque GTK+, qui permet de créer des interfaces graphiques dans les applications.  
- **Langage C** : GNOME 0.1 était principalement écrit en langage C, utilisant un modèle objet basé sur **GObject**, pierre angulaire du développement futur de GNOME.  

### Interface Utilisateur
- Interface très **basique**, sans gestionnaire de fenêtres avancé ni composants d’interface unifiés.  
- **Pas de gestion de sessions** : Les utilisateurs devaient lancer manuellement les applications à chaque démarrage.  

### Composants Restreints
- Pas de gestionnaire de fichiers complet comme **Nautilus** (introduit plus tard).  
- Ensemble limité d'outils : éditeur de texte et utilitaires de base.

### Support des applications
- Écosystème encore embryonnaire.  
- Pas encore d’applications majeures développées spécifiquement pour GNOME.  
- Principalement orienté vers les développeurs utilisant **GTK+**.  

---

## Compatibilité avec les distributions

### 1. Compatibilité avec GNU/Linux
- **Red Hat** et **Debian** furent les premières distributions intéressées par GNOME 0.1, bien qu’il fallait le compiler à partir des sources.  
- **Slackware** proposait un support limité nécessitant des ajustements manuels.  

### 2. Unix et autres systèmes compatibles
- **Portabilité** : Compatible avec Solaris, BSD ou AIX, bien que les performances fussent souvent inégales.  
- L'installation nécessitait des ajustements spécifiques.  

### 3. Distribution GNOME Spécifique
- Aucune distribution dédiée à GNOME n’existait encore.  
- GNOME pouvait être installé aux côtés d’environnements comme **KDE** ou **FVWM**.  

### 4. Problèmes de dépendances et de stabilité
- **Dépendances complexes** : Les bibliothèques nécessaires comme **GTK+** devaient être installées manuellement.  
- **Stabilité limitée** : Plantages fréquents en raison du caractère expérimental du logiciel.  

---

## Installation de GNOME 0.1

### Dépendances nécessaires

1. **GCC (GNU Compiler Collection)**  
   - Vérification :  
     `gcc --version`
   - Installation :  
     - Ubuntu/Debian : `sudo apt-get install build-essential`  
     - Fedora : `sudo dnf install gcc`  
     - Arch Linux : `sudo pacman -S gcc`  

2. **GTK+**  
   - Vérification :  
     `gtk-config --version`
   - Installation :  
     - Ubuntu/Debian : `sudo apt-get install libgtk2.0-dev`  
     - Fedora : `sudo dnf install gtk2-devel`  
     - Arch Linux : `sudo pacman -S gtk2`  

3. **Make**  
   - Vérification :  
     `make --version`
   - Installation :  
     - Ubuntu/Debian : `sudo apt-get install make`  
     - Fedora : `sudo dnf install make`  
     - Arch Linux : `sudo pacman -S make`  

4. **Autoconf**  
   - Vérification :  
     `autoconf --version`
   - Installation :  
     - Ubuntu/Debian : `sudo apt-get install autoconf`  
     - Fedora : `sudo dnf install autoconf`  
     - Arch Linux : `sudo pacman -S autoconf`  

5. **Automake**  
   - Vérification :  
     `automake --version`
   - Installation :  
     - Ubuntu/Debian : `sudo apt-get install automake`  
     - Fedora : `sudo dnf install automake`  
     - Arch Linux : `sudo pacman -S automake`  

6. **Libtool**  
   - Vérification :  
     `libtool --version`
   - Installation :
     - Ubuntu/Debian : `sudo apt-get install libtool`  
     - Fedora : `sudo dnf install libtool`  
     - Arch Linux : `sudo pacman -S libtool`  

---

### Étapes d'installation

1. **Télécharger les sources** :  
   `wget https://download.gnome.org/desktop/0.x/gnome-0.1.tar.gz`
   
2. **Extraire l'archive :**
  `tar -xvzf gnome-0.1.tar.gz`

3. **Se déplacer dans le répertoire extrait :**
  `cd gnome-0.1`

4. **Lancer le script de configuration :**
  `./configure`

5. **Compiler le code source :**
  `make`

6. **Installer GNOME :**
  `sudo make install`

Redémarrez et GNOME 0.1 sera installé sur votre machine. :)
