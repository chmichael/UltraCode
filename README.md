# UltraCode
Assembler & Parallel optimized RTL Replacement for Delphi/Free Pascal for Windows/Mac/Linux/iOS/Android

CPU Tagets:
PASCAL, SSE3, AVX, ARM

Operating Systems:
Windows, MacOS, Linux, IOS, Android

GPU Targets:
OpenCL, Vulkan

Please use the following Structure for filenames for Single Thread Targets: 
UltraCode."Routine"."SIMD"."OS".pas = UltraCode.Pos.AVX.Win.pas, UltraCode.Pos.AVX.Mac.pas, UltraCode.Pos.AVX.Linux.pas

Please use the following Structure for filenames for Parallel Thread Targets: 
UltraCodeP."Routine".Parallel."SIMD"."OS".pas = UltraCodeP.Pos.AVX.Win.pas, UltraCodeP.Pos.Parallel.AVX.Mac.pas, UltraCodeP.Pos.AVX.Linux.pas

Please use the following Structure for filenames for GPU Targets: 
UltraCodeG."Routine".Parallel."SIMD"."OS".pas = UltraCodeG.Pos.AVX.Win.pas, UltraCodeG.Pos.Parallel.AVX.Mac.pas, UltraCodeG.Pos.AVX.Linux.pas
