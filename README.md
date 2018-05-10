# To Build

Each slide can be built using pandoc and revealjs.

```
pandoc -s -i -t revealjs -o origami_code.html origami_code.md -V revealjs-url=http://lab.hakim.se/reveal-js -V theme=night --mathjax
```
