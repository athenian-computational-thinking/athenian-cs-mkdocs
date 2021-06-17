[![Netlify Status](https://api.netlify.com/api/v1/badges/af5a7ad9-fafc-461d-bcbb-3eab47fb7565/deploy-status)](https://app.netlify.com/sites/athenian-cs/deploys)

## Setup for local editing
* Clone the [athenian-cs-mkdocs](https://github.com/athenian-computational-thinking/athenian-cs-mkdocs) repo with: 
```
git clone git@github.com:athenian-computational-thinking/athenian-cs-mkdocs.git
```

* Install [MkDocs](https://www.mkdocs.org).
* Install the [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/) theme.
* Install the [Pygments](http://pygments.org/) syntax highlighter.
* Install the [PyMdown Extensions](https://facelessuser.github.io/pymdown-extensions/) Markdown extensions.


## Makefile Targets
| Command               | Description                                   |
|:----------------------|:----------------------------------------------|
| `make website`        | Build the website in site/                    |
| `make clean`          | Delete site/                                  |
| `make serve`         | Start the live-reloading docs server          |

## Additional Athenian Website Repos  
* [Athenian Programming](https://github.com/athenian-robotics/athenian-robotics-mkdocs)
* Athenian FLL