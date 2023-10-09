# gbench
This repository provides the code for G-Bench benchmarking suites: `G-Bench: Fair Benchmarking to Support Innovations in Streaming Graph Systems (GrAPL'23)`.

Right now, we have open-sourced the following codes:
* Aspen: https://github.com/pradeep-k/aspen is the codebase integrated with G-Bench. See https://github.com/pradeep-k/aspen/blob/master/code/tools/README.md for details on how to run.
* DZiG: https://github.com/pradeep-k/graphbolt is the codebase integrated with G-Bench. (TODO: README update is pending)
* Stinger: https://github.com/pradeep-k/stinger is the codebase integrated with G-Bench. (TODO: README update is pending)
* GraphOne: The new changes are still closed-source. We will be making it open-source in some time.


Kindly note that many of such systems rely on cilk+ for parallelization. G++/GCC version 6.4 supports cilk+, and all the benchmarks used this version. Later versions of G++/GCC do not support cilk+ out of the box.



