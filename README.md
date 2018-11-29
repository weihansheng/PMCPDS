# PMCPDS

PMCPDS is a parallel model cheker for pushdown systems. 
In this page it is possible to download the command-line version of PMCPDS. We provide it as a executable file, so that it can be directly used without having to compile it. PMCPDS requires at least CUDA9.0 and JDK1.8 to run. You can download CUDA9.0 form https://developer.nvidia.com/cuda-downloads. You also need a NVIDIA GPU, whose capability is above 6.0. 

## Usage 
The usage of the checker is as follows:
```shell
    PMCPDS <modelfile> <formula> [options]
    [-f]	     read <formula> as name of file containing Buchi automaton
    [-p]      print automaton 
    [-i NUM]  run NUM iterations per thread run (default 1)
    [-t NUM]  use NUM threads (default 1*32,num of  threads will be 23*NUM )
```
