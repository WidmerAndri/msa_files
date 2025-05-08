# msa_files
Bachelor Project

Several errors were found within the data. Some positions scored 0, even though containing phosphorylated amino acids (Y, T, S). I am currently fixing the error (06.05.2025).
A new version of the App was uploaded, which uses the new scoring system. t(x) was updated to a normalized version of the Relative von Neumann Entropy (08.05.2025).

With this Shiny application it is possible to explore conserved phosphosites of some protein groups. The project is still in prgress, so more functios and features will potentially be added.  There is some data overlap. But don't worry this is because in Yeast several genes are duplicated. The different databases use different ways to store and display the data. So for example OMA is storing it according to the position of a gene within the genome (duplication can be found twice) and UniProt has for two identical gene products only one entry. That is why some groups appear twice and are identical. There is a search function to find your favourite Protein! (if it is there) And you see how many phosphorylated positions each alignment has. Several filter options are usable to find the most interesting groups. Depending on what you are looking for, you can change between two scores. Give it some time to react, especially when using the search function. 

Some data was added to the application. It is now possible to screen orthologous Proteins of Yeast, Arabidopsis and Human, only Yeast and Arabidopsis or Yeast and Human.

Just download the Shiny_App_Phosphosites Markdown file and launch it, e.g. in RStudio.
