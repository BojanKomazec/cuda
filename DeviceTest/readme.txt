Example is based on the CUDA manual:
https://devblogs.nvidia.com/parallelforall/how-query-device-properties-and-handle-errors-cuda-cc/

Compilation:

$ nvcc main.cu -Wno-deprecated-gpu-targets -o CudaDeviceInfo.out

If run on machine with VGA compatible controller: NVIDIA Corporation GK107 [GeForce GT 640 OEM] (rev a1):

$ ./CudaDeviceInfo.out 
Device Number: 0
  Device name: GeForce GT 640
  Memory Clock Rate (KHz): 891000
  Memory Bus Width (bits): 128
  Peak Memory Bandwidth (GB/s): 28.512000
  Compute Capability: 3.0

