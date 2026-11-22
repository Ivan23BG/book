# book — feuille de livre

Feuille de livre (class `book`) : matter principal, chapters, préface via
`\frontmatter`/`\mainmatter`/`\appendix`, un table des matières complet.
Disponible en thèmes light et dark via `latex_handler compile --theme all`.
Basé sur latex-templates.

## Contents

| Document | Kind | Notes |
| --- | --- | --- |
| `src/book_main.tex` | Livre (`book`) | Front/main matter, chapters, appendix. |

## Use

```sh
latex_handler new mon_livre --template book
cd mon_livre
latex_handler compile
latex_handler compile --theme all
```

See `examples/README.md` for compile commands.
