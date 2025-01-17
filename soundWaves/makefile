all:
	pdflatex PhysAP2-C10-soundWaves
	pdflatex PhysAP2-C10-soundWaves
	pdflatex PhysAP2-C10-soundWaves-extendedVersion
	pdflatex PhysAP2-C10-soundWaves-extendedVersion
	pdflatex PhysAP2-C10-Homework
	pdflatex PhysAP2-C10-Homework
	cd handouts ; make
#	cd notes-for-teachers ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd handouts ; make clean
#	cd notes-for-teachers ; make clean

public:
	mkdir -p $(DESTINATION)/Class10
	cp *.pdf $(DESTINATION)/Class10
	cp handouts/*.pdf $(DESTINATION)/Class10
#	cp notes-for-teachers/*.pdf $(DESTINATION)/Class12/Phys11-C12-notes-for-teachers-DO-NOT-POST.pdf
