# ParaLarPD
Requirements:

C++ compiler support the C++11 standard
Boost C++ library -- 
Intel TBB library --

Compilation steps:

1. cd build
2. export TBB_INC_DIR=<path to Intel TBB include directory>   
3. export TBB_LIB_DIR=<path to Intel TBB library directory> 
4. cmake ..			
5. make	
####### 
./vpr <arch.xml> <benchmark_name> --pack --place
./Router <arch.xml> <benchmark_name> <thread_num> <iteration_num> <W> ## e.g. thread_num = 4, iteration_num, W = 30 or 40 ...any value
