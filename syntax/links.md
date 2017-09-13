# Des liens

Markdown prend en charge deux styles de liens: en ligne et référence.

Dans les deux styles, le texte du lien est délimité par [crochets].

Pour créer un lien en ligne, utilisez un ensemble de parenthèses régulières immédiatement après le crochet de fermeture du texte du lien. Dans les parenthèses, placez l'URL où vous souhaitez que le lien pointe, ainsi qu'un titre facultatif pour le lien, entre guillemets. Par exemple:
`` `markdown
[Je suis un lien en ligne] (https://www.google.com)

[Je suis un lien en ligne avec le titre] (https://www.google.com "Google's Homepage")

[Je suis un lien de style de référence] [Texte de référence arbitraire insensible à la casse]

[Je suis une référence relative à un fichier de dépôt] (../ blob / master / LICENSE)
`` `

Les liens de style de référence utilisent un deuxième ensemble de crochets, dans lequel vous placez une étiquette de votre choix pour identifier le lien:
`` `markdown
Ceci est [un exemple] [id] lien de style de référence.
`` `

Vous pouvez éventuellement utiliser un espace pour séparer les ensembles de supports:
`` `markdown
Ceci est [un exemple] [id] lien de style de référence.
`` `

Ensuite, n'importe où dans le document, vous définissez votre lien comme celui-ci, sur une ligne par lui-même:
`` `markdown
[id]: http://example.com/ "Titre facultatif ici"
`` `

** GitHub ** et ** GitBook ** prend en charge l'autholage automatique d'URL. Ils autoriseront automatiquement les URL standard, donc, si vous souhaitez lier une URL (au lieu de définir le texte du lien), vous pouvez simplement entrer l'URL et elle sera transformée en un lien vers cette URL.


---

Voici un quiz sur les liens de réduction.

Sélectionnez les liens valides:
- [x] `[un lien] (http://google.fr)`
- [] `(un lien) [http://google.fr]`

> Le texte du lien est délimité par [crochets].

Quelles sont les informations correctes de ce lien: `` `[un lien] (http://google.fr" google ")` ``
- [] le lien est https://google.fr
- [x] le titre du lien est "google"
- [] il affichera le texte "google"
- [x] il affichera le texte "un lien"

> Les liens peuvent comporter 3 parties: le texte, l'URL et un titre.
