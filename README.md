# BMPF
Microscopic description of neutron stars: speed of sound, mass, radius and composition

# Abstract
The high density behavior of nuclear matter is analyzed within a relativistic mean field description with non-linear meson interactions. To assess  the model parameters and their output, a Bayesian inference technique is used. The Bayesian setup is limited only by a few nuclear saturation properties, the neutron star maximum mass larger than 2 M$_\odot$, and the low-density pure neutron matter equation of state (EOS) produced by an accurate N$^3$LO calculation in chiral effective field theory. Depending on the strength of the non-linear  scalar vector  field contribution, we have found three distinct classes of EOSs, each one correlated to different star properties distributions. If  the non-linear vector  field contribution is absent, the gravitational maximum mass and the sound velocity at high densities are the greatest. However, it also gives the smallest speed of sound at  densities below three times saturation density. On the other hand,  models with the strongest  non-linear vector  field contribution,  predict the largest radii and tidal deformabilities for 1.4 M$_\odot$ stars, together with  the smallest mass for the onset of the nucleonic direct Urca processes and the smallest central baryonic densities for the maximum mass configuration.  These models have the largest speed of sound below three times saturation density, but the smallest at high densities, in particular, above four times saturation density the speed of sound decreases approaching approximately $\sqrt{0.4}c$ at the center of the maximum mass star. On the contrary, a weak non-linear vector contribution gives a monotonically increasing speed of sound. A 2.75 M$_\odot$ NS maximum mass was obtained in the tail of the posterior with a weak non-linear vector field interaction. This indicates that the secondary object in GW190814 could also be an NS.

# The files descriptions
We release 17829 RMF model parameters, its nuclear saturation properties, equation of state, particle fraction, and TOV solutions derived from Bayesian Inference with Prior Set 0 (see article for details). 


Our data release packet contains four CSV files, namely property.csv, bmpf_eos.csv, bmpf_pfrac.csv, and bmpf_tov.csv.

property.csv:
The file contains the parameters for the RMF model, as well as a few NS properties and nuclear saturation properties. It has the following columns:
model name,gs,gv,gr,B,C,xi,lam,rho0,e0,k0,q0,z0,jsym0,lsym0,
ksym0,qsym0,zsym0,m_max,r_max,r14,lam14,cs2_max, ec,rhoc,rho_durca.
It is to be noted that the parameter B and C are the 10^3*b and 10^3 c (see article for details). 

bmpf_eos.csv:
For those models in property.csv, it is the NS matter EOS file. It has the following columns: model name, baryon number density, energy density and pressure. The units for baryon number density is fm-3 and MeV/fm3 is for both energy density and pressure. 

bmpf_pfrac.csv:
For those models in bmpf_eos.csv, it is the practice fraction file. It has the following columns: model name, baryon number density rho(fm-3), electron fraction(rho_c/rho), muon fraction (rho_mu/rho), neutron fraction (rho_n/rho), proton fraction (rho_p/rho) and effective mass m*. 

bmpf_tov.csv:
For those models in bmpf_eos.csv, it is the TOV solutions. It has the following columns: model name, ns radius (km), ns mass (msun), cs2 (c2), and dimentionless tidal deformability $\Lambda$. 


# Citation
[1] Malik, T., Ferreira, M.,  and Providência, C., “Microscopic description of neutron stars: speed of sound, mass, radius and composition”, arXiv e-prints, 2023.


