all:
	xelatex PhysAP2-C11-lightOptics
	xelatex PhysAP2-C11-lightOptics
	cd homework ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework ; make clean

public:
	mkdir -p $(DESTINATION)/Class11
	cp *.pdf $(DESTINATION)/Class11
	cp homework/*Homework.pdf $(DESTINATION)/Class11
