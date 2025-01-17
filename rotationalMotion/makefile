all:
	xelatex PhysAP1-C12-rotMotion1
	xelatex PhysAP1-C12-rotMotion1
	cd practiceTest2 ; make

clean:
	rm -rf *~ *.*~ *.log *.nav *.aux *.out *.snm *.toc
	cd practiceTest2 ; make clean

public:
	mkdir -p $(DESTINATION)/Class12
	cp *.pdf $(DESTINATION)/Class12
	cp practiceTest2/*.pdf $(DESTINATION)/Class12
