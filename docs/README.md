To generate pdf file from `xyz.tex` and save it to `texout` folder, 
use the following commands:  
```
mkdir texout 
pdflatex -output-directory ./texout xyz
cd texout
rm *aux *.bbl *.blg *.fls *.fdb_latexmk *.log *.lol *.out *.synctex.gz *.toc
cd ..
```