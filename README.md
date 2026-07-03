<h1 align="center">
GSCA Prime: A Software Package for Generalized Structured Component Analysis (GSCA)
</h1>

## **Author**
- **GyeongCheol Cho**  
- Department of Psychology, The Ohio State University  
- Email: <cho.1240@osu.edu>

---

## **Overview**

**GSCA Prime** is a software package implementing the *Generalized Structured Component Analysis (GSCA)* model.  
It enables estimation and evaluation of component-based structural equation models and is designed to evolve with the latest methodological developments.  
Future releases will expand compatibility to support execution via the MATLAB Runtime (MCR), enabling external access from R and other platforms.

---

## **Core Features**

- Estimate GSCA model parameters with standard errors (SEs) and 95% confidence intervals (CIs).  
- Evaluate model performance in terms of both explanatory and predictive power.  
- Accommodate convex components using raw or standardized indicators.  
- Support higher-order components.  
- Handle missing values.  
- Enable parallel bootstrap sampling when supported by MATLAB Parallel Computing Toolbox.

---

## **Installation**

### 🔷 From GitHub Releases
1. Download the latest release file, `GSCA-Prime-<version>.mltbx`, from the [GitHub Releases page](https://github.com/PsycheMatrica/GSCA_Prime/releases).  
2. In MATLAB, install by double-clicking the file or by running:
   ```matlab
   matlab.addons.toolbox.installToolbox('GSCA-Prime-1.0.3.mltbx')
   ```
3. Once installed, the package is automatically added to the MATLAB path:
   ```matlab
   help gsca.fit
   gsca.fit(Data, Model, EstimationOption)
   ```

### 🧩 System Requirements
- MATLAB R2025b or later  
- Optimization Toolbox  
- Parallel Computing Toolbox  
- Statistics and Machine Learning Toolbox  

*(End users can later run the compiled version with MATLAB Runtime (MCR) without a MATLAB license.)*

---

## **Examples**

Example scripts are included within the package and can be accessed directly from the MATLAB Add-On folder.

---

## **Versioning and Repository Information**

- This repository provides **packaged releases (.mltbx)** for distribution. 

- Future versions will introduce an MCR-based interface for integration with R and other languages.

---

## **Citation (APA)**

> Cho, G. (2025). *GSCA Prime: A Software Package for Generalized Structured Component Analysis* [Computer software]. GitHub. <https://github.com/PsycheMatrica/GSCA_Prime>

---

## **License**

```
GSCA Prime License Agreement

Copyright (c) 2025 GyeongCheol Cho. All rights reserved.

This software is licensed for academic and research use only.  
Commercial use, redistribution, inclusion in other software packages, or creation of derivative works is prohibited without prior written permission from the copyright holder.
```

---

## **Contact**

For questions, feature requests, or bug reports, please visit:  
<https://github.com/PsycheMatrica/GSCA_Prime/issues>
