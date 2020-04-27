CAMAP: CAMAP.cpp
	g++ CAMAP.cpp CFGFILE.cpp -Wall -O2 -o CAMAP RSHM.so -lpthread -lrt /usr/xeno-x86/lib/libnative.so  /usr/xeno-x86/lib/libxenomai.so /home/Lynuc/CNC/CIComm.so
	strip -s CAMAP
clean: 
	rm *.o CAMAP
