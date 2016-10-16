# Cours 2: Devoirs

Merci à tous pour ce cours! J'espère que vous vous sentez plus à l'aise en Python.

Les devoirs pour la semaine qui vient:

**1. Installer pip (on en aura besoin pour le cours 3)**

  Sur Windows:
  
    - Ceux qui ne pouvaient pas lancer pip via le terminal n'arrivaient pas non plus à lancer python ("python is not recognized ..."): le problème vient du fait que votre machine ne sait pas où se trouve python.
  
      Le plus simple, c'est de relancer l'installer de Python 3.5, sélectionner Modify et cocher "Add Python.exe to path" à la réinstallation.
      
      Quand vous l'aurez fait, allez dans le terminal et tapez python.
      
        - Si même erreur, voir 2)
        
        - Si python se lance, tapez exit() pour revenir dans l'invite de commandes et tapez pip
          - Si vous avez une réponse, c'est bon
          - Si erreur, faites ce qui est indiqué dans les 2 premières lignes [ici](https://pip.pypa.io/en/stable/installing/#installing-with-get-pip-py) et réessayez, ça devrait fonctionner 
      
      Si Sublime marche pas quand vous ouvrez votre fichier Cours 2.py (ou autre) avec et que vous faites Ctrl + B, désinstallez-réinstallez Sublime, ça devrait fonctionner aussi.

    - Si fouiller dans l'ordi ne vous dérange pas, vous pouvez essayer de résoudre le problème en ajoutant ```C:\[directory où se trouve python.exe (pas le raccourci)]``` (e.g. chez moi ```C:\Users\Youssoup Pachaev\Anaconda3\```) + ```[même directory]\Scripts``` dans votre ```Control Panel/System and Security/System/Advanced system settings/Advanced/Environment variables/System variables/Path``` (ça ressemblera à ```C:\Windows;C:\dir\dir2;C:...;C:\le dir avec python.exe\;C:\le même dir\Scripts\```).

  Sur Mac:
    - On a pas essayé sur Mac je crois, ils disent [ici](https://docs.python.org/3/using/mac.html#getting-and-installing-macpython) que ça fonctionne tout de suite, mais si ça marche pas, vous pouvez suivre les instructions d'[ici](https://stackoverflow.com/questions/20082935/how-to-install-pip-for-python3-on-mac-os-x) ou d'[ici](https://pip.pypa.io/en/stable/installing/#installing-with-get-pip-py) (comme pour Windows).
    - Désinstaller-réinstaller Python 3.5 est la solution brute force
    
**2.** Si vous arrivez pas à installer, **venez me voir avant samedi**, je le ferai rapidement moi-même (envoyez un message au 06 51 46 73 65, n'hésitez surtout pas).

**3. Lisez le cours 2**: il n'est pas nécessaire d'installer BioPython pour refaire les exercices, BioPython a été créé pour les biologistes, pas les bio-informaticiens, donc c'est excessivement simple.

   Si vous installez BioPython, je vous interdis de l'utiliser en-dehors des exercices du cours, il faut que vous appreniez à coder vous-mêmes ce dont vous avez besoin.

**3. Entraînez-vous sur CheckIO ou [Rosalind](http://rosalind.info/problems/locations/) (dans Bioinformatics Stronghold).**

   Rosalind est très apprécié des bio-informaticiens (c'est toujours mentionné quand quelqu'un demande comment apprendre la bio-informatique). Les problèmes sont bien faits, les concepts liés aux exercices sont expliqués, etc. Les exercices du début sont un peu répétitifs, mais ça devient vite difficile.

   Si vous devez choisir entre les 2 sites, je vous demande de travailler sur CheckIO: Rosalind correspond plus au type de problèmes auxquels vous serez confrontés en bio-informatique, mais CheckIO vous rend un meilleur programmeur. Bien entendu, vous pouvez utiliser les 2 sites.

**4.** Aurélie m'a demandé une sélection d'exercices: je suis allé faire un tour dans Elementary et dans Scientific Expedition et je pense qu'ils sont tous utiles. Contrairement à Rosalind, CheckIO est un site de programmation general purpose, donc les exercices font appel à tout l'éventail des capacités de Python et enseignent principalement à réfléchir comme un programmeur. **Faites autant de problèmes que vous pouvez**, vous apprendrez à construire une vision très abstraite et logique de chaque problème, ce qui nous servira dès le cours suivant.

Je vais essayer de trouver un bon site pour faire un **groupe de discussion**, on pourra s'entraider. Je vous préviendrai quand ce sera fait.

Merci encore pour le cours, passez une bonne semaine!
