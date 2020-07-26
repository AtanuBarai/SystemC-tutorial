all:
	g++ -I. -I ${SYSTEMC_HOME}/include -L. -L${SYSTEMC_HOME}/lib-linux64 -Wl,-rpath=${SYSTEMC_HOME}/lib-linux64 -lsystemc -lm -o counter counter.cpp counter_tb.cpp

clean: 
	rm -rf counter counter.vcd
