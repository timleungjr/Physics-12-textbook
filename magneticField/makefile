all:
	$(LATEX) Phys12-C10-magField
	$(LATEX) Phys12-C10-magField
	cd homework; make

sub:
	cd homework; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework; make clean

public:
	mkdir -p $(DESTINATION)/Class10
	cp *.pdf $(DESTINATION)/Class10
	cp homework/*.pdf $(DESTINATION)/Class10

teacher:
	mkdir -p $(TEACHER_DIST)/Class10
	cp *.pdf $(TEACHER_DIST)/Class10
	cp homework/*.pdf $(TEACHER_DIST)/Class10
