---
weight: 3
title: "Sobre Hugo"
description: "Descriptions and examples of markdown syntaxes used in Hugo."
titleIcon: "fa-solid fa-cloud"
categories: ["Markdown"]
tags: ["Content management"]
---

Hugo est un framework pour créer des pages web.

L'un des plus populaires dans la création de sites statiques.


## Installation sous Linux

L'installation basée sur des commandes sous Linux est simple, il vous suffit de suivre les étapes.

**Facilité**

1. Installez snap pour télécharger hugo
{{< blockquote  >}}
sudo apt-get install snap
{{< /blockquote >}}
2.Installez hugo
{{< blockquote >}}
sudo snap install hugo --classic
{{< /blockquote >}}
3. Installez un éditeur (par exemple VisualStudioCode)
{{< blockquote >}}
sudo snap install code --classic
{{< /blockquote >}}

**Création de pages**
{{< blockquote >}}
hugo new site "exemple"
{{< /blockquote >}}

## Installation sous Windows

L'installation sur Windows est un peu plus compliquée.

**Installations**

1. Téléchargez la dernière version au format .zip depuis hugo
{{< blockquote >}}
https://github.com/gohugoio/hugo/releases
{{< /blockquote >}}
2. Extraire le .zip
3. Ouvrez CMD ou PowerShell et ajoutez le .exe qui se trouve dans le .zip non compressé, au chemin préféré
{{< blockquote >}}
set PATH=%PATH%;C:\Hugo\bin
{{< /blockquote >}}

**Création de pages**

Pareil que sur linux.

{{< blockquote >}}
hugo new site "exemple"
{{< /blockquote >}}

Si vous avez des doutes, regardez cette vidéo :

{{<youtube G7umPCU-8xc>}}