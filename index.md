---
title: "Style Master File - Application Reference"
author: "Nitish Kohli"
date: "2022-08-22"
site: bookdown::bookdown_site
documentclass: book
# bibliography: [book.bib, packages.bib]
# url: your book url like https://bookdown.org/yihui/bookdown
# cover-image: path to the social sharing image like images/cover.jpg
description: |
  This is a minimal example of using the bookdown package to write a book.
  The HTML output format for this example is bookdown::bs4_book,
  set in the _output.yml file.
# biblio-style: apalike
# csl: chicago-fullnote-bibliography.csl
---

# Overview

[Style Master File (SMF)](https://inqube.shinyapps.io/Style-Master-File/){target="_blank"} is a R Shiny application, developed primarily to streamline the Bulk Order Processing flow between the Marketing, PDC, Costing, and COE teams.

SMF App was developed to reduce the duplication of work, reduce the amount of workload and provide a more easy to use interface for handling higher volumes of orders. This application's process and architecture enables InQube to flexibly scale operations with ease to meet the ever-changing Customer requirements.

## Sections / Sub-Modules

The main application page is divided into the following tab sections.

-   [Dashboard]
-   [Product List]
-   [Bill of Materials]
-   [Orderbook]
-   [Bulk Cons][Bulk YY]
-   [Pattern Details]
-   [IE]
-   [Multiple BOM Editor]
-   [Thread YY]
-   [Thread YY - IE][Thread YY]
-   [COE Jobs]

## Process Map


```{=html}
<div id="htmlwidget-e885413de9431531dd45" style="width:672px;height:480px;" class="grViz html-widget"></div>
<script type="application/json" data-for="htmlwidget-e885413de9431531dd45">{"x":{"diagram":"digraph {\n  graph [layout = dot, rankdir = TB]\n  \n  node [shape = rectangle]        \n  rec1 [label = \"Create Product ID\"]\n  rec2 [label = \"Create BOM with Fabric\"]\n  rec3 [label = \"Add SMV &\nChassis Code (IE)\"]\n  rec4 [label = \"Update Pattern Details\"]\n  rec5 [label = \"Add Trims to BOM\"]\n  rec6 [label = \"Send Style Creation to COE\"]\n  rec7 [label = \"Recieve Buy from Customer\"]\n  rec8 [label = \"Upload Orderbook\"]\n  rec9 [label = \"Update BOM\nwith Final Changes\"]\n  rec10 [label = \"Update Bulk YY\"]\n  rec11 [label = \"Confirm Bulk YY Update\"]\n  rec12 [label = \"Send OC Creation Job\"]\n  rec13 [label = \"Send Bulk YY Update to COE\"]\n  \n  # edge definitions with the node IDs\n  rec1 -> rec2, rec3\n  \n  rec2 -> rec4, rec5\n  \n  rec3, rec4, rec5 -> rec6 -> rec7 -> rec8, rec9\n  \n  rec8 -> rec10, rec12\n  rec10 -> rec11\n  \n  rec9, rec11 -> rec13\n  \n  }","config":{"engine":"dot","options":null}},"evals":[],"jsHooks":[]}</script>
```
