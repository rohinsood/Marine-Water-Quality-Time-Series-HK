SHELL = /bin/sh
SYSTEM  = HP-UX
EXTRA   = +FPVZOUD +O3 -D$(SYSTEM)
EXTRA   = -g
EXTRA   = -O
CFLAGS = -Ae $(EXTRA)
FC = gfortran
FFLAGS = -std=legacy -ffixed-line-length-none -ffpe-summary=none
CC      = cc $(CFLAGS)

OBJECTS0 = AATSR.o ABSTRA.o AEROSO.o AKTOOL.o ATMREF.o AVHRR.o BBM.o BDM.o BRDFGRID.o \
CHAND.o CLEARW.o CSALBR.o DICA1.o DICA2.o DICA3.o  DISCOM.o \
DISCRE.o DUST.o ENVIRO.o EQUIVWL.o GAUSS.o GLI.o GOES.o HAPKALBE.o \
HAPKBRDF.o HRV.o IAPIALBE.o IAPIBRDF.o IAPITOOLS.o INTERP.o ISO.o \
KERNEL.o KERNELPOL.o LAKEW.o MAS.o MERIS.o METEO.o METH1.o METH2.o METH3.o METH4.o \
METH5.o METH6.o MIDSUM.o MIDWIN.o MIE.o MINNALBE.o MINNBRDF.o \
MOCA1.o MOCA2.o MOCA3.o MOCA4.o MOCA5.o MOCA6.o MODIS.o MSS.o NIOX1.o \
MODISBRDF.o MODISALBE.o \
NIOX2.o NIOX3.o NIOX4.o NIOX5.o NIOX6.o OCEA.o OCEAALBE.o OCEABRDF.o OCEABRDFFAST.o\
OCEATOOLS.o ODA550.o ODRAYL.o OS.o OSPOL.o OXYG3.o OXYG4.o OXYG5.o OXYG6.o \
OZON1.o PLANPOL.o POLDER.o POSGE.o POSGW.o POSLAN.o POSMTO.o POSNOA.o POSSOL.o POSSPO.o \
POLGLIT.o POLNAD.o  \
PRESPLANE.o PRESSURE.o PRINT_ERROR.o RAHMALBE.o RAHMBRDF.o ROUJALBE.o \
ROUJBRDF.o SAND.o SCATRA.o SEAWIFS.o SOLIRR.o SOOT.o SPECINTERP.o SPLIE2.o \
SPLIN2.o SPLINE.o SPLINT.o STM.o SUBSUM.o SUBWIN.o TM.o TROPIC.o \
TRUNCA.o US62.o VARSOL.o VEGETA.o VERSALBE.o VERSBRDF.o VERSTOOLS.o \
WALTALBE.o WALTBRDF.o WATE.o WAVA1.o WAVA2.o WAVA3.o WAVA4.o WAVA5.o \
WAVA6.o AEROPROF.o ALI.o ASTER.o ETM.o HYPBLUE.o VGT.o VIIRS.o

OBJECTS1= main.o 



sixs: $(OBJECTS0) $(OBJECTS1) 
	$(FC)  $(OBJECTS1) $(OBJECTS0) -o sixsV1.1  -lm
	

clean:
	rm -f *.o
	
	
	
