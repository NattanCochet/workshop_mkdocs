# Etape 1

## Création de l'espace de travail

Une fois avoir crée votre répo github clonez le et accédez y à l'aide du terminal

Tapez

```sh
mkdocs new
```

afin de créer un projet mkdocs, cela va générer deux choses, un dossier "docs" et un fichier "mkdocs.yml", le premier est l'emplacement où vous allez modifier les pages markdown qui génereront votre site et le fichier yml aura comme rôle de modifier l'aspect et l'arborescence du site (c'est à dire comment les pages seront organisées).

## Contenu des fichiers par défaut

Ouvrez un environnement de développment **(vscode fortement recommandé)** dans le repo , le contenu des fichiers par défaut sera le suivant :

* mkdocs.yml :

```yml
site_name = My Docs
```


* docs/index.md :

```markdown
# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
```

Afin d'observer le rendu obtenu avec ces fichiers par défaut veuillez utiliser la commande suivante :

```sh
mkdocs serve
```

Cela ouvrira un serveur local que vous pourrez visitez à l'adresse suivante et qui se mettra à jour automatiquement quand un fichier markdown sera modifié.

[http://localhost:8000/](http://localhost:8000/)