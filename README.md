# 📈 Interpolation Using Newton Polynomial

**Author**: Kaitlyn Kirt  
**Course**: CMOR 220  
**Term**: Spring 2024  
**Project**: Newton Polynomial Interpolation  
**Last Modified**: April 15, 2024  

---

## 📋 Overview

This project applies the **Newton Polynomial Interpolation** technique to approximate a smooth bell-shaped curve \( f(x) = e^{-10(x - 0.2)^2} \). It evaluates the interpolation's accuracy using varying node counts (k-values) and visually compares each result to the original curve.

---

## 📂 Files

- `Project10.ipynb`: Jupyter Notebook implementing Newton's method for polynomial interpolation and visual comparison with the original function.
- `README.md`: Description of the project and instructions for usage.

---

## 🔍 Techniques Used

- **Symbolic Interpolation**: Newton interpolation to derive a polynomial approximation.
- **Matrix Construction**: Manual setup of Vandermonde-like matrix for Newton's method.
- **Error Analysis**: Uses Euclidean norm to assess approximation quality.
- **Visualization**: Plots each interpolated polynomial against the actual function for comparison.

---

## 🛠️ Requirements

```bash
pip install numpy matplotlib
