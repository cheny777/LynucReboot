TableSvr: TableSvr.cpp
	g++ TableSvr.cpp SmoothFilters.cpp TableService.cpp TSvr.cpp PointSet.cpp LyDG.cpp -Wall -O2 -o TableSvr RSHM.so -lpthread -lrt /usr/xeno-x86/lib/libnative.so  /usr/xeno-x86/lib/libxenomai.so
	strip -s TableSvr
clean: 
	rm *.o TableSvr
