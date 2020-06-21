# gest-hh-wordpress

> **German Content**
>
> This repository contains SCSS files for creating a custom CSS for WordPress
> for the website [gest-hamburg.de](https://gest-hamburg.de/). You will find
> descriptions and commit messages in German, as it is a German website.

In diesem Repository finden Sie die SCSS-Quellen zur Erstellung eines
angepassten CSS for die Site [gest-hamburg.de](https://gest-hamburg.de/),
die auf WordPress basiert.

## Verwendung

### Voraussetzungen

* NodeJS, inklusive `npm`.

    Installation unter Windows etwa mittels [Scoop](https://github.com/lukesampson/scoop):

    ```bash
    λ scoop install nodejs
    ```

### Erstellung der CSS-Datei

* Einmaliges Erstellen von `custom-main.css`:

    ```bash
    λ npm run build
    ```

    Das Ergebnis befindet sich anschließend in `target/`.

* Automatisches Erstellen von `custom-main.css` bei Änderungen an den SCSS Dateien:

    ```bash
    λ npm run build
    ```

    Das Ergebnis befindet sich jewils in `target/`.

### Verwendung in WordPress

Um das Ergebnis in WordPress zu verwenden, muss der sogenannte _Customizer_
im Administrationsbereich _Design_ aufgerufen werden. Dort gibt es einen
Bereich _Zusätzliches CSS_. In diesen Bereich kann das entsprechende CSS
kopiert werden.

## Referenzen

Folgende Seiten waren mir bei der Entwicklung dienlich:

### SASS/SCSS

* [CSS { In Real Life } | A Modern Front End Workflow Part 1: Building a Project Starter with NPM Scripts](https://css-irl.info/a-modern-front-end-workflow-part-1/)
* [Introducing Sass Modules | CSS-Tricks](https://css-tricks.com/introducing-sass-modules/)
