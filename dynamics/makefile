all:
	$(LATEX) Phys12-C02-dynamics
	$(LATEX) Phys12-C02-dynamics
	$(LATEX) Phys12-C02-dynamics-print
	$(LATEX) Phys12-C02-dynamics-print
	cd homework; make all

homework:
	cd homework; make all

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework; make clean

public:
	mkdir -p $(DESTINATION)/Class02
	cp *.pdf $(DESTINATION)/Class02
	cp homework/*.pdf $(DESTINATION)/Class02

#teacher:
#	mkdir -p $(TEACHER_DIST)/Class02
#	cp *.pdf $(TEACHER_DIST)/Class02
#	cp homework/*.pdf $(TEACHER_DIST)/Class02

