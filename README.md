# docker-alpine-asciidoctor

A more lightweight version of the Asciidoctor Docker Container based on Alpine.

## Image Variants

### `alpine-asciidoctor`

[![](https://imagelayers.io/badge/rochdev/alpine-asciidoctor:latest.svg)](https://imagelayers.io/?images=rochdev/alpine-asciidoctor:latest 'Get your own badge on imagelayers.io')

This variant is the default and contains the full functionality from the official Asciidoctor image (except fopub at the moment).
Ideal if you need the full-fledged Asciidoctor in all its glory.

* Asciidoctor
* Aciidoctor Diagram with Graphviz integration so you can use plantuml and graphiz diagrams
* Asciidoctor PDF (alpha)
* Asciidoctor EPUB3 (alpha)
* Source highlighting using CodeRay or Pygments
* Asciidoctor backends
* Asciidoctor-confluence
* Lazybones (for Asciidoctor-revealjs)

### `alpine-asciidoctor:mini`

[![](https://imagelayers.io/badge/rochdev/alpine-asciidoctor:mini.svg)](https://imagelayers.io/?images=rochdev/alpine-asciidoctor:mini 'Get your own badge on imagelayers.io')

This variant is a trimmed down version with basic support for diagrams, support for PDF and EPUB3 formats and confluence.
Ideal if you need to export to several formats or make basic diagrams.

* Asciidoctor
* Aciidoctor Diagram
* Asciidoctor PDF (alpha)
* Asciidoctor EPUB3 (alpha)
* Source highlighting using CodeRay
* Asciidoctor-confluence

### `alpine-asciidoctor:micro`

[![](https://imagelayers.io/badge/rochdev/alpine-asciidoctor:micro.svg)](https://imagelayers.io/?images=rochdev/alpine-asciidoctor:micro 'Get your own badge on imagelayers.io')

This variant is a trimmed down version containing only the necessary to build basic asciidoc files with source highlighting.
Ideal for building simple documentation to HTML.

* Asciidoctor
* Source highlighting using CodeRay

## How to use it

See the documentation at the official repo: https://github.com/asciidoctor/docker-asciidoctor
