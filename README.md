#### proof-remove
A script that takes a LaTeX file and filters out all sections of the form `\begin{proof} ... \end{proof}`.

Usage: `proof-remove file.tex`

The result is printed to stdout, while error messages go to stderr.

**[UPDATE]** There already exist several LaTeX-packages that have the same functionality:

1. The [comment](https://ctan.org/pkg/comment)-package (via `excludecomment`)
2. The [versions](https://ctan.org/pkg/versions)-package (via `excludeversion`)
