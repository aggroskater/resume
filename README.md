# Compiling to pdf

$ ./Markdown.pl --html4tags RESUME.md > resume.html

Make any necessary manual adjustments to the html that you want.

$ ./wkhtmltopdf-amd64 resume.html resume.pdf
