# Municipal_Wastewater_Treatment
Evaluating analytical methods for nitrogen monitoring ($NO_2^-$, $NO_3^-$, TNb) in municipal wastewater using spectroscopy, photometric analysis, and mathematical modeling.
# Municipal Wastewater Nitrogen Monitoring: Analytical Method Evaluation and Process Efficiency

### Project Overview
This project, conducted at the **West Saxon University of Applied Sciences Zwickau (WHZ)**, focuses on the evaluation of analytical methods for nitrogen monitoring in municipal wastewater. The research compares high-temperature catalytic combustion, direct UV-VIS spectroscopy, and colorimetric photometric analysis to quantify Total Nitrogen Bound (TNb), Nitrate ($NO_{3}^{-}$), and Nitrite ($NO_{2}^{-}$).

### Environmental Context & Regulatory Compliance
Effective management of municipal wastewater is critical for preventing **eutrophication**, where nutrient proliferation triggers algal blooms and hypoxic "dead zones". This study ensures alignment with **EU Council Directive 91/271/EEC**, which mandates strict nitrogen effluent limits (10 mg/L for large plants) to maintain environmental stewardship.

---

### Experimental Methodology

#### 1. Total Nitrogen Bound (TNb)
TNb was determined using catalytic high-temperature combustion at 800°C.
* All nitrogen forms are converted to Nitrogen Monoxide (NO) via a platinum catalyst.
* NO is detected using **Chemiluminescence Detection (CLD)**, where emitted light is strictly proportional to the nitrogen concentration.

#### 2. Photometric Analysis (The Griess Reaction)
Selectivity is achieved through specific chemical derivatization:
* **Nitrite**: Reacts with sulfanilamide and NED in acidic conditions to form a red-violet azo dye measured at **541 nm**.
* **Nitrate**: Selectively reduced to nitrite using **hydrazine** with copper/zinc catalysts before undergoing the colorimetric reaction.

#### 3. Direct UV-VIS Spectroscopy
Standard solutions were analyzed between 190–300 nm to establish calibration functions according to the **Lambert-Beer Law**.

---

### Data Modeling and Spectral Analysis
Below are demonstrations of the data processing workflow used to establish calibration functions and analyze UV spectra.

#### Nitrate Calibration Modeling

https://github.com/user-attachments/assets/dc27d3d0-503f-48ce-8b0c-c0b06d654b07

#### UV-VIS Spectra Plotting

https://github.com/user-attachments/assets/5465e73c-c3e0-4104-a252-cbd7dc0361fd


### Mathematical Deconvolution of Mixed Species
To resolve the spectral overlap of $NO_{2}^{-}$ and $NO_{3}^{-}$ in mixed samples, two mathematical frameworks were applied]:

* **Cramer's Rule**: Solved a system of simultaneous equations based on absorbance at 202 nm and 215 nm.
* **Multi-Wavelength Least Squares Refinement**: Optimized results across 31 data points (200–230 nm), achieving a Mean Squared Error (MSE) of **0.000005** and an $R^{2} > 0.9999$.

---

### Process Performance & Results
The evaluation of real-world samples demonstrated high operational efficiency:

| Sample Point | Total Nitrogen (mg/L) | Efficiency / Insights |
| :--- | :--- | :--- |
| **Sample 1 (Inlet)** | 46.76 | Baseline untreated influent  |
| **Sample 2 (Aeration)** | 787.0 (diluted) | Dominance of nitrate confirms efficient nitrification  |
| **Sample 3 (Outlet)** | 7.87 | **83.17% Removal Efficiency** achieved  |

* **Sensitivity Ratio**: Photometric analysis was found to be **6.86 times more sensitive** for nitrite than direct UV spectroscopy.
* **Validation**: The low effluent concentration confirms compliance with legal discharge limits.

---

### Academic Information
* **Institution**: West Saxon University of Applied Sciences Zwickau (WHZ)
* **Course**: Environmental and Process Monitoring (PT152400)
* **Supervisors**: Prof. Dr. Philip Kitschke, Eng. Nicola Pausch
* **Lead Researcher**: Ahmed Mustafa 
