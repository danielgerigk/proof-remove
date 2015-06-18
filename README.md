##### proof-remove
A script that takes a LaTeX file and filters out all sections of the form `\begin{proof} ... \end{proof}`

Usage: `proof-remove file.tex`  
The result is printed to `stdout`, while error messages go to `stderr`.

There exist at least two LaTeX-packages that include the same functionality:

1. The [comment](https://ctan.org/pkg/comment)-package (via `excludecomment`)
2. The [versions](https://ctan.org/pkg/versions)-package (via `excludeversion`)





e44bb1d5cd23fc1712e95c77bbe8e7a29699a5d8c699f15383238810a3ebe4e5
