# Installation du hook pre-commit

Ce hook demande à chaque commit si vous voulez sauvegarder 
les informations du commit dans le fichier suivi/commitInfo.txt

## Installation :

1. Copier le fichier pre-commit dans .git/hooks/
   cp git-hooks/pre-commit .git/hooks/pre-commit

2. Rendre le script exécutable :
   chmod +x .git/hooks/pre-commit

3. Le hook est maintenant actif !

## Utilisation :

À chaque commit, le hook vous demandera :
"Sauvegarder les infos du commit (y/[n]) ?"

- Tapez "y" pour sauvegarder la date dans suivi/commitInfo.txt
- Tapez "n" ou Entrée pour ignorer
