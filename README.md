# Cellular-Plasticity-Model-for-Self-organized-phenotypes
data repository for Cellular Plasticity Model for Self-Organized Phenotypes in Multi-cellular Robots



cp_# represents the cellular plasticity trials
pt_# represents the performance tuned trials
pt_free_# represents the performance tuned trials in an obstacle-free environment only


This experiment evaluates Loopy’s ability to self-organize
its mechanical properties across two environments—contained
and obstacle-free—and three morphogenetic behaviors: forma-
tion, metamorphosis, and morphology rotation. An external
script sequentially modifies the underlying reaction-diffusion
system parameters to trigger transitions between these behav-
iors. Loopy begins in a random initial configuration within
the contained environment, where it is directed to form a
circular morphology, metamorphose into a three-lobed shape,
and then rotate its morphology. The environment is then
manually switched to obstacle-free, where Loopy continues
morphology rotation, stops rotation, and finally returns to a
circular morphology through another metamorphosis. Each
phase lasts two minutes.
