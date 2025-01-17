all:
	pdflatex PhysAP2-C01-thermodynamics
	pdflatex PhysAP2-C01-thermodynamics
	cd homework ; make
	cd courseOutline ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework ; make clean
	cd courseOutline ; make clean

public:
	mkdir -p $(DESTINATION)/Class01
	cp *.pdf $(DESTINATION)/Class01
	cp homework/*.pdf $(DESTINATION)/Class01
	cp courseOutline/*.pdf $(DESTINATION)/Class01
