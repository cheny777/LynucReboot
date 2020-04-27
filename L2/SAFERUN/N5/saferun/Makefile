SafeRun: SafeRun.cpp
	g++ SafeRun.cpp LyDG.cpp PointSet.cpp PsGather.cpp SafeMng.cpp CFGFILE.cpp Kine.cpp RobotCFG.cpp RITools.cpp -Wall -O2 -o SafeRun -lpthread -lrt /usr/xeno-x86/lib/libnative.so  /usr/xeno-x86/lib/libxenomai.so /home/Lynuc/CNC/CIComm.so
	strip -s SafeRun
clean: 
	rm *.o SafeRun
