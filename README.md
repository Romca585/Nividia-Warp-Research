# Nividia-Warp-Research
Nvidia Warp Research Paper

This paper was written in late 2023, when Nvidia Warp’s CPU mode didn’t actually support real parallelization. Even though it looked like it was using multiple threads, everything was still being run in serial behind the scenes. This paper was aimed to research a method of achieving full parallelization using the CPU.

Shortly after this project was finished, Nvidia updated Warp and reworked how the CPU mode works, adding proper multithreading and achieving full parallelisation via their own methods.
