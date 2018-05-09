# To Build

Each slide can be built using pandoc and revealjs.

```
pandoc --mathjax -t revealjs -s -o myslides.html myslides.md -V revealjs-url=http://lab.hakim.se/reveal-js
```
