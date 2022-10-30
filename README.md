# VPEReg
Complementary Julia registry for *VPE* libraries to accelerate development.

This registry contains Julia packages which are developed as part of the Voxel Populi game engine. These packages may also be registered in the [General registry](https://github.com/JuliaRegistries/General).

*VPE* is a complex multi-package project. Unfortunately, Julia's dependency management struggles with multi-level local dependencies. At the same time, initial registration of a package in the General registry faces a mandatory 3 day delay, which is highly disruptive to active development. Thus, I have introduced this [LocalRegistry](https://juliapackages.com/p/localregistry) to facilitate development of this multi-package project.
