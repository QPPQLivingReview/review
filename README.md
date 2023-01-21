#  **QPPQ**: *a living review of Quantum Computing + Plasma Physics*

<!DOCTYPE html><script src="https://cdn.jsdelivr.net/npm/texme@1.2.2"></script><textarea>

*Quantum Computing promises accelerated simulation of certain classes of problems, in particular in plasma physics. The goal of this document is to provide a comprehensive list of citations for those developing and applying these approaches to experimental or theoretical analyses. As a living document, it will be updated as often as possible to incorporate the latest developments.  Suggestions are most welcome.*

[![download](https://img.shields.io/badge/download-review-blue.svg)](https://QPPQLivingReview.github.io/review/review/review.pdf)

The purpose of this note is to collect references for quantum algorithms already relevant to plasma physics.  A minimal number of categories is chosen in order to be as useful as possible. Note that papers may be referenced in more than one category.

To facilitate search, if clearly appropriate, the following tags are applied 

* [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() __noisy-intermediate scale quantum computing__

* [![download](https://img.shields.io/badge/-FTol-red)]() __fault-tolerant quantum computing__

* [![download](https://img.shields.io/badge/-QAnn-blue)]() __quantum annealing__

* [![download](https://img.shields.io/badge/-QIns-grey)]() __quantum-inspired__

Color-filled tags indicate the type of content. Since most papers contain some form of theoretical analysis, we use

* [![download](https://img.shields.io/badge/-Theo-darkred)]() __theoretical__ tag solely for the papers with analytical results, and no considerable numerical or experimental results

* [![download](https://img.shields.io/badge/-Num-darkblue)]() marks papers with __numerical simulations__, but no experimental results run on quantum devices.

* [![download](https://img.shields.io/badge/-Exp-darkgreen)]() marks papers with displayed __experimental__ results. We may ommit this tag if the paper is referenced and tagged in a subsequent subsection.

The inclusion of a paper in the review does not indicate endorsement or validation of its content, as this is to be determined by the community and through peer review. The classification system may have limitations and we welcome feedback from the community on any papers that should be included, papers that have been misclassified or errors in citations or journal information.

In order to be as useful as possible, this document will continue to evolve so please check back. See [http://epp.ist.utl.pt/qppq/](http://epp.ist.utl.pt/qppq/) before you write your next paper. You can simply download the **.bib** file to get all of the latest references. Please consider citing Ref. **\cite{qppqlivingreview}** when referring to this living review.

*  **Modern reviews**

	*Below are links to (static) general and specialized reviews.*

	* Applications of Quantum Computing to Plasma Simulations [DS21a](https://arxiv.org/abs/2005.14369)
	* Quantum Computing for Fusion Energy Science Applications [Jos+22](https://arxiv.org/abs/2212.05054)
 
*  **System of linear equations**  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [HBR21](https://arxiv.org/abs/1909.07344) [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Bra+20](https://arxiv.org/abs/1909.05820)  [Xu+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [HHL09](https://doi.org/10.1103/PhysRevLett.103.150502) [CJS13](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.110.250504) [CKS17](https://epubs.siam.org/doi/10.1137/16M1087072) [WX22](https://arxiv.org/abs/2208.06763) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [SSO19](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.122.060504) [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [BL22](https://arxiv.org/abs/2206.10576) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [SM21](https://arxiv.org/abs/2103.10309)

	*Many problems in plasma physics may be formulated, either exactly or approximately, as a problem of the form* $Ax = b$ *where* $A$ *and* $b$ *encode the information about the system (including its initial conditions, if applicable), and the goal is to compute* $x$ *, which encodes the desired data.*
  
*  **System of nonlinear equations** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [DS21](https://arxiv.org/abs/2105.07317) [![download](https://img.shields.io/badge/-Num-darkblue)]() [XWG21](https://www.worldscientific.com/doi/10.1142/S201032472140004X) [Xue+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.032427)

	*Nonlinear equations depend nonlinearly on* $x$*, and they are generally much harder to solve. As quantum mechanics is inherently linear, many techniques rely on mapping the original nonlinear problem to a (usually approximate) linear one, that is easier to solve.*

	* **System of polynomial equations** [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Cha+19](https://www.nature.com/articles/s41598-019-46729-0)
	
		*System where each equation is a polynomial.*
	
* **Ordinary differential equations** [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]()  [Zan+21](https://doi.org/10.22331/q-2021-07-13-502)

	*Many plasma systems can be described by ordinary differential equations. Some techniques attempt to solve them directly, while others map the ODE to (larger) systems of linear equations, and solve those.*
	
	* **Linear**  [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Ber14](https://iopscience.iop.org/article/10.1088/1751-8113/47/10/105301) [Ber+17](https://link.springer.com/article/10.1007/s00220-017-3002-y) [CL20](https://link.springer.com/article/10.1007/s00220-020-03699-z) [FLT22](https://arxiv.org/abs/2208.06941) [JLY22a](https://arxiv.org/abs/2212.13969) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Zan+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631)
	
		*As quantum mechanics is inherently linear, linear ODEs are often more straight-forward to solve with quantum computers than nonlinear ones.*
		
		* **Second-order** [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [SS19](https://doi.org/10.1103/PhysRevA.99.052355)
			
			*The highest derivative appearing in these ODEs is the second derivative.*
			
			* **Quantum harmonic oscillator** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Ric+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.052431)
			
				*Here, the time-independent Schrödinger equation has a Hamiltonian with a potential proportional to* $x^2$.
			
			
			* **Laguerre**  [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
		
				*The Laguerre equation is of the form*
				
				$$x \dfrac{\mathrm{d}^2 y}{\mathrm{d} x^2} + (1-x) \dfrac{\mathrm{d} y}{\mathrm{d} x} + n ~y = 0$$
			
	* **Nonlinear** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [KPE21](https://link.aps.org/doi/10.1103/PhysRevA.103.052416) [Shi+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.103.062608) [![download](https://img.shields.io/badge/-FTol-red)]() [LO08](https://arxiv.org/abs/0812.4423) [DS21](https://arxiv.org/abs/2105.07317)  [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [Liu+20](https://arxiv.org/abs/2011.03185) [SGS22](https://arxiv.org/abs/2212.10775) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Zan+21](https://www.sciencedirect.com/science/article/pii/S2095927321004631)
	
		*There is no general reliable procedure to solve nonlinear ODEs, but some methods have been proposed.*
	
* **Partial differential equations (PDEs)** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [GRG22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.105.012433) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CLO21](https://doi.org/10.22331/q-2021-11-10-574) [Kro22](https://arxiv.org/abs/2202.01054) [![download](https://img.shields.io/badge/-QIns-grey)]() [Gar21](https://quantum-journal.org/papers/q-2021-04-15-431/)

	*In general, plasma systems are described by partial differential equations. Although some of the equations presented here do not commonly describe plasma systems, the techniques employed to solve them are often general enough that they could be adapted to tackle plasma PDEs.*
	
	*For ease of search, PDEs arising from stochastic processes are indicated both here and in the following section.*

	* **Linear** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [OMa+22](https://arxiv.org/abs/2205.00645), [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22a](https://arxiv.org/abs/2212.13969) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
		
		* **Non-homogeneous** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Bra+20](https://arxiv.org/abs/1909.05820) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Arr+19](https://doi.org/10.1103/PhysRevA.100.032306) [Ric+22](https://doi.org/10.1103/PhysRevA.106.052431) 
		
			* **Vlasov** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [ESP19](https://doi.org/10.1103/PhysRevA.100.062315)
			
				*The Vlasov equation models the evolution of the distribution functions of (charged) particles in a plasma system, including their long-range Coulomb interactions. It can be written in the general form*
				
				$$\dfrac{\partial }{\partial t} f(x,p,t) + \dfrac{d r}{d t} \dfrac{\partial }{\partial r} f + \dfrac{d p}{d t} \dfrac{\partial }{\partial p} f = \mathcal{C}$$
			
				*where* $\mathcal{C}$ *is a collision term. The* $dp/dt$ *term can be coupled the (Electromagnetic) fields either through to the Poisson or the set of Maxwell’s equations.*
				
			* **Poisson**  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [Bra+20](https://arxiv.org/abs/1909.05820) [Sat+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052409) [AK22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.052409) [Sah+22](https://arxiv.org/abs/2210.16668) [Lub+20](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.010301) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Cao+13](https://doi.org/10.1088/1367-2630/15/1/013021) [![download](https://img.shields.io/badge/-Num-darkblue)]() [Arr+19](https://doi.org/10.1103/PhysRevA.100.032306) [Ric+22](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.106.052431) [Liu+21](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.104.022418) [Wan+20](https://link.springer.com/article/10.1007/s11128-020-02669-7)
			
				*The Poisson equation is an elliptic PDE that relates a charge/mass density or velocity field with the electrical/gravitational potential or pressure field it originates, respectively. It takes the form*
				
				$$\nabla^2 \phi(x,y,z) = f(x,y,z)$$
				
				*This equation has significant applications in fluid dynamics (see Navier–Stokes equations).*

		* **Semi-classical Schrödinger** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLL22](https://quantum-journal.org/papers/q-2022-06-17-739/)
			
			*The semi-classical regime of the Schrödinger equation corresponds to the case when ħ ≪ 1. Possible applications include: quantum chemistry, including Born- Oppenheimer molecular dynamics and Ehrenfest dynamics.*
			
		* **Time-dependent Schrödinger** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [Jou22](https://arxiv.org/abs/2205.02358) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLL22](https://quantum-journal.org/papers/q-2022-06-17-739/)
		
			*Many problems can be mapped to the Schrödinger equation*
			
			$$\mathrm{i}\hbar \partial_t \ket{\psi(t)} = H\ket{\psi(t)}$$
			
			*described by some Hamiltonian H. Solving the Schrödinger equation can often be done much more efficiently with quantum computers.*
				
	* **Parabolic** [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)
	
		* **Heat/Convection** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]()  [LEK22](https://arxiv.org/abs/2204.02912) [Alb+22](https://arxiv.org/abs/2208.05805) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [LMS22](https://link.springer.com/article/10.1007/s00220-022-04442-6) [JLY22a](https://arxiv.org/abs/2212.13969) [JLY22d](https://linkinghub.elsevier.com/retrieve/pii/S0021999122007045) [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		
			*The prototypical parabolic linear PDE. This equation describes the diffusion of heat in a material*
			
			$$\partial_t u(t,x) = \alpha ~\Delta u $$
			
			*where α is the thermal diffusivity. Its applications are of fundamental importance in most branches of physics and engineering.*

		* **Black-Scholes** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [FJO21](https://epubs.siam.org/doi/10.1137/21M1397878) [MK22](https://ieeexplore.ieee.org/document/9618807/) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)
		
			*The Black–Scholes equation is a PDE which describes the price of the option V (S, t) over time t and price of underlying asset S(t), r is the ”force of interest, μ is the annualized drift rate of S, and σ is the standard deviation of the stock’s returns.*
			
			$$\frac{\partial V}{\partial t}+\frac{1}{2} \sigma^2 S^2 \frac{\partial^2 V}{\partial S^2}+r S \frac{\partial V}{\partial S}-r V=0$$
			
		* **Fokker-Planck** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Gar21](https://arxiv.org/abs/1909.06619)
	
		*The Fokker-Planck equation for the probability density* $p(x, t)$ *can be written as*
		
		$$\dfrac{\partial }{\partial t} p(x,t)  = - \dfrac{\partial }{\partial x} \left( \mu(x,t)~p(x,t)  \right) + \dfrac{\partial^2 }{\partial x^2} \left( D(x,t)~p(x,t) \right)$$
		
		*where* $\mu$ *and* $D$ *are the drift and diffusion coefficients (which may be time-dependent).*
		
		* **Hamilton-Jacobi-Bellman** [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)


	* **Hyperbolic/Wave-related** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22d](https://linkinghub.elsevier.com/retrieve/pii/S0021999122007045) [JL22](https://arxiv.org/abs/2202.07834)
	
		* **Wave** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323) [![download](https://img.shields.io/badge/-QAnn-blue)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [CS22](https://arxiv.org/abs/2204.03657)
		
			*The prototypical hyperbolic equation in physics, it describes oscillatory and propagating perturbations in a medium*
			
			$$\partial_{tt} u(t,x) = c^2 ~\nabla^2 u$$
			
		* **Maxwell’s** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323) [![download](https://img.shields.io/badge/-Num-darkblue)]() [NSD21](https://arxiv.org/abs/2112.06086) [NDS22](https://arxiv.org/abs/2212.09113)
		
			*The Maxwell equations are a set of coupled PDEs that are foundational to the modeling of electromagnetic phenomena, which important applications in fundamental physics, classical optics and electric circuits.*
			
			$$\nabla \cdot \mathbf{E}=\frac{\rho}{\varepsilon_0}, \nabla \cdot \mathbf{B}=0, \nabla \times \mathbf{E}=-\frac{\partial \mathbf{B}}{\partial t}, \nabla \times \mathbf{B}=\mu_0\left(\mathbf{J}+\varepsilon_0 \frac{\partial \mathbf{E}}{\partial t}\right)$$

		* **Klein-Gordon** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [CJO19](https://doi.org/10.1103/PhysRevA.99.012323)

			*The Klein-Gordon relativistic wave equation is a 2nd order equation both in space and time*
			
			$$\left(\frac{1}{c^2} \frac{\partial^2}{\partial t^2}-\nabla^2+\frac{m^2 c^2}{\hbar^2}\right) \psi(t, \mathbf{x})=0$$

		* **Helmholtz** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]()  [![download](https://img.shields.io/badge/-Num-darkblue)]() [Ewe+22](https://ieeexplore.ieee.org/document/9729563/)
		
			*The Helmholtz equation is the eigenvalue problem for the Laplace operator.*
			
			$$\nabla^2 f = - k^2~ f$$
			
			*Important applications include wave-like phenomena and diffusion processes.*


	* **Nonlinear** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JL22](https://arxiv.org/abs/2202.07834)
	
		* **Evolution equation**  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [LEK22](https://arxiv.org/abs/2204.02912)

			*General class of PDEs with time-domain.*
			
		* **Vlasov-Poisson** [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [YL22](https://arxiv.org/abs/2205.11990)
			
			*The coupled Vlasov-Poisson system describes the self-consistent evolution of charges and their (electrical) potentials. Because of this, the system is nonlinear.*
			
		* **Schrödinger-Poisson** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [MS21](dx.doi.org/10.3847/1538-4357/abe6ac)
			
			*Similar to the Vlasov-Poisson system, the Schrödinger-Poisson equation attempts to describe the self-consistent evolution of a wave-function and a potential.*
			
		* **Nonlinear-Schrödinger** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Lub+20](https://journals.aps.org/pra/abstract/10.1103/PhysRevA.101.010301)
			
			*Similar to the Schrödinger-Poisson system, however the potential is created by the square absolute value of the wave-function* $V= \vert \psi \vert^2$ *which induces a cubic nonlinearity in the equations.*
			
		* **Burger’s** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Oz+21](https://link.springer.com/article/10.1007/s11128-021-03391-8)
			
			*This nonlinear PDE with a quadratic nonlinearity is of fundamental importance to fluid dynamics and in particular in plasma physics. It is also a prototypical equation in turbulence related studies, and can be written in the form*
			
			$$\dfrac{\partial }{\partial t} u(x,t) +u \dfrac{\partial u}{\partial x} = \nu \dfrac{\partial^2 u}{\partial x^2}$$
			
		* **Reaction-diffusion** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [LEK22](https://arxiv.org/abs/2204.02912)  [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen.svg)]() [Dem+22](https://arxiv.org/abs/2208.11780), [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [An+22](https://arxiv.org/abs/2205.01141)
		
			*Reaction–diffusion equations describe transport/diffusion of substances and their transformation into other substances, for example to model the concentration of chemical components.*	
			
			*where* $D$ *is the diffusion coefficient and R is the local reaction rate.*		
		* **Navier-Stokes** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Gai20](https://www.nature.com/articles/s41534-020-00291-0)
		
			*The Navier-Stokes equations describe the motion of viscous fluids. They describe conservation of mass and momentum and often require equations of state for pressure, temperature and density to close the system of equations.*
			
			$$\partial_t \rho (x,t) + \nabla \cdot (\rho u) = 0, \frac{\partial}{\partial t}(\rho \mathbf{u})+\nabla \cdot(\rho \mathbf{u} \otimes \mathbf{u})=-\nabla p+\mu \nabla^2 \mathbf{u}+\frac{1}{3} \mu \nabla(\nabla \cdot \mathbf{u})+\rho \mathbf{g}$$
			
			* **Incompressible** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [LEK22](https://arxiv.org/abs/2204.02912) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Lap22](https://arxiv.org/abs/2206.00419)
			
				*The incompressible Navier-Stokes equations can be applied for low enough Mach numbers, and cannot be used to accurately simulate density or pres- sure waves like sound or shock waves. The fluid density is considered constant* $\rho = \rho_0$.

		* **Hamilton-Jacobi** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [JLY22c](https://arxiv.org/abs/2209.08478) [JL22](https://arxiv.org/abs/2202.07834)
			
			*A particular case of the Hamilton-Jacobi-Bellman. The Hamilton-Jacobi is an alternative formulation of classical mechanics, where given a Hamiltonian* $H(q, p, t)$ *of a mechanical system, the Hamilton–Jacobi equation is a first-order, non-linear PDE for the Hamilton’s principal function S. One of its advantages is in efficiently identifying conserved quantities of mechanical systems.*
			
		* **Black-Scholes-Barenblatt** [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Pat+22](https://arxiv.org/abs/2208.02235)
		
			*The Black-Scholes-Barenblatt equation is a nonlinear extension to the Black-Scholes equation, which models uncertain volatility and interest rates derived from the Black-Scholes equation.*
			
		* **Stefan problems** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Sar22](https://arxiv.org/abs/2205.02230).
		
			*Stefan problems are a particular kind of boundary value problems for a system of PDEs in which the boundary between the phases can move with time.*

* **Stochastic processes** [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Kub+20](https://arxiv.org/abs/2012.04429) [Alg+22](https://quantum-journal.org/papers/q-2022-06-07-730/) [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [An+21](https://quantum-journal.org/papers/q-2021-06-24-481/)

	*(Integro-)differential equations in which one or more of the terms is a stochastic process, leading to a solution which is stochastic in nature. Stochastic Differential Equations (SDEs) can be used to model physical systems subject to thermal fluctuations.*
	
	*Through the Feynman-Kac formula, many common SDEs can be reduced to solving a PDE for the probability density of interest, as is the case for the Fokker-Planck equation.*
	
	*For ease of search, PDEs arising from stochastic processes are indicated both here and in the previous section.*
	
	* **Fokker-Planck** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703) [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Gar21](https://arxiv.org/abs/1909.06619)
	
		*The Fokker-Planck equation for the probability density* $p(x, t)$ *can be written as*
		
		$$\dfrac{\partial }{\partial t} p(x,t)  = - \dfrac{\partial }{\partial x} \left( \mu(x,t)~p(x,t)  \right) + \dfrac{\partial^2 }{\partial x^2} \left( D(x,t)~p(x,t)  \right)$$
		
		*where* $\mu$ *and* $D$ *are the drift and diffusion coefficients (which may be time-dependent).*
		
	* **Linear Boltzmann/Rate equation** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [JLY22b](https://arxiv.org/abs/2212.14703)

		*The linear Boltzmann or Rate equation is a stochastic integro-differential equation for the probability density* $p(x, t)$ *can be written as*
		
		$$\dfrac{d }{d t} p(x,t)  = \int p(x',t) W(x,x') dx' - p(x,t) \int W(x',x) dx' $$
		
		*where* $W(x,x')$ *is the probability rate of transition from state* $x'$ *to state* $x$, *where* $dp/dt$ *can include partial derivatives of* $p(x, t)$.

* **Other techniques:**

	*  **Linear embedding of nonlinear dynamical systems** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [ESP21](https://aip.scitation.org/doi/10.1063/5.0040313) [JLY22c](https://arxiv.org/abs/2209.08478) [![download](https://img.shields.io/badge/-Num-darkblue)]() [Liu+20](https://arxiv.org/abs/2011.03185)
	
		*Several linear embedding of nonlinear dynamical systems have been developed to extend the class of problems that can be tackled by quantum computers. These include Koopman–von Neumann formulation, Quantum nonlinear Schrödinger lineariza- tion formulation and Carleman linearization, amongst others.*
	
	* **Koopman–von Neumann formulation** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Jos20](https://journals.aps.org/prresearch/abstract/10.1103/PhysRevResearch.2.043102) [JLY22c](https://arxiv.org/abs/2209.08478) [![download](https://img.shields.io/badge/-Num-darkblue)]() [Lin+22](https://arxiv.org/abs/2202.02188)
	
		*Koopman–von Neumann mechanics is a description of classical mechanics embedded in a Hilbert space. The dynamical equation can be written as*
		
		$$i \partial_t \psi = H_\mathrm{KvN} \psi$$
		
		*where the operator*
		
		$$H_\mathrm{KvN} = - i \sum_j \left(F_j \frac{\partial}{\partial x_j} + \frac{1}{2}  \frac{\partial F_j}{\partial x_j} \right)$$
		
		*Furthermore, the probability density is interpreted as* $\rho = \vert \psi \vert^2$  *. Applications may include the Vlasov-Maxwell coupled system of equations.*
	
	* **Quantum nonlinear Schrödinger linearization formulation** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [Llo+20](https://arxiv.org/abs/2011.06571)
	
		*Formulation of ODEs/PDEs of the type* $dx/dt + f(x) x = b(t)$ *with* $f = x^{\dagger \otimes m} F x^{\otimes m}$ *, as nonlinear Schrödinger equations. Potential applications of the method may in- clude the Navier-Stokes equation, plasma hydrodynamics, epidemiology.*
		
	* **Madelung transform for nonlinear relativistic fluids** [![download](https://img.shields.io/badge/-Num-darkblue)]() [Hat+19](https://www.nature.com/articles/s41598-019-40059-x) [![download](https://img.shields.io/badge/-NISQ-limegreen.svg)]() [![download](https://img.shields.io/badge/-Exp-darkgreen)]() [Zyl+22](https://arxiv.org/abs/2202.00918)
	
		*The Madelung equations are an alternative formulation to the Schrödinger equation, written in terms of hydrodynamical variables, with the addition of the Bohm quantum potential Q*
		
		$$\partial_t \rho_m+\nabla \cdot\left(\rho_m \mathbf{u}\right)=0, ~\frac{d \mathbf{u}}{d t}=\partial_t \mathbf{u}+\mathbf{u} \cdot \nabla \mathbf{u}=-\frac{1}{m} \nabla(Q+V)$$
		
		*Applications include modeling of shocks in plasmas.*
		
	* **Finite element method** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Theo-darkred)]() [MP16](https://doi.org/10.1103/PhysRevA.93.032324)
	
		*This approach relies on dividing a system/domain into smaller regions called finite elements. The discretization process applied to a boundary value problem leads to a system of algebraic equations, which can be less computationally expensive to resolve than the original PDE. Important applications include fluid flow, heat transfer, and electromagnetic potentials.*
		
	* **Lattice Boltzmann algorithms** [![download](https://img.shields.io/badge/-FTol-red)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [Lju22](https://www.worldscientific.com/doi/abs/10.1142/S0219749921500398)
	
		*Originally developed as a classical algorithm, this approach can be used to simulate fluid dynamics without having to solve the Navier–Stokes equations directly. The fluid density is represented on a lattice and evolves in time with streaming and collision processes. One of the advantages of the method is its efficiency/scalability in parallel architectures.*
	
	* **Quantum lattice algorithms** [![download](https://img.shields.io/badge/-QIns-grey)]() [![download](https://img.shields.io/badge/-Num-darkblue)]() [And+22](https://arxiv.org/abs/2211.16661) [Kou+22](https://arxiv.org/abs/2209.08523) [Oga+18](https://arxiv.org/abs/2209.08523) [Ram+21](https://aip.scitation.org/doi/10.1063/5.0067204) [Vah+20a](https://doi.org/10.1080/10420150.2020.1845685) [Vah+20b](https://arxiv.org/abs/2010.12264) [Vah+21a](https://arxiv.org/abs/2010.12264) [Vah+21b](https://www.tandfonline.com/doi/full/10.1080/10420150.2021.1891059) [Vah+22](https://www.tandfonline.com/doi/full/10.1080/10420150.2022.2049784) [VSV20](https://www.tandfonline.com/doi/full/10.1080/10420150.2020.1718136) [VVS20](https://www.tandfonline.com/doi/full/10.1080/10420150.2020.1718135) [Vah+21c](https://doi.org/10.2139/ssrn.3996913) [Vah+20c](https://doi.org/10.1017/S0022377820001166) [Vah+19](https://doi.org/10.1016/j.cnsns.2019.03.016) [Vah+20d](https://doi.org/10.1017/S0022377820001166) [Yep02](https://arxiv.org/abs/quant-ph/0210093) [Yep05](https://link.springer.com/article/10.1007/s11128-005-0009-7) [Yep16](https://doi.org/10.1117/12.2246702) [VYV03](https://linkinghub.elsevier.com/retrieve/pii/S0375960103003347) [Vah+11](https://doi.org/10.1145/2063384.2063416) [Vah+10](https://doi.org/10.1109/HPCMP-UGC.2010.15) [Oga+16a](https://doi.org/10.1080/10420150.2015.1137916) [Oga+16b](https://doi.org/10.1080/10420150.2015.1137916) [Oga+15](https://www.tandfonline.com/doi/full/10.1080/10420150.2014.988625) [Shi+18](https://link.aps.org/doi/10.1103/PhysRevE.97.053206) [And+23](https://arxiv.org/abs/2211.16661)
	
		*Highly parallelizable approach amenable to classical supercomputers, allowing the study of (Klein-Gordon-)Maxwell’s equations, the Gross-Pitaevski equation, the nonlinear Schrödinger equation, and the KdV equation. In some cases, the method may also be suitable for fault-tolerant quantum computers*
