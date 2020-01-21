# thesis-checker
grep thesis file(s) with the aim of improving grammar

Your thesis must be in a text format, such as [LaTeX](https://en.wikipedia.org/wiki/LaTeX).

## instructions
To check grammar, run ```./grammar-checker "path/to/files/to/check/*"``` or escape the asterisk with a backslash (\\)

To check spelling, first modify spelling-checker to fit your needs. Then run ```./spelling-checker```

## to-dos
* get spelling-checker to work on a given folder (aspell doesn't work with *)
* have grammar-checker use a list instead of running each check via individual commands
* don't split verbs
* ``Whenever you use a pronoun, ask if the antecedent can be mis-interpreted." - Dr. Corliss
* check for at most one URL per reference in the Bibliography
* what else do I typically do that is often corrected?

