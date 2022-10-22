---
weight: 3
title: "Sobre Hugo"
description: "Descriptions and examples of markdown syntaxes used in Hugo."
titleIcon: "fa-solid fa-cloud"
categories: ["Markdown"]
tags: ["Content management"]
---

Hugo is a framework for creating web pages.

One of the most popular in the creation of static sites.


## Installation on Linux

The command-based installation in linux is simple, you just have to follow the steps.

**Facility**

1. Install snap to download hugo
{{< blockquote >}}
sudo apt-get install snap
{{< /blockquote >}}
2. Install hugo
{{< blockquote >}}
sudo snap install hugo --classic
{{< /blockquote >}}
3. Install an editor (for example VisualStudioCode)
{{< blockquote >}}
sudo snap install code --classic
{{< /blockquote >}}

**Page creation**
{{< blockquote >}}
hugo new site "example"
{{< /blockquote >}}

## Installation on Windows

Installation on windows is somewhat more complicated.

**Facility**

1. Download the latest version in .zip format from hugo
{{< blockquote >}}
https://github.com/gohugoio/hugo/releases
{{< /blockquote >}}
2. Extract the .zip
3. Open CMD or PowerShell and add the .exe that is in the uncompressed .zip, to the preferred path
{{< blockquote >}}
set PATH=%PATH%;C:\Hugo\bin
{{< /blockquote >}}

**Page creation**

Same as on linux.

{{< blockquote >}}
hugo new site "example"
{{< /blockquote >}}

If you have doubts, watch this video:

{{<youtube G7umPCU-8xc>}}