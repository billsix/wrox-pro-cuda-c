APPS=hello

all: ${APPS}

%: %.cu
	nvcc -O2 -arch=sm_75 -o $@ $<
clean:
	rm -f ${APPS}
