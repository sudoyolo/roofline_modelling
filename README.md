# Roofline Modelling

CPU Statistics: 4CPUs, 16GB Memory, 3.10GHz Memory     
CPU AlexNet Training Metrics: Self CPU time total = 13.437s      
CPU ResNet18 Training Metrics: Self CPU time total = 39.140s       
      
T4 Statistics: 8CPUs, 16GB Memory, 65 TFLOPSs Speed, 320GB/s Memory Bandwidth       
T4 AlexNet Training Metrics: Self CPU time total = 6.482s, Self CUDA time total = 5.365s, Total FLOPS = 10486620979200, Total CUDA time = 1.316469 seconds, Performance = 7965.72 GFLOPS/s     
T4 ResNet18 Training Metrics: Self CPU time total = 18.492s, Self CUDA time total = 16.798s, Total FLOPS = 23213781811200, Total CUDA time = 3.520396 seconds, Performance = 6594.08 GFLOPS/s      

L4 Statistics: 16CPUs, 24GB Memory, 121 TFLOPSs Speed, 300GB/s Memory Bandwidth      
L4 AlexNet Training Metrics: Self CPU time total = 3.671s, Self CUDA time total = 2.982s, Total FLOPS = 10486620979200, Total CUDA time = 0.774669 seconds, Performance = 13536.91 GFLOPS/s       
L4 ResNet18 Training Metrics: Self CPU time total = 9.845s, Self CUDA time total = 8.716s, Total FLOPS = 23213781811200, Total CUDA time = 1.360620 seconds, Performance = 17061.18 GFLOPS/s       
