# Pandoc
I used [Pandoc](https://pandoc.org/) to create this document. It is a simple way to create LaTeX like documents, without the LaTeX syntax. It is also possible to generate docx or ePUB formats.

# Dependencies
You can just edit the text in Markdown. But if you want to build the PDF, you will need the `pandoc-citeproc` and `pandoc` packages.

# Build the PDF
You can build the PDF when you are in the working directory and run the following command: `pandoc -s -o config-management.pdf config-management.md --filter pandoc-citeproc && evince config-managent.pdf`.
