
### Navigation

- `pwd` : affiche le dossier où tu te trouves.
- `ls` : liste les fichiers du dossier (`-l` détail, `-a` fichiers cachés).
- `cd dossier` : entre dans un dossier (`cd ..` remonte, `cd` seul ramène chez toi).

### Fichiers et dossiers

- `mkdir nom` : crée un dossier (`-p` crée toute l'arborescence).
- `touch fichier` : crée un fichier vide (ou met à jour sa date).
- `cp source dest` : copie un fichier (`-r` pour un dossier).
- `mv source dest` : déplace ou renomme.
- `rm fichier` : supprime définitivement (`-r` pour un dossier, prudence avec `-rf`).
- `cat fichier` : affiche tout le contenu d'un fichier.
- `head fichier` : affiche les premières lignes (`-n 5` pour en choisir le nombre).
- `tail fichier` : affiche les dernières lignes.
- `wc fichier` : compte lignes, mots et caractères (`-l` pour les lignes seulement).

### Recherche et filtrage

- `grep "texte" fichier` : cherche un texte dans un fichier (`-i` ignore la casse, `-n` numéros de ligne, `-r` dans un dossier).
- `find . -name "*.c"` : cherche des fichiers par nom à partir d'un dossier.
- `sort fichier` : trie les lignes par ordre alphabétique.
- `diff f1 f2` : montre les différences entre deux fichiers.

### Redirections (à combiner avec tout le reste)

- `>` : envoie la sortie dans un fichier en l'écrasant.
- `>>` : ajoute la sortie à la fin d'un fichier.
- `|` (pipe) : envoie la sortie d'une commande vers l'entrée de la suivante.
- `<` : utilise un fichier comme entrée d'une commande.

### Droits et système

- `chmod +x fichier` : rend un fichier exécutable.
- `whoami` : affiche ton nom d'utilisateur.
- `sudo commande` : exécute avec les droits administrateur.
- `ps` : liste les processus en cours (`ps aux` pour tous).
- `kill PID` : arrête un processus grâce à son numéro.
- `which commande` : indique où se trouve une commande.
- `echo "texte"` : affiche un texte (pratique avec `>` pour écrire dans un fichier).
- `tar` : regroupe ou compresse des fichiers (`tar -xzf archive.tar.gz` pour décompresser).

### Aide

- `man commande` : ouvre le manuel complet (`q` pour quitter).
- `commande --help` : affiche un résumé rapide.
- `history` : liste les commandes que tu as tapées.

### Développement

- `gcc -Wall -Wextra -Werror fichier.c -o prog` : compile du C avec tous les avertissements en erreurs.
- `make` : compile automatiquement à partir d'un `Makefile`.
- `gdb ./prog` : débogue un programme pas à pas.
- `valgrind --leak-check=full ./prog` : détecte les fuites mémoire.
- `git init` : crée un dépôt Git dans le dossier courant.
- `git add fichier` : prépare un fichier pour le prochain commit.
- `git commit -m "message"` : enregistre une version avec un message.
- `git status` : montre l'état de tes fichiers (modifiés, préparés).
- `git log` : affiche l'historique des commits.
- `git push` : envoie tes commits vers GitHub.
- `git pull` : récupère les nouveautés depuis GitHub.
- `vim fichier` : ouvre un fichier dans Vim (`i` écrire, `Échap` puis `:wq` sauvegarder et quitter).

### Raccourcis clavier utiles

- `Tab` : complète automatiquement un nom de fichier ou de commande.
- `↑` / `↓` : parcourt l'historique des commandes.
- `Ctrl + C` : interrompt le programme en cours.
- `Ctrl + L` : nettoie l'écran.


