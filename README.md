# LAB 9 Software part2 TCF and gprof profilers
## SUMMARY
In this lab we set up a circuit with a zybo system, axi interconnect, two FIRs and a processor system reset. then we imports codes for respective testing. we debugged first using the TCF. first generated linker script. then run the program as hardware signle application debug. then find tool TCF profiler. then press start to sample all the stepping code.

To have the gprof profiler, first configure the C/C+= building setting. create symbols to track specific line of code if needed. else enable profiling(-pg) under the arm v7 gcc compiler tab. then in the run configuration, goes to application then click edit advance option to set profiling frequency.
then you will have a table show case the code latency. use sorted by function if needed.
