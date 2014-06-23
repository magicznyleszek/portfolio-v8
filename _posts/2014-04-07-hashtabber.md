---
title: HashTabber
thumbnail: hashtabber-thumbnail.svg
categories: [code, logo]
layout: post
language: pl-pl
---

[HashTabber](http://hashtabber.smutnyleszek.com) to prosty plugin `JavaScript` do zakładkowej nawigacji z uwzględnieniem *hashowych* linków.

Plugin został [wyróżniony w repozytorium jquer.in](http://jquer.in/javascript-frameworks-for-developing-rich-applications/hashtabber/).

W wolnej chwili zbudowałem proste logo bazujące na kształtach znaków "#" i "T" oraz samym interfejsie zakładkowym. Wizualnie ubrałem go w jadeitową zieleń i przestrzeń cieplejszych szarości.

[![logo][hashtabber-01]][hashtabber-01]

[![palette][hashtabber-02]][hashtabber-02]

*Modus operandi* skryptu jest dokładniej-techniczniej opisany [na stronie projektu](http://hashtabber.smutnyleszek.com), ale w skrócie można go opisać poniższym diagramem:

1. Aktywujesz zakładkę (zwykłym *hashowym* linkiem)
2. Adres przeglądarki zmienia się
3. Skrypt wyczekuje zmian adresu, skąd pobiera nazwę nowej zakładki
4. Skrypt paruje zakładkę z jej zawartością
5. Skrypt wyłącza starą zakładkę z zawartością i włącza nowe

Może to brzmieć banalnie, ale dzięki *hashowym* linkom strona nie przeładowuje się a zakładki można zmieniać z zewnątrz. Do tego cała funkcjonalność jest minimalistyczna, zręczna i gotowa do użycia przy bardzo niewielkich wymaganiach.

[![diagram][hashtabber-03]][hashtabber-03]

Sama strona nie potrzebowała praktycznie nic poza sprawną typografią -- użyłem *Source Sans Pro* od Paula Hunta, zgrabnej skali modularnej i kilku sprytnych `media queries` dla urządzeń mobilnych.

[![website-1][hashtabber-04]][hashtabber-04]

[![website-2][hashtabber-05]][hashtabber-05]

[![website-3][hashtabber-06]][hashtabber-06]

[![website-4][hashtabber-07]][hashtabber-07]

A w dodatku cały skrypt jest [udostępniony w Domenie Publicznej](https://creativecommons.org/publicdomain/zero/1.0/), czyli za darmoszkę.

[hashtabber-01]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-01-logo.png
[hashtabber-02]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-02-palette.png
[hashtabber-03]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-03-diagram.png
[hashtabber-04]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-04-website-1.png
[hashtabber-05]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-05-website-2.png
[hashtabber-06]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-06-website-3.png
[hashtabber-07]: {{site.baseurl}}/assets/img/project/hashtabber/hashtabber-07-website-4.png