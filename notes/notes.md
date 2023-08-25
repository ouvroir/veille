# Notes de travail

## 25/08/2023

- familiarisation avec les fichiers XML : 
	- lecture des fichiers
	- génération de RNG pour avoir une vue d'ensemble sur les tags utiliés dans chacun des fichiers


### Lecture de Projects.xml

`projects.xml` fait référence à [XBEL](http://xbel.sourceforge.net): 

XML Bookmark Exchange Language. C'est : "an Internet "bookmarks" interchange format [...] useful [...] for a range of browsers, including the major browsers and a number of less widely used browsers." La documentation est disponible ici: https://xbel.sourceforge.net/language/versions/1.0/xbel-1.0.xhtml.

**Questions :** 
- a-t-il été envisagé d'implémenter le schéma proposé par XBEL pour la description des projets?

**Potentielles tâches :** 
- faire un test sur les URL invalides dans la liste (`//idno/@type=uri`), voir s'il faut les mettre à jour
- faire un test sur les handles Twitter (`//idno/@type=twitter`), voir s'ils sont toujours actifs (nota: c'est plus difficile à faire sans l'API Twitter désormais)
- faire un listing de toutes les valeurs utilisées dans `//keywords` en vue d'une homogénéisation
- la balise `keywords` n'a pas l'air d'être acceptée en dehors de `teiHeader` (cf. [doc](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/examples-keywords.html)), il faudrait voir s'il existe une autre balise mieux adaptée.
- ajouter les informations `country` quand elles manquent
- l'élément `category/categories` (val: lab | project) n'est pas systématiquement utilisé. Trouver une autre manière de l'intégrer car comme `keywords`, `category` est attendu dans `teiHeader`, tandis que `categories` n'est pas un élément valide.
- :warning: à partir de la ligne 163, jusqu'à la ligne 432, dans `projects.xml`, il faut une conversion vers des éléments `org` car on a des `website` à la place.

### Lecture de Blogs.xml

**Questions :** 
- Veut-on chercher sur les handles/comptes Twitter existent désormais sur d'autres plateformes comme Mastodon?

**Potentielles tâches :** 
- TEIfier le document (`/blogs`)!
- faire un test sur les URL invalides dans la liste (`//url` et `//rss`), voir s'il faut les mettre à jour
- faire un test sur les handles Twitter (`//twitter`), voir s'ils sont toujours actifs (nota: c'est plus difficile à faire sans l'API Twitter désormais)
- les références ne sont pas systématiquement associées à des tags, ce serait peut-être difficile mais plus lisible d'avoir des mots-clef pour tout.
- faire un listing de toutes les valeurs utilisées dans `//tags/tag` en vue d'une homogénéisation

### Lecture de Researchers.xml 

**Potentielles tâches :** 
- rendre les métadonnées plus inclusives
- faire un test sur les URL invalides dans la liste (`//idno/@type="academic"` et `//idno/@type="github"` et `//idno/@type="lab"` et `//idno/@type="perso"` et `//idno/@type="linkedin"` et `//idno/@type="uri"`), voir s'il faut les mettre à jour
- faire un test sur les handles Twitter (`//idno/@type="twitter"`), voir s'ils sont toujours actifs (nota: c'est plus difficile à faire sans l'API Twitter désormais)
- garder en tête pour plus tard que les bio devraient peut-être être mises à jour (mais c'est un gros chantier que l'on peut faire plus tard, une fois que les données sont structurées)
- faire un listing de toutes les valeurs utilisées dans `//keywords` en vue d'une homogénéisation
- la balise `keywords` n'a pas l'air d'être acceptée en dehors de `teiHeader` (cf. [doc](https://www.tei-c.org/release/doc/tei-p5-doc/en/html/examples-keywords.html)), il faudrait voir s'il existe une autre balise mieux adaptée.