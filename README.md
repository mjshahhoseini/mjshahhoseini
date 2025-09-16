# MJ Shahhoseini

**Astrophysics PhD Student — ISM & Molecular Clouds**  
Astronomy & Plasma (AoP) | Space, Earth & Environment (SEE)  
Chalmers University of Technology · Onsala Space Observatory  

---

### 👋 About
My name is MJ (Mohammad Javad) Shahhoseini and I study the **interstellar medium (ISM)** in the Milky Way, focusing on the distribution of dust and gas, turbulence, extinction, and the structure of molecular clouds.  
I build and analyze **Gaia-based 3D dust-extinction maps** to derive density PDFs and compare 3D vs 2D statistics to probe star-formation physics.

---

### 🔭 Highlights
- **Research interests:** ISM, 3D dust/gas, turbulence, star formation, data analysis & ML in astronomy  
- **Education:** PhD (Astrophysics), Chalmers (2024– ); MSc (Gravity & Cosmology), SBU; BSc (Astrophysics), IAU  
- **Recent talk:** *Understanding the density PDFs of molecular clouds: the 3D view by Gaia* — Stellar Origins 2025  

---

### 🛰️ Affiliations
- PhD Student — AoP, Chalmers University (2024–present)  
- Teaching Assistant / Outreach — AoP & Onsala Space Observatory (2024–present)  
- Research Assistant — IPM, Tehran (2020–2023)  

---

### 🧑‍💻 Example (Python workflow)

```python
import numpy as np
from dustmaps.edenhofer2023 import Edenhofer2023Query

# Query extinction at (l, b, d)
query = Edenhofer2023Query()
Av = query(l=210, b=-20, d=400)  # mag extinction
print(f"A_V = {Av:.3f} mag")
