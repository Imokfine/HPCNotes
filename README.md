# HPCNotes
### Ref
[HPC Wiki](https://hpc-wiki.info/hpc/HPC_Wiki)
## HPC Hardware  
## HPC Software  
### Performance Analysis (profiling)  
* **Performance Metrics**  
  * Operation throughput (FLOPs)  
  * Overall instruction throughput (CPI)
  * Intruction counts broken down by:
    * Instruction types (FP instructions, load/stores, branch instructions, etc.)  
    * SIMD width (scalar, SSE, AVX, etc.)  
  * Data volumes and bandwidth to:
    * main memory (GB and GB/s)
    * different cache levels (GB and GB/s)
  * Clock (GHz)
  * Power (W)
* **Profiling tools**  
  * Hardware Performance Counters  
  * PAPI  
  * Score-P  
  * Scalasca  
