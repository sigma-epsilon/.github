# **SigmaEpsilon**
### A Python ecosystem for computational solid mechanics

SigmaEpsilon is an open, modular ecosystem of interrelated Python libraries designed to make **computational engineering**, **solid mechanics**, and **structural optimization** more accessible.  
The project combines reusable software components with sound theoretical foundations, supporting both **research-grade development** and **practical engineering workflows**.

At its core, SigmaEpsilon aims to:
- Lower the barrier to entry for advanced computational mechanics
- Encourage clean, reusable, and well-documented scientific code
- Accelerate research and experimentation in solid mechanics and optimization

---

## 📦 Modules

The SigmaEpsilon namespace currently consists of the following packages:

- [**sigmaepsilon.core**](https://github.com/sigma-epsilon/sigmaepsilon.core)  
  Common developer utilities and shared infrastructure across the ecosystem.

- [**sigmaepsilon.math**](https://github.com/sigma-epsilon/sigmaepsilon.math)  
  Mathematical tools with a focus on linear algebra, numerical methods, and optimization.

- [**sigmaepsilon.deepdict**](https://github.com/sigma-epsilon/sigmaepsilon.deepdict)  
  Flexible and efficient nested dictionary structures for complex data hierarchies.

- [**sigmaepsilon.mesh**](https://github.com/sigma-epsilon/sigmaepsilon.mesh)  
  Polygonal mesh handling, geometric operations, and visualization utilities.

- [**sigmaepsilon.solid.material**](https://github.com/sigma-epsilon/sigmaepsilon.solid.material)  
  Material models for beams, shells, and 3D solid continua.

- [**sigmaepsilon.solid.fourier**](https://github.com/sigma-epsilon/sigmaepsilon.solid.fourier)  
  Fourier-based numerical solutions for simplified structural models.

Each package is independently versioned and documented, with detailed installation guides, examples, and API references.

---

## 🧠 Background & Motivation

SigmaEpsilon originated as a personal effort to organize and consolidate research code during PhD studies. Over time, it evolved into a coherent **namespace-based architecture** aimed at supporting and accelerating research in **structural mechanics** and **structural topology optimization**.

While the ecosystem continues to grow, its design philosophy remains consistent:
- **Scientific correctness first**
- **Composable, interoperable modules**
- **Research-oriented but production-aware**

As a result, most solutions within the SigmaEpsilon ecosystem focus on solid mechanics, numerical modeling, and optimization—bridging the gap between theoretical research and practical implementation.
