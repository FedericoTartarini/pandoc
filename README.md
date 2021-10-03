# Markdown to PDF

Simple presentation
```
pandoc -t beamer .\simple-presentation.md -o out/simple-presentation.pdf
```
```
pandoc -t html -s simple-presentation.md -o out/simple-presentation-website.html
```
```
pandoc -t slidy -s simple-presentation.md -o out/simple-presentation.html
```
Other outputs available s5, slidy, slideous, dzslides, or revealjs
```
pandoc simple-presentation.md -o out/simple-presentation.pptx
```

Showcase main features
```
pandoc -t beamer -s --bibliography bib.bib --citeproc .\presentation.md -o out/presentation.pdf
```



