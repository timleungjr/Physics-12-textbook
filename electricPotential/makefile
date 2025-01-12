all:
	$(LATEX) Phys12-C09-elecPotential
	$(LATEX) Phys12-C09-elecPotential
	cd homework; make

sub:
	cd homework; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework; make clean

public:
	mkdir -p $(DESTINATION)/Class09
	cp *.pdf $(DESTINATION)/Class09
	cp homework/*.pdf $(DESTINATION)/Class09

teacher:
	mkdir -p $(TEACHER_DIST)/Class09
	cp *.pdf $(TEACHER_DIST)/Class09
	cp homework/*.pdf $(TEACHER_DIST)/Class09
