<div id="header" align="center">
  <img src="[banner.png](https://media.licdn.com/dms/image/v2/D4E16AQGkZiyrYSXlaQ/profile-displaybackgroundimage-shrink_350_1400/B4EaHrLg_xHEAU-/0/1794947027289?e=1796256000&v=beta&t=wpSYm3_64WBp6IPgsa_kr5Sv5P38-jajw7aJ963fNFo)"
       width="800" height="300"
       alt="Leandro Rímulo - Data Scientist"/>
</div>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/leandrorimulo/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:leandro.rimulo@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</div>

---

<h1 align="center">
  Hi, I'm Leandro Rímulo!
  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
</h1>

<p align="center">
  <strong>Data Scientist | Computational Physicist | Bayesian Inference & Uncertainty Quantification</strong><br/>
  PhD in Astronomy → turning messy, uncertain problems into models I can test and explain.
</p>

---

### 🚀 About Me

- 🌍 Brazilian and Italian citizen, living in Colombia (UTC−5, US-timezone aligned, remote)
- 🔭 Former astrophysicist: Bayesian inference, MCMC, Monte Carlo methods and
  time-series modelling of noisy observational data
- 🤖 Recently: designed adversarial physics/maths tasks to evaluate a frontier LLM's
  reasoning (Turing, contract, 2026)
- 🏥 Built MRI-utilisation analytics for a health-tech startup's pre-deployment product
  (unpaid, 2025–2026)
- 🎯 Moving into industry with a focus on **forecasting, risk and statistical modelling**
- 🌐 Portuguese (native), English and Spanish (fluent)

---

### 🛠️ Technical Stack

**Languages & Querying**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)

**Scientific Python**

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Methods:** Bayesian inference · MCMC (emcee) · Monte Carlo methods · uncertainty
quantification · time-series modelling · statistical quality control (control charts, R&R, ANOVA)

**Tools:** ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

**Developing now:** machine learning foundations · PyTorch · cloud deployment

---

### 📊 Featured Work

#### 🪐 orbital-time-game
**[Personal project · public repository: https://github.com/lrrimulo/orbital-time-game]**

> Orbital-mechanics game built on Monte Carlo sampling

- **Problem:** Given a work-day schedule, find two Keplerian orbits (vessel and home ship) around a
  planet of unknown density such that the ships dock at the end of the day and the planet hides
  one from the other, as a communication shadow, exactly during the silence intervals.
- **Approach:** My own derivations (orbits, shadow condition, priors), corrected after review.
  Docking is solved exactly as a two-dimensional Lambert problem. Each mode is refined to its
  maximum-posterior point, then sampled with emcee, and I pick the solution on a slider. Code
  written with an AI assistant (Claude), reviewed by me.
- **Technologies:** Python, NumPy, SciPy, Matplotlib, emcee
- **Known issues (documented):** the log-uniform density prior favours low-density planets; for
  short station blocks on such planets, MC2 often finds no junky-station orbit.

---

#### 🌌 Bayesian Modelling of Be-Star Disks (PhD Research)
**[Universidade de São Paulo, 2011–2017]**

> Inferring physical parameters from multi-year time series, with full uncertainties

- **Problem:** The disks of Be stars form and dissipate over years; two key physical
  parameters (angular momentum lost through the disk, disk viscosity) were not
  available for a statistically significant sample
- **Solution:** Automated Python pipeline fitting physical models to multi-year photometric
  time series of 54 stars with MCMC (emcee), against synthetic observables from
  hydrodynamic simulations coupled to Monte Carlo radiative transfer
- **Technologies:** Python, emcee, Fortran, IDL, Monte Carlo radiative transfer (HDUST)
- **Result:** both parameters recovered for 54 stars, the first statistically significant
  sample. First author, MNRAS 2018; co-author on three further journal papers and one
  IAU proceedings

---

#### 🏥 MRI-Utilisation Analytics
**[XRDOSE, Colombian health-tech · unpaid collaborator, 2025–2026 · pre-deployment]**

> Utilisation analytics for MRI scanners, from DICOM-derived exam data

- **Problem:** Idle scanner time is hard to see and harder to act on
- **Solution:** Interactive heatmaps (occupancy per 10-minute cell, time to next exam,
  available capacity) and a probability-of-fit view: the empirical probability that a
  set of exam durations fits a time window, from historical idle-gap distributions.
  Built on ~26 weeks of data from a two-site, five-scanner clinic
- **Technologies:** Python (prototyping), C#, ASP.NET Web Forms, SQL Server, ECharts
- **Status:** demo stage, not deployed. Code and data belong to the company and are not
  public

---

#### 📐 Calibration Data Quality Control
**[SENA ISO 17025 Laboratory, Medellín, 2024]**

> Python tools for metrology and statistical quality control

- **Problem:** Calibration measurements needed validation, traceability and
  uncertainty statements for ISO 17025
- **Solution:** Python tools for measurement data validation, control charts, R&R studies,
  ANOVA, measurement uncertainty and automated traceability checks
- **Technologies:** Python (pandas, NumPy, Matplotlib)

---

### 📈 Currently Learning

- **Forecast validation:** walk-forward backtesting, prediction-interval calibration
- **Experimental design & causal inference:** A/B testing, difference-in-differences
- **Machine learning foundations & PyTorch**

---

### 📫 Let's Connect

- **LinkedIn:** [linkedin.com/in/leandrorimulo](https://www.linkedin.com/in/leandrorimulo/)
- **Email:** leandro.rimulo@gmail.com
- **Location:** Colombia (remote-first)

---

### 💬 A Note

*"Inferring a stellar disk from noisy telescope data and producing a business forecast
you can trust take the same discipline: build the model, quantify the uncertainty,
and test it against data it never saw."*
