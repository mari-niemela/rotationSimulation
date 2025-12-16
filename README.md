# rotationSimulation
Intermeshing rotors exist in various applications, such as kneaders and extruders, and their
performance could be assessed using computational fluid dynamics simulations. It is essential to evaluate
the robustness and accuracy of such simulations. Here, we apply the overset mesh method to simulate
intermeshing rotors using a Newtonian fluid to assess the suitability of the method. First, the simulations
of concentric cylinders were used to evaluate the effect of three numerical approaches. Second, the
simulations of a rotating impeller were applied to study five different mesh topologies. Finally, two
intermeshing impellers were simulated to demonstrate the functionality of the overset mesh method, and
the conservation of transported scalar was evaluated. All cases were simulated using the OpenFOAM
open-source software. The general observations were: 1) The simulated velocity fields were in good
accordance with the reference cases and the passive scalar was conserved in the simulation case of
intermeshing impellers despite the inherent mass conservation errors. 2) However, fluctuations in power
number were detected for conformal meshes in the two impeller case.

The case files are provided in the following folders:

CASE I: concentric cylinders

CASE II: one rotating impeller

CASE III: two intermeshing impellers
