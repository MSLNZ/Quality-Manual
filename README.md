# Quality-Manual
LaTeX source files for the MSL Quality Manual and supplement documents.

The MSL Quality Manual is typeset using pdfLaTeX. A number of source files are complied to produce the final PDF document. There are several supplements to the Quality Manual that are also typeset in pdfLaTeX. All of the source files need to produce the Quality Manual and its supplements are available in this repository.

## Compiling the documents 
Each document has a folder (e.g., `quality_manual_document`, `guidelines_reporting_publishing`), which contains the LaTeX source files (extension `.tex`) and other files produced during the compilation process.

The name of the **main** LaTeX document in each folder begins with the prefix `MSL_` (e.g., `MSL_Guidelines_Measurement_Uncertainty`) 

To produce a PDF version of the Quality Manual or one of the supplements, simply compile the corresponding main document (list can be done from the command line or by using a LaTeX editing tool). 

### Note 
Compilation of the Quality Manual incorporates cross-references to sections in the supplements. PdfLaTeX looks for these cross-references in auxiliary files (extension `.aux`) in the supplement folder.  
