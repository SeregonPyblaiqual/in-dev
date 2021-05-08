# Obsidian mind map project

## What this is ?
This project aims to enable easy mindmaping for md notes in obsidian.

### Exemple:
#### First formating
```md
Main
- Alpha
    - A
    - a
- Beta
    - B
    - b
```

#### Second formating
```md
# Main <!-- If omited, will be the filename-->
## Alpha
### A
### a
## Beta
### B
### b
```
### Third formating
Can also use backlinks rather than headings
```md
// main file:
## [[Alpha]]
## [[Beta]]
```
```md
// Alpha file:
## [[A]]
## [[a]]
```




## Ressources
- [Markmap](https://github.com/dundalek/markmap)
    - [Mindmap obsidian extension](https://github.com/lynchjames/obsidian-mind-map)

## Business
- newsletter
    - Sponsored content
    - Partnerships

## Proposal
- [ ] Chrome extension syncronised with obsidian
- [ ] Add youtube video embeding in obsidian
- [ ] When creating a main file, with headers,
        ```md
        ## [[Social]]

        ## [[Neurosciences]]

        ## [[Subconscious]]
        ```, automaticaly create the subfiles with backlinks
- [ ] Embededs videos/content on hover