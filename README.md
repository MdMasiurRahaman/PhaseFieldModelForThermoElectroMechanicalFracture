# Thermodynamically consistent volumetric–deviatoric decomposition-based phase-field model for thermo-electro-mechanical fracture

Using a volumetric–deviatoric decomposition of strain, we propose a novel phase-field model for thermo-electro-mechanical fracture and provide an open-source finite element implementation
of the proposed model. Considering displacement, electric potential, temperature field, and phase-field variable, we have obtained the governing partial differential equations (PDEs), 
by utilizing the virtual power principle. We have obtained the constitutive relations for the necessary thermodynamic fluxes on satisfying the first and second laws of thermodynamics.
The proposed model can accommodate any dissipative effect, such as viscous damping, whenever necessary, in a thermodynamically consistent manner. We have developed open-source finite 
element codes for the proposed model using the Gridap package in Julia. Here, we have used the proposed model for fracture simulation in transversely isotropic material and functionally
graded material for compact tension and three-point bending tests. We have considered variations in thermal and electrical loading conditions and investigated the corresponding changes
in the structural responses. For the functionally graded specimens, we have also considered the variation in the material property gradation directions, along with the thermal and 
electrical boundary conditions to evaluate their effect on the structural responses of specimens.

# See the details using the link below:

https://www.sciencedirect.com/science/article/abs/pii/S0013794423004265

# Cite this article:

@article{behera2023thermodynamically,
  title={Thermodynamically consistent volumetric--deviatoric decomposition-based phase-field model for thermo-electro-mechanical fracture},
  author={Behera, Akash Kumar and Sudeep, Kolati Heman and Rahaman, Mohammad Masiur},
  journal={Engineering Fracture Mechanics},
  volume={290},
  pages={109468},
  year={2023},
  publisher={Elsevier}
}
