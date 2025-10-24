<p align="center">
  <img src="https://github.com/CausalInference/.github/blob/main/assets/HarvardChan_logo_hrz_alt_RGB_Large.png" height="80">
  <img src="https://github.com/CausalInference/.github/blob/main/assets/CausaLab%2BClaim_rgb.jpg" height="80">
</p>

# CausaLab - A Center to Learn What Works
Our research at the Harvard T.H. Chan School of Public Health helps improve health outcomes for the treatment and prevention of cardiovascular disease, cancer, infectious disease, mental health, pregnancy complications, and others.

We answer questions such as: are diabetes drugs safe during pregnancy? Can HIV therapies be simplified? How effective is a new vaccine? What is the impact of bariatric surgery on cardiovascular disease? What is the comparative effectiveness of treatments for early psychosis? 

# Actionable Causal Inference
Advanced methods have real world impact when they deliver actionable information. To identify the causal questions that matter to decision makers, our team works closely with colleagues embedded in health systems, consults with government agencies and coordinates international consortia of clinical investigators. We then identify research-grade information sources and invest resources building pipelines from the raw data to the analytic datasets. We not only talk the talk of causal inference; we also walk the walk.

# Accessible Research
As pioneers in causal inference research, we are committed to transparent reporting and resource sharing that empowers investigators at every level. We foster a collaborative environment by developing open-source software for causal inference and freely accessible books & publications. We also train the next generation of investigators in causal inference via comprehensive education programs including online resources, seminar series and in-person courses at Harvard T.H. Chan School of Public Health.

# Software Offerings
CAUSALab is committed to offering free tools, code, and events to make causal inference more accessible. If you’d like to support our work at Harvard T.H. Chan School of Public Health, consider making a [financial contribution](https://hsph.harvard.edu/research/causalab/support-our-work/).

## NICE G-formula
The g-formula (Robins, 1986) uses data with time-varying treatments and confounders to estimate the risk or mean of an outcome under hypothetical treatment strategies specified by the user. The software below implements a plug-in estimator of the non-iterative conditional expectation (NICE) representation of the g-formula.

- R: [gfoRmula package](https://github.com/CausalInference/gfoRmula)
- SAS: [GFORMULA Macro](https://github.com/CausalInference/GFORMULA-SAS)
- SAS: [GFORMULA_RCT](https://github.com/CausalInference/GFORMULA-RCT-SAS) macro to estimate the per-protocol effect in randomized trials with protocol deviations
- Python: [pygformula package](https://github.com/CausalInference/pygformula)

## ICE G-Formula
This software implements a plug-in estimator of the iterative conditional expectation (ICE) representation of the g-formula, with a choice between both singly robust and multiply-robust estimators.
- R: [gfoRmulaICE package](https://github.com/CausalInference/gfoRmulaICE)

## Sequential target trial emulation
- R: [SEQTaRget package](https://github.com/CausalInference/SEQTaRget)

## Inverse Probability Weighting of Marginal Structural Cox Models
- SAS: [MSM Macro](https://github.com/CausalInference/MSM-SAS) macros to estimate the parameters of a marginal structural Cox model and estimate risk under hypothetical static interventions (requires SAS IML)
- SAS: [Sample Program](https://github.com/CausalInference/SamplePrograms/blob/main/MSMCOX.sas) to estimate the parameter of a marginal structural Cox model. An earlier version of this program appeared in the appendix of Hernán, Brumback, and Robins (2000).

## G-estimation of Structural Nested Models
- SAS: [SNCFTM Macro]()[DEADLINK]
- SAS: [Sample Program](https://github.com/CausalInference/SamplePrograms/blob/main/SNAFTM.sas) to simulate data from a Structural Nested Accelerated Failure Time Model as described by Young et al.
- R: [SNCTM R function](https://github.com/joy-shi1/sncftms) function implements g-estimation of the parameters of a Structural Nested Cumulative Failure Time Model using an instrumental variable, and estimation of marginal cumulative risks under a hypothetical static treatment regime as described by Shi et al., BMC Medical Research Methodology 2021.

## Partial Identification using Instrumental Variables
- SAS: [IV_BOUNDS Macro](https://github.com/CausalInference/IV-Bounds) provides bounds for the average treatment effect of a binary treatment as described by Swannson et al. Partial identification of the average treatment effect using instrumental variables. JASA 2018; 113(522):933-947.
