sources=carre.cpp
objets=$(sources:.cpp=.o)

CourbeCarre:$(objets)
	g++ -l QtGui -l QtCore -l qcustomplot -L /autofs/netapp/travail/tfrances/m2/s3/genie_log/grelard/TP1/qcustomplot/sharedlib/compilation $^ -o $@

carre.o:carre.cpp
	g++ -I /usr/include/qt4/ -I /usr/include/qt4/QtGui/ -I /usr/include/qt4/QtCore/ -I /autofs/netapp/travail/tfrances/m2/s3/genie_log/grelard/TP1/qcustomplot -c $^ -o $@

export "LD_LIBRARY_PATH"=/autofs/netapp/travail/tfrances/m2/s3/genie_log/grelard/TP1/qcustomplot/sharedlib/compilation
