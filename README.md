# Pandoc
I used [Pandoc](https://pandoc.org/) to create this document. It is a simple way to create LaTeX like documents, without the LaTeX syntax. It is also possible to generate docx or ePUB formats.
The PDF can be build when you are in the working directory and run the following command: `pandoc -s -o config-management.pdf config-management.md --filter pandoc-citeproc && evince config-managent.pdf`.
