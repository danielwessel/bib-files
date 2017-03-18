# bib-files


Biblatex is able to access the bib files in this repository.
Here is a minimal example:


% !BIB TS-program = biber

\documentclass{article}

\usepackage[backend=biber,style=numeric]{biblatex}

\addbibresource{https://raw.githubusercontent.com/danielwessel/bib-files/master/besancon.bib}

\begin{document}

Lorem ipsum \cite{aczel:notes}.

\printbibliography

\end{document}



---


See further

https://www.ctan.org/pkg/biblatex?lang=en
