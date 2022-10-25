---
weight: 3
title: "Sobre Hugo"
description: "Descriptions and examples of markdown syntaxes used in Hugo."
titleIcon: "fa-solid fa-cloud"
categories: ["Markdown"]
tags: ["Content management"]
---

Hugo es un framework destinado a la creación de páginas web.

Uno de los más populares en la creación de sitios estáticos.


## Instalación en Linux

La instalación en linux a base de comandos es sencilla, tan solo hay que seguir los pasos.

**Instalación**

1. Instalar snap para descargar hugo
{{< blockquote >}}
sudo apt-get install snap
{{< /blockquote >}}
2. Instalar hugo
{{< blockquote >}}
sudo snap install hugo --classic
{{< /blockquote >}}
3. Instalar un editor(por ejemplo VisualStudioCode)
{{< blockquote >}}
sudo snap install code --classic
{{< /blockquote >}}

**Creacion de la página**
{{< blockquote >}}
hugo new site "ejemplo"
{{< /blockquote >}}

***

## Instalación en Windows

La instalación en windows es algo más complicada.

**Instalación**

1. Descargar la ultima version en formato .zip de hugo
{{< blockquote >}}
https://github.com/gohugoio/hugo/releases
{{< /blockquote >}}
2. Extraer el .zip
3. Abrir CMD o PowerShell y añadir el .exe que hay en el .zip descomprimido, a la ruta preferida
{{< blockquote >}}
set PATH=%PATH%;C:\Hugo\bin
{{< /blockquote >}}

**Creacion de la página**

Igual que en linux.

{{< blockquote >}}
hugo new site "ejemplo"
{{< /blockquote >}}

Si tienes dudas mirate este video:

<!-- Viva cristo rey -->
{{<youtube G7umPCU-8xc>}}

