# Modular Project Template

Template repository for synthesizer modules. Documentation with MkDocs, hardware with KiCAD 9

## Organization

* docs/
  * index.md: Table of contents
  * assembly.md: Assembly guide/build notes
  * theory.md: Design notes
  * assets/
    * bom.csv and bom.md (reference in assembly guide)
    * schematic.pdf
    * images/ 
* hardware/
  * place KiCAD projects here (usually only one for schematic+board)
  * plots/ is ignored by .gitignore, PBC files go here.
* firmware/ (optional)
  * place PiO projects here
