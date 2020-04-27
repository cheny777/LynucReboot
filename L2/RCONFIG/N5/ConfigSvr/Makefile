CFGSVR: ConfigSvr.cpp
	g++ ConfigSvr.cpp CFGFILE.cpp -Wall -O2 -o CFGSVR RSHM.so -lpthread -lrt /usr/xeno-x86/lib/libnative.so  /usr/xeno-x86/lib/libxenomai.so
	strip -s CFGSVR
clean: 
	rm *.o CFGSVR
