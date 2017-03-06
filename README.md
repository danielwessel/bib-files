# bib-files


Biblatex can retrieve data from the web.
Here is an example:


% !BIB TS-program = biber

\documentclass{article}

\usepackage[backend=biber,style=numeric]{biblatex}

\addbibresource{https://raw.githubusercontent.com/danielwessel/bib-files/master/Bibliographie.bib}

\begin{document}

Lorem ipsum \cite{aczel:notes}.

\printbibliography

\end{document}
