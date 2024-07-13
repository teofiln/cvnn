# My CV in Markdown

## Rendering 
pandoc -f markdown -t html5 -o index.html cvnn.md 

pandoc --pdf-engine "tectonic" -f markdown -t pdf -o cvnn.pdf cvnn.md
