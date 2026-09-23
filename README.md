<h1 align="center">Hi 👋, I'm Junyi Li</h1>

<h3 align="center">
Scientific Machine Learning · Computational Fluid Dynamics · HPC
</h3>

<p align="center">
  <a href="https://www.nthu.edu.tw/" target="_blank">
    <img src="https://img.shields.io/badge/NTHU-M.S.%20Candidate-0b7285?style=for-the-badge" />
  </a>
  <img src="https://img.shields.io/badge/Taiwan-%F0%9F%87%B9%F0%9F%87%BC-2f9e44?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RDSS-Available%20Feb%202027-5c7cfa?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JAX-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" />
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/CFD-0F172A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/SciML-7C3AED?style=for-the-badge" />
</p>

---

## 🧑‍💻 About Me

I'm an **M.S. candidate at National Tsing Hua University (NTHU)** working at the intersection of **scientific machine learning, numerical simulation, and fluid dynamics**.

My research focuses on reconstructing complex turbulent flow fields from sparse measurements using **physics-informed neural networks and neural operators**, with particular interests in scalable training, numerical PDEs, and scientific computing.

- 🔬 Researching **physics-informed neural operators for sparse turbulent-flow reconstruction**
- 🌊 Working with **high-Reynolds-number turbulence, Navier–Stokes equations, DNS/LES, and CFD**
- 🧠 Interested in **Scientific Machine Learning (SciML), AI for Science, neural operators, and surrogate modeling**
- ⚡ Developing models with **JAX / Flax / XLA, PyTorch, and CUDA**
- 🖥️ Experienced with **GPU/HPC environments, Slurm, Linux, InfiniBand, and multi-node research infrastructure**
- 📊 Interested in robust scientific ML through **ablation studies, uncertainty quantification, benchmarking, and sparse sensing**
- 🎓 M.S. thesis completed; manuscript on physics-informed neural operators currently in preparation
- 💼 **RDSS eligible in Taiwan — available from February 2027**
- 🔎 Open to **Scientific ML, AI4Science, Computational R&D, CFD, and HPC-related opportunities**

---

## 🔬 Featured Research

### PI-CON — Physics-Informed Neural Operator for Turbulent-Flow Reconstruction

My current research explores reconstruction of full turbulent flow fields from only sparse point measurements.

**Highlights**
- Built a **3.1M-parameter JAX/Flax physics-informed neural operator**
- Reconstructed **Re = 10,000 turbulent flows from 200 point sensors**
- Achieved **8.5% velocity relative L2 error**
- Outperformed a capacity-matched PINN baseline across multiple random seeds
- Designed a **CfC branch + distance-biased cross-attention + DeepONet decoder**
- Developed memory-efficient PDE-residual evaluation using **nested forward-mode automatic differentiation**
- Reduced peak training memory by **2.8–5.9×**
- Studied sparse sensing, QR-pivot sensor placement, noise robustness, and Reynolds-number transfer

➡️ [PI-CON Repository](https://github.com/latteine1217/pi-lnn-jax)

---

## 🧪 Other Research Projects

### High-Reynolds-Number PINNs
**PirateNet + SOAP**

Physics-informed reconstruction and forward solving for **Re = 10⁶ Kolmogorov flow**, using:

`JAX` · `SOAP` · `GradNorm` · `Causal Training` · `Slurm`

➡️ [JAX-PI Repository](https://github.com/latteine1217/jaxpi)

### Sparse-Data-Assisted PINN

**2D Lid-Driven Cavity Flow — Re = 5,000**

Combined sparse measurements with physics-informed learning to accelerate convergence and improve reconstruction accuracy.

➡️ [NSFnet Repository](https://github.com/latteine1217/NSFnet)

### GPU-Accelerated Conjugate Heat Transfer Solver

Developed a conjugate heat-transfer solver for Li-ion battery cooling using:

`Python` · `Taichi` · `D2Q9 LBM` · `Finite Difference Method`

Coupled fluid flow, thermal transport, and solid conduction across continuous heat-flux interfaces.

---

## 🛠️ Research & Engineering Stack

### Scientific Machine Learning

`PINNs` · `DeepONet` · `FNO` · `Neural Operators` · `Physics-Informed Learning`  
`Surrogate Modeling` · `Sparse-State Reconstruction` · `Uncertainty Quantification`

### Scientific Computing & CFD

`Navier–Stokes` · `DNS` · `LES` · `FVM` · `LBM` · `Numerical PDEs`  
`ANSYS Fluent` · `OpenFOAM` · `Lethe`

### ML & GPU Computing

`Python` · `JAX` · `Flax` · `XLA` · `PyTorch` · `CUDA C++` · `Taichi`  
`NumPy` · `SciPy`

### HPC & Research Infrastructure

`Linux` · `Slurm` · `InfiniBand` · `NFS` · `Ansible`  
`CUDA Drivers / Toolkits` · `Environment Modules`

### Research Engineering

`Git` · `pytest` · `Weights & Biases` · `TensorBoard` · `Orbax`  
`Ablation Studies` · `Multi-seed Evaluation` · `Benchmarking`

---

## 💼 Experience

### AI Algorithm Courseware Developer
Developing technical curriculum and engineering materials covering machine learning topics including computer vision, sequence models, generative AI, and reinforcement learning.

Also contributed to **CodefyUI**, an open-source visual model editor based on React, TypeScript, FastAPI, and PyTorch.

➡️ [CodefyUI](https://github.com/CodefyUI/CodefyUI)

### HPC Systems Administrator — NTHU Applied CFD & Heat Transfer Lab
Previously administered a **29-node Ubuntu HPC cluster**, including:

- Slurm scheduling
- CUDA drivers and toolkits
- NVIDIA GPU configuration
- InfiniBand networking
- 16 TB NFS storage
- Environment modules
- Ansible-based provisioning

---

## 🎯 Research Interests

<p align="left">
  <img src="https://img.shields.io/badge/Scientific%20Machine%20Learning-7C3AED?style=flat-square" />
  <img src="https://img.shields.io/badge/AI%20for%20Science-2563EB?style=flat-square" />
  <img src="https://img.shields.io/badge/Neural%20Operators-0891B2?style=flat-square" />
  <img src="https://img.shields.io/badge/Physics--Informed%20Learning-0284C7?style=flat-square" />
  <img src="https://img.shields.io/badge/Turbulence-334155?style=flat-square" />
  <img src="https://img.shields.io/badge/CFD-475569?style=flat-square" />
  <img src="https://img.shields.io/badge/HPC-52525B?style=flat-square" />
</p>

---

## 🤝 Connect with Me

<p>
  <a href="mailto:felix.tc.tw@gmail.com">
    <img src="https://img.shields.io/badge/Email-felix.tc.tw%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://github.com/latteine1217">
    <img src="https://img.shields.io/badge/GitHub-latteine1217-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/junyi-li-a76068340">
    <img src="https://img.shields.io/badge/LinkedIn-Junyi%20Li-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
</p>
