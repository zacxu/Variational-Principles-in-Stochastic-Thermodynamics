## Research Abstract

Variational formulations of nonequilibrium thermodynamics extend Hamilton’s principle to systems with irreversible processes such as friction and heat conduction.

While deterministic structure-preserving discretization exists, the corresponding methods for stochastic thermodynamic systems that preserve both energy balance and entropy production remain underdeveloped. Standard stochastic integrators may fail to preserve the entropy production structure and fluctuation-dissipation relation. In this paper, we develop thermodynamically consistent numerical schemes for stochastic systems formulated in the Stratonovich framework.

We consider finite-dimensional thermodynamic systems derived from a variational principle and extend them to stochastic thermodynamics through Langevin-type forces satisfying fluctuation–dissipation relations. Deterministic systems are discretized using discrete gradient methods that guarantee exact energy balance and non-negative entropy production.

We then construct discretization schemes by extending discrete gradient methods and stochastic integrators to systems with noise. The proposed algorithms are then applied to stochastic models. We show that deterministic discrete gradient schemes conserve total energy exactly in isolated systems. In the stochastic case, we prove discrete energy balance, and will further discuss entropy production, and recovery of equilibrium distributions consistent with the Einstein fluctuation–dissipation relation. We derive the one-step transition kernel, compare forward and reversed path probabilities, and use their ratio to define the discrete medium entropy production, thereby deriving a discrete general fluctuationdissipation relation.

*Keywords: Stochastic Thermodynamics, Discrete Gradient Methods, Structure Preserving Discretization*