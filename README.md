# Quality Manual
This repository contains the LaTeX source files for the MSL Quality Manual and supplementary documents.

The authoritative versions of the manual and supplements are held on the MSL QMS sharepoint site. The files available in this github repository are, in general, undergoing change and will not have been approved by the MSL Quality Council.

The MSL Quality Manual is typeset using pdfLaTeX. A number of source files are complied to produce the final PDF document. There are several supplements to the Quality Manual that are also typeset in pdfLaTeX. All of the source files needed to produce the Quality Manual and its supplements are available in this repository.

## Compiling the documents 
Each document has a folder (e.g., `quality_manual_document`, `guidelines_reporting_publishing`), which contains the LaTeX source files (extension `.tex`) and other files produced during the compilation process.

The name of the **main** LaTeX document in each folder begins with the prefix `MSL_` (e.g., `MSL_Guidelines_Measurement_Uncertainty`) 

To produce a PDF version of the Quality Manual, or one of the supplements, simply compile the corresponding main document. This can be done from the command line (e.g., `> pdflatex MSL_Quality_Manual`) or by using a LaTeX editing tool. It is necessary to perform two successive compilations to resolve all the cross-references and citation links in the final document. 

#### Note 
Compilation of the Quality Manual incorporates cross-references to sections in the supplements. PdfLaTeX looks for these cross-references in auxiliary files (extension `.aux`) in the supplement folders.  
