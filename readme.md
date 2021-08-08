# Fonte do site do sancaLUG em Markdown

Conversão de Markdown para html com Pandoc:  
`pandoc -s index.md --template sancalug-template.html -o index.html`

Lembre-se de fazer o commit do `html` gerado para o branch do `gh-pages`:
```
$ git checkout gh-pages 
$ git checkout <hash do último commit da master> index.html 
```
Mais detalhes na resposta de *Marina Liu* no [StackOverflow](https://stackoverflow.com/questions/42467062/commit-a-single-file-to-another-branch#42467121)
