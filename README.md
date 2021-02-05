## Technical Details

The Playbook is compiled from [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") files using [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). To propose a specific change, you can submit a [pull request](https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") with your change to one of these source Markdown files. The Plays from the Playbook are [available in the `_plays` folder](https://github.com/cds-snc/technical-playbook-manuel-technique/tree/main/_plays).

You can also use Github's in-browser editing feature to make an edit to one of these Markdown files and submit your change for consideration without needing to install any additional software.

### Running the Site Locally

To run the site locally on your own computer (most helpful for previewing your own changes), you will need to install Jekyll and other dependencies:

1. If you don't already have Ruby and Bundler installed, follow [the first two steps in these Jekyll installation instructions](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").
2. Next, [fork this repository](https://help.github.com/articles/fork-a-repo/ "Instructions for Forking Your Repository") and clone it on your computer.
3. Navigate to the folder on your computer, and run the command `bundle install` at the command line prompt.

To run the site locally, run `jekyll serve --watch`, then visit `http://localhost:4000/` in your browser to preview the site.

### Editing the Stylesheets

This project uses [Sass](http://sass-lang.com/ "Link to Learn More About Sass") for managing its style sheets. These styles are defined in the [`styles.scss` file](assets/_sass/styles.scss). We use [Jekyll's native SASS support](https://jekyllrb.com/docs/assets/) to auto-generate the required CSS when you run the site locally, as described above.

---

## Détails Techniques

Le manuel est compilé à partir des fichiers [Markdown](https://help.github.com/articles/github-flavored-markdown "Link to More Information About Markdown") en utilisant [Jekyll](https://github.com/jekyll/jekyll "Link to More Information about Jekyll"). Pour proposer un changement, vous devez soumettre un Pull Request (https://help.github.com/articles/creating-a-pull-request "More Information on Submitting Pull Requests") avec votre changement dans l'un de ces fichiers Markdown source. Les stratégies techniques sont [disponibles dans le dossier `_plays`](https://github.com/cds-snc/technical-playbook-manuel-technique/tree/main/_plays).

Vous pouvez également utiliser la fonction d'édition dans le navigateur de Github pour modifier l'un de ces fichiers et soumettre vos changements.

### Faire fonctionner le site localement

Pour faire fonctionner le site en local sur votre propre ordinateur (ce qui est très utile pour prévisualiser vos propres modifications), vous devrez installer Jekyll et d'autres dépendances:

1. Si vous n'avez pas encore installé Ruby et Bundler, suivez [les deux premières étapes de ces instructions d'installation de Jekyll](https://help.github.com/articles/using-jekyll-with-pages#installing-jekyll "Installation instructions for Jekyll").
2. Ensuite, [créez une bifurcation de ce dépôt](https://help.github.com/articles/fork-a-repo/ "Instructions for Forking Your Repository") et clonez-la sur votre ordinateur.
3. Naviguez vers le dossier sur votre ordinateur, et lancez la commande "Bundle install" à l'invite de la ligne de commande.

Pour faire fonctionner le site localement, executez `jekyll serve --watch` dans l'invite de la ligne de commande, puis visitez `http://localhost:4000/` dans votre navigateur pour prévisionner le site.

### Modifier les feuilles de style

Ce projet utilise [Sass](http://sass-lang.com/ "Link to Learn More About Sass") pour gérer ses feuilles de style.
Ces styles sont définis dans le fichier [`styles.scss`](assets/_sass/styles.scss). Nous utilisons [le support SASS natif de Jekyll](https://jekyllrb.com/docs/assets/) pour générer automatiquement les feuilles de style CSS requises lorsque vous exécutez le site en local, comme décrit ci-dessus.
