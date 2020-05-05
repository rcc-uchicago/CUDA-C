cudaFlags = -arch=sm_30 -O3 --use_fast_math



sharedMem: sharedMem.cu
	nvcc -o sharedMem $(cudaFlags) sharedMem.cu

clean:
	rm -f sharedMem
