# ⚗️ Virial Mixture Fugacity Calculator

![Python](https://img.shields.io/badge/Python-3.x-blue)
![GUI](https://img.shields.io/badge/GUI-CustomTkinter-007ACC)
![Physics](https://img.shields.io/badge/Thermodynamics-Virial%20EOS-orange)

**[English]**
A modern desktop application designed to calculate **Fugacity Coefficients ($\phi_i$)** and **Partial Fugacities ($\hat{f}_i$)** for a ternary gas mixture (Methane, Propylene, Water). It utilizes the **Virial Equation of State** truncated after the second term, applying Pitzer-Curl correlations and standard mixing rules for the second virial coefficient ($B_{mix}$).

**[Español]**
Una aplicación de escritorio moderna diseñada para calcular **Coeficientes de Fugacidad ($\phi_i$)** y **Fugacidades Parciales ($\hat{f}_i$)** para una mezcla gaseosa ternaria (Metano, Propileno, Agua). Utiliza la **Ecuación de Estado Virial** truncada en el segundo término, aplicando las correlaciones de Pitzer-Curl y reglas de mezclado estándar para el segundo coeficiente virial ($B_{mix}$).

---

## 🚀 Key Features / Características Principales

### 🇬🇧 English
* **Thermodynamic Model:** Implements the Virial EOS with the exact calculation of cross-coefficients ($B_{ij}$) using:
  * Geometric mean for Critical Temperature ($T_{c_{ij}}$).
  * Arithmetic mean for Acentric Factor ($\omega_{ij}$) and Critical Compressibility ($Z_{c_{ij}}$).
* **Modern UI:** Built with **CustomTkinter** for a clean, high-DPI aware, and dark/light mode compatible interface.
* **Result Formatting:** Displays results in a neatly formatted ASCII table directly in the application window.
* **Input Validation:** Automatically ensures mole fractions sum to 1.0 before calculation.

### 🇪🇸 Español
* **Modelo Termodinámico:** Implementa la Ecuación Virial con el cálculo exacto de coeficientes cruzados ($B_{ij}$) usando:
  * Media geométrica para la Temperatura Crítica ($T_{c_{ij}}$).
  * Media aritmética para el Factor Acéntrico ($\omega_{ij}$) y Compresibilidad Crítica ($Z_{c_{ij}}$).
* **Interfaz Moderna:** Construida con **CustomTkinter** para una interfaz limpia, compatible con pantallas de alta resolución y modos claro/oscuro.
* **Formato de Resultados:** Muestra los resultados en una tabla ASCII perfectamente alineada dentro de la ventana de la aplicación.
* **Validación de Datos:** Asegura automáticamente que las fracciones molares sumen 1.0 antes de calcular.

---

## 🧪 Mixture Components / Componentes de la Mezcla

The code is currently pre-configured for the following system:
El código está preconfigurado para el siguiente sistema:

1.  **Methane (Metano)** - $CH_4$
2.  **Propylene (Propileno)** - $C_3H_6$
3.  **Water (Agua)** - $H_2O$

---

## 📦 Installation / Instalación

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/TU_USUARIO/Virial-Fugacity-Calc.git](https://github.com/TU_USUARIO/Virial-Fugacity-Calc.git)
    cd Virial-Fugacity-Calc
    ```

2.  **Install dependencies (Required for the GUI):**
    ```bash
    pip install numpy customtkinter packaging
    ```

3.  **Run the application:**
    ```bash
    python main.py
    ```

---

## 🖼️ Preview

*(<img width="1365" height="732" alt="image" src="https://github.com/user-attachments/assets/42807bf6-27f8-4b17-86a0-4179638c930f" />
)(<img width="1365" height="456" alt="image" src="https://github.com/user-attachments/assets/f234bdbe-1169-429a-93c8-a221f580b79b" />
)*

---

**Author:** [Angel Torres ]
