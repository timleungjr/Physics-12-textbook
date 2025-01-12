all:
	$(LATEX) Phys12-C12-lightInterference
	$(LATEX) Phys12-C12-lightInterference
	cd homework; make

sub:
	cd homework; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework; make clean

public:
	mkdir -p $(DESTINATION)/Class12
	cp *.pdf $(DESTINATION)/Class12
	cp homework/*.pdf $(DESTINATION)/Class12

teacher:
	mkdir -p $(TEACHER_DIST)/Class12
	cp *.pdf $(TEACHER_DIST)/Class12
	cp homework/*.pdf $(TEACHER_DIST)/Class12
