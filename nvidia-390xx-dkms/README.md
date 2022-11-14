Linux f13 6.0.1-arch2-1 #1 SMP PREEMPT_DYNAMIC Thu, 13 Oct 2022 18:58:49 +0000 x86_64 GNU/Linux

fix linux 6.0 patch nvidia-390xx


[Fuck Fuck Go](https://yuceltoluyag.github.io/linux-ekran-karti-kurulumu/)

* this patch is not working properly.
* Install linux-lts kernel, all your problems will be solved
# Problem
 That patch unfortunately disablea ACPI function thus limiting my max GPU performance level (from perf 2 (Graphics 525MHz, Memory 3000MHz, Processor 1050MHz) to perf 1 (Graphics 73MHz, Memory 648MHz, Processor 101MHz))
 
# Edit

this seems to have fixed the problem, i will try it soon https://github.com/FiestaLake/nvidia-390xx-utils
