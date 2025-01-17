all:
	xelatex PhysAP1-C13-rotMotion2
	xelatex PhysAP1-C13-rotMotion2
	cd homework ; make
	cd Handouts ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd homework ; make clean
	cd Handouts ; make clean

public:
	mkdir -p $(DESTINATION)/Class13
	cp *.pdf $(DESTINATION)/Class13
	cp homework/*.pdf $(DESTINATION)/Class13
	cp Handouts/*.pdf $(DESTINATION)/Class13
