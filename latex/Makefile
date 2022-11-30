# Splits the project description file into a 15-page file (that contains the text) and the remaining pages (references)
desc.pdf refs.pfd &: description.pdf
	pdftk description.pdf cat 1-15 output desc.pdf
	pdftk description.pdf cat 16-end output refs.pdf
