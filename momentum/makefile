all:
	$(LATEX) Phys12-C05-momentum
	$(LATEX) Phys12-C05-momentum
	$(LATEX) Phys12-C05-momentum-print
	$(LATEX) Phys12-C05-momentum-print
	cd homework; make
	cd handouts; make

sub:
	cd homework; make
	cd handouts; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework; make clean
	cd handouts; make clean

public:
	mkdir -p $(DESTINATION)/Class05
	cp *.pdf $(DESTINATION)/Class05
	cp homework/*.pdf $(DESTINATION)/Class05
	cp handouts/*.pdf $(DESTINATION)/Class05

#teacher:
#	mkdir -p $(TEACHER_DIST)/Class05
#	cp *.pdf $(TEACHER_DIST)/Class05
#	cp homework/*.pdf $(TEACHER_DIST)/Class05
#	cp handouts/*.pdf $(TEACHER_DIST)/Class05
