all:
#	pdflatex PhysAP2-C05-capacitors
#	pdflatex PhysAP2-C05-capacitors
	pdflatex PhysAP2-C04-notice
	cd homework ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework ; make clean

public:
	mkdir -p $(DESTINATION)/Class04
	cp *.pdf $(DESTINATION)/Class04
	cp homework/*Homework.pdf $(DESTINATION)/Class04
