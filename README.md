# Hi, I'm Huzaifa Ahmad 👋

**Materials Engineer | Machine Learning & Computational Materials Science**

I work at the intersection of materials engineering, machine learning, and computational materials science. My background combines experimental materials characterization and corrosion research with data-driven modelling and materials discovery.

### Research interests
- Materials informatics and machine learning
- Computational materials science and atomistic modelling
- Battery materials and sustainable electrode discovery
- Corrosion, degradation, and structure–property relationships

---

## Projects

### 1. Machine Learning-Based Prediction of Steel Fatigue Strength
**Python · Scikit-learn · TensorFlow/Keras**

Developed machine learning models to predict fatigue strength at \(10^7\) cycles using a dataset of 437 steel samples and 25 features.

- Random Forest: **R² = 0.985**, RMSE = **24.7 MPa**
- Artificial Neural Network: **R² = 0.978**, RMSE = **29.8 MPa**
- Received **1st Prize at Pakistan Auto Show 2024 (PAAPAM)**.

The project also examined how validation strategy affects model performance. Randomly shuffled validation produced substantially lower errors than compositionally grouped/contiguous validation, highlighting the challenge of generalizing to unseen steel groups.

### 2. Graph Neural Networks for Materials and Battery Electrode Prediction
**Python · CGCNN · PyTorch · Materials Project**

Explored crystal graph convolutional neural networks (CGCNN) for formation-energy and battery-electrode voltage prediction.

- Reproduced a Matbench formation-energy result with an MAE of **0.0327 eV/atom**.
- Evaluated **3,342 Materials Project electrode pairs**.
- For unseen chemical systems, achieved a voltage MAE of **0.409 V** and Spearman correlation of **0.895**.

The model captured voltage rankings reasonably well, but voltage magnitude errors remained above the predefined 0.25 V target. This project helped identify the limits of transferring formation-energy predictions into voltage estimates.

### 3. Sustainability-Aware Screening of Battery Electrode Materials
**Python · Materials Project API · Pymatgen · Pandas · Scikit-learn**

Built a computational workflow to screen insertion-electrode materials using voltage, capacity, stability, volume-change, oxygen-content, and elemental-abundance criteria.

- Screened **6,847 electrode records** across 10 working ions.
- Reduced the initial lithium-ion dataset of 2,688 records to a shortlist of **45 Co/Ni-free candidates**, including 29 candidates that also avoid other scarce elements.
- Identified **7 sodium-ion candidates** after applying the screening criteria.
- Compared stability cut-offs to understand how screening decisions affect candidate selection.

This is a computational screening study, not experimental validation or the discovery of a new material.

### 4. Early Prediction of Lithium-Ion Battery Cycle Life
**Python · Pandas · NumPy · Scikit-learn**

Reimplemented a data-driven battery lifetime prediction approach using early-cycle measurements from **124 LFP/graphite cells**.

- Used differential-capacity curve variance (ΔQ(V)) features from the first 100 cycles.
- Achieved RMSE values of **138.4 cycles** and **196.0 cycles** on two test sets.
- Improved on predict-the-mean baselines of **398.8 cycles** and **510.6 cycles**, respectively.
- Found that useful prediction performance emerged at approximately cycle 40.

The work also included data-quality checks that identified seven corrupted cells and an assessment of model overfitting.

### 5. Composition-Based Crystal Symmetry Prediction
**Python · Matminer · Magpie Descriptors · Random Forest · XGBoost**

Reproduced and extended a machine-learning workflow for predicting crystal symmetry from chemical composition.

- Reproduced the cubic crystal-system result with **95.7% accuracy**, close to the published 96.1% result.
- Extended the analysis to seven crystal systems using a dataset of **102,528 compounds**.
- Achieved weighted F1 = **0.956** and MCC = **0.940** for the cubic classification task.
- Compared Random Forest and XGBoost models and examined common classification errors.

### 6. CDVAE vs. Enumeration for Perovskite Composition Screening
**Python · PyTorch · CDVAE · Materials Data Analysis**

Evaluated whether a generative model could outperform simple enumeration when screening a Perov-5 composition space.

- Analysed **18,928 compositions** across a \(52 \times 52 \times 7\) search space.
- Identified composition overlap between conventional random splits and created a composition-grouped split for a fairer evaluation.
- Compared CDVAE sampling against direct enumeration of the best-performing composition range.
- Found that CDVAE sampling achieved a **7.7% best-decile hit rate**, while direct enumeration retrieved all entries in the best decile in approximately **0.01 seconds**.

The main outcome was a benchmark showing the importance of data-leakage checks and simple baseline comparisons when evaluating generative materials models.

---

## Experimental Research

### Corrosion of Mild Steel in Recirculating Brine
Investigated the effect of flow rate on mild-steel corrosion in **3.5 wt.% NaCl** using immersion/weight-loss testing and post-test characterization. The work involved electrochemical and materials characterization techniques, including SEM, XRD, and atomic absorption spectroscopy.

### Intergranular Corrosion of Additively Manufactured Al-Si Alloy
Studied intergranular corrosion using **ASTM G67-24** and **ISO 11846:1995**, comparing the response of the alloy under different standardized test methods.

---

## Technical Skills

- **Programming & data science:** Python, NumPy, Pandas, Matplotlib, Scikit-learn, TensorFlow/Keras, PyTorch, XGBoost
- **Computational materials:** Pymatgen, Matminer, Materials Project API, CGCNN, materials data analysis
- **Engineering tools:** MATLAB/Simulink, Origin, FreeCAD
- **Experimental techniques:** SEM, XRD, AAS, electrochemical corrosion testing, immersion/weight-loss testing, heat treatment
- **Other:** Git, GitHub, Linux, technical reporting

---

## Connect

- **LinkedIn:** [linkedin.com/in/huzaifa-ahmad24](https://www.linkedin.com/in/huzaifa-ahmad24/)
- **GitHub:** [github.com/Huzaifaahmad001](https://github.com/Huzaifaahmad001)
- **Email:** [huzaifaahmad805@gmail.com](mailto:huzaifaahmad805@gmail.com)
- **Portfolio:** [huzaifaahmad-portfolio.netlify.app](https://huzaifaahmad-portfolio.netlify.app/)

---

*Turning materials data into engineering insight.*
