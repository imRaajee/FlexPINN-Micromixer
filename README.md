# PINN Micromixer – Extra Codes and Results

This repository contains **sample codes, geometries, and additional results** from a project where we used **Physics-Informed Neural Networks (PINNs)** to simulate a **3D micromixer** with various fin shapes, orientations, and Reynolds numbers.

The main objective of the project was to explore the effect of geometric and flow variations on mixing efficiency within micromixers, validated against COMSOL results.

---

## 🧠 What's Inside

- `/Geometry Codes/` – Micromixer geometry data (e.g., coordinates of fins or channel structure).
- `/results/` – Sample visual results and figures (e.g., mixing index vs. Re, flow visualization).
- `README.md` – You're here.

---

## 📦 Dependencies

The sample code requires the following libraries:

`numpy`
`matplotlib`
`pyDOE`

Make sure to install `pyDOE`, as it’s not included in the standard Python distribution:

pip install pyDOE

---

## 📂 Applications

These codes are meant to support and extend the results shared in our main article. They can be used for:

- Generating or modifying micromixer geometries.
- Visualizing fin placement and flow domain.
- Performing basic sampling using Latin Hypercube Sampling (LHS).
- Exploring parameter variations across different Reynolds numbers.

---

## 📌 Notes

- This is **not** the full PINN training code – only supporting scripts and data are provided here.
- COMSOL validation and in-depth training routines are discussed in the main publication.
- If you use any of these resources, please cite the paper (link or citation to be added later).

---

## 📝 License

This repository is open-sourced under the MIT License. Feel free to use and modify the materials with attribution.

---

## ✉️ Contact

For questions or collaborations, feel free to reach out via GitHub or email.
