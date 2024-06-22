This repository contains the instances of Minecraft (Linux ppc64le)

But why? Because Mojang has never officially supported PowerPC 64 architecture.
The OpenPOWER community has no choice but to hack the game to work.

As we might have known the game uses LWJGL3 and handful of proprietary libraries
for example text2speech. The latter is optional so as long as LWJGL3 libaries
supports PPC64LE, things would just work as expected. Pre-LWJGL 3.3.4 there were
NO support for PPC64LE, so the community members have to build their own LWJGL
then modify the launcher config to override the default Mojang's LWJGL3 libraries
to make the game run.

I hope that Minecraft 1.22.x would start adopting LWJGL 3.3.4 so that we do not
to custom build LWJGL anymore.

So how to use these instances? Use Prism Launcher to Add New Instance via Import from Zip

I believe the same instance would work with MultiMC5 and other forks.
