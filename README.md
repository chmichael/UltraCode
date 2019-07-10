# UltraCode
Assembler & Parallel optimized RTL Replacement for Delphi/Free Pascal for Windows/Mac/Linux/iOS/Android

CPU Tagets:
PASCAL, SSE3, AVX, ARM

Operating Systems:
Windows, MacOS, Linux, IOS, Android

GPU Targets:
OpenCL, Vulkan

Please use the following Structure for filenames for Single Thread Targets: 
UC64."Routine"."SIMD"."OS".pas = UC64.Pos.AVX.Win.pas, UC64.Pos.AVX.Mac.pas, UC64.Pos.AVX.Linux.pas

Please use the following Structure for filenames for Parallel Thread Targets: 
UC64P."Routine".Parallel."SIMD"."OS".pas = UC64P.Pos.AVX.Win.pas, UC64P.Pos.Parallel.AVX.Mac.pas, UC64P.Pos.AVX.Linux.pas

Please use the following Structure for filenames for GPU Targets: 
UC64G."Routine".Parallel."SIMD"."OS".pas = UC64G.Pos.AVX.Win.pas, UC64G.Pos.Parallel.AVX.Mac.pas, UC64G.Pos.AVX.Linux.pas
