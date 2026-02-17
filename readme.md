Ce projet vous permet d'utiliser la charte graphique de Centrale Méditerranée pour rédiger un rapport technique, notamment pour un rapport de stage ou un rapport de projet. Le projet est organisé de la manière suivante :

- `main.tex` : le fichier principal du projet, qui inclut les autres fichiers nécessaires à la compilation du rapport.
- `style.sty` : le fichier de style qui définit la charte graphique de Centrale Méditerranée.
- `biblio.bib` : un fichier de bibliographie au format BibTeX, utilisé pour gérer les références bibliographiques du rapport.
- `images/` : un dossier contenant les images utilisées dans le rapport.
- `build/` : un dossier qui sera généré lors de la compilation du rapport, contenant les fichiers intermédiaires et le PDF final.
- `sections/` : un dossier contenant les différentes sections du rapport, organisées en fichiers séparés pour une meilleure lisibilité et modularité.
  - `0-titlepage.tex` : la page de titre du rapport.
  - `1-remerciements.tex` : la section des remerciements.
  - `2-resume.tex` : le résumé du rapport.
  - `3-abstract.tex` : le résumé en anglais du rapport.
  - `4-keywords.tex` : la section des mots-clés du rapport.
  - `5-glossaire.tex` : le glossaire du rapport.
  - `6-body.tex` : le corps du rapport. Ce fichier liste les différentes parties du corps, chacune étant dans un fichier séparé dans le dossier `6-body`:
    - `0-intro.tex` : l'introduction du rapport.
    - `1-presentation.tex` : la section des matériels et méthodes.
    - `2-missions.tex` : la section des missions effectuées.
    - `3-competencescentraliennes.tex` : la section des résultats obtenus.
    - `4-conclusion.tex` : la section de conclusion.
  - `7-annexes.tex` : la section des annexes. Ce fichier liste les différentes annexes, chacune étant dans un fichier séparé dans le dossier `7-annexes`:
    - `annexeA.tex` : la première annexe du rapport.
    - `annexeB.tex` : la deuxième annexe du rapport.

Pour compiler le rapport:

- Si vous voulez une solution clé en main, je recommande d'utiliser Overleaf.

- Si vous souhaitez compiler localement, vous pouvez utiliser MixTex sur Windows, ou TeXLive sur Linux. Pour éditer, le mieux est alors d'utiliser Visual Studio Code avec l'extension LaTeX Workshop.


Vous pouvez accéder au rapport vierge compilé avec le fichier [main.pdf](main.pdf).
