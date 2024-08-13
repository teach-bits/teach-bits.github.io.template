---
layout: post
title: Hello World!
description: >
  Erster Blogpost 🥳 Dazu eine kurze Dokumentation der verwendeten Tools.
sitemap: false
hide_last_modified: true
---

Ich bin ein Berliner Informatik-Lehrer und verschriftliche endlich mal all die Ideen, die für andere Lehrkräfte interessant sein könnten.

Wir gründen eine neue Maker AG an meiner Schule und sie ist ein guter Grund, einen Blog zu beginnen. Geplant sind kleine "Bits", die für sich alleine stehend Maschinen, Software oder Themen vorstellen und im weiteren Verlauf aufeinander aufbauen.

## Github Pages
Github bietet mit [Github Pages](https://pages.github.com) eine kostenlose Möglichkeit, einen statischen Blog zu hosten. Das klingt spitze und muss ich unbedingt mal testen.
Ich habe mich dafür entschieden, dafür einen neuen Github Account zu erstellen, so dass hier nur der Content des Blogs liegt.

## Hydejack
Github Pages verwendet [Jekyll](https://github.com/jekyll/jekyll) und angeblich ist die Einbindung von Themes ganz einfach. Ich habe als ersten Versuch das Theme [Hydejack](https://hydejack.com) geforked, brauche hier aber den Branch *gh-pages*. Das war soweit leicht, bringt aber eine größere Dateistruktur mit vielen Beispiel-Posts etc. mit sich, die ich erstmal aufräumen muss.

## Lokal
In der Github Seite zu arbeiten ist zwar ganz nett und hat auf Anhieb funktioniert, aber so möchte ich keine Blogposts schreiben. Daher habe ich das Repo gecloned und nach der [Hydejack-Doku](https://hydejack.com/docs/install/) mit den zwei einfachen Zeilen
~~~bash
bundle install
bundle exec jekyll serve
~~~
alle Dependencies installiert und kann den aktuellen Stand als [localhost](http://localhost:4000/)-Seite sehen.
