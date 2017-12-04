SOURCE = dotfiles

%.dvi: %.latex
	latex -shell-escape $<

slides: ${SOURCE}.dvi
	dvipdf $< ${SOURCE}_slides.pdf
