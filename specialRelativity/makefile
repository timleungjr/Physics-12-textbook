all:
	$(LATEX) Phys12-C14-relativity
	$(LATEX) Phys12-C14-relativity
	$(LATEX) Phys12-C14-relativity-longversion
	$(LATEX) Phys12-C14-relativity-longversion
	$(LATEX) Phys12-C14-relativity-print
	$(LATEX) Phys12-C14-relativity-print
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
	mkdir -p $(DESTINATION)/Class14
	cp *.pdf $(DESTINATION)/Class14
	cp homework/*.pdf $(DESTINATION)/Class14
	cp handouts/*.pdf $(DESTINATION)/Class14

#teacher:
#	mkdir -p $(TEACHER_DIST)/Class14
#	cp *.pdf $(TEACHER_DIST)/Class14
#	cp homework/*.pdf $(TEACHER_DIST)/Class14
#	cp handouts/*.pdf $(TEACHER_DIST)/Class14
