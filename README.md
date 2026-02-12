# Awesome AI/ML Applications in Pharmacometrics 🧬🤖

A curated list of research papers on AI/ML applications in pharmacometrics and clinical pharmacology, regularly updated.

**Last Updated**: 2026-02-12

---
## Table of Contents

- [Adherence to drug regimen](#adherence-to-drug-regimen)
- [Automation of PK/PD modeling](#automation-of-pkpd-modeling)
- [Covariate selection / confounding adjustment](#covariate-selection-confounding-adjustment)
- [Data imputation](#data-imputation)
- [Discovery of subpatient groups](#discovery-of-subpatient-groups)
- [Disease progression modeling](#disease-progression-modeling)
- [Dose selection / optimization](#dose-selection-optimization)
- [Drug repurposing](#drug-repurposing)
- [Drug toxicity prediction](#drug-toxicity-prediction)
- [Endpoint / biomarker assessment](#endpoint-biomarker-assessment)
- [Enrichment design](#enrichment-design)
- [Exposure–response analysis](#exposureresponse-analysis)
- [Other/General](#othergeneral)
- [Outcome prediction](#outcome-prediction)
- [Patient risk stratification / management](#patient-risk-stratification-management)
- [Pharmacodynamic modeling](#pharmacodynamic-modeling)
- [Pharmacokinetic modeling](#pharmacokinetic-modeling)
- [Postmarketing surveillance](#postmarketing-surveillance)
- [Precision medicine / optimized treatment regimen](#precision-medicine-optimized-treatment-regimen)
- [RWD phenotyping](#rwd-phenotyping)
- [Survival analysis](#survival-analysis)

## Adherence to drug regimen

- **[Machine learning-integrated electrochemical sensing of ciprofloxacin for digital point-of-care therapeutic drug monitoring.](https://pubmed.ncbi.nlm.nih.gov/41361653/)**
	- Methodology: Supervised learning, Neural networks, Tree-based models, Ensemble learning
	- Published: 2025Dec09
	- Summary: Machine learning models (MLP, SVM, decision tree, random forest) are integrated with electrochemical sensors to accurately quantify ciprofloxacin in urine for therapeutic drug monitoring.

## Automation of PK/PD modeling

- **[Leveraging large language models in pharmacometrics: evaluation of NONMEM output interpretation and simulation capabilities.](https://pubmed.ncbi.nlm.nih.gov/40464844/)**
	- Methodology: LLM
	- Published: 2025Jun04
	- Summary: This study evaluates large language models (Claude, ChatGPT, Gemini, Llama) for automating pharmacometric tasks including generating model diagrams, tables, and reports from NONMEM outputs.

- **[Redefining Parameter Estimation and Covariate Selection via Variational Autoencoders: One Run Is All You Need.](https://pubmed.ncbi.nlm.nih.gov/41186137/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Model selection
	- Published: 2025Dec
	- Summary: A VAE framework is developed for NLME modeling that automates parameter estimation and covariate selection in pharmacometrics within a single run.

- **[Stochastic Gates for Covariate Selection in Population Pharmacokinetics Modeling.](https://pubmed.ncbi.nlm.nih.gov/41637692/)**
	- Methodology: Deep learning, Neural networks, Feature selection
	- Published: 2026Feb
	- Summary: Neural networks with stochastic gates are used for automated covariate selection in population pharmacokinetics modeling to efficiently identify relevant covariates.

- **[Shap-Cov: An Explainable Machine Learning Based Workflow for Rapid Covariate Identification in Population Modeling.](https://pubmed.ncbi.nlm.nih.gov/40601439/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Aug
	- Summary: The paper presents Shap-Cov, an explainable ML workflow using SHAP analysis for automated covariate identification in population PK/PD modeling with uncertainty quantification.

- **[Assessing the Potential of Generative Artificial Intelligence Models to Assist Experts in the Development of Pharmacokinetic Models.](https://pubmed.ncbi.nlm.nih.gov/40922744/)**
	- Methodology: LLM
	- Published: 2025Jul
	- Summary: This study explores using generative AI models to assist experts in developing scripts for pharmacokinetic models, specifically for constructing population PK models.

- **[Automatic detection of arterial input function for brain DCE-MRI in multi-site cohorts.](https://pubmed.ncbi.nlm.nih.gov/40808286/)**
	- Methodology: Deep learning
	- Published: 2025Dec
	- Summary: A deep learning model is developed to automatically extract arterial input functions from DCE-MRI images for quantitative pharmacokinetic modeling in multi-site cohorts.

- **[Learning Chemotherapy Drug Action via Universal Physics-Informed Neural Networks.](https://pubmed.ncbi.nlm.nih.gov/40244511/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models, Mechanism-informed machine learning
	- Published: 2025Apr
	- Summary: The paper applies Universal Physics-Informed Neural Networks to learn unknown components of differential equations modeling chemotherapy pharmacodynamics in QSP.

- **[Opportunities for AI-based Model-informed Drug Development: A Comparative Analysis of NONMEM and AI-based Models for Population Pharmacokinetic Prediction.](https://pubmed.ncbi.nlm.nih.gov/41254220/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Nov18
	- Summary: This study compares AI/ML models including deep learning and neural ODEs against traditional NONMEM for population pharmacokinetic modeling to evaluate predictive performance improvements.

- **[A machine learning approach to population pharmacokinetic modelling automation.](https://pubmed.ncbi.nlm.nih.gov/40745042/)**
	- Methodology: Model selection
	- Published: 2025Jul31
	- Summary: This paper presents an automated machine learning approach using optimization algorithms (pyDarwin) to streamline population pharmacokinetic model development for extravascular drugs.

- **[Fully Automated Deep Learning Enabled Miniature Mass Spectrometry System for Psychoactive Therapeutic Drug Monitoring.](https://pubmed.ncbi.nlm.nih.gov/40405757/)**
	- Methodology: Deep learning
	- Published: 2025Aug
	- Summary: Deep learning U-net algorithm automates peak area recognition in miniature mass spectrometry for psychoactive drug monitoring with >98% identification accuracy.

- **[QSP-Copilot: An AI-Augmented Platform for Accelerating Quantitative Systems Pharmacology Model Development.](https://pubmed.ncbi.nlm.nih.gov/41159846/)**
	- Methodology: LLM, AI Agents
	- Published: 2025Nov
	- Summary: QSP-Copilot uses large language models and multi-agent systems to automate quantitative systems pharmacology model development workflows, reducing development time by 40%.

- **[Accelerating virtual patient generation with a Bayesian optimization and machine learning surrogate model.](https://pubmed.ncbi.nlm.nih.gov/39630593/)**
	- Methodology: Bayesian ML, Surrogate modeling
	- Published: 2025Mar
	- Summary: The paper uses Bayesian optimization with machine learning surrogate models to accelerate virtual patient generation for QSP model validation in clinical trial simulations.

## Covariate selection / confounding adjustment

- **[Redefining Parameter Estimation and Covariate Selection via Variational Autoencoders: One Run Is All You Need.](https://pubmed.ncbi.nlm.nih.gov/41186137/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Model selection
	- Published: 2025Dec
	- Summary: A VAE framework is developed for NLME modeling that automates parameter estimation and covariate selection in pharmacometrics within a single run.

- **[From chemical to mechanism-driven quality control of Glehniae Radix: spectrum effect - chemometrics-pharmacology integration decoding antioxidant-anti-inflammatory crosstalk.](https://pubmed.ncbi.nlm.nih.gov/40922625/)**
	- Methodology: Tree-based models, Feature selection
	- Published: 2025Sep25
	- Summary: Random forest algorithm is used to optimize spectrum-effect relationships and predict bioactive constituents for quality control of Glehniae Radix herbal medicine.

- **[AI-NLME: A New Artificial Intelligence-Driven Nonlinear Mixed Effect Modeling Approach for Analyzing Longitudinal Data in Randomized Placebo-Controlled Clinical Trials.](https://pubmed.ncbi.nlm.nih.gov/40898887/)**
	- Methodology: Neural networks
	- Published: 2025Sep
	- Summary: Proposes AI-NLME approach using artificial neural networks to estimate probability of non-specific treatment response for controlling confounding effects in clinical trials.

- **[Stochastic Gates for Covariate Selection in Population Pharmacokinetics Modeling.](https://pubmed.ncbi.nlm.nih.gov/41637692/)**
	- Methodology: Deep learning, Neural networks, Feature selection
	- Published: 2026Feb
	- Summary: Neural networks with stochastic gates are used for automated covariate selection in population pharmacokinetics modeling to efficiently identify relevant covariates.

- **[Uncovering Population PK Covariates from VAE-Generated Latent Spaces.](https://pubmed.ncbi.nlm.nih.gov/41336851/)**
	- Methodology: Deep learning, Feature selection, Unsupervised learning
	- Published: 2025Jul
	- Summary: Uses VAEs and LASSO regression to identify key covariates from PK profiles for improved population pharmacokinetic modeling and personalized dosing strategies.

- **[Shap-Cov: An Explainable Machine Learning Based Workflow for Rapid Covariate Identification in Population Modeling.](https://pubmed.ncbi.nlm.nih.gov/40601439/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Aug
	- Summary: The paper presents Shap-Cov, an explainable ML workflow using SHAP analysis for automated covariate identification in population PK/PD modeling with uncertainty quantification.

- **[Preparation of aspirin inhalable powder by ultrasound-intensified anti-solvent crystallization for pulmonary drug delivery.](https://pubmed.ncbi.nlm.nih.gov/40680606/)**
	- Methodology: Tree-based models, Explainable AI
	- Published: 2025Sep
	- Summary: Decision Tree Regressor with Shapley Value analysis was used to elucidate the influence of critical process parameters in aspirin inhalable powder preparation.

- **[Improving Genotype Imputation in High-Dimensional Pharmacogenomics Using Multiple Imputation: Evaluation with Machine Learning Approaches.](https://pubmed.ncbi.nlm.nih.gov/41407383/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Dec17
	- Summary: The paper develops a multiple imputation framework using machine learning approaches including random forest and penalized regression for genotype imputation and covariate selection in pharmacogenomics.

- **[Development of PBPK Population Model for End-Stage Renal Disease Patients to Inform OATP1B-, BCRP-, P-gp-, and CYP3A4-Mediated Drug Disposition with Individual Influencing Factors.](https://pubmed.ncbi.nlm.nih.gov/40871097/)**
	- Methodology: Supervised learning
	- Published: 2025Aug20
	- Summary: Machine learning is used to identify factors influencing individual clearance in a PBPK population model for end-stage renal disease patients to enable precision dosing.

- **[Utilization of Machine Learning Approaches for Drug Clearance Prediction and Population Pharmacokinetic Covariate Analysis.](https://pubmed.ncbi.nlm.nih.gov/40968579/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Explainable AI, Neural networks
	- Published: 2025Sep
	- Summary: This study applies multiple ML models including CNNs and gradient boosting with SHAP-based XAI for drug clearance prediction and covariate analysis in population pharmacokinetics.

- **[Microdose Cocktail Study Reveals the Activity and Key Influencing Factors of OATP1B, P-Gp, BCRP, and CYP3A in End-Stage Renal Disease Patients.](https://pubmed.ncbi.nlm.nih.gov/39789999/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: Machine learning models were used alongside population pharmacokinetic modeling to identify key factors influencing drug transporter/enzyme activities in ESRD patients.

## Data imputation

- **[Improving Genotype Imputation in High-Dimensional Pharmacogenomics Using Multiple Imputation: Evaluation with Machine Learning Approaches.](https://pubmed.ncbi.nlm.nih.gov/41407383/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Dec17
	- Summary: The paper develops a multiple imputation framework using machine learning approaches including random forest and penalized regression for genotype imputation and covariate selection in pharmacogenomics.

- **[MMPK: A Multimodal Deep Learning Framework to Predict Human Oral Pharmacokinetic Parameters.](https://pubmed.ncbi.nlm.nih.gov/40741939/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Aug14
	- Summary: MMPK uses multimodal deep learning to predict human oral pharmacokinetic parameters by integrating molecular graphs, substructures, and SMILES sequences.

## Discovery of subpatient groups

- **[Molecular features of human pathological tau distinguish tauopathy-associated dementias.](https://pubmed.ncbi.nlm.nih.gov/41616780/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2026Feb05
	- Summary: Uses unsupervised and supervised ML to identify distinct molecular features of pathological tau protein for disease stratification and biomarker discovery across tauopathies.

- **[Machine learning-guided clinical pharmacist interventions improve treatment outcomes in tuberculosis patients: a precision medicine approach.](https://pubmed.ncbi.nlm.nih.gov/41487272/)**
	- Methodology: Unsupervised learning
	- Published: 2025
	- Summary: Machine learning techniques are used to identify TB patient subtypes and optimize clinical pharmacist interventions for precision medicine treatment approaches.

- **[Network-based disease fingerprinting with neuroinflammation PET imaging.](https://pubmed.ncbi.nlm.nih.gov/41282214/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2025Oct21
	- Summary: Machine learning classifiers are applied to network-based TSPO PET imaging data to identify disease-specific neuroinflammatory patterns and classify different neurological conditions.

- **[Virtual patients inspired by multiomics predict the efficacy of an anti-IFNα mAb in cutaneous lupus.](https://pubmed.ncbi.nlm.nih.gov/39925417/)**
	- Methodology: Unsupervised learning, Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Feb21
	- Summary: Uses multiomics clustering to identify patient subgroups, then applies ML with mechanistic modeling to predict anti-IFNα antibody treatment responses in virtual lupus patients.

## Disease progression modeling

- **[Robust temporal knowledge inference via pathway snapshots with liquid neural network.](https://pubmed.ncbi.nlm.nih.gov/40349883/)**
	- Methodology: Deep learning, Reinforcement learning, Neural networks, AI Agents, Time-series modeling
	- Published: 2025Sep
	- Summary: The paper develops liquid neural network-based AI agents for temporal knowledge inference in disease pathways and drug pharmacokinetic processes using imitation learning.

## Dose selection / optimization

- **[Hybrid Population PK-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40654807/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models, Neural networks, Ensemble learning
	- Published: 2025May07
	- Summary: Combines machine learning algorithms with population PK Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients for better dose individualization.

- **[FormulationLAI: A physiology-based machine learning framework for accelerated development of long-acting injectable formulations.](https://pubmed.ncbi.nlm.nih.gov/41260272/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2026Jan10
	- Summary: The paper presents a computational framework integrating ML with PBPK modeling and MD simulations to accelerate long-acting injectable formulation development and optimization.

- **[Comparison of Machine Learning Algorithms and Bayesian Estimation in Predicting Tacrolimus Concentration in Tunisian Kidney Transplant Patients During the Early Post-Transplant Period.](https://pubmed.ncbi.nlm.nih.gov/40338501/)**
	- Methodology: Tree-based models, Deep learning, Time-series modeling
	- Published: 2025May
	- Summary: Compares XGBoost and LSTM machine learning algorithms with Bayesian modeling for predicting tacrolimus concentrations to optimize dosing in kidney transplant patients.

- **[Multicycle Dosimetric Behavior and Dose-Effect Relationships in [177Lu]Lu-DOTATATE Peptide Receptor Radionuclide Therapy.](https://pubmed.ncbi.nlm.nih.gov/40274371/)**
	- Methodology: Deep learning
	- Published: 2025Jun02
	- Summary: Deep learning algorithm used for kidney segmentation in dosimetric analysis to develop personalized dosimetry-guided PRRT treatments for neuroendocrine tumors.

- **[Concentration monitoring and dose optimization for infliximab in Crohn's disease patients: a machine learning-based covariate ensemble model.](https://pubmed.ncbi.nlm.nih.gov/41438746/)**
	- Methodology: Ensemble learning
	- Published: 2025
	- Summary: Machine learning ensemble model developed to predict infliximab trough concentrations and optimize dosing for Crohn's disease patients in real-time.

- **[Model-informed Deep Q-Networks to Guide Infliximab Dosing in Pediatric Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40791331/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2025Jul18
	- Summary: Deep Q-Networks are used to automate and optimize infliximab dosing decisions for pediatric Crohn's disease patients by learning optimal strategies through reinforcement learning.

- **[A Comparison of AI and Population PK Models to Predict the Concentrations of Antiepileptic Drugs Using Therapeutic Drug Monitoring Records.](https://pubmed.ncbi.nlm.nih.gov/41127895/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2025Oct
	- Summary: This study compares AI models (including ensemble and deep learning methods) with population PK models to predict antiepileptic drug concentrations using TDM data.

- **[Development of Co-Amorphous Systems for Inhalation Therapy-Part 2: In Silico Guided Co-Amorphous Rifampicin-Moxifloxacin and -Ethambutol Formulations.](https://pubmed.ncbi.nlm.nih.gov/41155974/)**
	- Methodology: Supervised learning
	- Published: 2025Oct16
	- Summary: Machine learning tool identifies promising API combinations for tuberculosis therapy, combined with PBPK modeling to optimize co-amorphous formulations for inhalation delivery.

- **[Ensemble Machine Learning Model for Real-Time Valproic Acid Prediction in Epilepsy Treatment.](https://pubmed.ncbi.nlm.nih.gov/40456293/)**
	- Methodology: Ensemble learning, Tree-based models, Explainable AI
	- Published: 2025Jun02
	- Summary: Develops ensemble ML model using gradient boosting algorithms with SHAP interpretation to predict valproic acid concentrations for optimized epilepsy treatment dosing.

- **[Automated quality assurance of imaging dose and protocol adherence in computed tomography radiotherapy planning using TotalSegmentator-based segmentation.](https://pubmed.ncbi.nlm.nih.gov/41313446/)**
	- Methodology: Deep learning
	- Published: 2025Nov28
	- Summary: The paper uses TotalSegmentator-based deep learning segmentation to automate quality assurance of CT imaging doses and protocol adherence in radiotherapy planning.

- **[Machine Learning-Based Algorithm for Tacrolimus Dose Optimization in Hospitalized Kidney Transplant Patients.](https://pubmed.ncbi.nlm.nih.gov/41374329/)**
	- Methodology: Supervised learning, Tree-based models, Deep learning, Neural networks, Ensemble learning, Explainable AI
	- Published: 2025Nov21
	- Summary: ML models (XGBoost, CatBoost, LightGBM, MLP) with ensemble approach predict tacrolimus concentrations for precision dosing optimization in kidney transplant patients.

- **[Artificial intelligence and precision medicine: a pilot study predicting optimal ceftaroline dosage for pediatric patients.](https://pubmed.ncbi.nlm.nih.gov/41626576/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning models are used to predict optimal ceftaroline dosage for pediatric patients to enable individualized therapy and overcome age-related physiological variability.

- **[Dose-time-concentration prediction method based on GRU-TCN with temporal-channel attention.](https://pubmed.ncbi.nlm.nih.gov/41201288/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Nov07
	- Summary: The paper develops a GRU-TCN deep learning model with attention mechanisms for predicting drug concentration-time profiles to support precision dosing decisions.

- **[Machine learning approach for personalized vancomycin steady-state trough concentration prediction: a superior approach over Bayesian population pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40575776/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning model developed to predict vancomycin steady-state trough concentrations for personalized dosing, compared against traditional Bayesian population PK approaches.

- **[Machine learning-based prediction model for teicoplanin plasma concentrations in adults with liver disease using real-world data.](https://pubmed.ncbi.nlm.nih.gov/41424785/)**
	- Methodology: Supervised learning, Deep learning
	- Published: 2025
	- Summary: Machine learning and deep learning techniques are used to construct a prediction model for teicoplanin plasma concentrations in liver disease patients using real-world data.

- **[AI-driven ANN and RSM-CCD integrated optimization of cinnarizine-domperidone bilayer tablet: In-vitro evaluation and in-silico PBPK modeling using GastroPlus®.](https://pubmed.ncbi.nlm.nih.gov/41546579/)**
	- Methodology: Neural networks, Surrogate modeling
	- Published: 2026Feb
	- Summary: The paper uses artificial neural networks (ANN) integrated with response surface methodology to optimize cinnarizine-domperidone bilayer tablet formulation with PBPK modeling validation.

- **[Prediction of High-Dose Methotrexate Blood Concentration in Osteosarcoma Patients Using Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40336661/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025
	- Summary: Uses interpretable machine learning to predict high-dose methotrexate blood concentrations in osteosarcoma patients for early exposure prediction and toxicity prevention.

- **[Forecasting anesthetic depth using an auto-regressive transformer in propofol infusion during the induction phase.](https://pubmed.ncbi.nlm.nih.gov/40522504/)**
	- Methodology: Deep learning, Time-series modeling
	- Published: 2025Oct
	- Summary: The paper uses auto-regressive transformers to forecast depth of anesthesia for optimizing propofol dosing during anesthesia induction phase.

- **[Optimizing Mycophenolate Therapy in Renal Transplant Patients Using Machine Learning and Population Pharmacokinetic Modeling.](https://pubmed.ncbi.nlm.nih.gov/41133517/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct20
	- Summary: The paper combines population pharmacokinetic modeling with machine learning techniques to optimize mycophenolate dosing for renal transplant patients.

- **[Predicting Vancomycin Clearance in Neonates and Infants by Integrating Machine Learning and Metabolomics With Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40616641/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Jul
	- Summary: Machine learning methods, particularly Gradient Boosting Regressor, are used to predict vancomycin clearance in neonates by integrating clinical covariates and metabolomics data.

- **[Estimation of Overall Cyclosporine Exposure Using Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40698833/)**
	- Methodology: Supervised learning, Tree-based models
	- Published: 2025Dec01
	- Summary: XGBoost machine learning models are developed to predict cyclosporine AUC using blood concentrations and compared against traditional Bayesian estimation methods.

- **[Artificial intelligence generated 3D body composition predicts dose modifications in patients undergoing neoadjuvant chemotherapy for rectal cancer.](https://pubmed.ncbi.nlm.nih.gov/40379920/)**
	- Methodology: Deep learning
	- Published: 2025May16
	- Summary: AI-generated 3D body composition analysis is used to predict chemotherapy dose modifications and adverse events in rectal cancer patients receiving neoadjuvant therapy.

- **[Combined Experimental and Computational Approaches for Ternary Solid Dispersions to Enhance the Oral Bioavailability of Penfluridol.](https://pubmed.ncbi.nlm.nih.gov/41471061/)**
	- Methodology: Tree-based models
	- Published: 2025Nov30
	- Summary: Random forest regression was used to optimize the formulation composition of ternary solid dispersions to enhance penfluridol's oral bioavailability.

- **[Machine Learning-Based Model Selection and Averaging Outperform Single-Model Approaches for a Priori Vancomycin Precision Dosing.](https://pubmed.ncbi.nlm.nih.gov/40734640/)**
	- Methodology: Supervised learning, Tree-based models, Model selection, Ensemble learning
	- Published: 2025Oct
	- Summary: ML-based XGBoost model selects and averages population PK models for individualized vancomycin dosing, outperforming single-model approaches in precision dosing applications.

- **[nnDoseNet: Intuitive and flexible deep learning framework to train and evaluate radiotherapy dose prediction models.](https://pubmed.ncbi.nlm.nih.gov/41151501/)**
	- Methodology: Deep learning
	- Published: 2025Nov
	- Summary: The paper presents a deep learning framework for training and evaluating radiotherapy dose prediction models to optimize treatment planning.

- **[Mechanism-informed machine learning for individualized tacrolimus dose adjustment in the early post-kidney transplant period.](https://pubmed.ncbi.nlm.nih.gov/41531243/)**
	- Methodology: Mechanism-informed machine learning
	- Published: 2026Jan13
	- Summary: The paper develops mechanism-informed ML models to optimize individualized tacrolimus dosing in kidney transplant patients during the early post-transplant period.

- **[Hybrid Population Pharmacokinetic-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40885855/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: The paper develops a hybrid approach combining machine learning with population PK-based Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients.

- **[Explainable cluster-based learning for prediction of postprandial glycemic events and insulin dose optimization in type 1 diabetes.](https://pubmed.ncbi.nlm.nih.gov/40956852/)**
	- Methodology: Supervised learning, Unsupervised learning, Tree-based models, Explainable AI, Ensemble learning
	- Published: 2025Sep
	- Summary: Uses cluster-based ensemble ML with explainable AI to predict postprandial glycemic events and optimize insulin dosing in type 1 diabetes patients.

- **[Beyond Algorithms: Machine Learning and Clinical Determinants of Voriconazole Plasma Levels in Therapeutic Drug Monitoring.](https://pubmed.ncbi.nlm.nih.gov/41288921/)**
	- Methodology: Supervised learning
	- Published: 2025Nov25
	- Summary: Machine learning is used to predict subtherapeutic or supratherapeutic voriconazole plasma levels for therapeutic drug monitoring optimization.

- **[Optimizing Tacrolimus Dosing During Hospitalization After Kidney Transplantation: A Comparative Model Analysis.](https://pubmed.ncbi.nlm.nih.gov/40165354/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Apr01
	- Summary: This study compares XGBoost, Elastic Net, and Linear Regression models to optimize tacrolimus dosing in kidney transplant patients during early hospitalization.

- **[Deep learning-based automatic dose optimization for brachytherapy.](https://pubmed.ncbi.nlm.nih.gov/40532513/)**
	- Methodology: Deep learning
	- Published: 2025Nov
	- Summary: Deep learning is used for dose prediction and inverse optimization algorithms to improve brachytherapy treatment planning quality and dose optimization.

- **[Targeting the glabellar frown lines with OnabotulinumtoxinA: In-silico evidence supporting concentrated, low-volume injection protocols.](https://pubmed.ncbi.nlm.nih.gov/40907830/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: Uses machine learning for off-target risk prediction integrated with mechanistic PK/PD modeling to optimize BoNT-A dosing protocols for glabellar frown line treatment.

- **[Development of a patient-specific cone-beam computed tomography dose optimization model using machine learning in image-guided radiation therapy.](https://pubmed.ncbi.nlm.nih.gov/40982207/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: Machine learning model using support vector regression to predict optimal patient-specific CBCT radiation doses that minimize exposure while maintaining image quality.

- **[Machine Learning Modeling for Predicting Infliximab Pharmacokinetics in Pediatric and Young Adult Patients With Crohn Disease: Leveraging Ensemble Modeling With Synthetic and Real-World Data.](https://pubmed.ncbi.nlm.nih.gov/40459932/)**
	- Methodology: Ensemble learning, Supervised learning
	- Published: 2026Feb01
	- Summary: This study develops an ensemble ML model to predict infliximab pharmacokinetics in pediatric Crohn disease patients using synthetic and real-world data for individualized dosing optimization.

- **[PlasmoBridge: Stable hotspot engineering and targeted Surface-enhanced Raman spectroscopy (SERS) monitoring of methotrexate.](https://pubmed.ncbi.nlm.nih.gov/41082836/)**
	- Methodology: Deep learning
	- Published: 2026Jan15
	- Summary: The paper uses convolutional neural networks to enhance spectral analysis accuracy for methotrexate therapeutic drug monitoring via SERS technology.

- **[TuNa-AI: A Hybrid Kernel Machine To Design Tunable Nanoparticles for Drug Delivery.](https://pubmed.ncbi.nlm.nih.gov/40934473/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025Sep23
	- Summary: Develops a hybrid kernel machine combining molecular features and compositional data to predict nanoparticle formulation outcomes and optimize drug delivery systems.

- **[DeepTDM: Deep Learning-Based Prediction of Sequential Therapeutic Drug Monitoring Levels of Vancomycin.](https://pubmed.ncbi.nlm.nih.gov/41220794/)**
	- Methodology: Deep learning
	- Published: 2025
	- Summary: Deep learning is used to predict sequential vancomycin therapeutic drug monitoring levels in critically ill patients to optimize dosing and improve treatment outcomes.

- **[Improving Vancomycin Through Level Prediction with Machine Learning: A Comparative Study of Feature Selection and Model Performance.](https://pubmed.ncbi.nlm.nih.gov/41336096/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning models (Random Forest, LightGBM, XGBoost) are used to predict vancomycin trough levels for individualized dosing, outperforming traditional Bayesian methods.

- **[Value Decomposition-Based Multi-Agent Learning for Anesthetics Collaborative Control.](https://pubmed.ncbi.nlm.nih.gov/40828726/)**
	- Methodology: Reinforcement learning, AI Agents, Tree-based models
	- Published: 2025Aug19
	- Summary: Multi-agent deep reinforcement learning framework for personalized collaborative control of multiple anesthetics (propofol and remifentanil) in closed-loop TIVA systems.

- **[Predicting prolonged dalbavancin exposure using machine learning: a validated strategy for individualized redosing.](https://pubmed.ncbi.nlm.nih.gov/41369581/)**
	- Methodology: Supervised learning
	- Published: 2026Jan07
	- Summary: Machine learning models, specifically support vector machines, were developed to predict dalbavancin plasma concentrations for individualized redosing decisions in clinical practice.

- **[Applying exposure-response analysis to enhance Mycophenolate Mofetil dosing precision in pediatric patients with immune-mediated renal diseases by machine learning models.](https://pubmed.ncbi.nlm.nih.gov/40447059/)**
	- Methodology: Supervised learning
	- Published: 2025Aug01
	- Summary: Machine learning models are applied to develop pharmacokinetic models for mycophenolic acid and optimize MMF dosing in pediatric patients with immune-mediated renal diseases.

- **[Model-Informed Deep Q-Networks to Guide Infliximab Dosing in Pediatric Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/41189499/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2026Feb
	- Summary: Deep Q-Network reinforcement learning is used to automate and optimize infliximab dosing decisions for pediatric Crohn's disease patients using population PK models.

- **[Machine learning approach for dosage individualization of azithromycin in children with community-acquired pneumonia.](https://pubmed.ncbi.nlm.nih.gov/40181615/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning is used to predict azithromycin AUC0-24 in children with pneumonia to enable individualized dosing regimens.

- **[Machine learning-assisted tacrolimus dose optimization in childhood- onset systemic lupus erythematosus through population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/40684660/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: Machine learning algorithms are integrated with population pharmacokinetic modeling to predict individualized tacrolimus dosing for optimized therapy in childhood-onset systemic lupus erythematosus.

- **[Precision Dosing in Presence of Multiobjective Therapies by Integrating Reinforcement Learning and PK-PD Models: Application to Givinostat Treatment of Polycythemia Vera.](https://pubmed.ncbi.nlm.nih.gov/40325832/)**
	- Methodology: Hybrid mechanistic–ML models, Reinforcement learning
	- Published: 2025Jun
	- Summary: The paper integrates Q-Learning reinforcement learning with PK-PD models to develop adaptive dosing protocols for givinostat treatment in polycythemia vera patients.

- **[Precision dosing of voriconazole in immunocompromised children under 2 years: integrated machine learning and population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/41031158/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: The paper integrates machine learning with population pharmacokinetic modeling to develop individualized voriconazole dosing strategies for immunocompromised children under 2 years.

- **[Nephrocast-V: A Deep Learning Model for the Prediction of Vancomycin Trough Concentration Using Electronic Health Record Data.](https://pubmed.ncbi.nlm.nih.gov/41025800/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A deep learning model is developed to predict vancomycin trough concentrations using electronic health record data to optimize therapeutic dosing.

- **[Using Machine Learning for the Discovery and Development of Multitarget Flavonoid-Based Functional Products in MASLD.](https://pubmed.ncbi.nlm.nih.gov/41226123/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Oct22
	- Summary: Machine learning ensemble methods (Random Forest, XGBoost, CatBoost) are used to predict bioactivity of flavonoids against MASLD targets for nutraceutical product development.

- **[Optimizing Dosing Strategies in Cell Therapy With Machine Learning and Exposure-Response Integration.](https://pubmed.ncbi.nlm.nih.gov/41369984/)**
	- Methodology: Tree-based models
	- Published: 2026Jan-Feb
	- Summary: The paper proposes a random forest-based seamless phase I/II design that integrates toxicity, efficacy, and cellular kinetics data for optimal dose selection in cell therapy.

- **[A Real-Time Plasma Concentration Prediction Model for Voriconazole in Elderly Patients via Machine Learning Combined with Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40401163/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025
	- Summary: Machine learning combined with population pharmacokinetics to develop a real-time plasma concentration prediction model for voriconazole in elderly patients.

- **[Dosing prediction of valproic acid in pediatric patients with epilepsy: population pharmacokinetic model or machine learning model?](https://pubmed.ncbi.nlm.nih.gov/40617982/)**
	- Methodology: Neural networks
	- Published: 2025Sep
	- Summary: This study compares population pharmacokinetic models with neural networks to predict valproic acid concentrations and optimize dosing in pediatric epilepsy patients.

- **[Optimizing Initial Vancomycin Dosing in Hospitalized Patients Using Machine Learning Approach for Enhanced Therapeutic Outcomes: Algorithm Development and Validation Study.](https://pubmed.ncbi.nlm.nih.gov/40163845/)**
	- Methodology: Supervised learning
	- Published: 2025Mar31
	- Summary: Machine learning approach is used to develop and validate an algorithm for optimizing initial vancomycin dosing in hospitalized patients to enhance therapeutic outcomes.

- **[A deep learning model to predict dose distributions for breast cancer radiotherapy.](https://pubmed.ncbi.nlm.nih.gov/39937302/)**
	- Methodology: Deep learning
	- Published: 2025Feb12
	- Summary: A 3D U-Net deep learning model is developed to predict dose distributions for breast cancer radiotherapy treatment planning.

- **[Deep reinforcement learning for multi-targets propofol dosing.](https://pubmed.ncbi.nlm.nih.gov/40045084/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2025Jun
	- Summary: This paper applies deep reinforcement learning (TD3 algorithm) to automate propofol dosing for maintaining multiple physiological parameters within safe ranges during anesthesia.

- **[RSM and AI based machine learning for quality by design development of rivaroxaban push-pull osmotic tablets and its PBPK modeling.](https://pubmed.ncbi.nlm.nih.gov/40050302/)**
	- Methodology: Neural networks, Surrogate modeling
	- Published: 2025Mar07
	- Summary: ANN-based machine learning is used alongside RSM to optimize rivaroxaban osmotic tablet formulations, with PBPK modeling to predict in vivo performance.

- **[Long short-term memory algorithm for personalized tacrolimus dosing: A simple and effective time series forecasting approach post-lung transplantation.](https://pubmed.ncbi.nlm.nih.gov/39510206/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Mar
	- Summary: Uses LSTM neural networks for time series forecasting to predict tacrolimus trough levels and optimize dosing in lung transplant patients.

- **[Estimation of Ganciclovir Exposure in Adults Transplant Patients by Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40021573/)**
	- Methodology: Supervised learning
	- Published: 2025Feb28
	- Summary: Machine learning algorithms are trained and validated to accurately estimate ganciclovir AUC0-24h exposure in solid organ transplant patients for improved dosing.

- **[Machine learning and population pharmacokinetics: a hybrid approach for optimizing vancomycin therapy in sepsis patients.](https://pubmed.ncbi.nlm.nih.gov/40162774/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models
	- Published: 2025Mar31
	- Summary: This study compares PPK, Bayesian, ML, and hybrid PPK-ML models for predicting vancomycin AUC24 to optimize dosing in sepsis patients using machine learning approaches.

- **[Comparing Scientific Machine Learning With Population Pharmacokinetic and Classical Machine Learning Approaches for Prediction of Drug Concentrations.](https://pubmed.ncbi.nlm.nih.gov/39921335/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025Apr
	- Summary: The paper compares a scientific machine learning framework (MMPK-SciML) with classical ML and population PK models for predicting drug plasma concentrations using fluorouracil and sunitinib datasets.

## Drug repurposing

- **[AI-driven discovery of brain-penetrant Galectin-3 inhibitors for Alzheimer's disease therapy.](https://pubmed.ncbi.nlm.nih.gov/40543907/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: AI-driven virtual screening platform was used to discover and prioritize novel brain-penetrant Galectin-3 inhibitors for Alzheimer's disease therapy.

- **[In-silico investigation integrated with machine learning to identify potential inhibitors targeting AKT2: Key driver of cancer cell progression and metastasis.](https://pubmed.ncbi.nlm.nih.gov/40305999/)**
	- Methodology: Supervised learning
	- Published: 2025Jul
	- Summary: Machine learning is integrated with in-silico methods to identify potential AKT2 inhibitors for cancer treatment, focusing on drug discovery and repurposing applications.

- **[Discovery of Mangifera indica-based natural inhibitors against TEM-1 β-lactamase from Escherichia coli using machine learning approaches.](https://pubmed.ncbi.nlm.nih.gov/41297205/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2026Feb
	- Summary: Deep learning neural network trained on 220 compounds to identify Mangifera indica phytochemicals as potential TEM-1 β-lactamase inhibitors for antimicrobial resistance.

- **[Discovery of selective TLR9 antagonists via machine learning-driven structural modeling and experimental validation.](https://pubmed.ncbi.nlm.nih.gov/41371528/)**
	- Methodology: Supervised learning
	- Published: 2026Jan
	- Summary: Machine learning QSAR classifiers combined with molecular modeling to discover novel selective TLR9 antagonist compounds for therapeutic applications.

- **[DualPG-DTA: A Large Language Model-Powered Graph Neural Network Framework for Enhanced Drug-Target Affinity Prediction and Discovery of Novel CDK9 Inhibitors Exhibiting in Vivo Anti-Leukemia Activity.](https://pubmed.ncbi.nlm.nih.gov/41589601/)**
	- Methodology: Deep learning, LLM, Neural networks
	- Published: 2026Jan27
	- Summary: DualPG-DTA uses large language models and graph neural networks to predict drug-target binding affinity, successfully identifying a novel CDK9 inhibitor for leukemia treatment.

- **[Single nucleus RNA sequencing profile analysis to reveal cell type specific common molecular drivers of Parkinson's disease and therapeutic agents.](https://pubmed.ncbi.nlm.nih.gov/40715263/)**
	- Methodology: Unsupervised learning
	- Published: 2025Jul25
	- Summary: Uses unsupervised clustering methods (scVI) on single-nucleus RNA sequencing data to identify molecular drivers of Parkinson's disease and suggest repurposed therapeutic drugs.

- **[Biomarker discovery and drug repurposing in hepatocellular carcinoma through transcriptomics, machine learning, network pharmacology, and molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41671946/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2026Feb08
	- Summary: Uses machine learning classifiers (XGBoost, Random Forest, SVM, Logistic Regression) with SHAP explainability to identify HCC biomarkers and explore drug repurposing opportunities.

- **[In-silico study of approved drugs as potential inhibitors against 3CLpro and other viral proteins of CoVID-19.](https://pubmed.ncbi.nlm.nih.gov/40561178/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025
	- Summary: The paper uses machine learning regression models including Decision Tree, XGBoost, and ensemble methods to predict binding affinities for drug repurposing against COVID-19 viral proteins.

- **[Multi-omics pan-cancer profiling of CDK2 and in silico identification of plant-derived inhibitors using machine learning approaches.](https://pubmed.ncbi.nlm.nih.gov/41058670/)**
	- Methodology: Supervised learning
	- Published: 2025Oct02
	- Summary: Machine learning approaches are used to screen and identify plant-derived CDK2 inhibitors for cancer treatment through cheminformatics and predictive modeling.

- **[Generating 3D Binding Molecules Using Shape-Conditioned Diffusion Models with Guidance.](https://pubmed.ncbi.nlm.nih.gov/41255553/)**
	- Methodology: Deep learning
	- Published: 2025May
	- Summary: DiffSMol uses diffusion models to generate 3D binding molecules based on ligand shapes and protein pockets for drug development applications.

- **[Decoding GuaB: Machine Learning-Powered Discovery of Enzyme Inhibitors Against the Superbug Acinetobacter baumannii.](https://pubmed.ncbi.nlm.nih.gov/41471330/)**
	- Methodology: Supervised learning
	- Published: 2025Dec02
	- Summary: Machine learning models based on chemical fingerprints were used for virtual screening to discover enzyme inhibitors against multidrug-resistant Acinetobacter baumannii.

- **[Discovery and optimization of Menin-MLL inhibitors targeting acute myeloid leukemia.](https://pubmed.ncbi.nlm.nih.gov/41666760/)**
	- Methodology: Unsupervised learning, Supervised learning
	- Published: 2026Feb05
	- Summary: Machine learning guided drug discovery using unsupervised clustering for scaffold identification and QSAR modeling to develop menin-MLL inhibitors for acute myeloid leukemia treatment.

- **[Development of Co-Amorphous Systems for Inhalation Therapy-Part 2: In Silico Guided Co-Amorphous Rifampicin-Moxifloxacin and -Ethambutol Formulations.](https://pubmed.ncbi.nlm.nih.gov/41155974/)**
	- Methodology: Supervised learning
	- Published: 2025Oct16
	- Summary: Machine learning tool identifies promising API combinations for tuberculosis therapy, combined with PBPK modeling to optimize co-amorphous formulations for inhalation delivery.

- **[In silico investigation of the efficacy of benzopyrazine derivatives on breast cancer by VEGFR2 inhibition using ML/DL based CADD software.](https://pubmed.ncbi.nlm.nih.gov/41237486/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2026Jan
	- Summary: Uses ML/DL-based CADD software to investigate benzopyrazine derivatives as VEGFR2 inhibitors for breast cancer treatment through QSAR modeling and AI-based synthesizability prediction.

- **[Computational Screening and Cytotoxic Analysis of Beta vulgaris L. phytoconstituents as potent Dengue virus-NS5 Polymerase inhibitors.](https://pubmed.ncbi.nlm.nih.gov/40645353/)**
	- Methodology: Supervised learning, Unsupervised learning, Feature selection
	- Published: 2025Oct
	- Summary: Machine learning is used for data preprocessing, gene expression analysis, and pathway enrichment to identify Beta vulgaris phytoconstituents as potential dengue virus NS5 inhibitors.

- **[Omics Integration Uncovers Mechanisms Associated with HIV Viral Load and Potential Therapeutic Insights.](https://pubmed.ncbi.nlm.nih.gov/40766151/)**
	- Methodology: Supervised learning
	- Published: 2025Jul30
	- Summary: Machine learning network biology tools (GRIN and MENTOR) integrate multi-omic datasets to identify biological mechanisms associated with HIV viral load and drug repurposing candidates.

- **[Drug repurposing targeting COVID-19 3CL protease using molecular docking and machine learning regression approaches.](https://pubmed.ncbi.nlm.nih.gov/40436944/)**
	- Methodology: Supervised learning, Tree-based models
	- Published: 2025May28
	- Summary: The paper uses machine learning regression models, particularly Decision Tree Regression, combined with molecular docking to identify potential COVID-19 drug candidates.

- **[Experimental and computational approaches for evaluating molecule interactions with equilibrative nucleoside transporters 1 and 2.](https://pubmed.ncbi.nlm.nih.gov/40779912/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Sep
	- Summary: Random forest models were built to predict ENT1/ENT2 transporter inhibition, leading to identification of FDA-approved drugs as potential repurposed inhibitors.

- **[AI-driven de novo design of BRAF inhibitors with enhanced binding affinity and optimized drug-likeness.](https://pubmed.ncbi.nlm.nih.gov/41497266/)**
	- Methodology: Deep learning
	- Published: 2026
	- Summary: AI-driven de novo design uses deep learning to create novel BRAF inhibitors with improved binding affinity and drug-likeness properties for cancer treatment.

- **[Repurposing drugs for the human dopamine transporter through WHALES descriptors-based virtual screening and bioactivity evaluation.](https://pubmed.ncbi.nlm.nih.gov/40893439/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning methods are used for virtual screening with WHALES descriptors to identify novel dopamine transporter inhibitors for drug repurposing applications.

- **[Breaking resistance with machine and deep learning: A computational intelligence hunt for AmvR (TetR) inhibitors in Acinetobacterbaumannii.](https://pubmed.ncbi.nlm.nih.gov/41442824/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2026Mar
	- Summary: Machine learning models (RF, SVM, KNN, XGBoost) and CNN deep learning were used to screen natural compounds for AmvR inhibitors against multidrug-resistant Acinetobacter baumannii.

- **[Identification of novel Menin-MLL interaction inhibitors targeting leukemia using in-silico virtual screening and structure-based drug design approaches.](https://pubmed.ncbi.nlm.nih.gov/41386877/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: The paper uses machine learning (PSICHIC model) for binding affinity prediction in virtual screening to identify novel Menin-MLL interaction inhibitors for leukemia treatment.

- **[Transfer Learning for Heterocycle Retrosynthesis.](https://pubmed.ncbi.nlm.nih.gov/40729356/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Aug11
	- Summary: The paper uses transfer learning with deep neural networks to improve retrosynthesis prediction models for heterocycle formation in drug discovery applications.

- **[Potential Inhibitors of SARS-CoV-2 Developed through Machine Learning, Molecular Docking, and MD Simulation.](https://pubmed.ncbi.nlm.nih.gov/40464176/)**
	- Methodology: Supervised learning
	- Published: 2025Jun03
	- Summary: Machine learning is used alongside molecular docking and MD simulation to identify potential SARS-CoV-2 inhibitors targeting the ACE2-spike protein interaction.

- **[Support vector machine classification-guided identification of novel monoamine oxidase-B inhibitors via structure-based modeling to treat neurodegenerative diseases.](https://pubmed.ncbi.nlm.nih.gov/40825424/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2025Sep
	- Summary: SVM classification models with molecular fingerprints were used to screen FDA-approved drugs for repurposing as novel MAO-B inhibitors to treat neurodegenerative diseases.

- **[Machine learning guided virtual screening of FDA approved drugs targeting GSK-3β in Alzheimer's disease.](https://pubmed.ncbi.nlm.nih.gov/41354678/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Dec07
	- Summary: Machine learning models, particularly Random Forest, are used to screen FDA-approved drugs for repurposing as GSK-3β inhibitors in Alzheimer's disease treatment.

- **[Computer-aided drug discovery of a dual-target inhibitor for ovarian cancer: therapeutic intervention targeting CDK1/TTK signaling pathway and structural insights in the NCI-60.](https://pubmed.ncbi.nlm.nih.gov/40446543/)**
	- Methodology: Unsupervised learning, Feature selection
	- Published: 2025Jul
	- Summary: AI-driven network modeling and multi-omics integration are used to identify and characterize a dual-target inhibitor for ovarian cancer treatment.

- **[A machine learning-Assisted QSAR and integrative computational combined with network pharmacology approach for rational identification of tankyrase inhibitors in colon adenocarcinoma.](https://pubmed.ncbi.nlm.nih.gov/40945215/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Oct
	- Summary: Machine learning with random forest classification and feature selection is used for QSAR modeling to identify novel tankyrase inhibitors for colon cancer treatment.

- **[An integrative computational approach for identification of NLRP3 inhibitors through machine learning, docking, dynamics and DFT analysis.](https://pubmed.ncbi.nlm.nih.gov/41461937/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Dec29
	- Summary: Machine learning models, particularly Random Forest, are used for virtual screening to identify phytochemical NLRP3 inhibitors for neuroinflammation treatment.

- **[Computational screening of natural products as tryptophan 2,3-dioxygenase inhibitors: Insights from CNN-based QSAR, molecular docking, ADMET, and molecular dynamics simulations.](https://pubmed.ncbi.nlm.nih.gov/40233673/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Jun
	- Summary: CNN-based QSAR models and machine learning are used to computationally screen natural products as potential TDO inhibitors for Parkinson's disease treatment.

- **[A generative AI-discovered TNIK inhibitor for idiopathic pulmonary fibrosis: a randomized phase 2a trial.](https://pubmed.ncbi.nlm.nih.gov/40461817/)**
	- Methodology: Deep learning
	- Published: 2025Aug
	- Summary: This paper reports clinical trial results for rentosertib, a TNIK inhibitor discovered using generative AI for treating idiopathic pulmonary fibrosis.

- **[Deep learning and molecular dynamics reveal promising EZH2 inhibitors for epigenetic cancer targeting.](https://pubmed.ncbi.nlm.nih.gov/41237543/)**
	- Methodology: Deep learning, Reinforcement learning
	- Published: 2026Feb
	- Summary: Deep learning generative model (REINVENT) with reinforcement learning identifies novel EZH2 inhibitors for cancer treatment through molecular generation and screening.

- **[Halicin: A New Approach to Antibacterial Therapy, a Promising Avenue for the Post-Antibiotic Era.](https://pubmed.ncbi.nlm.nih.gov/40723999/)**
	- Methodology: Supervised learning
	- Published: 2025Jul11
	- Summary: This paper evaluates halicin, an anti-diabetic compound repurposed as an antibiotic through AI screening, testing its antibacterial activity against multidrug-resistant bacteria.

- **[Developing inhibitors of the guanosine triphosphate hydrolysis accelerating activity of Regulator of G protein Signaling-14.](https://pubmed.ncbi.nlm.nih.gov/40667230/)**
	- Methodology: Deep learning
	- Published: 2025Aug09
	- Summary: The paper uses structure-guided virtual screening, ligand docking, and deep learning-based scoring to develop inhibitors of RGS14 protein for drug discovery.

- **[AI-assisted identification of innovative phytochemicals from Aizoon canariense aimed at brachyury protein in chordoma: a computational strategy.](https://pubmed.ncbi.nlm.nih.gov/41419749/)**
	- Methodology: Deep learning
	- Published: 2025Dec19
	- Summary: AI-assisted drug discovery approach used to optimize phytochemicals from Aizoon canariense for targeting TBXT protein in chordoma treatment.

- **[Elucidation of Artemisinin as a Potent GSK3β Inhibitor for Neurodegenerative Disorders via Machine Learning-Driven QSAR and Virtual Screening of Natural Compounds.](https://pubmed.ncbi.nlm.nih.gov/40573222/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025May31
	- Summary: Machine learning models (SVM, RF, KNN) with feature selection were used for virtual screening to identify artemisinin as a potent GSK3β inhibitor for neurodegenerative disorders.

- **[Deep learning-guided discovery of selective JAK2-JH2 allosteric inhibitors: integration of MLP predictive modeling, BREED-based library design, and computational validation.](https://pubmed.ncbi.nlm.nih.gov/41404389/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025
	- Summary: Deep learning MLP model trained on JAK2 compounds to predict and discover selective allosteric inhibitors through computational screening and molecular design.

- **[Neurotherapeutics across blood-brain barrier: screening of BBB-permeable and CNS-active molecules for neurodegenerative disease.](https://pubmed.ncbi.nlm.nih.gov/41079713/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning models are used to predict blood-brain barrier permeability and CNS activity for screening neurotherapeutic molecules in neurodegenerative disease drug discovery.

- **[Crystal engineering optimizes emodin-tetramethylpyrazine combination: From cocrystal design to in vivo anti-colitis efficacy assessment.](https://pubmed.ncbi.nlm.nih.gov/41323843/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: Machine learning was used to assess cocrystallization propensity for rational design of an emodin-tetramethylpyrazine cocrystal to improve bioavailability for ulcerative colitis treatment.

- **[Bioactive structures for inhibitors of Candida auris polymerase enzyme by artificial intelligence.](https://pubmed.ncbi.nlm.nih.gov/40247646/)**
	- Methodology: Deep learning
	- Published: 2025Apr
	- Summary: The paper uses AI and de novo drug design to create new bioactive compounds as potential inhibitors of C. auris polymerase enzyme.

- **[AI-powered literature mining reveals the therapeutic significance of GLP-1 receptor: Simulation of natural agonist candidates based on molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41389576/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2026Apr
	- Summary: AI-integrated pipeline using BioBERT text mining and ML-guided ADMET profiling to identify natural GLP-1 receptor agonist candidates through virtual screening and molecular dynamics.

- **[Drug repurposing of natural depsipeptide from Eleftheria terrae isolated via iChip for anti-breast cancer therapy.](https://pubmed.ncbi.nlm.nih.gov/41221054/)**
	- Methodology: Deep learning
	- Published: 2025
	- Summary: The paper uses AI for drug repurposing of natural depsipeptides for anti-breast cancer therapy, incorporating clinical trial simulation and multimodal health records analysis.

- **[Circumventing glioblastoma resistance to temozolomide through optimal drug combinations designed by systems pharmacology and machine learning.](https://pubmed.ncbi.nlm.nih.gov/40229949/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning is used alongside systems pharmacology to design optimal drug combinations for overcoming temozolomide resistance in glioblastoma treatment.

- **[Ai derivation and exploration of antibiotic class spaces.](https://pubmed.ncbi.nlm.nih.gov/41546122/)**
	- Methodology: Unsupervised learning
	- Published: 2026Jan16
	- Summary: AI methods are used to systematically explore and generate compounds within antibiotic chemical spaces for automated discovery of new antibiotic candidates.

- **[AI-Driven Discovery and Optimization of Positive Allosteric Modulators for NMDA Receptors: Potential Applications in Depression.](https://pubmed.ncbi.nlm.nih.gov/40741898/)**
	- Methodology: Deep learning
	- Published: 2025Aug14
	- Summary: AI-assisted optimization and structure-based virtual screening were used to discover and optimize positive allosteric modulators for NMDA receptors as potential antidepressants.

- **[Exploring the mechanism of Stephania tetrandra S. Moore in the treatment of cisplatin resistance against ovarian cancer through integration of network pharmacology and molecular docking.](https://pubmed.ncbi.nlm.nih.gov/41239601/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Nov14
	- Summary: Machine learning algorithms were integrated to identify core targets for Stephania tetrandra treatment of cisplatin-resistant ovarian cancer through network pharmacology analysis.

- **[An innovative machine learning-based QSAR approach for prediction and structural analysis of novel/repurposed acid ceramidase (ASAH1) inhibitors for glioblastoma therapy.](https://pubmed.ncbi.nlm.nih.gov/40682750/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul19
	- Summary: ML-QSAR approach using extra trees regressor and SHAP analysis to predict and identify novel ASAH1 inhibitors for glioblastoma therapy through virtual screening.

- **[Designing new hit series of JAK3 inhibitors using generative AI, reinforcement learning, and molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41125009/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2025Nov
	- Summary: This paper uses generative AI and reinforcement learning to design novel JAK3 inhibitors, generating new molecular scaffolds and optimizing compounds for drug development.

- **[Targeting the core: C9ORF72 antagonists as pioneers in amyotrophic lateral sclerosis therapy-a computational and machine learning based approach.](https://pubmed.ncbi.nlm.nih.gov/41282964/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Uses machine learning-based tools for high throughput virtual screening to identify potential C9ORF72 agonists as therapeutic compounds for ALS treatment.

- **[Integration of artificial intelligence and high-content screening enabled identification of drugs for long-term treatment of cerebral cavernous malformation disease.](https://pubmed.ncbi.nlm.nih.gov/41427327/)**
	- Methodology: Supervised learning
	- Published: 2025Dec11
	- Summary: AI integrated with high-content screening to identify existing drugs for repurposing as long-term treatments for cerebral cavernous malformation disease.

- **[Artificial Intelligence Driven Virtual Screening and Molecular Docking Approaches Identified LIFR, BTG2, EPHX2, and PAK3 as Targets and BI-2536, AP-24534, and AZ-628 as Repurposed Drugs for PDAC.](https://pubmed.ncbi.nlm.nih.gov/41605175/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2026Jan28
	- Summary: AI algorithms including SVM, logistic regression, random forest, XGB, and CNN are used for gene ranking and identification of differentially expressed genes in PDAC for drug repurposing.

- **[Decoding the gut microbiota metabolite-matrix metalloproteinase-3 axis in breast cancer: a multi-omics and network pharmacology study.](https://pubmed.ncbi.nlm.nih.gov/40946247/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Sep14
	- Summary: This study uses machine learning with SHAP explainability to identify gut microbiota metabolites as potential therapeutic targets for breast cancer treatment via MMP3 axis.

- **[Unveiling Berberine analogues as potential inhibitors of Escherichia coli FtsZ through machine learning molecular docking and molecular dynamics approach.](https://pubmed.ncbi.nlm.nih.gov/40287515/)**
	- Methodology: Supervised learning
	- Published: 2025Apr26
	- Summary: Machine learning is used to screen berberine analogues for drug-likeness and toxicity prediction, combined with molecular docking to identify potential FtsZ inhibitors.

- **[AI-driven peptide discovery for endometrial cancer: deep generative modeling and molecular simulation in the big data era.](https://pubmed.ncbi.nlm.nih.gov/41524971/)**
	- Methodology: Deep learning, Reinforcement learning, Neural networks
	- Published: 2026Jan12
	- Summary: AI-driven pipeline using deep reinforcement learning, GANs, and VAEs to generate and screen novel peptide-like molecules for endometrial cancer treatment.

- **[Using Machine Learning for the Discovery and Development of Multitarget Flavonoid-Based Functional Products in MASLD.](https://pubmed.ncbi.nlm.nih.gov/41226123/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Oct22
	- Summary: Machine learning ensemble methods (Random Forest, XGBoost, CatBoost) are used to predict bioactivity of flavonoids against MASLD targets for nutraceutical product development.

- **[Computational Evaluation of Potential c-Abl Kinase Inhibitors for Parkinson's Disease: QSAR, Docking, Bioisosteric Replacement, ADMET, and MD Simulations.](https://pubmed.ncbi.nlm.nih.gov/41148549/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: Machine learning-based QSAR modeling is used to identify and optimize potential c-Abl kinase inhibitors for Parkinson's disease treatment through computational screening and evaluation.

- **[Integrated machine learning and deep learning-based virtual screening framework identifies novel natural GSK-3β inhibitors for Alzheimer's disease.](https://pubmed.ncbi.nlm.nih.gov/40668407/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Explainable AI
	- Published: 2025Jul16
	- Summary: Integrates random forest and deep learning for virtual screening to identify natural GSK-3β inhibitors for Alzheimer's disease using SHAP for model interpretability.

- **[Uralenol, Glycyrol, and Abyssinone II as potent inhibitors of fibroblast growth factor receptor 2 from anti-cancer plants: A deep learning and molecular dynamics approach.](https://pubmed.ncbi.nlm.nih.gov/41615925/)**
	- Methodology: Deep learning
	- Published: 2026
	- Summary: Deep learning models are used to predict pIC50 values and identify potential FGFR2 inhibitors from phytochemicals for cancer treatment applications.

- **[Machine learning-guided identification and simulation-based validation of potent JAK3 inhibitors for cancer therapy.](https://pubmed.ncbi.nlm.nih.gov/41385500/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025
	- Summary: Machine learning classifiers, particularly Random Forest, are used to virtually screen compounds and identify novel JAK3 inhibitors for cancer therapy through computational drug discovery.

- **[Developing inhibitors of the guanosine triphosphate hydrolysis accelerating activity of Regulator of G protein Signaling-14.](https://pubmed.ncbi.nlm.nih.gov/40848973/)**
	- Methodology: Deep learning
	- Published: 2025Oct
	- Summary: The paper uses structure-guided virtual screening, ligand docking, and deep learning-based scoring to develop inhibitors of RGS14 protein for drug discovery.

- **[Integrating machine learning with in silico studies and Quantum Chemistry: Exploring novel compounds through multiscale screening targeting the CDK2 enzyme.](https://pubmed.ncbi.nlm.nih.gov/40639010/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Sep
	- Summary: Random forest machine learning is used to screen 477,975 molecules for potential CDK2 enzyme inhibitors, integrating ML with molecular docking and quantum chemistry studies.

- **[Deep Supramolecular Language Processing for Co-Crystal Prediction.](https://pubmed.ncbi.nlm.nih.gov/40358977/)**
	- Methodology: Deep learning, Explainable AI
	- Published: 2025Jul
	- Summary: DeepCocrystal uses deep learning to predict co-crystal formation for improving drug physicochemical properties, with explainable AI to understand decision-making processes.

- **[Discovery of novel polymyxin E adjuvants against Acinetobacter baumannii guided by a stacking-based machine learning model.](https://pubmed.ncbi.nlm.nih.gov/41522627/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2026Jan04
	- Summary: Machine learning stacking model combining random forest and gradient boosting to screen compounds for polymyxin E adjuvants against antibiotic-resistant bacteria.

- **[AI fragment based optimization of saffron and chamomile phytochemicals as aryl hydrocarbon receptor inhibitors for dementia therapy an integrated computational approach.](https://pubmed.ncbi.nlm.nih.gov/40784071/)**
	- Methodology: Deep learning
	- Published: 2026Feb
	- Summary: AI generative models are used to optimize phytochemicals from saffron and chamomile as aryl hydrocarbon receptor inhibitors for dementia therapy through fragment-based optimization.

- **[Integrated AI and machine learning pipeline identifies novel WEE1 kinase inhibitors for targeted cancer therapy.](https://pubmed.ncbi.nlm.nih.gov/40106128/)**
	- Methodology: Unsupervised learning, Feature selection
	- Published: 2025Aug
	- Summary: AI-driven pipeline using MORLD platform, UMAP dimensionality reduction, and K-means clustering to identify novel WEE1 kinase inhibitors for targeted cancer therapy.

- **[Drug repurposing through Biophysical Insights: Focus on Indoleamine 2,3-Dioxygenase and Tryptophan 2,3-Dioxygenase Dual Inhibitors.](https://pubmed.ncbi.nlm.nih.gov/40133710/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: This paper uses machine learning analysis alongside molecular docking to repurpose FDA-approved drugs as dual IDO1/TDO inhibitors for cancer treatment.

- **[Intestinal mucosal barrier repair and immune regulation with an AI-developed gut-restricted PHD inhibitor.](https://pubmed.ncbi.nlm.nih.gov/39663371/)**
	- Methodology: Deep learning
	- Published: 2025Nov
	- Summary: The paper uses a multimodel multimodal generative AI platform to design a gut-restricted PHD inhibitor for treating inflammatory bowel disease.

- **[Pan-cancer analysis of CDC7 in human tumors: Integrative multi-omics insights and discovery of novel marine-based inhibitors through machine learning and computational approaches.](https://pubmed.ncbi.nlm.nih.gov/40120182/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: Machine learning is used to screen marine-derived compounds for CDC7 inhibitors and predict their toxicity, combined with pan-cancer analysis of CDC7 as a therapeutic target.

- **[Unveiling the molecular mechanisms of Haitang-Xiaoyin Mixture in psoriasis treatment based on bioinformatics, network pharmacology, machine learning, and molecular docking verification.](https://pubmed.ncbi.nlm.nih.gov/39993869/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: The paper uses machine learning alongside bioinformatics and network pharmacology to identify molecular mechanisms and targets of a traditional Chinese medicine for psoriasis treatment.

- **[Therapeutic Mechanisms of Medicine Food Homology Plants in Alzheimer's Disease: Insights from Network Pharmacology, Machine Learning, and Molecular Docking.](https://pubmed.ncbi.nlm.nih.gov/40076742/)**
	- Methodology: Unsupervised learning
	- Published: 2025Feb27
	- Summary: Uses hierarchical clustering to group small molecules from medicinal plants and applies machine learning algorithms to predict binding capabilities for Alzheimer's disease treatment.

- **[Probing the dark chemical matter against PDE4 for the management of psoriasis using in silico, in vitro and in vivo approach.](https://pubmed.ncbi.nlm.nih.gov/40095248/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning and AI were used for pharmacokinetics optimization in discovering novel PDE4D inhibitors from dark chemical matter for psoriasis treatment.

- **[Integrating machine learning and structural dynamics to explore B-cell lymphoma-2 inhibitors for chronic lymphocytic leukemia therapy.](https://pubmed.ncbi.nlm.nih.gov/39786521/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Aug
	- Summary: Machine learning models (Random Forest, SVM, ANN) are used to screen and identify novel BCL-2 inhibitors from ChEMBL database for chronic lymphocytic leukemia therapy.

- **[Machine Learning-Based High-Throughput Screening, Molecular Modeling and Quantum Chemical Analysis to Investigate Mycobacterium tuberculosis MetRS Inhibitors.](https://pubmed.ncbi.nlm.nih.gov/39996268/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning algorithms including Random Forest, Extra Trees, and Nu-Support Vector are used in a voting classifier to screen 10 million molecules for Mtb MetRS inhibitors.

## Drug toxicity prediction

- **[MolP-PC: a multi-view fusion and multi-task learning framework for drug ADMET property prediction.](https://pubmed.ncbi.nlm.nih.gov/41260779/)**
	- Methodology: Deep learning, Neural networks, Ensemble learning
	- Published: 2025Nov
	- Summary: Deep learning framework using multi-view fusion and multi-task learning to predict drug ADMET properties from molecular representations.

- **[DualPG-DTA: A Large Language Model-Powered Graph Neural Network Framework for Enhanced Drug-Target Affinity Prediction and Discovery of Novel CDK9 Inhibitors Exhibiting in Vivo Anti-Leukemia Activity.](https://pubmed.ncbi.nlm.nih.gov/41589601/)**
	- Methodology: Deep learning, LLM, Neural networks
	- Published: 2026Jan27
	- Summary: DualPG-DTA uses large language models and graph neural networks to predict drug-target binding affinity, successfully identifying a novel CDK9 inhibitor for leukemia treatment.

- **[Advancing ADMET prediction through multiscale fragment-aware pretraining with MSformer-ADMET.](https://pubmed.ncbi.nlm.nih.gov/41021261/)**
	- Methodology: Deep learning
	- Published: 2025Aug31
	- Summary: MSformer-ADMET uses Transformer-based deep learning with multiscale fragment-aware pretraining to predict ADMET properties for drug development.

- **[Multi-omics pan-cancer profiling of CDK2 and in silico identification of plant-derived inhibitors using machine learning approaches.](https://pubmed.ncbi.nlm.nih.gov/41058670/)**
	- Methodology: Supervised learning
	- Published: 2025Oct02
	- Summary: Machine learning approaches are used to screen and identify plant-derived CDK2 inhibitors for cancer treatment through cheminformatics and predictive modeling.

- **[Design, synthesis, deep learning-guided prediction, and biological evaluation of novel pyridine-thiophene-based imine-benzalacetophenone hybrids as promising antimicrobial agent.](https://pubmed.ncbi.nlm.nih.gov/41186782/)**
	- Methodology: Deep learning, Neural networks, Explainable AI
	- Published: 2025Nov04
	- Summary: Deep learning neural network with SHAP analysis predicts antimicrobial activity (pMIC values) of novel pyridine-thiophene hybrid compounds for drug development.

- **[In silico investigation of the efficacy of benzopyrazine derivatives on breast cancer by VEGFR2 inhibition using ML/DL based CADD software.](https://pubmed.ncbi.nlm.nih.gov/41237486/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2026Jan
	- Summary: Uses ML/DL-based CADD software to investigate benzopyrazine derivatives as VEGFR2 inhibitors for breast cancer treatment through QSAR modeling and AI-based synthesizability prediction.

- **[From chemical to mechanism-driven quality control of Glehniae Radix: spectrum effect - chemometrics-pharmacology integration decoding antioxidant-anti-inflammatory crosstalk.](https://pubmed.ncbi.nlm.nih.gov/40922625/)**
	- Methodology: Tree-based models, Feature selection
	- Published: 2025Sep25
	- Summary: Random forest algorithm is used to optimize spectrum-effect relationships and predict bioactive constituents for quality control of Glehniae Radix herbal medicine.

- **[Expert-Guided Substructure Information Bottleneck for Molecular Property Prediction.](https://pubmed.ncbi.nlm.nih.gov/40702819/)**
	- Methodology: Deep learning, Ensemble learning, Neural networks
	- Published: 2025Aug11
	- Summary: Proposes ESIB-Mol framework combining Mixture of Experts with Information Bottleneck principle for molecular property prediction using substructure-specific experts.

- **[In silico evaluation of pharmacokinetic properties and molecular docking for the identification of potential anticancer compounds.](https://pubmed.ncbi.nlm.nih.gov/40803051/)**
	- Methodology: Supervised learning
	- Published: 2026Feb
	- Summary: The paper uses in silico methods including QSAR/SAR/QSPR for predicting ADME-Tox properties and identifying potential anticancer compounds through molecular docking.

- **[Computational Screening and Cytotoxic Analysis of Beta vulgaris L. phytoconstituents as potent Dengue virus-NS5 Polymerase inhibitors.](https://pubmed.ncbi.nlm.nih.gov/40645353/)**
	- Methodology: Supervised learning, Unsupervised learning, Feature selection
	- Published: 2025Oct
	- Summary: Machine learning is used for data preprocessing, gene expression analysis, and pathway enrichment to identify Beta vulgaris phytoconstituents as potential dengue virus NS5 inhibitors.

- **[Discovery of Bergamotanes against Hepatic Ischemia-Reperfusion Injury Based on DeepSAT Technology from Paraconiothyrium sp. H-B.](https://pubmed.ncbi.nlm.nih.gov/41283635/)**
	- Methodology: Neural networks
	- Published: 2025Dec10
	- Summary: The paper uses DeepSAT, a neural network-based tool for HSQC spectrum analysis, to guide discovery of bergamotane compounds with hepatoprotective effects against liver injury.

- **[Pushing the boundaries of few-shot learning for low-data drug discovery with a Bayesian meta-learning hypernetwork framework.](https://pubmed.ncbi.nlm.nih.gov/40814226/)**
	- Methodology: Deep learning, Bayesian ML
	- Published: 2025Jul02
	- Summary: Meta-Mol uses Bayesian meta-learning with hypernetworks for few-shot learning to predict molecular properties in drug discovery with limited data.

- **[MetaboGNN: predicting liver metabolic stability with graph neural networks and cross-species data.](https://pubmed.ncbi.nlm.nih.gov/40903787/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Sep03
	- Summary: MetaboGNN uses Graph Neural Networks with contrastive learning to predict liver metabolic stability across species, improving drug discovery predictions.

- **[Discovery of newer 1,3,4-Oxadiazole clubbed Isoindoline-1,3-dione derivatives as potential anticancer agents: Design, machine learning, synthesis, molecular docking, ADMET, DFT and MD simulation.](https://pubmed.ncbi.nlm.nih.gov/40306097/)**
	- Methodology: Supervised learning
	- Published: 2025Oct
	- Summary: Machine learning is used to predict IC50 values for anticancer drug candidates in the design and discovery of novel 1,3,4-Oxadiazole clubbed Isoindoline-1,3-dione derivatives.

- **[Explainable Reasoning Path Inference of Anti-Cancer Drug Sensitivity on Genomic Knowledge Graph via Macro-Micro Agent Collaborative Reinforcement Learning.](https://pubmed.ncbi.nlm.nih.gov/40920533/)**
	- Methodology: Reinforcement learning, Deep learning, Explainable AI, AI Agents
	- Published: 2025Nov-Dec
	- Summary: The paper develops a dual-agent reinforcement learning system using knowledge graphs to predict anticancer drug sensitivity with explainable reasoning paths for precision medicine.

- **[Machine Learning Models and Structure-Based Antibacterial Drug Discovery of the Key ABC Transporter Maltose-Binding Protein A.](https://pubmed.ncbi.nlm.nih.gov/40583298/)**
	- Methodology: Supervised learning, Neural networks
	- Published: 2025Jun
	- Summary: ML-QSAR models using GFA, SVM, and ANN predict antibacterial activity of quinoline-based MsbA inhibitors to discover new drugs against multidrug-resistant bacteria.

- **[Computer-Aided optimization of quinazoline-based Aurora kinase inhibitors for enhanced metabolic stability.](https://pubmed.ncbi.nlm.nih.gov/41512537/)**
	- Methodology: Supervised learning
	- Published: 2026Mar05
	- Summary: Machine learning models were used to predict metabolic sites of quinazoline-based Aurora kinase inhibitors to guide optimization for enhanced metabolic stability.

- **[Prediction of Internal Exposures after Virtual Oral Doses of Disparate Chemicals in Rats and Humans Using Simplified Physiologically Based Pharmacokinetic Models with In Silico-Generated Input Parameters.](https://pubmed.ncbi.nlm.nih.gov/40628652/)**
	- Methodology: Supervised learning
	- Published: 2025Jul21
	- Summary: Uses machine learning to generate PBPK model input parameters from chemical descriptors for predicting internal exposures of diverse compounds in rats and humans.

- **[RCAN-DDI: Relation-aware cross adversarial network for drug-drug interaction prediction.](https://pubmed.ncbi.nlm.nih.gov/41079788/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Sep
	- Summary: The paper proposes RCAN-DDI, a deep learning model using adversarial networks to predict drug-drug interactions by integrating structural and topological drug features.

- **[Research on the optimization model of anti-breast cancer candidate drugs based on machine learning.](https://pubmed.ncbi.nlm.nih.gov/40276676/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025
	- Summary: Machine learning models including Random Forest, LightGBM, and XGBoost with SHAP explainability are used to optimize anti-breast cancer drug candidates for biological activity and ADMET properties.

- **[Repurposing drugs for the human dopamine transporter through WHALES descriptors-based virtual screening and bioactivity evaluation.](https://pubmed.ncbi.nlm.nih.gov/40893439/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning methods are used for virtual screening with WHALES descriptors to identify novel dopamine transporter inhibitors for drug repurposing applications.

- **[Prediction of pharmacokinetic/pharmacodynamic properties of aldosterone synthase inhibitors at drug discovery stage using an artificial intelligence-physiologically based pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40356995/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: An AI-PBPK model integrating machine learning with classical PBPK modeling is developed to predict PK/PD properties of aldosterone synthase inhibitors for drug discovery screening.

- **[Breaking resistance with machine and deep learning: A computational intelligence hunt for AmvR (TetR) inhibitors in Acinetobacterbaumannii.](https://pubmed.ncbi.nlm.nih.gov/41442824/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2026Mar
	- Summary: Machine learning models (RF, SVM, KNN, XGBoost) and CNN deep learning were used to screen natural compounds for AmvR inhibitors against multidrug-resistant Acinetobacter baumannii.

- **[Guided Ensemble Stacking Method for Predicting Biological Activities of Compounds.](https://pubmed.ncbi.nlm.nih.gov/41457256/)**
	- Methodology: Ensemble learning, Supervised learning
	- Published: 2025Dec
	- Summary: The paper develops a guided ensemble stacking ML approach combining multiple algorithms to predict compound biological activities for improved drug discovery.

- **[Machine learning guided virtual screening of FDA approved drugs targeting GSK-3β in Alzheimer's disease.](https://pubmed.ncbi.nlm.nih.gov/41354678/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Dec07
	- Summary: Machine learning models, particularly Random Forest, are used to screen FDA-approved drugs for repurposing as GSK-3β inhibitors in Alzheimer's disease treatment.

- **[A multi-compartment physiologically based pharmacokinetic (PBPK) model coupled with Fourier-ARIMA (auto regressive integrated moving average) for estimation and prediction of polychlorinated biphenyls (PCB) concentration in tuna.](https://pubmed.ncbi.nlm.nih.gov/40577972/)**
	- Methodology: Hybrid mechanistic–ML models, Time-series modeling
	- Published: 2025Sep
	- Summary: The paper develops a hybrid PBPK-Fourier-ARIMA model to predict PCB concentrations in tuna tissues, combining mechanistic modeling with time-series analysis for contamination forecasting.

- **[A Machine Learning-Empowered Quantitative Structure-Activity Relationship Model for Predicting the Plasma Half-life of Drugs in Dogs.](https://pubmed.ncbi.nlm.nih.gov/41254440/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov18
	- Summary: Deep neural networks and supervised ML algorithms are used to build QSAR models predicting drug plasma half-life in dogs from chemical structure descriptors.

- **[Integrative Profiling for BBB Permeability Using Capillary Electrochromatography, Experimental Physicochemical Parameters, and Ensemble Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/41516205/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Dec28
	- Summary: The paper uses ensemble machine learning methods including k-NN and time series classification to predict blood-brain barrier permeability from experimental data.

- **[Computer-aided drug discovery of a dual-target inhibitor for ovarian cancer: therapeutic intervention targeting CDK1/TTK signaling pathway and structural insights in the NCI-60.](https://pubmed.ncbi.nlm.nih.gov/40446543/)**
	- Methodology: Unsupervised learning, Feature selection
	- Published: 2025Jul
	- Summary: AI-driven network modeling and multi-omics integration are used to identify and characterize a dual-target inhibitor for ovarian cancer treatment.

- **[Analytical and machine learning approaches identify a sea star steroid with promising activity for COVID-19 therapeutic development.](https://pubmed.ncbi.nlm.nih.gov/41057530/)**
	- Methodology: Supervised learning
	- Published: 2025Oct07
	- Summary: The paper develops a machine learning-based web application to predict IC50 values of SARS-CoV-2 inhibitors for drug discovery screening.

- **[IQSPred-PLM: An Interpretable Quorum Sensing Peptides Prediction Model Based on Protein Language Model.](https://pubmed.ncbi.nlm.nih.gov/40859107/)**
	- Methodology: Deep learning, Neural networks, LLM, Explainable AI
	- Published: 2025Aug26
	- Summary: The paper presents IQSPred-PLM, which uses protein language models (ESM-2) and CNNs to predict quorum sensing peptides for understanding bacterial regulation mechanisms.

- **[Machine Learning Models of Early Longitudinal Toxicity Trajectories Predict Cetuximab Concentration and Metastatic Colorectal Cancer Survival in the Canadian Cancer Trials Group/AGITG CO.17/20 Trials.](https://pubmed.ncbi.nlm.nih.gov/40215447/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: Machine learning models analyze early toxicity trajectories to predict cetuximab concentration and survival outcomes in metastatic colorectal cancer patients.

- **[Machine learning approaches for assessing medication transfer to human breast milk.](https://pubmed.ncbi.nlm.nih.gov/40240653/)**
	- Methodology: Supervised learning, Neural networks, Tree-based models, Feature selection
	- Published: 2025Apr16
	- Summary: Machine learning algorithms including KNN, Random Forest, SVM, and Neural Networks are used to predict milk/plasma drug concentration ratios for breastfeeding safety assessment.

- **[Prediction of High-Dose Methotrexate Blood Concentration in Osteosarcoma Patients Using Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40336661/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025
	- Summary: Uses interpretable machine learning to predict high-dose methotrexate blood concentrations in osteosarcoma patients for early exposure prediction and toxicity prevention.

- **[A machine learning-Assisted QSAR and integrative computational combined with network pharmacology approach for rational identification of tankyrase inhibitors in colon adenocarcinoma.](https://pubmed.ncbi.nlm.nih.gov/40945215/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Oct
	- Summary: Machine learning with random forest classification and feature selection is used for QSAR modeling to identify novel tankyrase inhibitors for colon cancer treatment.

- **[Enhancing Severe Neutropenia Prediction: PKPD-Informed Labeling for Machine Learning Models Trained on Real-World Data.](https://pubmed.ncbi.nlm.nih.gov/41208554/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models
	- Published: 2026Feb
	- Summary: PKPD-informed labeling strategy enhances machine learning models (logistic regression, XGBoost, TabPFN) for predicting docetaxel-induced severe neutropenia using real-world data.

- **[An integrative computational approach for identification of NLRP3 inhibitors through machine learning, docking, dynamics and DFT analysis.](https://pubmed.ncbi.nlm.nih.gov/41461937/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Dec29
	- Summary: Machine learning models, particularly Random Forest, are used for virtual screening to identify phytochemical NLRP3 inhibitors for neuroinflammation treatment.

- **[Multimodal profiling of Pepcan-CB1 receptor structure-activity relationships: integrating molecular dynamics simulations, biological profiling, and the deep learning model MuMoPepcan.](https://pubmed.ncbi.nlm.nih.gov/41005111/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models
	- Published: 2025Oct
	- Summary: Deep learning model MuMoPepcan integrates molecular dynamics simulations with experimental data to predict pepcan peptide bioactivity for CB1 receptor drug discovery.

- **[Integrating Pharmacokinetics and Quantitative Systems Pharmacology Approaches in Generative Drug Design.](https://pubmed.ncbi.nlm.nih.gov/40343729/)**
	- Methodology: Reinforcement learning, Supervised learning
	- Published: 2025May26
	- Summary: The paper integrates AI/ML methods including reinforcement learning and QSPR models in a generative drug design framework to optimize both PK properties and receptor affinity.

- **[Computational screening of natural products as tryptophan 2,3-dioxygenase inhibitors: Insights from CNN-based QSAR, molecular docking, ADMET, and molecular dynamics simulations.](https://pubmed.ncbi.nlm.nih.gov/40233673/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Jun
	- Summary: CNN-based QSAR models and machine learning are used to computationally screen natural products as potential TDO inhibitors for Parkinson's disease treatment.

- **[Artificial intelligence generated 3D body composition predicts dose modifications in patients undergoing neoadjuvant chemotherapy for rectal cancer.](https://pubmed.ncbi.nlm.nih.gov/40379920/)**
	- Methodology: Deep learning
	- Published: 2025May16
	- Summary: AI-generated 3D body composition analysis is used to predict chemotherapy dose modifications and adverse events in rectal cancer patients receiving neoadjuvant therapy.

- **[QSAR Prediction of BBB Permeability Based on Machine Learning upon PETBD: A Novel Data Set of PET Tracers.](https://pubmed.ncbi.nlm.nih.gov/41494098/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI
	- Published: 2026Jan22
	- Summary: Machine learning models, particularly extreme gradient boosting, predict blood-brain barrier permeability and brain drug concentrations using a novel PET tracer dataset.

- **[Prediction of plasma concentration-time profiles in mice using deep neural network integrated with pharmacokinetic models.](https://pubmed.ncbi.nlm.nih.gov/40250502/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Neural networks, Explainable AI
	- Published: 2025May15
	- Summary: Deep neural networks integrated with two-compartmental PK models to predict plasma concentration-time profiles in mice using chemical structure and ADME features.

- **[Deep learning and molecular dynamics reveal promising EZH2 inhibitors for epigenetic cancer targeting.](https://pubmed.ncbi.nlm.nih.gov/41237543/)**
	- Methodology: Deep learning, Reinforcement learning
	- Published: 2026Feb
	- Summary: Deep learning generative model (REINVENT) with reinforcement learning identifies novel EZH2 inhibitors for cancer treatment through molecular generation and screening.

- **[In-silico identification of a Doxorubicin alternative with reduced cardiotoxicity informed by LLM-assisted modeling.](https://pubmed.ncbi.nlm.nih.gov/41223606/)**
	- Methodology: LLM, Tree-based models, Explainable AI
	- Published: 2026Jan
	- Summary: LLM-assisted pipeline with random forest and SHAP for predicting ADME/ADMET properties to identify safer doxorubicin alternatives with reduced cardiotoxicity.

- **[New Machine Learning Models for Predicting the Organic Cation Transporters OCT1, OCT2, and OCT3 Uptake.](https://pubmed.ncbi.nlm.nih.gov/41048715/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Sep30
	- Summary: Machine learning models using decision tree ensemble algorithms predict organic cation transporter uptake to forecast pharmacokinetic liabilities in drug development.

- **[LLM-Enhanced Multimodal Framework for Drug-Drug Interaction Prediction.](https://pubmed.ncbi.nlm.nih.gov/41153642/)**
	- Methodology: Deep learning, LLM
	- Published: 2025Sep26
	- Summary: A multimodal deep learning framework integrating chemical structure, BioBERT embeddings, and protein data to predict drug-drug interactions with high accuracy.

- **[Machine-Learning Framework to Predict the Performance of Lipid Nanoparticles for Nucleic Acid Delivery.](https://pubmed.ncbi.nlm.nih.gov/40267508/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning, Feature selection
	- Published: 2025May19
	- Summary: Machine learning framework using multiple algorithms and molecular features to predict lipid nanoparticle activity and cell viability for nucleic acid delivery applications.

- **[Beyond Algorithms: Machine Learning and Clinical Determinants of Voriconazole Plasma Levels in Therapeutic Drug Monitoring.](https://pubmed.ncbi.nlm.nih.gov/41288921/)**
	- Methodology: Supervised learning
	- Published: 2025Nov25
	- Summary: Machine learning is used to predict subtherapeutic or supratherapeutic voriconazole plasma levels for therapeutic drug monitoring optimization.

- **[Artificial intelligence modelling of tyrosine kinase inhibitors at risk of malabsorption and bioavailability-enhancing strategies.](https://pubmed.ncbi.nlm.nih.gov/40625205/)**
	- Methodology: Supervised learning
	- Published: 2025Nov
	- Summary: AI model developed to predict tyrosine kinase inhibitors at risk of malabsorption in patients with specific conditions and identify bioavailability enhancement strategies.

- **[AI-assisted identification of innovative phytochemicals from Aizoon canariense aimed at brachyury protein in chordoma: a computational strategy.](https://pubmed.ncbi.nlm.nih.gov/41419749/)**
	- Methodology: Deep learning
	- Published: 2025Dec19
	- Summary: AI-assisted drug discovery approach used to optimize phytochemicals from Aizoon canariense for targeting TBXT protein in chordoma treatment.

- **[ADME-drug-likeness: enriching molecular foundation models via pharmacokinetics-guided multi-task learning for drug-likeness prediction.](https://pubmed.ncbi.nlm.nih.gov/40662819/)**
	- Methodology: Deep learning, Supervised learning, Neural networks
	- Published: 2025Jul01
	- Summary: Deep learning pipeline enhances molecular foundation models via sequential ADME multi-task learning to improve drug-likeness prediction by incorporating pharmacokinetic factors.

- **[Elucidation of Artemisinin as a Potent GSK3β Inhibitor for Neurodegenerative Disorders via Machine Learning-Driven QSAR and Virtual Screening of Natural Compounds.](https://pubmed.ncbi.nlm.nih.gov/40573222/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025May31
	- Summary: Machine learning models (SVM, RF, KNN) with feature selection were used for virtual screening to identify artemisinin as a potent GSK3β inhibitor for neurodegenerative disorders.

- **[Neurotherapeutics across blood-brain barrier: screening of BBB-permeable and CNS-active molecules for neurodegenerative disease.](https://pubmed.ncbi.nlm.nih.gov/41079713/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning models are used to predict blood-brain barrier permeability and CNS activity for screening neurotherapeutic molecules in neurodegenerative disease drug discovery.

- **[Curated CYP450 Interaction Dataset: Covering the Majority of Phase I Drug Metabolism.](https://pubmed.ncbi.nlm.nih.gov/40813405/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Aug14
	- Summary: The paper presents a curated CYP450 interaction dataset and develops ML models including Graph Convolutional Networks to predict drug-enzyme interactions for metabolism prediction.

- **[AI-powered literature mining reveals the therapeutic significance of GLP-1 receptor: Simulation of natural agonist candidates based on molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41389576/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2026Apr
	- Summary: AI-integrated pipeline using BioBERT text mining and ML-guided ADMET profiling to identify natural GLP-1 receptor agonist candidates through virtual screening and molecular dynamics.

- **[Targeting the glabellar frown lines with OnabotulinumtoxinA: In-silico evidence supporting concentrated, low-volume injection protocols.](https://pubmed.ncbi.nlm.nih.gov/40907830/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: Uses machine learning for off-target risk prediction integrated with mechanistic PK/PD modeling to optimize BoNT-A dosing protocols for glabellar frown line treatment.

- **[Computational approaches in drug chemistry leveraging python powered QSPR study of antimalaria compounds by using artificial neural networks.](https://pubmed.ncbi.nlm.nih.gov/40456832/)**
	- Methodology: Neural networks, Tree-based models, Supervised learning
	- Published: 2025Jun02
	- Summary: Uses artificial neural networks and random forest to predict physicochemical properties of antimalarial compounds through QSPR modeling with molecular descriptors.

- **[PlasmoBridge: Stable hotspot engineering and targeted Surface-enhanced Raman spectroscopy (SERS) monitoring of methotrexate.](https://pubmed.ncbi.nlm.nih.gov/41082836/)**
	- Methodology: Deep learning
	- Published: 2026Jan15
	- Summary: The paper uses convolutional neural networks to enhance spectral analysis accuracy for methotrexate therapeutic drug monitoring via SERS technology.

- **[Virtual screening of sweet peptides from milk protein and molecular dynamics simulations mechanism analysis.](https://pubmed.ncbi.nlm.nih.gov/41421526/)**
	- Methodology: Supervised learning
	- Published: 2025Dec18
	- Summary: Machine learning models predict sweet and bitter taste properties of milk-derived peptides, combined with molecular docking and dynamics simulations for virtual screening.

- **[An Integrated AI-PBPK Platform for Predicting Drug In Vivo Fate and Tissue Distribution in Human and Inter-Species Extrapolation.](https://pubmed.ncbi.nlm.nih.gov/40418625/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct
	- Summary: Develops an integrated AI-PBPK platform using machine learning to predict drug properties from molecular structures, which feeds into PBPK models for human PK prediction.

- **[Improving Vancomycin Through Level Prediction with Machine Learning: A Comparative Study of Feature Selection and Model Performance.](https://pubmed.ncbi.nlm.nih.gov/41336096/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning models (Random Forest, LightGBM, XGBoost) are used to predict vancomycin trough levels for individualized dosing, outperforming traditional Bayesian methods.

- **[Fitness Landscape for Antibodies 2: Benchmarking Reveals That Protein AI Models Cannot Yet Consistently Predict Developability Properties.](https://pubmed.ncbi.nlm.nih.gov/41497662/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Dec27
	- Summary: This paper benchmarks 30 AI models including protein language models on predicting antibody developability properties using the largest public therapeutic antibody dataset (FLAb2).

- **[Computational modeling and experimental validation of the interaction between tumor biomarker mesothelin and an engineered targeting protein with therapeutic activity.](https://pubmed.ncbi.nlm.nih.gov/40815278/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: The paper uses AlphaFold3 deep learning algorithm alongside computational docking to predict protein-protein interactions for engineered therapeutic targeting proteins.

- **[De novo drug design and biological evaluation of coumarin-pyrimidine co-drug derivatives as diabetic inhibitors: expanding a multi-algorithm approach with the integration of machine learning in pharmaceutical research.](https://pubmed.ncbi.nlm.nih.gov/40656568/)**
	- Methodology: Supervised learning
	- Published: 2025Jul10
	- Summary: Machine learning is integrated into de novo drug design for coumarin-pyrimidine derivatives as diabetic inhibitors, including toxicity prediction using web-based servers.

- **[Antagonistic Trends Between Binding Affinity and Drug-Likeness in SARS-CoV-2 Mpro Inhibitors Revealed by Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40733553/)**
	- Methodology: Supervised learning
	- Published: 2025Jun30
	- Summary: Machine learning models (SVM and Logistic Regression) classify SARS-CoV-2 Mpro inhibitors based on IC50 data to reveal antagonistic trends between binding affinity and drug-likeness.

- **[Improving Absorption, Distribution, Metabolism, and Excretion Property Predictions by Integrating Public and Proprietary Data.](https://pubmed.ncbi.nlm.nih.gov/41290196/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2026Jan
	- Summary: This study uses supervised learning and multitask models to predict ADME properties by integrating public and proprietary datasets for improved drug discovery.

- **[Convolutional neural network-assisted screening of natural product inhibitors against Naja naja venom: insights from molecular docking, molecular dynamics simulations and ADMET profiling.](https://pubmed.ncbi.nlm.nih.gov/41459409/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2026
	- Summary: Uses convolutional neural networks (GraphDTA with GINConvNet) for virtual screening of natural compounds against snake venom proteins to identify potential antivenom candidates.

- **[Exploring the mechanism of Stephania tetrandra S. Moore in the treatment of cisplatin resistance against ovarian cancer through integration of network pharmacology and molecular docking.](https://pubmed.ncbi.nlm.nih.gov/41239601/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Nov14
	- Summary: Machine learning algorithms were integrated to identify core targets for Stephania tetrandra treatment of cisplatin-resistant ovarian cancer through network pharmacology analysis.

- **[Prediction of Permeability and Efflux Using Multitask Learning.](https://pubmed.ncbi.nlm.nih.gov/41280832/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov18
	- Summary: This paper uses multitask graph neural networks to predict cell membrane permeability and efflux endpoints for drug discovery applications.

- **[High-Throughput Physiologically Based Pharmacokinetic Model for Rodent Pharmacokinetics Prediction Using Machine Learning-Predicted Inputs and a Large In Vivo Pharmacokinetics Data Set.](https://pubmed.ncbi.nlm.nih.gov/41617209/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2026Jan30
	- Summary: The paper develops a high-throughput PBPK model (SwiftPK) that uses machine learning to predict in vitro parameters from chemical structures for rodent pharmacokinetic prediction.

- **[An innovative machine learning-based QSAR approach for prediction and structural analysis of novel/repurposed acid ceramidase (ASAH1) inhibitors for glioblastoma therapy.](https://pubmed.ncbi.nlm.nih.gov/40682750/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul19
	- Summary: ML-QSAR approach using extra trees regressor and SHAP analysis to predict and identify novel ASAH1 inhibitors for glioblastoma therapy through virtual screening.

- **[Enhancing the Predictive Power of Macrocyclic Drug Permeability by Knowledge Distillation from Analogous Pretraining Data.](https://pubmed.ncbi.nlm.nih.gov/41420604/)**
	- Methodology: Deep learning, Supervised learning, Explainable AI
	- Published: 2026Jan08
	- Summary: Multi_DDPP uses deep learning with knowledge distillation to predict macrocyclic drug membrane permeability from 2D molecular structures, improving drug development efficiency.

- **[DrugAppy - An end-to-end deep learning framework for computational drug discovery.](https://pubmed.ncbi.nlm.nih.gov/41110298/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: DrugAppy combines deep learning with computational chemistry methods for end-to-end drug discovery, predicting pharmacokinetics and activity against cancer targets.

- **[Unveiling Berberine analogues as potential inhibitors of Escherichia coli FtsZ through machine learning molecular docking and molecular dynamics approach.](https://pubmed.ncbi.nlm.nih.gov/40287515/)**
	- Methodology: Supervised learning
	- Published: 2025Apr26
	- Summary: Machine learning is used to screen berberine analogues for drug-likeness and toxicity prediction, combined with molecular docking to identify potential FtsZ inhibitors.

- **[AI-driven peptide discovery for endometrial cancer: deep generative modeling and molecular simulation in the big data era.](https://pubmed.ncbi.nlm.nih.gov/41524971/)**
	- Methodology: Deep learning, Reinforcement learning, Neural networks
	- Published: 2026Jan12
	- Summary: AI-driven pipeline using deep reinforcement learning, GANs, and VAEs to generate and screen novel peptide-like molecules for endometrial cancer treatment.

- **[Toxicity assessment of doxycycline-aided artificial intelligence-assisted drug design targeting candidate 16S rRNA methyltransferase gene.](https://pubmed.ncbi.nlm.nih.gov/41272886/)**
	- Methodology: Supervised learning
	- Published: 2025Nov21
	- Summary: AI-assisted drug design is used to assess toxicity of doxycycline targeting 16S rRNA methyltransferase for treating antibiotic-resistant infections.

- **[Rational Design of Safer Inorganic Nanoparticles via Mechanistic Modeling-Informed Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40460056/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models, Explainable AI
	- Published: 2025Jun17
	- Summary: ML framework predicts nanoparticle toxicity by integrating PBPK modeling with binary classification models to enable rational design of safer inorganic nanoparticles.

- **[Using Machine Learning for the Discovery and Development of Multitarget Flavonoid-Based Functional Products in MASLD.](https://pubmed.ncbi.nlm.nih.gov/41226123/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Oct22
	- Summary: Machine learning ensemble methods (Random Forest, XGBoost, CatBoost) are used to predict bioactivity of flavonoids against MASLD targets for nutraceutical product development.

- **[SF-Rx: A Multioutput Deep Neural Network-Based Framework Predicting Drug-Drug Interaction under Realistic Conditions for Safe Prescription.](https://pubmed.ncbi.nlm.nih.gov/40310752/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025May12
	- Summary: A deep neural network framework predicts drug-drug interactions using structural similarity and PK/PD features with federated learning for safe prescription.

- **[Computational Evaluation of Potential c-Abl Kinase Inhibitors for Parkinson's Disease: QSAR, Docking, Bioisosteric Replacement, ADMET, and MD Simulations.](https://pubmed.ncbi.nlm.nih.gov/41148549/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: Machine learning-based QSAR modeling is used to identify and optimize potential c-Abl kinase inhibitors for Parkinson's disease treatment through computational screening and evaluation.

- **[Integrated machine learning and deep learning-based virtual screening framework identifies novel natural GSK-3β inhibitors for Alzheimer's disease.](https://pubmed.ncbi.nlm.nih.gov/40668407/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Explainable AI
	- Published: 2025Jul16
	- Summary: Integrates random forest and deep learning for virtual screening to identify natural GSK-3β inhibitors for Alzheimer's disease using SHAP for model interpretability.

- **[Uralenol, Glycyrol, and Abyssinone II as potent inhibitors of fibroblast growth factor receptor 2 from anti-cancer plants: A deep learning and molecular dynamics approach.](https://pubmed.ncbi.nlm.nih.gov/41615925/)**
	- Methodology: Deep learning
	- Published: 2026
	- Summary: Deep learning models are used to predict pIC50 values and identify potential FGFR2 inhibitors from phytochemicals for cancer treatment applications.

- **[QSPR analysis of physico-chemical and pharmacological properties of medications for Parkinson's treatment utilizing neighborhood degree-based topological descriptors.](https://pubmed.ncbi.nlm.nih.gov/40374678/)**
	- Methodology: Supervised learning
	- Published: 2025May15
	- Summary: Uses machine learning with topological descriptors in QSPR analysis to predict physico-chemical and pharmacological properties of Parkinson's disease medications.

- **[Substrate Specificity of the Organic Cation Transporters MATE1 and MATE2K and Functional Overlap with OCT1 and OCT2.](https://pubmed.ncbi.nlm.nih.gov/40512599/)**
	- Methodology: Supervised learning
	- Published: 2025Jun26
	- Summary: Machine learning classifiers using 15 physicochemical parameters were used to predict substrates of organic cation transporters MATE1, MATE2K, OCT1, and OCT2.

- **[Machine learning-guided identification and simulation-based validation of potent JAK3 inhibitors for cancer therapy.](https://pubmed.ncbi.nlm.nih.gov/41385500/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025
	- Summary: Machine learning classifiers, particularly Random Forest, are used to virtually screen compounds and identify novel JAK3 inhibitors for cancer therapy through computational drug discovery.

- **[Deep learning model enables the discovery of a novel BET inhibitor YD-851.](https://pubmed.ncbi.nlm.nih.gov/40779884/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: Deep learning models were used for scaffold hopping and rational design of carboline derivatives as BET inhibitors, leading to discovery of YD-851 with improved efficacy and reduced toxicity.

- **[Integrating machine learning with in silico studies and Quantum Chemistry: Exploring novel compounds through multiscale screening targeting the CDK2 enzyme.](https://pubmed.ncbi.nlm.nih.gov/40639010/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Sep
	- Summary: Random forest machine learning is used to screen 477,975 molecules for potential CDK2 enzyme inhibitors, integrating ML with molecular docking and quantum chemistry studies.

- **[Combining Retip Retention Time Prediction with High-Resolution Mass Spectrometry: A Systematic Analysis of Schisandra chinensis-Evodia Conducted for the First Time.](https://pubmed.ncbi.nlm.nih.gov/41379647/)**
	- Methodology: Tree-based models, Deep learning, Ensemble learning
	- Published: 2025Dec23
	- Summary: The paper uses machine learning models (Random Forest, XGBoost, LightGBM, neural networks) to predict retention times for systematic identification of herbal medicine compounds.

- **[Improving the potency prediction for chemically modified siRNAs through insights from molecular modeling of individual sequence positions.](https://pubmed.ncbi.nlm.nih.gov/40171444/)**
	- Methodology: Supervised learning
	- Published: 2025Mar11
	- Summary: Machine learning is used to predict siRNA biological activity by correlating molecular modeling properties with experimental potency data for rational drug design.

- **[AI fragment based optimization of saffron and chamomile phytochemicals as aryl hydrocarbon receptor inhibitors for dementia therapy an integrated computational approach.](https://pubmed.ncbi.nlm.nih.gov/40784071/)**
	- Methodology: Deep learning
	- Published: 2026Feb
	- Summary: AI generative models are used to optimize phytochemicals from saffron and chamomile as aryl hydrocarbon receptor inhibitors for dementia therapy through fragment-based optimization.

- **[Development of Machine Learning and Chemical Language Model-Based QSAR Models for Predicting Drug Residue Depletion Half-Lives in Plasma and Tissues of Cattle Across Various Administration Routes.](https://pubmed.ncbi.nlm.nih.gov/41442152/)**
	- Methodology: Supervised learning, Deep learning, Neural networks, LLM, Ensemble learning
	- Published: 2025Dec24
	- Summary: Machine learning and chemical language models (ImprovedChemBERTa) are used to predict drug depletion half-lives in cattle plasma and tissues for food safety applications.

- **[MWB_Analyzer: An Automated Embedded System for Real-Time Quantitative Analysis of Morphine Withdrawal Behaviors in Rodents.](https://pubmed.ncbi.nlm.nih.gov/40711031/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Jul14
	- Summary: The paper presents MWB_Analyzer, an automated system using YOLO-based deep learning to quantitatively assess morphine withdrawal behaviors in rodents for toxicological evaluation.

- **[DeepMetab: a comprehensive and mechanistically informed graph learning framework for end-to-end drug metabolism prediction.](https://pubmed.ncbi.nlm.nih.gov/40963553/)**
	- Methodology: Deep learning, Neural networks, Mechanism-informed machine learning
	- Published: 2025Oct15
	- Summary: DeepMetab uses graph neural networks with mechanistic knowledge to predict CYP450-mediated drug metabolism through integrated substrate profiling, site identification, and metabolite generation.

- **[Development of an artificial intelligence-enhanced warfarin interaction checker platform.](https://pubmed.ncbi.nlm.nih.gov/40127068/)**
	- Methodology: LLM
	- Published: 2025Mar
	- Summary: Development of a bilingual AI web application using GPT-4 API to identify potential warfarin drug interactions through text, picture, or voice input for patient safety.

- **[Drug repurposing through Biophysical Insights: Focus on Indoleamine 2,3-Dioxygenase and Tryptophan 2,3-Dioxygenase Dual Inhibitors.](https://pubmed.ncbi.nlm.nih.gov/40133710/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: This paper uses machine learning analysis alongside molecular docking to repurpose FDA-approved drugs as dual IDO1/TDO inhibitors for cancer treatment.

- **[Meta-MolNet: A Cross-Domain Benchmark for Few Examples Drug Discovery.](https://pubmed.ncbi.nlm.nih.gov/40038923/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Mar
	- Summary: Introduces Meta-MolNet benchmark and Meta-GAT algorithm using graph attention networks with meta-learning for cross-domain molecular property prediction in drug discovery.

- **[MMDDI-SSE: A Novel Multi-Modal Feature Fusion Model With Static Subgraph Embedding for Drug-Drug Interaction Event Prediction.](https://pubmed.ncbi.nlm.nih.gov/40067720/)**
	- Methodology: Deep learning, Neural networks, Unsupervised learning
	- Published: 2025Aug
	- Summary: A multi-modal deep learning model using graph autoencoders and static subgraph embedding to predict drug-drug interaction events by fusing sequence and graph representations.

- **[Pan-cancer analysis of CDC7 in human tumors: Integrative multi-omics insights and discovery of novel marine-based inhibitors through machine learning and computational approaches.](https://pubmed.ncbi.nlm.nih.gov/40120182/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: Machine learning is used to screen marine-derived compounds for CDC7 inhibitors and predict their toxicity, combined with pan-cancer analysis of CDC7 as a therapeutic target.

- **[Deep Learning-Assisted SERS for Therapeutic Drug Monitoring of Clozapine in Serum on Plasmonic Metasurfaces.](https://pubmed.ncbi.nlm.nih.gov/40111434/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Apr02
	- Summary: Deep learning with artificial neural networks is integrated with SERS for rapid therapeutic drug monitoring of clozapine and metabolites in human serum.

- **[Refined ADME Profiles for ATC Drug Classes.](https://pubmed.ncbi.nlm.nih.gov/40142973/)**
	- Methodology: Supervised learning
	- Published: 2025Feb28
	- Summary: Machine learning models are developed to predict ADME properties of small molecules and analyze their distributions across different ATC drug classes to guide drug discovery.

- **[Rational Design of Safer Inorganic Nanoparticles via Mechanistic Modeling-informed Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40034433/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models, Explainable AI
	- Published: 2025Feb18
	- Summary: ML framework predicts nanoparticle toxicity by integrating PBPK modeling with binary classification models to enable rational design of safer inorganic nanoparticles.

- **[Predicting Liver-Related In Vitro Endpoints with Machine Learning to Support Early Detection of Drug-Induced Liver Injury.](https://pubmed.ncbi.nlm.nih.gov/40064588/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Apr21
	- Summary: Machine learning models using multi-task learning and ensemble methods to predict liver-related in vitro endpoints for early detection of drug-induced liver injury.

- **[Predictive modeling of pediatric drug-induced liver injury: Dynamic classifier selection with clustering analysis.](https://pubmed.ncbi.nlm.nih.gov/40123880/)**
	- Methodology: Ensemble learning, Unsupervised learning
	- Published: 2025Jan-Dec
	- Summary: The paper develops predictive models for pediatric drug-induced liver injury using dynamic classifier selection combined with clustering analysis to improve early identification.

- **[Discovering Severe Adverse Reactions From Pharmacokinetic Drug-Drug Interactions Through Literature Analysis and Electronic Health Record Verification.](https://pubmed.ncbi.nlm.nih.gov/39585167/)**
	- Methodology: Supervised learning, Deep learning
	- Published: 2025Apr
	- Summary: Uses NLP techniques including Named Entity Recognition and Relation Extraction to discover severe adverse drug reactions from drug-drug interactions through literature mining and EHR validation.

- **[MONSTROUS: a web-based chemical-transporter interaction profiler.](https://pubmed.ncbi.nlm.nih.gov/40078284/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025
	- Summary: Develops MONSTROUS web tool using graph convolutional neural networks and similarity methods to predict chemical-transporter interactions for drug screening.

- **[Machine Learning-Based High-Throughput Screening, Molecular Modeling and Quantum Chemical Analysis to Investigate Mycobacterium tuberculosis MetRS Inhibitors.](https://pubmed.ncbi.nlm.nih.gov/39996268/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning algorithms including Random Forest, Extra Trees, and Nu-Support Vector are used in a voting classifier to screen 10 million molecules for Mtb MetRS inhibitors.

- **[Predicting Pharmacokinetics in Rats Using Machine Learning: A Comparative Study Between Empirical, Compartmental, and PBPK-Based Approaches.](https://pubmed.ncbi.nlm.nih.gov/40091606/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Mar
	- Summary: This study compares ML approaches integrated with empirical and mechanistic PK models to predict complete plasma concentration-time profiles in rats prior to synthesis.

- **[Advancing exposure science through artificial intelligence: Neural ordinary differential equations for predicting blood concentrations of volatile organic compounds.](https://pubmed.ncbi.nlm.nih.gov/39978105/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Mar01
	- Summary: Neural ODEs are used to predict blood concentrations of volatile organic compounds, outperforming traditional PBPK models for toxicological forecasting and risk assessment.

## Endpoint / biomarker assessment

- **[Functional Ultrasound Imaging Combined with Machine Learning for Whole-Brain Analysis of Drug-Induced Hemodynamic Changes.](https://pubmed.ncbi.nlm.nih.gov/40895074/)**
	- Methodology: Deep learning, Supervised learning, Neural networks, Explainable AI
	- Published: 2025Aug19
	- Summary: This paper compares CNN, SVM, and ViT machine learning approaches combined with functional ultrasound imaging to analyze pharmacodynamics of MK-801 drug effects on whole-brain hemodynamics.

- **[Biomarker discovery and drug repurposing in hepatocellular carcinoma through transcriptomics, machine learning, network pharmacology, and molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41671946/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2026Feb08
	- Summary: Uses machine learning classifiers (XGBoost, Random Forest, SVM, Logistic Regression) with SHAP explainability to identify HCC biomarkers and explore drug repurposing opportunities.

- **[[A GA-BP neural network model based on spectrum-effect relationship for assessing spectrum-effect score and quality evaluation of Cassia seeds extract].](https://pubmed.ncbi.nlm.nih.gov/41139439/)**
	- Methodology: Neural networks
	- Published: 2025Oct20
	- Summary: The paper develops a GA-BP neural network model to assess spectrum-effect relationships for quality control of Cassia seeds extract using spectrum-effect scoring.

- **[Dynamic Contrast-enhanced MRI for Evaluating Breast Cancer Chemotherapy Response Using Conditional Generative Adversarial Networks.](https://pubmed.ncbi.nlm.nih.gov/41347917/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A conditional GAN is developed to rapidly translate DCE-MRI data to pharmacokinetic permeability maps for evaluating breast cancer chemotherapy response.

- **[Molecular features of human pathological tau distinguish tauopathy-associated dementias.](https://pubmed.ncbi.nlm.nih.gov/41616780/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2026Feb05
	- Summary: Uses unsupervised and supervised ML to identify distinct molecular features of pathological tau protein for disease stratification and biomarker discovery across tauopathies.

- **[High-Resolution MRI Using Artificial Intelligence-Assisted Acceleration and Radial Dynamic Contrast Enhancement for Improved Detection of Pituitary Microadenomas in Cushing's Disease.](https://pubmed.ncbi.nlm.nih.gov/41663207/)**
	- Methodology: Deep learning
	- Published: 2026Feb09
	- Summary: AI-assisted compressed sensing is applied to MRI imaging to improve spatial and temporal resolution for better detection of pituitary microadenomas in Cushing's disease.

- **[Analysis of Crosstalk Between Pathogens and Immune System in Human Airway Mucus via Machine Learning-Enhanced DIA Mass Spectrometry.](https://pubmed.ncbi.nlm.nih.gov/41104598/)**
	- Methodology: Supervised learning
	- Published: 2025Nov
	- Summary: Machine learning is used to enhance mass spectrometry analysis by matching low-abundance spectra to predicted peptide spectra for proteomic analysis of pathogen-immune interactions.

- **[Leveraging AI for facioscapulohumeral muscular dystrophy prediction and omics biomarker identification.](https://pubmed.ncbi.nlm.nih.gov/41256551/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Oct03
	- Summary: This paper develops ML models using Random Forest and SVM-RFE to predict FSHD from multi-omics data and identify key biomarker features for disease classification.

- **[A myocardial reorientation method based on feature point detection for quantitative analysis of PET myocardial perfusion imaging.](https://pubmed.ncbi.nlm.nih.gov/40367541/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Aug
	- Summary: This paper develops a CNN for automatic reorientation of cardiac PET images to enable quantitative analysis of myocardial perfusion imaging.

- **[Large Language Models for Clinical Trial Protocol Assessments.](https://pubmed.ncbi.nlm.nih.gov/41121745/)**
	- Methodology: LLM
	- Published: 2026Feb
	- Summary: This paper evaluates the utility of large language models (GPT-4o) for reviewing statistical analysis plans and PK-PD components of clinical trial protocols.

- **[Ribociclib derivative Rib-CA suppresses breast cancer progression via p53-dependent apoptosis.](https://pubmed.ncbi.nlm.nih.gov/40675394/)**
	- Methodology: Supervised learning
	- Published: 2025Oct
	- Summary: Machine learning was used to identify CACHD1 and LAGE3 as potential biomarkers for a novel ribociclib derivative's mechanism of action in breast cancer treatment.

- **[Unsupervised Deep Learning for Blood-Brain Barrier Leakage Detection in Diffuse Glioma Using Dynamic Contrast-enhanced MRI.](https://pubmed.ncbi.nlm.nih.gov/40172325/)**
	- Methodology: Unsupervised learning, Deep learning
	- Published: 2025May
	- Summary: Develops an unsupervised deep learning autoencoder framework to detect blood-brain barrier leakage in glioma patients using dynamic contrast-enhanced MRI without pharmacokinetic models.

- **[Metabolomics and lipidomics predictor of survival in hepatocellular carcinoma patients receiving tyrosine kinase inhibitor and immune checkpoint inhibitor combination therapy.](https://pubmed.ncbi.nlm.nih.gov/41265377/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025Dec
	- Summary: Machine learning framework combining random forest, LASSO regression, and Cox modeling to identify metabolomic and lipidomic biomarkers predicting survival in HCC patients.

- **[Fully Automated Deep Learning Enabled Miniature Mass Spectrometry System for Psychoactive Therapeutic Drug Monitoring.](https://pubmed.ncbi.nlm.nih.gov/40405757/)**
	- Methodology: Deep learning
	- Published: 2025Aug
	- Summary: Deep learning U-net algorithm automates peak area recognition in miniature mass spectrometry for psychoactive drug monitoring with >98% identification accuracy.

- **[Network-based disease fingerprinting with neuroinflammation PET imaging.](https://pubmed.ncbi.nlm.nih.gov/41282214/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2025Oct21
	- Summary: Machine learning classifiers are applied to network-based TSPO PET imaging data to identify disease-specific neuroinflammatory patterns and classify different neurological conditions.

- **[Decoding the gut microbiota metabolite-matrix metalloproteinase-3 axis in breast cancer: a multi-omics and network pharmacology study.](https://pubmed.ncbi.nlm.nih.gov/40946247/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Sep14
	- Summary: This study uses machine learning with SHAP explainability to identify gut microbiota metabolites as potential therapeutic targets for breast cancer treatment via MMP3 axis.

- **[Multi-cohort, cross-species urinary proteomics reveals signatures of LRRK2 dysfunction in Parkinson's disease.](https://pubmed.ncbi.nlm.nih.gov/41611872/)**
	- Methodology: Supervised learning
	- Published: 2026Jan29
	- Summary: Machine learning was used to develop a 30-protein urinary panel that classifies LRRK2 G2019S carriers in Parkinson's disease with high accuracy across independent cohorts.

- **[MWB_Analyzer: An Automated Embedded System for Real-Time Quantitative Analysis of Morphine Withdrawal Behaviors in Rodents.](https://pubmed.ncbi.nlm.nih.gov/40711031/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Jul14
	- Summary: The paper presents MWB_Analyzer, an automated system using YOLO-based deep learning to quantitatively assess morphine withdrawal behaviors in rodents for toxicological evaluation.

- **[Analyzing patient perspectives with large language models: a cross-sectional study of sentiment and thematic classification on exception from informed consent.](https://pubmed.ncbi.nlm.nih.gov/39979559/)**
	- Methodology: LLM
	- Published: 2025Feb20
	- Summary: This study evaluates large language models (LLMs) including GPT-4 for analyzing patient sentiment and thematic classification in exception from informed consent interviews.

- **[Ultra-low-dose coronary CT angiography via super-resolution deep learning reconstruction: impact on image quality, coronary plaque, and stenosis analysis.](https://pubmed.ncbi.nlm.nih.gov/39891682/)**
	- Methodology: Deep learning
	- Published: 2025Aug
	- Summary: The paper uses super-resolution deep learning reconstruction to reduce radiation exposure in coronary CT angiography while maintaining image quality for plaque and stenosis analysis.

## Enrichment design

- **[AI-NLME: A New Artificial Intelligence-Driven Nonlinear Mixed Effect Modeling Approach for Analyzing Longitudinal Data in Randomized Placebo-Controlled Clinical Trials.](https://pubmed.ncbi.nlm.nih.gov/40898887/)**
	- Methodology: Neural networks
	- Published: 2025Sep
	- Summary: Proposes AI-NLME approach using artificial neural networks to estimate probability of non-specific treatment response for controlling confounding effects in clinical trials.

## Exposure–response analysis

- **[Applying exposure-response analysis to enhance Mycophenolate Mofetil dosing precision in pediatric patients with immune-mediated renal diseases by machine learning models.](https://pubmed.ncbi.nlm.nih.gov/40447059/)**
	- Methodology: Supervised learning
	- Published: 2025Aug01
	- Summary: Machine learning models are applied to develop pharmacokinetic models for mycophenolic acid and optimize MMF dosing in pediatric patients with immune-mediated renal diseases.

- **[Effect of Cumulative Exposure on the Efficacy of Paroxetine: A Population Pharmacokinetic-Pharmacodynamic and Machine Learning Analyses.](https://pubmed.ncbi.nlm.nih.gov/40358139/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Jun
	- Summary: Machine learning models predict paroxetine treatment remission using PK/PD data, with SHAP values explaining feature contributions for depression outcome prediction.

- **[Optimizing Dosing Strategies in Cell Therapy With Machine Learning and Exposure-Response Integration.](https://pubmed.ncbi.nlm.nih.gov/41369984/)**
	- Methodology: Tree-based models
	- Published: 2026Jan-Feb
	- Summary: The paper proposes a random forest-based seamless phase I/II design that integrates toxicity, efficacy, and cellular kinetics data for optimal dose selection in cell therapy.

## Other/General

- **[A Hybrid Diffusion Model Enhances Multiparametric 3D Photoacoustic Computed Tomography.](https://pubmed.ncbi.nlm.nih.gov/41126760/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: The paper develops a hybrid diffusion model to enhance 3D photoacoustic computed tomography imaging quality using fewer ultrasound transducers for biological and pharmacokinetic studies.

- **[Accuracy and teachability of artificial intelligence chatbots in solving pharmaceutical calculations: a descriptive study.](https://pubmed.ncbi.nlm.nih.gov/40493330/)**
	- Methodology: LLM
	- Published: 2025Aug
	- Summary: This study evaluates the accuracy of AI chatbots (LLMs) in performing pharmaceutical calculations for pharmacy education and practice.

- **[Post marketing safety assessment of the novel postpartum depression drug, Zuranolone: evidence from real-world pharmacovigilance analysis based on the FDA adverse event reporting system.](https://pubmed.ncbi.nlm.nih.gov/40896228/)**
	- Published: 2025
	- Summary: This paper conducts a traditional pharmacovigilance analysis of Zuranolone safety using FAERS database without employing AI/ML methods.

- **[Deep learning-based bone removal in head and neck computed tomography angiography: a comparative study with conventional algorithms.](https://pubmed.ncbi.nlm.nih.gov/41209247/)**
	- Methodology: Deep learning
	- Published: 2025Nov01
	- Summary: This study evaluates a deep learning-based algorithm for bone removal in head and neck CT angiography compared to conventional methods for improved diagnostic imaging.

- **[Low-Dose CT Quality Assurance at Scale: Automated Detection of Overscanning, Underscanning, and Image Noise.](https://pubmed.ncbi.nlm.nih.gov/41598306/)**
	- Published: 2026Jan16
	- Summary: This paper focuses on automated quality assurance for low-dose CT lung screening using AI for image segmentation and noise assessment, which is outside the scope of pharmacometrics and drug development applications.

- **[Plasmonic Fiber Optic Sensing Platform for Point-of-Care Pharmacokinetic Monitoring of Platinum Chemotherapeutics: Toward Ultratrace Multi-omics Precision Chemotherapy Management.](https://pubmed.ncbi.nlm.nih.gov/40726318/)**
	- Published: 2025Aug22
	- Summary: This paper develops a plasmonic fiber-optic sensing platform for pharmacokinetic monitoring of platinum chemotherapeutics without using AI/ML methods.

- **[State-of-the-art 32 cm field-of-view digital PET/CT system: preliminary study for protocols optimization and DRLs update.](https://pubmed.ncbi.nlm.nih.gov/41626940/)**
	- Methodology: Deep learning
	- Published: 2026Feb02
	- Summary: This paper evaluates a PET/CT system's performance including deep learning reconstruction for image quality enhancement, focusing on protocol optimization and diagnostic reference levels.

- **[Diagnostic performance of four AI tools in pharmacology MCQs: Accuracy, sensitivity, and specificity.](https://pubmed.ncbi.nlm.nih.gov/41401168/)**
	- Methodology: LLM
	- Published: 2025
	- Summary: This paper evaluates the diagnostic performance of four AI tools on pharmacology multiple-choice questions, assessing their accuracy, sensitivity, and specificity.

- **[Highly Precise Prediction of Micro- and Supra-pKa Based on 3D Descriptors Integrating Non-Covalent Interactions.](https://pubmed.ncbi.nlm.nih.gov/39904757/)**
	- Published: 2025Apr11
	- Summary: This paper presents H-SPOC, a 3D descriptor-based computational method for pKa prediction that does not appear to use AI/ML techniques but rather molecular modeling approaches.

- **[Correction to "Comparing Scientific Machine Learning With Population Pharmacokinetic and Classical Machine Learning Approaches for Prediction of Drug Concentrations".](https://pubmed.ncbi.nlm.nih.gov/40134374/)**
	- Published: 2025Apr
	- Summary: This is a correction to a previously published paper and contains no substantive content to classify for AI/ML methods or applications.

## Outcome prediction

- **[Meta-Analysis and Machine Learning Prediction of Protein Corona Composition across Nanoparticle Systems in Biological Media.](https://pubmed.ncbi.nlm.nih.gov/41031442/)**
	- Methodology: Tree-based models, Ensemble learning, Explainable AI
	- Published: 2025Nov04
	- Summary: Uses interpretable machine learning models (LightGBM and XGBoost) to predict protein corona composition on nanoparticles based on physicochemical parameters.

- **[Dynamic Contrast-enhanced MRI for Evaluating Breast Cancer Chemotherapy Response Using Conditional Generative Adversarial Networks.](https://pubmed.ncbi.nlm.nih.gov/41347917/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A conditional GAN is developed to rapidly translate DCE-MRI data to pharmacokinetic permeability maps for evaluating breast cancer chemotherapy response.

- **[Design, synthesis, deep learning-guided prediction, and biological evaluation of novel pyridine-thiophene-based imine-benzalacetophenone hybrids as promising antimicrobial agent.](https://pubmed.ncbi.nlm.nih.gov/41186782/)**
	- Methodology: Deep learning, Neural networks, Explainable AI
	- Published: 2025Nov04
	- Summary: Deep learning neural network with SHAP analysis predicts antimicrobial activity (pMIC values) of novel pyridine-thiophene hybrid compounds for drug development.

- **[Proteolysis-targeting Chimera efficacy prediction using a deep-learning-QSP model.](https://pubmed.ncbi.nlm.nih.gov/41521293/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Neural networks
	- Published: 2026Jan12
	- Summary: Deep learning models are integrated with QSP modeling to predict PROTAC efficacy parameters (DC50 and Dmax) for targeted protein degradation therapeutics.

- **[Prediction of Early Neoadjuvant Chemotherapy Response of Breast Cancer through Deep Learning-based Pharmacokinetic Quantification of DCE MRI.](https://pubmed.ncbi.nlm.nih.gov/40631989/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: Deep learning is used for pharmacokinetic quantification of DCE MRI to predict pathologic complete response to neoadjuvant chemotherapy in breast cancer patients.

- **[Gut microbiota and metabolites related intra-patient variability of tacrolimus pharmacokinetics predicted adverse one-year outcomes following kidney transplantation.](https://pubmed.ncbi.nlm.nih.gov/40913864/)**
	- Methodology: Tree-based models, Supervised learning
	- Published: 2025Nov14
	- Summary: Random forest model used to classify kidney transplant patients into high/low tacrolimus variability groups based on gut microbiota and metabolites to predict adverse outcomes.

- **[Leveraging AI for facioscapulohumeral muscular dystrophy prediction and omics biomarker identification.](https://pubmed.ncbi.nlm.nih.gov/41256551/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Oct03
	- Summary: This paper develops ML models using Random Forest and SVM-RFE to predict FSHD from multi-omics data and identify key biomarker features for disease classification.

- **[Predicting lymphatic transport potential using graph transformer based on limited historical data from in vivo studies.](https://pubmed.ncbi.nlm.nih.gov/40393527/)**
	- Methodology: Deep learning
	- Published: 2025Aug10
	- Summary: The paper uses graph transformer deep learning to predict lymphatic transport potential of drugs based on limited historical in vivo data from 185 compounds.

- **[Analytical and machine learning approaches identify a sea star steroid with promising activity for COVID-19 therapeutic development.](https://pubmed.ncbi.nlm.nih.gov/41057530/)**
	- Methodology: Supervised learning
	- Published: 2025Oct07
	- Summary: The paper develops a machine learning-based web application to predict IC50 values of SARS-CoV-2 inhibitors for drug discovery screening.

- **[Machine Learning Models of Early Longitudinal Toxicity Trajectories Predict Cetuximab Concentration and Metastatic Colorectal Cancer Survival in the Canadian Cancer Trials Group/AGITG CO.17/20 Trials.](https://pubmed.ncbi.nlm.nih.gov/40215447/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: Machine learning models analyze early toxicity trajectories to predict cetuximab concentration and survival outcomes in metastatic colorectal cancer patients.

- **[Integrative Machine Learning Model Leveraging DCE-MRI and PSA Values for Advanced Risk Stratification in Prostate Cancer.](https://pubmed.ncbi.nlm.nih.gov/41203263/)**
	- Methodology: Supervised learning
	- Published: 2025Nov07
	- Summary: Machine learning model integrates DCE-MRI pharmacokinetic parameters with PSA values to predict ISUP grade metastatic risk groups for prostate cancer risk stratification.

- **[Multimodal profiling of Pepcan-CB1 receptor structure-activity relationships: integrating molecular dynamics simulations, biological profiling, and the deep learning model MuMoPepcan.](https://pubmed.ncbi.nlm.nih.gov/41005111/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models
	- Published: 2025Oct
	- Summary: Deep learning model MuMoPepcan integrates molecular dynamics simulations with experimental data to predict pepcan peptide bioactivity for CB1 receptor drug discovery.

- **[Integrating artificial intelligence and physiologically based pharmacokinetic modeling to predict in vitro and in vivo fate of amorphous solid dispersions.](https://pubmed.ncbi.nlm.nih.gov/40825400/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025Oct10
	- Summary: This paper integrates AI with PBPK modeling using TabPFN to predict molecular dissolution and systemic absorption of amorphous solid dispersions for drug development.

- **[Machine Learning Prediction and Validation of Plasma Concentration-Time Profiles.](https://pubmed.ncbi.nlm.nih.gov/40345671/)**
	- Methodology: Tree-based models, Supervised learning
	- Published: 2025Jun02
	- Summary: This study uses Random Forest models to predict plasma concentration-time profiles for remifentanil, demonstrating high accuracy on both virtual and real-world data sets.

- **[Machine-Learning Framework to Predict the Performance of Lipid Nanoparticles for Nucleic Acid Delivery.](https://pubmed.ncbi.nlm.nih.gov/40267508/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning, Feature selection
	- Published: 2025May19
	- Summary: Machine learning framework using multiple algorithms and molecular features to predict lipid nanoparticle activity and cell viability for nucleic acid delivery applications.

- **[Numerical modeling and prediction of late estimated glomerular filtration rate in kidney transplant recipients based on machine learning models and the Monte Carlo simulation method.](https://pubmed.ncbi.nlm.nih.gov/41562636/)**
	- Methodology: Supervised learning, Surrogate modeling
	- Published: 2026Jan22
	- Summary: Machine learning models combined with Monte Carlo simulation are used to predict late estimated glomerular filtration rate in kidney transplant recipients on tacrolimus.

- **[Explainable cluster-based learning for prediction of postprandial glycemic events and insulin dose optimization in type 1 diabetes.](https://pubmed.ncbi.nlm.nih.gov/40956852/)**
	- Methodology: Supervised learning, Unsupervised learning, Tree-based models, Explainable AI, Ensemble learning
	- Published: 2025Sep
	- Summary: Uses cluster-based ensemble ML with explainable AI to predict postprandial glycemic events and optimize insulin dosing in type 1 diabetes patients.

- **[Design, synthesis and anti-gastric cancer activity of stable Bisamide curcumin analogues.](https://pubmed.ncbi.nlm.nih.gov/40749269/)**
	- Methodology: Tree-based models
	- Published: 2025Sep
	- Summary: The paper uses random forest algorithm to establish QSAR models for predicting anti-gastric cancer activity of bisamide curcumin analogues.

- **[Personalized Prediction of Clozapine Treatment Response Using Therapeutic Drug Monitoring Data in Japanese Patients with Treatment-Resistant Schizophrenia.](https://pubmed.ncbi.nlm.nih.gov/41227287/)**
	- Methodology: Tree-based models, Explainable AI
	- Published: 2025Nov06
	- Summary: Random forest model predicts clozapine treatment response in schizophrenia patients using TDM data, with SHAP analysis for model interpretability.

- **[TuNa-AI: A Hybrid Kernel Machine To Design Tunable Nanoparticles for Drug Delivery.](https://pubmed.ncbi.nlm.nih.gov/40934473/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025Sep23
	- Summary: Develops a hybrid kernel machine combining molecular features and compositional data to predict nanoparticle formulation outcomes and optimize drug delivery systems.

- **[Fitness Landscape for Antibodies 2: Benchmarking Reveals That Protein AI Models Cannot Yet Consistently Predict Developability Properties.](https://pubmed.ncbi.nlm.nih.gov/41497662/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Dec27
	- Summary: This paper benchmarks 30 AI models including protein language models on predicting antibody developability properties using the largest public therapeutic antibody dataset (FLAb2).

- **[Metabolomics and lipidomics predictor of survival in hepatocellular carcinoma patients receiving tyrosine kinase inhibitor and immune checkpoint inhibitor combination therapy.](https://pubmed.ncbi.nlm.nih.gov/41265377/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025Dec
	- Summary: Machine learning framework combining random forest, LASSO regression, and Cox modeling to identify metabolomic and lipidomic biomarkers predicting survival in HCC patients.

- **[A simulation-based framework for modeling and prediction of personalized blood pressure trajectories in hypertensive patients after antihypertensive treatment.](https://pubmed.ncbi.nlm.nih.gov/40209154/)**
	- Methodology: Gaussian processes
	- Published: 2025
	- Summary: The paper develops a simulation framework for blood pressure trajectories using PK/PD modeling and evaluates Gaussian processes for predicting steady-state blood pressure under treatment.

- **[Effect of Cumulative Exposure on the Efficacy of Paroxetine: A Population Pharmacokinetic-Pharmacodynamic and Machine Learning Analyses.](https://pubmed.ncbi.nlm.nih.gov/40358139/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Jun
	- Summary: Machine learning models predict paroxetine treatment remission using PK/PD data, with SHAP values explaining feature contributions for depression outcome prediction.

- **[Nephrocast-V: A Deep Learning Model for the Prediction of Vancomycin Trough Concentration Using Electronic Health Record Data.](https://pubmed.ncbi.nlm.nih.gov/41025800/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A deep learning model is developed to predict vancomycin trough concentrations using electronic health record data to optimize therapeutic dosing.

- **[Primary infliximab failure in pediatric colonic inflammatory bowel disease: Development of a proteomics predictive model using a prospective Canadian cohort.](https://pubmed.ncbi.nlm.nih.gov/41671043/)**
	- Methodology: Supervised learning
	- Published: 2026Feb11
	- Summary: The paper develops a serum proteomics-based predictive model using supervised learning to predict primary nonresponse to infliximab in pediatric inflammatory bowel disease.

- **[Improving the potency prediction for chemically modified siRNAs through insights from molecular modeling of individual sequence positions.](https://pubmed.ncbi.nlm.nih.gov/40171444/)**
	- Methodology: Supervised learning
	- Published: 2025Mar11
	- Summary: Machine learning is used to predict siRNA biological activity by correlating molecular modeling properties with experimental potency data for rational drug design.

- **[Multi-cohort, cross-species urinary proteomics reveals signatures of LRRK2 dysfunction in Parkinson's disease.](https://pubmed.ncbi.nlm.nih.gov/41611872/)**
	- Methodology: Supervised learning
	- Published: 2026Jan29
	- Summary: Machine learning was used to develop a 30-protein urinary panel that classifies LRRK2 G2019S carriers in Parkinson's disease with high accuracy across independent cohorts.

- **[A translational multimodal machine-learning prototype predicting valproate response in epilepsy treatment.](https://pubmed.ncbi.nlm.nih.gov/40909818/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025Aug27
	- Summary: Develops a multimodal machine learning classifier integrating genetic and in-vitro data to predict valproate treatment response in epilepsy patients for personalized treatment decisions.

- **[Comparison of time-series models for predicting physiological metrics under sedation.](https://pubmed.ncbi.nlm.nih.gov/39470955/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Jun
	- Summary: Compares statistical and deep learning time-series models (LSTM, GRU, TCN, Transformers) for predicting bispectral index to assess sedation depth during surgery.

- **[Global Deep Forecasting with Patient-Specific Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/37965077/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Time-series modeling
	- Published: 2025Feb12
	- Summary: A hybrid global-local deep learning architecture with PK encoder forecasts blood glucose levels by incorporating patient-specific pharmacokinetic properties for improved accuracy.

- **[Pan-cancer analysis of CDC7 in human tumors: Integrative multi-omics insights and discovery of novel marine-based inhibitors through machine learning and computational approaches.](https://pubmed.ncbi.nlm.nih.gov/40120182/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: Machine learning is used to screen marine-derived compounds for CDC7 inhibitors and predict their toxicity, combined with pan-cancer analysis of CDC7 as a therapeutic target.

- **[Virtual patients inspired by multiomics predict the efficacy of an anti-IFNα mAb in cutaneous lupus.](https://pubmed.ncbi.nlm.nih.gov/39925417/)**
	- Methodology: Unsupervised learning, Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Feb21
	- Summary: Uses multiomics clustering to identify patient subgroups, then applies ML with mechanistic modeling to predict anti-IFNα antibody treatment responses in virtual lupus patients.

- **[Item Response Modeling and Artificial Neural Network for Differentiation of Parkinson's Patients and Subjects Without Evidence of Dopaminergic Deficit.](https://pubmed.ncbi.nlm.nih.gov/40045658/)**
	- Methodology: Neural networks, Supervised learning
	- Published: 2025May
	- Summary: The paper uses artificial neural networks and item response theory to classify Parkinson's disease patients versus subjects without dopaminergic deficits using MDS-UPDRS scores.

## Patient risk stratification / management

- **[Biomarker discovery and drug repurposing in hepatocellular carcinoma through transcriptomics, machine learning, network pharmacology, and molecular dynamics.](https://pubmed.ncbi.nlm.nih.gov/41671946/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2026Feb08
	- Summary: Uses machine learning classifiers (XGBoost, Random Forest, SVM, Logistic Regression) with SHAP explainability to identify HCC biomarkers and explore drug repurposing opportunities.

- **[Molecular features of human pathological tau distinguish tauopathy-associated dementias.](https://pubmed.ncbi.nlm.nih.gov/41616780/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2026Feb05
	- Summary: Uses unsupervised and supervised ML to identify distinct molecular features of pathological tau protein for disease stratification and biomarker discovery across tauopathies.

- **[Gut microbiota and metabolites related intra-patient variability of tacrolimus pharmacokinetics predicted adverse one-year outcomes following kidney transplantation.](https://pubmed.ncbi.nlm.nih.gov/40913864/)**
	- Methodology: Tree-based models, Supervised learning
	- Published: 2025Nov14
	- Summary: Random forest model used to classify kidney transplant patients into high/low tacrolimus variability groups based on gut microbiota and metabolites to predict adverse outcomes.

- **[Machine Learning Models of Early Longitudinal Toxicity Trajectories Predict Cetuximab Concentration and Metastatic Colorectal Cancer Survival in the Canadian Cancer Trials Group/AGITG CO.17/20 Trials.](https://pubmed.ncbi.nlm.nih.gov/40215447/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: Machine learning models analyze early toxicity trajectories to predict cetuximab concentration and survival outcomes in metastatic colorectal cancer patients.

- **[Enhancing Severe Neutropenia Prediction: PKPD-Informed Labeling for Machine Learning Models Trained on Real-World Data.](https://pubmed.ncbi.nlm.nih.gov/41208554/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models
	- Published: 2026Feb
	- Summary: PKPD-informed labeling strategy enhances machine learning models (logistic regression, XGBoost, TabPFN) for predicting docetaxel-induced severe neutropenia using real-world data.

- **[Integrative Machine Learning Model Leveraging DCE-MRI and PSA Values for Advanced Risk Stratification in Prostate Cancer.](https://pubmed.ncbi.nlm.nih.gov/41203263/)**
	- Methodology: Supervised learning
	- Published: 2025Nov07
	- Summary: Machine learning model integrates DCE-MRI pharmacokinetic parameters with PSA values to predict ISUP grade metastatic risk groups for prostate cancer risk stratification.

- **[Explainable cluster-based learning for prediction of postprandial glycemic events and insulin dose optimization in type 1 diabetes.](https://pubmed.ncbi.nlm.nih.gov/40956852/)**
	- Methodology: Supervised learning, Unsupervised learning, Tree-based models, Explainable AI, Ensemble learning
	- Published: 2025Sep
	- Summary: Uses cluster-based ensemble ML with explainable AI to predict postprandial glycemic events and optimize insulin dosing in type 1 diabetes patients.

- **[Artificial intelligence modelling of tyrosine kinase inhibitors at risk of malabsorption and bioavailability-enhancing strategies.](https://pubmed.ncbi.nlm.nih.gov/40625205/)**
	- Methodology: Supervised learning
	- Published: 2025Nov
	- Summary: AI model developed to predict tyrosine kinase inhibitors at risk of malabsorption in patients with specific conditions and identify bioavailability enhancement strategies.

- **[Metabolomics and lipidomics predictor of survival in hepatocellular carcinoma patients receiving tyrosine kinase inhibitor and immune checkpoint inhibitor combination therapy.](https://pubmed.ncbi.nlm.nih.gov/41265377/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025Dec
	- Summary: Machine learning framework combining random forest, LASSO regression, and Cox modeling to identify metabolomic and lipidomic biomarkers predicting survival in HCC patients.

- **[Development of an artificial intelligence-enhanced warfarin interaction checker platform.](https://pubmed.ncbi.nlm.nih.gov/40127068/)**
	- Methodology: LLM
	- Published: 2025Mar
	- Summary: Development of a bilingual AI web application using GPT-4 API to identify potential warfarin drug interactions through text, picture, or voice input for patient safety.

- **[Global Deep Forecasting with Patient-Specific Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/37965077/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Time-series modeling
	- Published: 2025Feb12
	- Summary: A hybrid global-local deep learning architecture with PK encoder forecasts blood glucose levels by incorporating patient-specific pharmacokinetic properties for improved accuracy.

- **[Virtual patients inspired by multiomics predict the efficacy of an anti-IFNα mAb in cutaneous lupus.](https://pubmed.ncbi.nlm.nih.gov/39925417/)**
	- Methodology: Unsupervised learning, Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Feb21
	- Summary: Uses multiomics clustering to identify patient subgroups, then applies ML with mechanistic modeling to predict anti-IFNα antibody treatment responses in virtual lupus patients.

- **[Item Response Modeling and Artificial Neural Network for Differentiation of Parkinson's Patients and Subjects Without Evidence of Dopaminergic Deficit.](https://pubmed.ncbi.nlm.nih.gov/40045658/)**
	- Methodology: Neural networks, Supervised learning
	- Published: 2025May
	- Summary: The paper uses artificial neural networks and item response theory to classify Parkinson's disease patients versus subjects without dopaminergic deficits using MDS-UPDRS scores.

## Pharmacodynamic modeling

- **[Functional Ultrasound Imaging Combined with Machine Learning for Whole-Brain Analysis of Drug-Induced Hemodynamic Changes.](https://pubmed.ncbi.nlm.nih.gov/40895074/)**
	- Methodology: Deep learning, Supervised learning, Neural networks, Explainable AI
	- Published: 2025Aug19
	- Summary: This paper compares CNN, SVM, and ViT machine learning approaches combined with functional ultrasound imaging to analyze pharmacodynamics of MK-801 drug effects on whole-brain hemodynamics.

- **[Representation meets optimization: Training PINNs and PIKANs for gray-box discovery in systems pharmacology.](https://pubmed.ncbi.nlm.nih.gov/41447950/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2026Jan15
	- Summary: Compares Physics-Informed Neural Networks (PINNs) and Physics-Informed Kolmogorov-Arnold Networks (PIKANs) for gray-box system identification in pharmacokinetic and pharmacodynamic modeling.

- **[Proteolysis-targeting Chimera efficacy prediction using a deep-learning-QSP model.](https://pubmed.ncbi.nlm.nih.gov/41521293/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Neural networks
	- Published: 2026Jan12
	- Summary: Deep learning models are integrated with QSP modeling to predict PROTAC efficacy parameters (DC50 and Dmax) for targeted protein degradation therapeutics.

- **[Prediction of pharmacokinetic/pharmacodynamic properties of aldosterone synthase inhibitors at drug discovery stage using an artificial intelligence-physiologically based pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40356995/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: An AI-PBPK model integrating machine learning with classical PBPK modeling is developed to predict PK/PD properties of aldosterone synthase inhibitors for drug discovery screening.

- **[Shap-Cov: An Explainable Machine Learning Based Workflow for Rapid Covariate Identification in Population Modeling.](https://pubmed.ncbi.nlm.nih.gov/40601439/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Aug
	- Summary: The paper presents Shap-Cov, an explainable ML workflow using SHAP analysis for automated covariate identification in population PK/PD modeling with uncertainty quantification.

- **[Functional ultrasound imaging combined with machine learning for whole-brain analysis of drug-induced hemodynamic changes.](https://pubmed.ncbi.nlm.nih.gov/40948602/)**
	- Methodology: Deep learning, Supervised learning, Neural networks, Explainable AI
	- Published: 2025
	- Summary: The paper uses CNN, SVM, and ViT machine learning approaches with functional ultrasound imaging to analyze pharmacodynamics of dizocilpine (MK-801) for whole-brain hemodynamic analysis.

- **[Representation Meets Optimization: Training PINNs and PIKANs for Gray-Box Discovery in Systems Pharmacology.](https://pubmed.ncbi.nlm.nih.gov/40297233/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Apr10
	- Summary: Compares Physics-Informed Neural Networks (PINNs) and Physics-Informed Kolmogorov-Arnold Networks (PIKANs) for gray-box system identification in pharmacology modeling.

- **[Forecasting anesthetic depth using an auto-regressive transformer in propofol infusion during the induction phase.](https://pubmed.ncbi.nlm.nih.gov/40522504/)**
	- Methodology: Deep learning, Time-series modeling
	- Published: 2025Oct
	- Summary: The paper uses auto-regressive transformers to forecast depth of anesthesia for optimizing propofol dosing during anesthesia induction phase.

- **[Integrating Pharmacokinetics and Quantitative Systems Pharmacology Approaches in Generative Drug Design.](https://pubmed.ncbi.nlm.nih.gov/40343729/)**
	- Methodology: Reinforcement learning, Supervised learning
	- Published: 2025May26
	- Summary: The paper integrates AI/ML methods including reinforcement learning and QSPR models in a generative drug design framework to optimize both PK properties and receptor affinity.

- **[Learning Chemotherapy Drug Action via Universal Physics-Informed Neural Networks.](https://pubmed.ncbi.nlm.nih.gov/40244511/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models, Mechanism-informed machine learning
	- Published: 2025Apr
	- Summary: The paper applies Universal Physics-Informed Neural Networks to learn unknown components of differential equations modeling chemotherapy pharmacodynamics in QSP.

- **[Numerical modeling and prediction of late estimated glomerular filtration rate in kidney transplant recipients based on machine learning models and the Monte Carlo simulation method.](https://pubmed.ncbi.nlm.nih.gov/41562636/)**
	- Methodology: Supervised learning, Surrogate modeling
	- Published: 2026Jan22
	- Summary: Machine learning models combined with Monte Carlo simulation are used to predict late estimated glomerular filtration rate in kidney transplant recipients on tacrolimus.

- **[A machine learning model (Sol_ME) assisted development of a unit-dose lipid formulation for apalutamide: formulation, pharmacokinetics, and pharmacodynamics evaluation.](https://pubmed.ncbi.nlm.nih.gov/40858184/)**
	- Methodology: Supervised learning
	- Published: 2025Nov10
	- Summary: A machine learning model (Sol_ME) is used to assist in developing a lipid-based formulation for apalutamide with PK/PD evaluation for prostate cancer treatment.

- **[Targeting the glabellar frown lines with OnabotulinumtoxinA: In-silico evidence supporting concentrated, low-volume injection protocols.](https://pubmed.ncbi.nlm.nih.gov/40907830/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: Uses machine learning for off-target risk prediction integrated with mechanistic PK/PD modeling to optimize BoNT-A dosing protocols for glabellar frown line treatment.

- **[Neural Controlled Differential Equation and Its Application in Pharmacokinetics and Pharmacodynamics.](https://pubmed.ncbi.nlm.nih.gov/41241764/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2026Jan
	- Summary: This paper investigates neural controlled differential equations (NCDE) for data-driven PK/PD modeling, combining differential equation dynamics with ML flexibility.

- **[A simulation-based framework for modeling and prediction of personalized blood pressure trajectories in hypertensive patients after antihypertensive treatment.](https://pubmed.ncbi.nlm.nih.gov/40209154/)**
	- Methodology: Gaussian processes
	- Published: 2025
	- Summary: The paper develops a simulation framework for blood pressure trajectories using PK/PD modeling and evaluates Gaussian processes for predicting steady-state blood pressure under treatment.

- **[Antagonistic Trends Between Binding Affinity and Drug-Likeness in SARS-CoV-2 Mpro Inhibitors Revealed by Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40733553/)**
	- Methodology: Supervised learning
	- Published: 2025Jun30
	- Summary: Machine learning models (SVM and Logistic Regression) classify SARS-CoV-2 Mpro inhibitors based on IC50 data to reveal antagonistic trends between binding affinity and drug-likeness.

- **[Effect of Cumulative Exposure on the Efficacy of Paroxetine: A Population Pharmacokinetic-Pharmacodynamic and Machine Learning Analyses.](https://pubmed.ncbi.nlm.nih.gov/40358139/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Jun
	- Summary: Machine learning models predict paroxetine treatment remission using PK/PD data, with SHAP values explaining feature contributions for depression outcome prediction.

- **[State-space models are accurate and efficient neural operators for dynamical systems.](https://pubmed.ncbi.nlm.nih.gov/41447828/)**
	- Methodology: Deep learning, Neural networks, Mechanism-informed machine learning
	- Published: 2025Dec19
	- Summary: The paper introduces Mamba state-space models for physics-informed machine learning of dynamical systems, with application to tumor growth modeling in quantitative systems pharmacology.

- **[Comparison of time-series models for predicting physiological metrics under sedation.](https://pubmed.ncbi.nlm.nih.gov/39470955/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Jun
	- Summary: Compares statistical and deep learning time-series models (LSTM, GRU, TCN, Transformers) for predicting bispectral index to assess sedation depth during surgery.

## Pharmacokinetic modeling

- **[MolP-PC: a multi-view fusion and multi-task learning framework for drug ADMET property prediction.](https://pubmed.ncbi.nlm.nih.gov/41260779/)**
	- Methodology: Deep learning, Neural networks, Ensemble learning
	- Published: 2025Nov
	- Summary: Deep learning framework using multi-view fusion and multi-task learning to predict drug ADMET properties from molecular representations.

- **[Adaptive AI framework for pharmacokinetics using GATs, transformers, and AutoML.](https://pubmed.ncbi.nlm.nih.gov/41160339/)**
	- Methodology: Deep learning, Neural networks, Ensemble learning
	- Published: 2025Oct29
	- Summary: The paper presents an adaptive AI framework combining graph attention networks, transformers, and AutoML for real-time pharmacokinetic parameter prediction in drug discovery.

- **[Leveraging Neural ODEs for Population Pharmacokinetics of Dalbavancin in Sparse Clinical Data.](https://pubmed.ncbi.nlm.nih.gov/40566189/)**
	- Methodology: Deep learning, Neural networks, Explainable AI
	- Published: 2025Jun05
	- Summary: Neural ODEs are used as an alternative to traditional compartmental models for pharmacokinetic modeling of Dalbavancin, with SHAP analysis for model explainability.

- **[Advancing ADMET prediction through multiscale fragment-aware pretraining with MSformer-ADMET.](https://pubmed.ncbi.nlm.nih.gov/41021261/)**
	- Methodology: Deep learning
	- Published: 2025Aug31
	- Summary: MSformer-ADMET uses Transformer-based deep learning with multiscale fragment-aware pretraining to predict ADMET properties for drug development.

- **[Hybrid Population PK-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40654807/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models, Neural networks, Ensemble learning
	- Published: 2025May07
	- Summary: Combines machine learning algorithms with population PK Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients for better dose individualization.

- **[FormulationLAI: A physiology-based machine learning framework for accelerated development of long-acting injectable formulations.](https://pubmed.ncbi.nlm.nih.gov/41260272/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2026Jan10
	- Summary: The paper presents a computational framework integrating ML with PBPK modeling and MD simulations to accelerate long-acting injectable formulation development and optimization.

- **[Dynamic Contrast-enhanced MRI for Evaluating Breast Cancer Chemotherapy Response Using Conditional Generative Adversarial Networks.](https://pubmed.ncbi.nlm.nih.gov/41347917/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A conditional GAN is developed to rapidly translate DCE-MRI data to pharmacokinetic permeability maps for evaluating breast cancer chemotherapy response.

- **[PKSmart: an open-source computational model to predict intravenous pharmacokinetics of small molecules.](https://pubmed.ncbi.nlm.nih.gov/41013647/)**
	- Methodology: Supervised learning, Tree-based models
	- Published: 2025Sep26
	- Summary: Develops Random Forest machine learning models to predict human pharmacokinetic parameters from molecular structure and animal PK data for drug discovery.

- **[Prediction of Intravenous Pharmacokinetic Parameters across Multiple Species by a Multifidelity Deep Learning Framework.](https://pubmed.ncbi.nlm.nih.gov/41493218/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2026Jan26
	- Summary: A multifidelity deep learning framework using transfer learning to predict intravenous pharmacokinetic parameters across multiple species from molecular structures.

- **[Uncertainty estimates in pharmacokinetic modelling of DCE-MRI.](https://pubmed.ncbi.nlm.nih.gov/41371063/)**
	- Methodology: Deep learning, Neural networks, Ensemble learning, Hybrid mechanistic–ML models
	- Published: 2026Mar
	- Summary: The paper uses ensemble neural networks with uncertainty estimation to improve pharmacokinetic parameter quantification in DCE-MRI compared to conventional methods.

- **[Concentration monitoring and dose optimization for infliximab in Crohn's disease patients: a machine learning-based covariate ensemble model.](https://pubmed.ncbi.nlm.nih.gov/41438746/)**
	- Methodology: Ensemble learning
	- Published: 2025
	- Summary: Machine learning ensemble model developed to predict infliximab trough concentrations and optimize dosing for Crohn's disease patients in real-time.

- **[A Comparison of AI and Population PK Models to Predict the Concentrations of Antiepileptic Drugs Using Therapeutic Drug Monitoring Records.](https://pubmed.ncbi.nlm.nih.gov/41127895/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2025Oct
	- Summary: This study compares AI models (including ensemble and deep learning methods) with population PK models to predict antiepileptic drug concentrations using TDM data.

- **[Ensemble Machine Learning Model for Real-Time Valproic Acid Prediction in Epilepsy Treatment.](https://pubmed.ncbi.nlm.nih.gov/40456293/)**
	- Methodology: Ensemble learning, Tree-based models, Explainable AI
	- Published: 2025Jun02
	- Summary: Develops ensemble ML model using gradient boosting algorithms with SHAP interpretation to predict valproic acid concentrations for optimized epilepsy treatment dosing.

- **[Expert-Guided Substructure Information Bottleneck for Molecular Property Prediction.](https://pubmed.ncbi.nlm.nih.gov/40702819/)**
	- Methodology: Deep learning, Ensemble learning, Neural networks
	- Published: 2025Aug11
	- Summary: Proposes ESIB-Mol framework combining Mixture of Experts with Information Bottleneck principle for molecular property prediction using substructure-specific experts.

- **[In silico evaluation of pharmacokinetic properties and molecular docking for the identification of potential anticancer compounds.](https://pubmed.ncbi.nlm.nih.gov/40803051/)**
	- Methodology: Supervised learning
	- Published: 2026Feb
	- Summary: The paper uses in silico methods including QSAR/SAR/QSPR for predicting ADME-Tox properties and identifying potential anticancer compounds through molecular docking.

- **[MetaboGNN: predicting liver metabolic stability with graph neural networks and cross-species data.](https://pubmed.ncbi.nlm.nih.gov/40903787/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Sep03
	- Summary: MetaboGNN uses Graph Neural Networks with contrastive learning to predict liver metabolic stability across species, improving drug discovery predictions.

- **[Representation meets optimization: Training PINNs and PIKANs for gray-box discovery in systems pharmacology.](https://pubmed.ncbi.nlm.nih.gov/41447950/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2026Jan15
	- Summary: Compares Physics-Informed Neural Networks (PINNs) and Physics-Informed Kolmogorov-Arnold Networks (PIKANs) for gray-box system identification in pharmacokinetic and pharmacodynamic modeling.

- **[Prediction of Internal Exposures after Virtual Oral Doses of Disparate Chemicals in Rats and Humans Using Simplified Physiologically Based Pharmacokinetic Models with In Silico-Generated Input Parameters.](https://pubmed.ncbi.nlm.nih.gov/40628652/)**
	- Methodology: Supervised learning
	- Published: 2025Jul21
	- Summary: Uses machine learning to generate PBPK model input parameters from chemical descriptors for predicting internal exposures of diverse compounds in rats and humans.

- **[Prediction of Early Neoadjuvant Chemotherapy Response of Breast Cancer through Deep Learning-based Pharmacokinetic Quantification of DCE MRI.](https://pubmed.ncbi.nlm.nih.gov/40631989/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: Deep learning is used for pharmacokinetic quantification of DCE MRI to predict pathologic complete response to neoadjuvant chemotherapy in breast cancer patients.

- **[Research on the optimization model of anti-breast cancer candidate drugs based on machine learning.](https://pubmed.ncbi.nlm.nih.gov/40276676/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025
	- Summary: Machine learning models including Random Forest, LightGBM, and XGBoost with SHAP explainability are used to optimize anti-breast cancer drug candidates for biological activity and ADMET properties.

- **[Stochastic Gates for Covariate Selection in Population Pharmacokinetics Modeling.](https://pubmed.ncbi.nlm.nih.gov/41637692/)**
	- Methodology: Deep learning, Neural networks, Feature selection
	- Published: 2026Feb
	- Summary: Neural networks with stochastic gates are used for automated covariate selection in population pharmacokinetics modeling to efficiently identify relevant covariates.

- **[Dose-time-concentration prediction method based on GRU-TCN with temporal-channel attention.](https://pubmed.ncbi.nlm.nih.gov/41201288/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Nov07
	- Summary: The paper develops a GRU-TCN deep learning model with attention mechanisms for predicting drug concentration-time profiles to support precision dosing decisions.

- **[Prediction of pharmacokinetic/pharmacodynamic properties of aldosterone synthase inhibitors at drug discovery stage using an artificial intelligence-physiologically based pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40356995/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: An AI-PBPK model integrating machine learning with classical PBPK modeling is developed to predict PK/PD properties of aldosterone synthase inhibitors for drug discovery screening.

- **[Enhancing Chemical Prediction in Plasma Protein Binding: A Deep Learning Model Combining Molecular Descriptors and Fingerprint Representation With Attention Mechanisms.](https://pubmed.ncbi.nlm.nih.gov/40811414/)**
	- Methodology: Deep learning
	- Published: 2025Mar-Apr
	- Summary: A deep learning model combining molecular descriptors, fingerprints, and graph features with attention mechanisms to predict plasma protein binding properties of drug molecules.

- **[Uncovering Population PK Covariates from VAE-Generated Latent Spaces.](https://pubmed.ncbi.nlm.nih.gov/41336851/)**
	- Methodology: Deep learning, Feature selection, Unsupervised learning
	- Published: 2025Jul
	- Summary: Uses VAEs and LASSO regression to identify key covariates from PK profiles for improved population pharmacokinetic modeling and personalized dosing strategies.

- **[Shap-Cov: An Explainable Machine Learning Based Workflow for Rapid Covariate Identification in Population Modeling.](https://pubmed.ncbi.nlm.nih.gov/40601439/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Aug
	- Summary: The paper presents Shap-Cov, an explainable ML workflow using SHAP analysis for automated covariate identification in population PK/PD modeling with uncertainty quantification.

- **[Machine learning approach for personalized vancomycin steady-state trough concentration prediction: a superior approach over Bayesian population pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40575776/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning model developed to predict vancomycin steady-state trough concentrations for personalized dosing, compared against traditional Bayesian population PK approaches.

- **[A multi-compartment physiologically based pharmacokinetic (PBPK) model coupled with Fourier-ARIMA (auto regressive integrated moving average) for estimation and prediction of polychlorinated biphenyls (PCB) concentration in tuna.](https://pubmed.ncbi.nlm.nih.gov/40577972/)**
	- Methodology: Hybrid mechanistic–ML models, Time-series modeling
	- Published: 2025Sep
	- Summary: The paper develops a hybrid PBPK-Fourier-ARIMA model to predict PCB concentrations in tuna tissues, combining mechanistic modeling with time-series analysis for contamination forecasting.

- **[A Machine Learning-Empowered Quantitative Structure-Activity Relationship Model for Predicting the Plasma Half-life of Drugs in Dogs.](https://pubmed.ncbi.nlm.nih.gov/41254440/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov18
	- Summary: Deep neural networks and supervised ML algorithms are used to build QSAR models predicting drug plasma half-life in dogs from chemical structure descriptors.

- **[Machine learning-based prediction model for teicoplanin plasma concentrations in adults with liver disease using real-world data.](https://pubmed.ncbi.nlm.nih.gov/41424785/)**
	- Methodology: Supervised learning, Deep learning
	- Published: 2025
	- Summary: Machine learning and deep learning techniques are used to construct a prediction model for teicoplanin plasma concentrations in liver disease patients using real-world data.

- **[Integrative Profiling for BBB Permeability Using Capillary Electrochromatography, Experimental Physicochemical Parameters, and Ensemble Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/41516205/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2025Dec28
	- Summary: The paper uses ensemble machine learning methods including k-NN and time series classification to predict blood-brain barrier permeability from experimental data.

- **[Representation Meets Optimization: Training PINNs and PIKANs for Gray-Box Discovery in Systems Pharmacology.](https://pubmed.ncbi.nlm.nih.gov/40297233/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Apr10
	- Summary: Compares Physics-Informed Neural Networks (PINNs) and Physics-Informed Kolmogorov-Arnold Networks (PIKANs) for gray-box system identification in pharmacology modeling.

- **[AI-driven ANN and RSM-CCD integrated optimization of cinnarizine-domperidone bilayer tablet: In-vitro evaluation and in-silico PBPK modeling using GastroPlus®.](https://pubmed.ncbi.nlm.nih.gov/41546579/)**
	- Methodology: Neural networks, Surrogate modeling
	- Published: 2026Feb
	- Summary: The paper uses artificial neural networks (ANN) integrated with response surface methodology to optimize cinnarizine-domperidone bilayer tablet formulation with PBPK modeling validation.

- **[Pixel-level transformer GAN for enhanced parametric mapping of DCE MRI analysis.](https://pubmed.ncbi.nlm.nih.gov/40891183/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: The paper uses transformer GAN deep learning to enhance parametric mapping for DCE-MRI pharmacokinetic analysis in cancer diagnosis and monitoring.

- **[Machine learning approaches for assessing medication transfer to human breast milk.](https://pubmed.ncbi.nlm.nih.gov/40240653/)**
	- Methodology: Supervised learning, Neural networks, Tree-based models, Feature selection
	- Published: 2025Apr16
	- Summary: Machine learning algorithms including KNN, Random Forest, SVM, and Neural Networks are used to predict milk/plasma drug concentration ratios for breastfeeding safety assessment.

- **[Prediction of High-Dose Methotrexate Blood Concentration in Osteosarcoma Patients Using Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40336661/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025
	- Summary: Uses interpretable machine learning to predict high-dose methotrexate blood concentrations in osteosarcoma patients for early exposure prediction and toxicity prevention.

- **[Integrating Pharmacokinetics and Quantitative Systems Pharmacology Approaches in Generative Drug Design.](https://pubmed.ncbi.nlm.nih.gov/40343729/)**
	- Methodology: Reinforcement learning, Supervised learning
	- Published: 2025May26
	- Summary: The paper integrates AI/ML methods including reinforcement learning and QSPR models in a generative drug design framework to optimize both PK properties and receptor affinity.

- **[Optimizing Mycophenolate Therapy in Renal Transplant Patients Using Machine Learning and Population Pharmacokinetic Modeling.](https://pubmed.ncbi.nlm.nih.gov/41133517/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct20
	- Summary: The paper combines population pharmacokinetic modeling with machine learning techniques to optimize mycophenolate dosing for renal transplant patients.

- **[Predicting Vancomycin Clearance in Neonates and Infants by Integrating Machine Learning and Metabolomics With Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40616641/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Jul
	- Summary: Machine learning methods, particularly Gradient Boosting Regressor, are used to predict vancomycin clearance in neonates by integrating clinical covariates and metabolomics data.

- **[Estimation of Overall Cyclosporine Exposure Using Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40698833/)**
	- Methodology: Supervised learning, Tree-based models
	- Published: 2025Dec01
	- Summary: XGBoost machine learning models are developed to predict cyclosporine AUC using blood concentrations and compared against traditional Bayesian estimation methods.

- **[Integrating artificial intelligence and physiologically based pharmacokinetic modeling to predict in vitro and in vivo fate of amorphous solid dispersions.](https://pubmed.ncbi.nlm.nih.gov/40825400/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025Oct10
	- Summary: This paper integrates AI with PBPK modeling using TabPFN to predict molecular dissolution and systemic absorption of amorphous solid dispersions for drug development.

- **[QSAR Prediction of BBB Permeability Based on Machine Learning upon PETBD: A Novel Data Set of PET Tracers.](https://pubmed.ncbi.nlm.nih.gov/41494098/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI
	- Published: 2026Jan22
	- Summary: Machine learning models, particularly extreme gradient boosting, predict blood-brain barrier permeability and brain drug concentrations using a novel PET tracer dataset.

- **[Machine Learning-Based Model Selection and Averaging Outperform Single-Model Approaches for a Priori Vancomycin Precision Dosing.](https://pubmed.ncbi.nlm.nih.gov/40734640/)**
	- Methodology: Supervised learning, Tree-based models, Model selection, Ensemble learning
	- Published: 2025Oct
	- Summary: ML-based XGBoost model selects and averages population PK models for individualized vancomycin dosing, outperforming single-model approaches in precision dosing applications.

- **[Machine Learning Prediction and Validation of Plasma Concentration-Time Profiles.](https://pubmed.ncbi.nlm.nih.gov/40345671/)**
	- Methodology: Tree-based models, Supervised learning
	- Published: 2025Jun02
	- Summary: This study uses Random Forest models to predict plasma concentration-time profiles for remifentanil, demonstrating high accuracy on both virtual and real-world data sets.

- **[Prediction of plasma concentration-time profiles in mice using deep neural network integrated with pharmacokinetic models.](https://pubmed.ncbi.nlm.nih.gov/40250502/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Neural networks, Explainable AI
	- Published: 2025May15
	- Summary: Deep neural networks integrated with two-compartmental PK models to predict plasma concentration-time profiles in mice using chemical structure and ADME features.

- **[In-silico identification of a Doxorubicin alternative with reduced cardiotoxicity informed by LLM-assisted modeling.](https://pubmed.ncbi.nlm.nih.gov/41223606/)**
	- Methodology: LLM, Tree-based models, Explainable AI
	- Published: 2026Jan
	- Summary: LLM-assisted pipeline with random forest and SHAP for predicting ADME/ADMET properties to identify safer doxorubicin alternatives with reduced cardiotoxicity.

- **[Automatic detection of arterial input function for brain DCE-MRI in multi-site cohorts.](https://pubmed.ncbi.nlm.nih.gov/40808286/)**
	- Methodology: Deep learning
	- Published: 2025Dec
	- Summary: A deep learning model is developed to automatically extract arterial input functions from DCE-MRI images for quantitative pharmacokinetic modeling in multi-site cohorts.

- **[New Machine Learning Models for Predicting the Organic Cation Transporters OCT1, OCT2, and OCT3 Uptake.](https://pubmed.ncbi.nlm.nih.gov/41048715/)**
	- Methodology: Supervised learning, Tree-based models, Ensemble learning
	- Published: 2025Sep30
	- Summary: Machine learning models using decision tree ensemble algorithms predict organic cation transporter uptake to forecast pharmacokinetic liabilities in drug development.

- **[Hybrid Population Pharmacokinetic-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40885855/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: The paper develops a hybrid approach combining machine learning with population PK-based Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients.

- **[Improved pharmacokinetic parameter estimation from DCE-MRI via spatial-temporal information-driven unsupervised learning.](https://pubmed.ncbi.nlm.nih.gov/40987314/)**
	- Methodology: Unsupervised learning, Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Oct07
	- Summary: The paper develops STUDE, an unsupervised deep learning method combining CNNs and Vision Transformers to improve pharmacokinetic parameter estimation from DCE-MRI data.

- **[Opportunities for AI-based Model-informed Drug Development: A Comparative Analysis of NONMEM and AI-based Models for Population Pharmacokinetic Prediction.](https://pubmed.ncbi.nlm.nih.gov/41254220/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Nov18
	- Summary: This study compares AI/ML models including deep learning and neural ODEs against traditional NONMEM for population pharmacokinetic modeling to evaluate predictive performance improvements.

- **[Artificial intelligence modelling of tyrosine kinase inhibitors at risk of malabsorption and bioavailability-enhancing strategies.](https://pubmed.ncbi.nlm.nih.gov/40625205/)**
	- Methodology: Supervised learning
	- Published: 2025Nov
	- Summary: AI model developed to predict tyrosine kinase inhibitors at risk of malabsorption in patients with specific conditions and identify bioavailability enhancement strategies.

- **[ADME-drug-likeness: enriching molecular foundation models via pharmacokinetics-guided multi-task learning for drug-likeness prediction.](https://pubmed.ncbi.nlm.nih.gov/40662819/)**
	- Methodology: Deep learning, Supervised learning, Neural networks
	- Published: 2025Jul01
	- Summary: Deep learning pipeline enhances molecular foundation models via sequential ADME multi-task learning to improve drug-likeness prediction by incorporating pharmacokinetic factors.

- **[A machine learning model (Sol_ME) assisted development of a unit-dose lipid formulation for apalutamide: formulation, pharmacokinetics, and pharmacodynamics evaluation.](https://pubmed.ncbi.nlm.nih.gov/40858184/)**
	- Methodology: Supervised learning
	- Published: 2025Nov10
	- Summary: A machine learning model (Sol_ME) is used to assist in developing a lipid-based formulation for apalutamide with PK/PD evaluation for prostate cancer treatment.

- **[Neurotherapeutics across blood-brain barrier: screening of BBB-permeable and CNS-active molecules for neurodegenerative disease.](https://pubmed.ncbi.nlm.nih.gov/41079713/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning models are used to predict blood-brain barrier permeability and CNS activity for screening neurotherapeutic molecules in neurodegenerative disease drug discovery.

- **[Curated CYP450 Interaction Dataset: Covering the Majority of Phase I Drug Metabolism.](https://pubmed.ncbi.nlm.nih.gov/40813405/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Aug14
	- Summary: The paper presents a curated CYP450 interaction dataset and develops ML models including Graph Convolutional Networks to predict drug-enzyme interactions for metabolism prediction.

- **[Targeting the glabellar frown lines with OnabotulinumtoxinA: In-silico evidence supporting concentrated, low-volume injection protocols.](https://pubmed.ncbi.nlm.nih.gov/40907830/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: Uses machine learning for off-target risk prediction integrated with mechanistic PK/PD modeling to optimize BoNT-A dosing protocols for glabellar frown line treatment.

- **[Machine Learning Modeling for Predicting Infliximab Pharmacokinetics in Pediatric and Young Adult Patients With Crohn Disease: Leveraging Ensemble Modeling With Synthetic and Real-World Data.](https://pubmed.ncbi.nlm.nih.gov/40459932/)**
	- Methodology: Ensemble learning, Supervised learning
	- Published: 2026Feb01
	- Summary: This study develops an ensemble ML model to predict infliximab pharmacokinetics in pediatric Crohn disease patients using synthetic and real-world data for individualized dosing optimization.

- **[Machine learning enabled multiscale model for nanoparticle margination and physiology based pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40657536/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models
	- Published: 2025Jul
	- Summary: DeepONet neural network is integrated with mechanistic models to predict nanoparticle margination and biodistribution for targeted drug delivery applications.

- **[DeepTDM: Deep Learning-Based Prediction of Sequential Therapeutic Drug Monitoring Levels of Vancomycin.](https://pubmed.ncbi.nlm.nih.gov/41220794/)**
	- Methodology: Deep learning
	- Published: 2025
	- Summary: Deep learning is used to predict sequential vancomycin therapeutic drug monitoring levels in critically ill patients to optimize dosing and improve treatment outcomes.

- **[An Integrated AI-PBPK Platform for Predicting Drug In Vivo Fate and Tissue Distribution in Human and Inter-Species Extrapolation.](https://pubmed.ncbi.nlm.nih.gov/40418625/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct
	- Summary: Develops an integrated AI-PBPK platform using machine learning to predict drug properties from molecular structures, which feeds into PBPK models for human PK prediction.

- **[Improving Vancomycin Through Level Prediction with Machine Learning: A Comparative Study of Feature Selection and Model Performance.](https://pubmed.ncbi.nlm.nih.gov/41336096/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning models (Random Forest, LightGBM, XGBoost) are used to predict vancomycin trough levels for individualized dosing, outperforming traditional Bayesian methods.

- **[Oral bioavailability property prediction based on task similarity transfer learning.](https://pubmed.ncbi.nlm.nih.gov/40928678/)**
	- Methodology: Deep learning, Neural networks, Transfer learning
	- Published: 2025Sep10
	- Summary: The paper develops a transfer learning framework using graph neural networks and transformers to predict human oral bioavailability from molecular structures and physicochemical properties.

- **[A machine learning approach to population pharmacokinetic modelling automation.](https://pubmed.ncbi.nlm.nih.gov/40745042/)**
	- Methodology: Model selection
	- Published: 2025Jul31
	- Summary: This paper presents an automated machine learning approach using optimization algorithms (pyDarwin) to streamline population pharmacokinetic model development for extravascular drugs.

- **[Neural Controlled Differential Equation and Its Application in Pharmacokinetics and Pharmacodynamics.](https://pubmed.ncbi.nlm.nih.gov/41241764/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2026Jan
	- Summary: This paper investigates neural controlled differential equations (NCDE) for data-driven PK/PD modeling, combining differential equation dynamics with ML flexibility.

- **[Applying exposure-response analysis to enhance Mycophenolate Mofetil dosing precision in pediatric patients with immune-mediated renal diseases by machine learning models.](https://pubmed.ncbi.nlm.nih.gov/40447059/)**
	- Methodology: Supervised learning
	- Published: 2025Aug01
	- Summary: Machine learning models are applied to develop pharmacokinetic models for mycophenolic acid and optimize MMF dosing in pediatric patients with immune-mediated renal diseases.

- **[Fraction-based Linear Extrapolation (FLEX) Method for Predicting Human Pharmacokinetic Clearance: Advanced Allometric Scaling Method and Machine Learning Approach.](https://pubmed.ncbi.nlm.nih.gov/40931222/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: The paper develops a machine learning approach combined with advanced allometric scaling to predict human pharmacokinetic clearance using the FLEX method.

- **[A simulation-based framework for modeling and prediction of personalized blood pressure trajectories in hypertensive patients after antihypertensive treatment.](https://pubmed.ncbi.nlm.nih.gov/40209154/)**
	- Methodology: Gaussian processes
	- Published: 2025
	- Summary: The paper develops a simulation framework for blood pressure trajectories using PK/PD modeling and evaluates Gaussian processes for predicting steady-state blood pressure under treatment.

- **[Improving Absorption, Distribution, Metabolism, and Excretion Property Predictions by Integrating Public and Proprietary Data.](https://pubmed.ncbi.nlm.nih.gov/41290196/)**
	- Methodology: Supervised learning, Ensemble learning
	- Published: 2026Jan
	- Summary: This study uses supervised learning and multitask models to predict ADME properties by integrating public and proprietary datasets for improved drug discovery.

- **[Machine learning approach for dosage individualization of azithromycin in children with community-acquired pneumonia.](https://pubmed.ncbi.nlm.nih.gov/40181615/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning is used to predict azithromycin AUC0-24 in children with pneumonia to enable individualized dosing regimens.

- **[Machine learning-assisted tacrolimus dose optimization in childhood- onset systemic lupus erythematosus through population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/40684660/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: Machine learning algorithms are integrated with population pharmacokinetic modeling to predict individualized tacrolimus dosing for optimized therapy in childhood-onset systemic lupus erythematosus.

- **[Effect of Cumulative Exposure on the Efficacy of Paroxetine: A Population Pharmacokinetic-Pharmacodynamic and Machine Learning Analyses.](https://pubmed.ncbi.nlm.nih.gov/40358139/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Jun
	- Summary: Machine learning models predict paroxetine treatment remission using PK/PD data, with SHAP values explaining feature contributions for depression outcome prediction.

- **[Prediction of Permeability and Efflux Using Multitask Learning.](https://pubmed.ncbi.nlm.nih.gov/41280832/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov18
	- Summary: This paper uses multitask graph neural networks to predict cell membrane permeability and efflux endpoints for drug discovery applications.

- **[High-Throughput Physiologically Based Pharmacokinetic Model for Rodent Pharmacokinetics Prediction Using Machine Learning-Predicted Inputs and a Large In Vivo Pharmacokinetics Data Set.](https://pubmed.ncbi.nlm.nih.gov/41617209/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2026Jan30
	- Summary: The paper develops a high-throughput PBPK model (SwiftPK) that uses machine learning to predict in vitro parameters from chemical structures for rodent pharmacokinetic prediction.

- **[Enhancing the Predictive Power of Macrocyclic Drug Permeability by Knowledge Distillation from Analogous Pretraining Data.](https://pubmed.ncbi.nlm.nih.gov/41420604/)**
	- Methodology: Deep learning, Supervised learning, Explainable AI
	- Published: 2026Jan08
	- Summary: Multi_DDPP uses deep learning with knowledge distillation to predict macrocyclic drug membrane permeability from 2D molecular structures, improving drug development efficiency.

- **[Deep learning-assisted SERS platform for label-free detection of celecoxib in serum using ag@Pt@porous silicon Bragg mirror composite substrate.](https://pubmed.ncbi.nlm.nih.gov/41242102/)**
	- Methodology: Deep learning
	- Published: 2026Mar05
	- Summary: Deep learning models (GoogleNet, ResNet, VGG) are used to classify blood drug concentrations of celecoxib from SERS spectral data for therapeutic drug monitoring.

- **[DrugAppy - An end-to-end deep learning framework for computational drug discovery.](https://pubmed.ncbi.nlm.nih.gov/41110298/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: DrugAppy combines deep learning with computational chemistry methods for end-to-end drug discovery, predicting pharmacokinetics and activity against cancer targets.

- **[Precision dosing of voriconazole in immunocompromised children under 2 years: integrated machine learning and population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/41031158/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: The paper integrates machine learning with population pharmacokinetic modeling to develop individualized voriconazole dosing strategies for immunocompromised children under 2 years.

- **[Rational Design of Safer Inorganic Nanoparticles via Mechanistic Modeling-Informed Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40460056/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models, Explainable AI
	- Published: 2025Jun17
	- Summary: ML framework predicts nanoparticle toxicity by integrating PBPK modeling with binary classification models to enable rational design of safer inorganic nanoparticles.

- **[Deep learning enhances reliability of dynamic contrast-enhanced MRI in diffuse gliomas: bypassing post-processing and providing uncertainty maps.](https://pubmed.ncbi.nlm.nih.gov/40252095/)**
	- Methodology: Deep learning
	- Published: 2025Oct
	- Summary: Deep learning model directly estimates pharmacokinetic parameter maps from DCE-MRI in gliomas, bypassing traditional post-processing while providing uncertainty estimation.

- **[QSPR analysis of physico-chemical and pharmacological properties of medications for Parkinson's treatment utilizing neighborhood degree-based topological descriptors.](https://pubmed.ncbi.nlm.nih.gov/40374678/)**
	- Methodology: Supervised learning
	- Published: 2025May15
	- Summary: Uses machine learning with topological descriptors in QSPR analysis to predict physico-chemical and pharmacological properties of Parkinson's disease medications.

- **[Robust temporal knowledge inference via pathway snapshots with liquid neural network.](https://pubmed.ncbi.nlm.nih.gov/40349883/)**
	- Methodology: Deep learning, Reinforcement learning, Neural networks, AI Agents, Time-series modeling
	- Published: 2025Sep
	- Summary: The paper develops liquid neural network-based AI agents for temporal knowledge inference in disease pathways and drug pharmacokinetic processes using imitation learning.

- **[Microsensor Array for the Electrochemical Analysis of Hydroxyurea in Blood Samples of Children Affected by Sickle Cell Anemia.](https://pubmed.ncbi.nlm.nih.gov/41060845/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Model selection
	- Published: 2025Nov11
	- Summary: Machine learning models (elastic net, random forest, PLSR) are used to predict hydroxyurea levels from electrochemical microsensor data for pharmacokinetic analysis.

- **[A Real-Time Plasma Concentration Prediction Model for Voriconazole in Elderly Patients via Machine Learning Combined with Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40401163/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025
	- Summary: Machine learning combined with population pharmacokinetics to develop a real-time plasma concentration prediction model for voriconazole in elderly patients.

- **[Advancing the development of deep learning and machine learning models for oral drugs through diverse descriptor classes: a focus on pharmacokinetic parameters (Vdss and PPB).](https://pubmed.ncbi.nlm.nih.gov/40498231/)**
	- Methodology: Deep learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025Jun11
	- Summary: This paper develops deep learning and machine learning models to predict pharmacokinetic parameters (Vdss and PPB) for oral drugs using molecular descriptors and feature engineering.

- **[LSTM-Based Prediction of Human PK Profiles and Parameters for Intravenous Small Molecule Drugs Using ADME and Physicochemical Properties.](https://pubmed.ncbi.nlm.nih.gov/41147737/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Dec
	- Summary: LSTM neural networks are used to predict human pharmacokinetic concentration-time profiles and parameters for IV drugs using ADME and physicochemical properties.

- **[MMPK: A Multimodal Deep Learning Framework to Predict Human Oral Pharmacokinetic Parameters.](https://pubmed.ncbi.nlm.nih.gov/40741939/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025Aug14
	- Summary: MMPK uses multimodal deep learning to predict human oral pharmacokinetic parameters by integrating molecular graphs, substructures, and SMILES sequences.

- **[Dosing prediction of valproic acid in pediatric patients with epilepsy: population pharmacokinetic model or machine learning model?](https://pubmed.ncbi.nlm.nih.gov/40617982/)**
	- Methodology: Neural networks
	- Published: 2025Sep
	- Summary: This study compares population pharmacokinetic models with neural networks to predict valproic acid concentrations and optimize dosing in pediatric epilepsy patients.

- **[Development of Machine Learning and Chemical Language Model-Based QSAR Models for Predicting Drug Residue Depletion Half-Lives in Plasma and Tissues of Cattle Across Various Administration Routes.](https://pubmed.ncbi.nlm.nih.gov/41442152/)**
	- Methodology: Supervised learning, Deep learning, Neural networks, LLM, Ensemble learning
	- Published: 2025Dec24
	- Summary: Machine learning and chemical language models (ImprovedChemBERTa) are used to predict drug depletion half-lives in cattle plasma and tissues for food safety applications.

- **[DeepMetab: a comprehensive and mechanistically informed graph learning framework for end-to-end drug metabolism prediction.](https://pubmed.ncbi.nlm.nih.gov/40963553/)**
	- Methodology: Deep learning, Neural networks, Mechanism-informed machine learning
	- Published: 2025Oct15
	- Summary: DeepMetab uses graph neural networks with mechanistic knowledge to predict CYP450-mediated drug metabolism through integrated substrate profiling, site identification, and metabolite generation.

- **[Development of PBPK Population Model for End-Stage Renal Disease Patients to Inform OATP1B-, BCRP-, P-gp-, and CYP3A4-Mediated Drug Disposition with Individual Influencing Factors.](https://pubmed.ncbi.nlm.nih.gov/40871097/)**
	- Methodology: Supervised learning
	- Published: 2025Aug20
	- Summary: Machine learning is used to identify factors influencing individual clearance in a PBPK population model for end-stage renal disease patients to enable precision dosing.

- **[Utilization of Machine Learning Approaches for Drug Clearance Prediction and Population Pharmacokinetic Covariate Analysis.](https://pubmed.ncbi.nlm.nih.gov/40968579/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Explainable AI, Neural networks
	- Published: 2025Sep
	- Summary: This study applies multiple ML models including CNNs and gradient boosting with SHAP-based XAI for drug clearance prediction and covariate analysis in population pharmacokinetics.

- **[Gastric stress events impact the bioavailability of a poorly soluble weak base dabigatran from pellet-filled capsules: An outcome from pharmacokinetic simulations based on biorelevant dissolution testing, machine learning, and a novel timewise first-order dissolution model.](https://pubmed.ncbi.nlm.nih.gov/40086652/)**
	- Methodology: Surrogate modeling
	- Published: 2025Apr15
	- Summary: Machine learning generates dissolution profiles to overcome experimental limitations in biorelevant testing for PBBM-based pharmacokinetic simulations of dabigatran bioavailability.

- **[Application of Machine Learning and Mechanistic Modeling to Predict Intravenous Pharmacokinetic Profiles in Humans.](https://pubmed.ncbi.nlm.nih.gov/40146185/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Apr10
	- Summary: This paper develops machine learning models combined with physiologically based pharmacokinetic modeling to predict human IV pharmacokinetic profiles from compound properties.

- **[Meta-MolNet: A Cross-Domain Benchmark for Few Examples Drug Discovery.](https://pubmed.ncbi.nlm.nih.gov/40038923/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Mar
	- Summary: Introduces Meta-MolNet benchmark and Meta-GAT algorithm using graph attention networks with meta-learning for cross-domain molecular property prediction in drug discovery.

- **[Microdose Cocktail Study Reveals the Activity and Key Influencing Factors of OATP1B, P-Gp, BCRP, and CYP3A in End-Stage Renal Disease Patients.](https://pubmed.ncbi.nlm.nih.gov/39789999/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: Machine learning models were used alongside population pharmacokinetic modeling to identify key factors influencing drug transporter/enzyme activities in ESRD patients.

- **[Global Deep Forecasting with Patient-Specific Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/37965077/)**
	- Methodology: Deep learning, Hybrid mechanistic–ML models, Time-series modeling
	- Published: 2025Feb12
	- Summary: A hybrid global-local deep learning architecture with PK encoder forecasts blood glucose levels by incorporating patient-specific pharmacokinetic properties for improved accuracy.

- **[RSM and AI based machine learning for quality by design development of rivaroxaban push-pull osmotic tablets and its PBPK modeling.](https://pubmed.ncbi.nlm.nih.gov/40050302/)**
	- Methodology: Neural networks, Surrogate modeling
	- Published: 2025Mar07
	- Summary: ANN-based machine learning is used alongside RSM to optimize rivaroxaban osmotic tablet formulations, with PBPK modeling to predict in vivo performance.

- **[SERS based determination of ceftriaxone, ampicillin, and vancomycin in serum using WS2/Au@Ag nanocomposites and a 2D-CNN regression model.](https://pubmed.ncbi.nlm.nih.gov/39929115/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025May15
	- Summary: A 2D-CNN regression model is used with SERS spectroscopy to predict antibiotic concentrations in serum for therapeutic drug monitoring and personalized treatment.

- **[Refined ADME Profiles for ATC Drug Classes.](https://pubmed.ncbi.nlm.nih.gov/40142973/)**
	- Methodology: Supervised learning
	- Published: 2025Feb28
	- Summary: Machine learning models are developed to predict ADME properties of small molecules and analyze their distributions across different ATC drug classes to guide drug discovery.

- **[Rational Design of Safer Inorganic Nanoparticles via Mechanistic Modeling-informed Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40034433/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models, Explainable AI
	- Published: 2025Feb18
	- Summary: ML framework predicts nanoparticle toxicity by integrating PBPK modeling with binary classification models to enable rational design of safer inorganic nanoparticles.

- **[Estimation of Ganciclovir Exposure in Adults Transplant Patients by Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/40021573/)**
	- Methodology: Supervised learning
	- Published: 2025Feb28
	- Summary: Machine learning algorithms are trained and validated to accurately estimate ganciclovir AUC0-24h exposure in solid organ transplant patients for improved dosing.

- **[Highly Sensitive and Interference-Free Detection of Multiple Drug Molecules in Serum Using Dual-Modified SERS Substrates Combined with AI Algorithm Analysis.](https://pubmed.ncbi.nlm.nih.gov/39901357/)**
	- Published: 2025Feb18
	- Summary: AI algorithm is integrated to automatically recognize and analyze Raman spectral features for detecting multiple drug molecules in serum using SERS technology.

- **[Machine learning and population pharmacokinetics: a hybrid approach for optimizing vancomycin therapy in sepsis patients.](https://pubmed.ncbi.nlm.nih.gov/40162774/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models
	- Published: 2025Mar31
	- Summary: This study compares PPK, Bayesian, ML, and hybrid PPK-ML models for predicting vancomycin AUC24 to optimize dosing in sepsis patients using machine learning approaches.

- **[Probing the dark chemical matter against PDE4 for the management of psoriasis using in silico, in vitro and in vivo approach.](https://pubmed.ncbi.nlm.nih.gov/40095248/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning and AI were used for pharmacokinetics optimization in discovering novel PDE4D inhibitors from dark chemical matter for psoriasis treatment.

- **[Predicting Pharmacokinetics in Rats Using Machine Learning: A Comparative Study Between Empirical, Compartmental, and PBPK-Based Approaches.](https://pubmed.ncbi.nlm.nih.gov/40091606/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Mar
	- Summary: This study compares ML approaches integrated with empirical and mechanistic PK models to predict complete plasma concentration-time profiles in rats prior to synthesis.

- **[Comparing Scientific Machine Learning With Population Pharmacokinetic and Classical Machine Learning Approaches for Prediction of Drug Concentrations.](https://pubmed.ncbi.nlm.nih.gov/39921335/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025Apr
	- Summary: The paper compares a scientific machine learning framework (MMPK-SciML) with classical ML and population PK models for predicting drug plasma concentrations using fluorouracil and sunitinib datasets.

- **[Advancing exposure science through artificial intelligence: Neural ordinary differential equations for predicting blood concentrations of volatile organic compounds.](https://pubmed.ncbi.nlm.nih.gov/39978105/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Mar01
	- Summary: Neural ODEs are used to predict blood concentrations of volatile organic compounds, outperforming traditional PBPK models for toxicological forecasting and risk assessment.

## Postmarketing surveillance

- **[Application of surface-enhanced Raman scattering combined with artificial intelligence for multiplex detection of chemotherapeutic agents used in solid tumors.](https://pubmed.ncbi.nlm.nih.gov/41324706/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Dec01
	- Summary: The paper uses convolutional neural networks to analyze SERS spectra for automated detection and quantification of multiple chemotherapeutic drugs in serum.

- **[Discovering Severe Adverse Reactions From Pharmacokinetic Drug-Drug Interactions Through Literature Analysis and Electronic Health Record Verification.](https://pubmed.ncbi.nlm.nih.gov/39585167/)**
	- Methodology: Supervised learning, Deep learning
	- Published: 2025Apr
	- Summary: Uses NLP techniques including Named Entity Recognition and Relation Extraction to discover severe adverse drug reactions from drug-drug interactions through literature mining and EHR validation.

## Precision medicine / optimized treatment regimen

- **[Hybrid Population PK-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40654807/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models, Neural networks, Ensemble learning
	- Published: 2025May07
	- Summary: Combines machine learning algorithms with population PK Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients for better dose individualization.

- **[Comparison of Machine Learning Algorithms and Bayesian Estimation in Predicting Tacrolimus Concentration in Tunisian Kidney Transplant Patients During the Early Post-Transplant Period.](https://pubmed.ncbi.nlm.nih.gov/40338501/)**
	- Methodology: Tree-based models, Deep learning, Time-series modeling
	- Published: 2025May
	- Summary: Compares XGBoost and LSTM machine learning algorithms with Bayesian modeling for predicting tacrolimus concentrations to optimize dosing in kidney transplant patients.

- **[Multicycle Dosimetric Behavior and Dose-Effect Relationships in [177Lu]Lu-DOTATATE Peptide Receptor Radionuclide Therapy.](https://pubmed.ncbi.nlm.nih.gov/40274371/)**
	- Methodology: Deep learning
	- Published: 2025Jun02
	- Summary: Deep learning algorithm used for kidney segmentation in dosimetric analysis to develop personalized dosimetry-guided PRRT treatments for neuroendocrine tumors.

- **[Concentration monitoring and dose optimization for infliximab in Crohn's disease patients: a machine learning-based covariate ensemble model.](https://pubmed.ncbi.nlm.nih.gov/41438746/)**
	- Methodology: Ensemble learning
	- Published: 2025
	- Summary: Machine learning ensemble model developed to predict infliximab trough concentrations and optimize dosing for Crohn's disease patients in real-time.

- **[Model-informed Deep Q-Networks to Guide Infliximab Dosing in Pediatric Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40791331/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2025Jul18
	- Summary: Deep Q-Networks are used to automate and optimize infliximab dosing decisions for pediatric Crohn's disease patients by learning optimal strategies through reinforcement learning.

- **[A Comparison of AI and Population PK Models to Predict the Concentrations of Antiepileptic Drugs Using Therapeutic Drug Monitoring Records.](https://pubmed.ncbi.nlm.nih.gov/41127895/)**
	- Methodology: Supervised learning, Deep learning, Tree-based models, Ensemble learning
	- Published: 2025Oct
	- Summary: This study compares AI models (including ensemble and deep learning methods) with population PK models to predict antiepileptic drug concentrations using TDM data.

- **[Ensemble Machine Learning Model for Real-Time Valproic Acid Prediction in Epilepsy Treatment.](https://pubmed.ncbi.nlm.nih.gov/40456293/)**
	- Methodology: Ensemble learning, Tree-based models, Explainable AI
	- Published: 2025Jun02
	- Summary: Develops ensemble ML model using gradient boosting algorithms with SHAP interpretation to predict valproic acid concentrations for optimized epilepsy treatment dosing.

- **[Explainable Reasoning Path Inference of Anti-Cancer Drug Sensitivity on Genomic Knowledge Graph via Macro-Micro Agent Collaborative Reinforcement Learning.](https://pubmed.ncbi.nlm.nih.gov/40920533/)**
	- Methodology: Reinforcement learning, Deep learning, Explainable AI, AI Agents
	- Published: 2025Nov-Dec
	- Summary: The paper develops a dual-agent reinforcement learning system using knowledge graphs to predict anticancer drug sensitivity with explainable reasoning paths for precision medicine.

- **[Machine Learning-Based Algorithm for Tacrolimus Dose Optimization in Hospitalized Kidney Transplant Patients.](https://pubmed.ncbi.nlm.nih.gov/41374329/)**
	- Methodology: Supervised learning, Tree-based models, Deep learning, Neural networks, Ensemble learning, Explainable AI
	- Published: 2025Nov21
	- Summary: ML models (XGBoost, CatBoost, LightGBM, MLP) with ensemble approach predict tacrolimus concentrations for precision dosing optimization in kidney transplant patients.

- **[Artificial intelligence and precision medicine: a pilot study predicting optimal ceftaroline dosage for pediatric patients.](https://pubmed.ncbi.nlm.nih.gov/41626576/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning models are used to predict optimal ceftaroline dosage for pediatric patients to enable individualized therapy and overcome age-related physiological variability.

- **[Dose-time-concentration prediction method based on GRU-TCN with temporal-channel attention.](https://pubmed.ncbi.nlm.nih.gov/41201288/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Nov07
	- Summary: The paper develops a GRU-TCN deep learning model with attention mechanisms for predicting drug concentration-time profiles to support precision dosing decisions.

- **[Machine learning-guided clinical pharmacist interventions improve treatment outcomes in tuberculosis patients: a precision medicine approach.](https://pubmed.ncbi.nlm.nih.gov/41487272/)**
	- Methodology: Unsupervised learning
	- Published: 2025
	- Summary: Machine learning techniques are used to identify TB patient subtypes and optimize clinical pharmacist interventions for precision medicine treatment approaches.

- **[Uncovering Population PK Covariates from VAE-Generated Latent Spaces.](https://pubmed.ncbi.nlm.nih.gov/41336851/)**
	- Methodology: Deep learning, Feature selection, Unsupervised learning
	- Published: 2025Jul
	- Summary: Uses VAEs and LASSO regression to identify key covariates from PK profiles for improved population pharmacokinetic modeling and personalized dosing strategies.

- **[Machine learning approach for personalized vancomycin steady-state trough concentration prediction: a superior approach over Bayesian population pharmacokinetic model.](https://pubmed.ncbi.nlm.nih.gov/40575776/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: Machine learning model developed to predict vancomycin steady-state trough concentrations for personalized dosing, compared against traditional Bayesian population PK approaches.

- **[Optimizing Mycophenolate Therapy in Renal Transplant Patients Using Machine Learning and Population Pharmacokinetic Modeling.](https://pubmed.ncbi.nlm.nih.gov/41133517/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct20
	- Summary: The paper combines population pharmacokinetic modeling with machine learning techniques to optimize mycophenolate dosing for renal transplant patients.

- **[Predicting Vancomycin Clearance in Neonates and Infants by Integrating Machine Learning and Metabolomics With Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40616641/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Jul
	- Summary: Machine learning methods, particularly Gradient Boosting Regressor, are used to predict vancomycin clearance in neonates by integrating clinical covariates and metabolomics data.

- **[Machine Learning-Based Model Selection and Averaging Outperform Single-Model Approaches for a Priori Vancomycin Precision Dosing.](https://pubmed.ncbi.nlm.nih.gov/40734640/)**
	- Methodology: Supervised learning, Tree-based models, Model selection, Ensemble learning
	- Published: 2025Oct
	- Summary: ML-based XGBoost model selects and averages population PK models for individualized vancomycin dosing, outperforming single-model approaches in precision dosing applications.

- **[Mechanism-informed machine learning for individualized tacrolimus dose adjustment in the early post-kidney transplant period.](https://pubmed.ncbi.nlm.nih.gov/41531243/)**
	- Methodology: Mechanism-informed machine learning
	- Published: 2026Jan13
	- Summary: The paper develops mechanism-informed ML models to optimize individualized tacrolimus dosing in kidney transplant patients during the early post-transplant period.

- **[Hybrid Population Pharmacokinetic-Machine Learning Modeling to Predict Infliximab Pharmacokinetics in Pediatric and Young Adult Patients with Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/40885855/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: The paper develops a hybrid approach combining machine learning with population PK-based Bayesian methods to improve infliximab concentration predictions in pediatric Crohn's disease patients.

- **[Explainable cluster-based learning for prediction of postprandial glycemic events and insulin dose optimization in type 1 diabetes.](https://pubmed.ncbi.nlm.nih.gov/40956852/)**
	- Methodology: Supervised learning, Unsupervised learning, Tree-based models, Explainable AI, Ensemble learning
	- Published: 2025Sep
	- Summary: Uses cluster-based ensemble ML with explainable AI to predict postprandial glycemic events and optimize insulin dosing in type 1 diabetes patients.

- **[Beyond Algorithms: Machine Learning and Clinical Determinants of Voriconazole Plasma Levels in Therapeutic Drug Monitoring.](https://pubmed.ncbi.nlm.nih.gov/41288921/)**
	- Methodology: Supervised learning
	- Published: 2025Nov25
	- Summary: Machine learning is used to predict subtherapeutic or supratherapeutic voriconazole plasma levels for therapeutic drug monitoring optimization.

- **[Personalized Prediction of Clozapine Treatment Response Using Therapeutic Drug Monitoring Data in Japanese Patients with Treatment-Resistant Schizophrenia.](https://pubmed.ncbi.nlm.nih.gov/41227287/)**
	- Methodology: Tree-based models, Explainable AI
	- Published: 2025Nov06
	- Summary: Random forest model predicts clozapine treatment response in schizophrenia patients using TDM data, with SHAP analysis for model interpretability.

- **[Targeting the glabellar frown lines with OnabotulinumtoxinA: In-silico evidence supporting concentrated, low-volume injection protocols.](https://pubmed.ncbi.nlm.nih.gov/40907830/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Nov
	- Summary: Uses machine learning for off-target risk prediction integrated with mechanistic PK/PD modeling to optimize BoNT-A dosing protocols for glabellar frown line treatment.

- **[Machine Learning Modeling for Predicting Infliximab Pharmacokinetics in Pediatric and Young Adult Patients With Crohn Disease: Leveraging Ensemble Modeling With Synthetic and Real-World Data.](https://pubmed.ncbi.nlm.nih.gov/40459932/)**
	- Methodology: Ensemble learning, Supervised learning
	- Published: 2026Feb01
	- Summary: This study develops an ensemble ML model to predict infliximab pharmacokinetics in pediatric Crohn disease patients using synthetic and real-world data for individualized dosing optimization.

- **[PlasmoBridge: Stable hotspot engineering and targeted Surface-enhanced Raman spectroscopy (SERS) monitoring of methotrexate.](https://pubmed.ncbi.nlm.nih.gov/41082836/)**
	- Methodology: Deep learning
	- Published: 2026Jan15
	- Summary: The paper uses convolutional neural networks to enhance spectral analysis accuracy for methotrexate therapeutic drug monitoring via SERS technology.

- **[DeepTDM: Deep Learning-Based Prediction of Sequential Therapeutic Drug Monitoring Levels of Vancomycin.](https://pubmed.ncbi.nlm.nih.gov/41220794/)**
	- Methodology: Deep learning
	- Published: 2025
	- Summary: Deep learning is used to predict sequential vancomycin therapeutic drug monitoring levels in critically ill patients to optimize dosing and improve treatment outcomes.

- **[Circumventing glioblastoma resistance to temozolomide through optimal drug combinations designed by systems pharmacology and machine learning.](https://pubmed.ncbi.nlm.nih.gov/40229949/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning is used alongside systems pharmacology to design optimal drug combinations for overcoming temozolomide resistance in glioblastoma treatment.

- **[Improving Vancomycin Through Level Prediction with Machine Learning: A Comparative Study of Feature Selection and Model Performance.](https://pubmed.ncbi.nlm.nih.gov/41336096/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Explainable AI, Ensemble learning
	- Published: 2025Jul
	- Summary: Machine learning models (Random Forest, LightGBM, XGBoost) are used to predict vancomycin trough levels for individualized dosing, outperforming traditional Bayesian methods.

- **[Value Decomposition-Based Multi-Agent Learning for Anesthetics Collaborative Control.](https://pubmed.ncbi.nlm.nih.gov/40828726/)**
	- Methodology: Reinforcement learning, AI Agents, Tree-based models
	- Published: 2025Aug19
	- Summary: Multi-agent deep reinforcement learning framework for personalized collaborative control of multiple anesthetics (propofol and remifentanil) in closed-loop TIVA systems.

- **[Predicting prolonged dalbavancin exposure using machine learning: a validated strategy for individualized redosing.](https://pubmed.ncbi.nlm.nih.gov/41369581/)**
	- Methodology: Supervised learning
	- Published: 2026Jan07
	- Summary: Machine learning models, specifically support vector machines, were developed to predict dalbavancin plasma concentrations for individualized redosing decisions in clinical practice.

- **[Applying exposure-response analysis to enhance Mycophenolate Mofetil dosing precision in pediatric patients with immune-mediated renal diseases by machine learning models.](https://pubmed.ncbi.nlm.nih.gov/40447059/)**
	- Methodology: Supervised learning
	- Published: 2025Aug01
	- Summary: Machine learning models are applied to develop pharmacokinetic models for mycophenolic acid and optimize MMF dosing in pediatric patients with immune-mediated renal diseases.

- **[A simulation-based framework for modeling and prediction of personalized blood pressure trajectories in hypertensive patients after antihypertensive treatment.](https://pubmed.ncbi.nlm.nih.gov/40209154/)**
	- Methodology: Gaussian processes
	- Published: 2025
	- Summary: The paper develops a simulation framework for blood pressure trajectories using PK/PD modeling and evaluates Gaussian processes for predicting steady-state blood pressure under treatment.

- **[Model-Informed Deep Q-Networks to Guide Infliximab Dosing in Pediatric Crohn's Disease.](https://pubmed.ncbi.nlm.nih.gov/41189499/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2026Feb
	- Summary: Deep Q-Network reinforcement learning is used to automate and optimize infliximab dosing decisions for pediatric Crohn's disease patients using population PK models.

- **[Machine learning approach for dosage individualization of azithromycin in children with community-acquired pneumonia.](https://pubmed.ncbi.nlm.nih.gov/40181615/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Machine learning is used to predict azithromycin AUC0-24 in children with pneumonia to enable individualized dosing regimens.

- **[Machine learning-assisted tacrolimus dose optimization in childhood- onset systemic lupus erythematosus through population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/40684660/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: Machine learning algorithms are integrated with population pharmacokinetic modeling to predict individualized tacrolimus dosing for optimized therapy in childhood-onset systemic lupus erythematosus.

- **[Precision Dosing in Presence of Multiobjective Therapies by Integrating Reinforcement Learning and PK-PD Models: Application to Givinostat Treatment of Polycythemia Vera.](https://pubmed.ncbi.nlm.nih.gov/40325832/)**
	- Methodology: Hybrid mechanistic–ML models, Reinforcement learning
	- Published: 2025Jun
	- Summary: The paper integrates Q-Learning reinforcement learning with PK-PD models to develop adaptive dosing protocols for givinostat treatment in polycythemia vera patients.

- **[Improving Genotype Imputation in High-Dimensional Pharmacogenomics Using Multiple Imputation: Evaluation with Machine Learning Approaches.](https://pubmed.ncbi.nlm.nih.gov/41407383/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection
	- Published: 2025Dec17
	- Summary: The paper develops a multiple imputation framework using machine learning approaches including random forest and penalized regression for genotype imputation and covariate selection in pharmacogenomics.

- **[Decoding the gut microbiota metabolite-matrix metalloproteinase-3 axis in breast cancer: a multi-omics and network pharmacology study.](https://pubmed.ncbi.nlm.nih.gov/40946247/)**
	- Methodology: Supervised learning, Explainable AI
	- Published: 2025Sep14
	- Summary: This study uses machine learning with SHAP explainability to identify gut microbiota metabolites as potential therapeutic targets for breast cancer treatment via MMP3 axis.

- **[Precision dosing of voriconazole in immunocompromised children under 2 years: integrated machine learning and population pharmacokinetic modeling.](https://pubmed.ncbi.nlm.nih.gov/41031158/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: The paper integrates machine learning with population pharmacokinetic modeling to develop individualized voriconazole dosing strategies for immunocompromised children under 2 years.

- **[Nephrocast-V: A Deep Learning Model for the Prediction of Vancomycin Trough Concentration Using Electronic Health Record Data.](https://pubmed.ncbi.nlm.nih.gov/41025800/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: A deep learning model is developed to predict vancomycin trough concentrations using electronic health record data to optimize therapeutic dosing.

- **[A Real-Time Plasma Concentration Prediction Model for Voriconazole in Elderly Patients via Machine Learning Combined with Population Pharmacokinetics.](https://pubmed.ncbi.nlm.nih.gov/40401163/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025
	- Summary: Machine learning combined with population pharmacokinetics to develop a real-time plasma concentration prediction model for voriconazole in elderly patients.

- **[A translational multimodal machine-learning prototype predicting valproate response in epilepsy treatment.](https://pubmed.ncbi.nlm.nih.gov/40909818/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025Aug27
	- Summary: Develops a multimodal machine learning classifier integrating genetic and in-vitro data to predict valproate treatment response in epilepsy patients for personalized treatment decisions.

- **[Development of PBPK Population Model for End-Stage Renal Disease Patients to Inform OATP1B-, BCRP-, P-gp-, and CYP3A4-Mediated Drug Disposition with Individual Influencing Factors.](https://pubmed.ncbi.nlm.nih.gov/40871097/)**
	- Methodology: Supervised learning
	- Published: 2025Aug20
	- Summary: Machine learning is used to identify factors influencing individual clearance in a PBPK population model for end-stage renal disease patients to enable precision dosing.

- **[Optimizing Initial Vancomycin Dosing in Hospitalized Patients Using Machine Learning Approach for Enhanced Therapeutic Outcomes: Algorithm Development and Validation Study.](https://pubmed.ncbi.nlm.nih.gov/40163845/)**
	- Methodology: Supervised learning
	- Published: 2025Mar31
	- Summary: Machine learning approach is used to develop and validate an algorithm for optimizing initial vancomycin dosing in hospitalized patients to enhance therapeutic outcomes.

- **[Accelerating virtual patient generation with a Bayesian optimization and machine learning surrogate model.](https://pubmed.ncbi.nlm.nih.gov/39630593/)**
	- Methodology: Bayesian ML, Surrogate modeling
	- Published: 2025Mar
	- Summary: The paper uses Bayesian optimization with machine learning surrogate models to accelerate virtual patient generation for QSP model validation in clinical trial simulations.

- **[Deep reinforcement learning for multi-targets propofol dosing.](https://pubmed.ncbi.nlm.nih.gov/40045084/)**
	- Methodology: Reinforcement learning, Deep learning
	- Published: 2025Jun
	- Summary: This paper applies deep reinforcement learning (TD3 algorithm) to automate propofol dosing for maintaining multiple physiological parameters within safe ranges during anesthesia.

- **[SERS based determination of ceftriaxone, ampicillin, and vancomycin in serum using WS2/Au@Ag nanocomposites and a 2D-CNN regression model.](https://pubmed.ncbi.nlm.nih.gov/39929115/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025May15
	- Summary: A 2D-CNN regression model is used with SERS spectroscopy to predict antibiotic concentrations in serum for therapeutic drug monitoring and personalized treatment.

- **[Deep Learning-Assisted SERS for Therapeutic Drug Monitoring of Clozapine in Serum on Plasmonic Metasurfaces.](https://pubmed.ncbi.nlm.nih.gov/40111434/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Apr02
	- Summary: Deep learning with artificial neural networks is integrated with SERS for rapid therapeutic drug monitoring of clozapine and metabolites in human serum.

- **[Long short-term memory algorithm for personalized tacrolimus dosing: A simple and effective time series forecasting approach post-lung transplantation.](https://pubmed.ncbi.nlm.nih.gov/39510206/)**
	- Methodology: Deep learning, Neural networks, Time-series modeling
	- Published: 2025Mar
	- Summary: Uses LSTM neural networks for time series forecasting to predict tacrolimus trough levels and optimize dosing in lung transplant patients.

- **[Virtual patients inspired by multiomics predict the efficacy of an anti-IFNα mAb in cutaneous lupus.](https://pubmed.ncbi.nlm.nih.gov/39925417/)**
	- Methodology: Unsupervised learning, Supervised learning, Hybrid mechanistic–ML models
	- Published: 2025Feb21
	- Summary: Uses multiomics clustering to identify patient subgroups, then applies ML with mechanistic modeling to predict anti-IFNα antibody treatment responses in virtual lupus patients.

- **[Assessing GPT-4's accuracy in answering clinical pharmacological questions on pain therapy.](https://pubmed.ncbi.nlm.nih.gov/40066678/)**
	- Methodology: LLM
	- Published: 2025Aug
	- Summary: This study evaluates GPT-4's accuracy in answering clinical pharmacological questions about pain therapy to assess its potential as a patient-facing medical information tool.

- **[Machine learning and population pharmacokinetics: a hybrid approach for optimizing vancomycin therapy in sepsis patients.](https://pubmed.ncbi.nlm.nih.gov/40162774/)**
	- Methodology: Supervised learning, Tree-based models, Hybrid mechanistic–ML models
	- Published: 2025Mar31
	- Summary: This study compares PPK, Bayesian, ML, and hybrid PPK-ML models for predicting vancomycin AUC24 to optimize dosing in sepsis patients using machine learning approaches.

- **[Comparing Scientific Machine Learning With Population Pharmacokinetic and Classical Machine Learning Approaches for Prediction of Drug Concentrations.](https://pubmed.ncbi.nlm.nih.gov/39921335/)**
	- Methodology: Hybrid mechanistic–ML models, Supervised learning
	- Published: 2025Apr
	- Summary: The paper compares a scientific machine learning framework (MMPK-SciML) with classical ML and population PK models for predicting drug plasma concentrations using fluorouracil and sunitinib datasets.

## RWD phenotyping

- **[Network-based disease fingerprinting with neuroinflammation PET imaging.](https://pubmed.ncbi.nlm.nih.gov/41282214/)**
	- Methodology: Supervised learning, Unsupervised learning
	- Published: 2025Oct21
	- Summary: Machine learning classifiers are applied to network-based TSPO PET imaging data to identify disease-specific neuroinflammatory patterns and classify different neurological conditions.

## Survival analysis

- **[Machine Learning Models of Early Longitudinal Toxicity Trajectories Predict Cetuximab Concentration and Metastatic Colorectal Cancer Survival in the Canadian Cancer Trials Group/AGITG CO.17/20 Trials.](https://pubmed.ncbi.nlm.nih.gov/40215447/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: Machine learning models analyze early toxicity trajectories to predict cetuximab concentration and survival outcomes in metastatic colorectal cancer patients.

- **[Metabolomics and lipidomics predictor of survival in hepatocellular carcinoma patients receiving tyrosine kinase inhibitor and immune checkpoint inhibitor combination therapy.](https://pubmed.ncbi.nlm.nih.gov/41265377/)**
	- Methodology: Supervised learning, Tree-based models, Feature selection, Ensemble learning
	- Published: 2025Dec
	- Summary: Machine learning framework combining random forest, LASSO regression, and Cox modeling to identify metabolomic and lipidomic biomarkers predicting survival in HCC patients.

## Reviews / Tutorials / Perspectives

- **[A Novel Perspective on Using Artificial Intelligence and Nanoinformatics to Develop Nanomedicines.](https://pubmed.ncbi.nlm.nih.gov/41568483/)**
	- Methodology: Supervised learning
	- Published: 2026Jan09
	- Summary: This review surveys AI/ML applications in nanomedicine development, focusing on QSAR/QSPR models and PBPK modeling for optimizing physicochemical properties and predicting biodistribution.

- **[A Review on AI-Based Data-Driven Models for Optimization of Nanocarriers as Drug Delivery Systems.](https://pubmed.ncbi.nlm.nih.gov/41668335/)**
	- Methodology: Supervised learning, Unsupervised learning, Hybrid mechanistic–ML models
	- Published: 2026Feb10
	- Summary: This review surveys AI/ML approaches for optimizing nanocarrier drug delivery systems, covering supervised/unsupervised learning and hybrid models for PK/PD, toxicity prediction, and personalized medicine.

- **[A Review on New Frontiers in Drug-Drug Interaction Predictions and Safety Evaluations with In Vitro Cellular Models.](https://pubmed.ncbi.nlm.nih.gov/40574059/)**
	- Published: 2025Jun06
	- Summary: This review surveys conventional and AI-enhanced methods for predicting drug-drug interactions, highlighting artificial intelligence applications in DDI safety evaluations.

- **[A new chapter in pharmacology: Artificial intelligence's expanding role in pharmacokinetics, pharmacodynamics, and pharmacovigilance.](https://pubmed.ncbi.nlm.nih.gov/41093670/)**
	- Methodology: Supervised learning, Deep learning, Neural networks, Hybrid mechanistic–ML models
	- Published: 2025Sep16
	- Summary: This narrative review surveys AI applications in pharmacokinetics, pharmacodynamics, and pharmacovigilance, highlighting machine learning and neural network approaches.

- **[A new perspective on antimicrobial therapeutic drug monitoring: Surface-enhanced Raman spectroscopy.](https://pubmed.ncbi.nlm.nih.gov/40154051/)**
	- Methodology: Supervised learning
	- Published: 2025Sep01
	- Summary: This review surveys SERS techniques for antimicrobial therapeutic drug monitoring, including machine learning data processing methods for personalized treatment.

- **[AAV Gene Therapy Drug Development and Translation of Engineered Ocular and Neurotropic Capsids: A Systematic Review Using Natural Language Processing.](https://pubmed.ncbi.nlm.nih.gov/41316525/)**
	- Methodology: Supervised learning
	- Published: 2025Dec
	- Summary: This systematic review uses Natural Language Processing to identify and categorize engineered AAV capsids for neurotropic and ocular applications from PubMed abstracts.

- **[AI for NONMEM Coding in Pharmacometrics Research and Education: Shortcut or Pitfall?](https://pubmed.ncbi.nlm.nih.gov/41187068/)**
	- Methodology: LLM
	- Published: 2025Dec
	- Summary: This paper evaluates seven Large Language Models for generating NONMEM code in pharmacometric modeling tasks and discusses AI applications in pharmacometrics education.

- **[AI screening of nuclear medicine safety breaches: patterns, causes, and opportunities for improved protocols: a systematic review.](https://pubmed.ncbi.nlm.nih.gov/41166047/)**
	- Published: 2026Jan
	- Summary: A systematic review examining AI applications for screening, predicting, and preventing nuclear medicine safety incidents and occupational exposure risks for healthcare professionals.

- **[AI-driven precision in prostate brachytherapy: A systematic review of 70 studies.](https://pubmed.ncbi.nlm.nih.gov/41474559/)**
	- Methodology: Deep learning, Reinforcement learning
	- Published: 2025Oct01
	- Summary: Systematic review of 70 studies evaluating AI/ML applications in prostate brachytherapy for imaging, treatment planning, and outcome prediction using deep learning and reinforcement learning.

- **[AI-powered in silico twins: redefining precision medicine through simulation, personalization, and predictive healthcare.](https://pubmed.ncbi.nlm.nih.gov/41441931/)**
	- Methodology: Hybrid mechanistic–ML models, Deep learning, Neural networks
	- Published: 2025Dec24
	- Summary: This review explores AI-powered in silico twins that integrate mechanistic modeling with ML for personalized medicine, predictive diagnostics, and therapeutic optimization.

- **[Advancements in radiation dose reduction for pediatric CT head Imaging: A scoping review of emerging Technologies, Protocols, and optimization strategies.](https://pubmed.ncbi.nlm.nih.gov/41567817/)**
	- Methodology: Deep learning
	- Published: 2026Mar
	- Summary: A scoping review of radiation dose reduction techniques in pediatric CT head imaging, highlighting deep learning image reconstruction algorithms as advanced AI-based solutions.

- **[Advances and Challenges in Drug Screening for Cancer Therapy: A Comprehensive Review.](https://pubmed.ncbi.nlm.nih.gov/41463612/)**
	- Methodology: Supervised learning
	- Published: 2025Dec01
	- Summary: This review surveys AI-enabled modeling for cancer drug response prediction, biomarker development, and rational drug combinations in precision oncology screening platforms.

- **[Advances in Cytotoxicity Testing: From In Vitro Assays to In Silico Models.](https://pubmed.ncbi.nlm.nih.gov/41303685/)**
	- Methodology: Supervised learning
	- Published: 2025Nov19
	- Summary: This review surveys advances in cytotoxicity testing including AI/ML methods like QSAR and machine learning for drug toxicity prediction and computational toxicology.

- **[Advances in nanorobotics for gastrointestinal surgery: a new frontier in precision medicine and minimally invasive therapeutics.](https://pubmed.ncbi.nlm.nih.gov/40660043/)**
	- Methodology: AI Agents
	- Published: 2025Jul14
	- Summary: This review surveys AI-integrated nanorobotics for precision gastrointestinal surgery, focusing on intelligent autonomous agents for minimally invasive therapeutics.

- **[Advancing Drug-Drug Interaction Prediction with Biomimetic Improvements: Leveraging the Latest Artificial Intelligence Techniques to Guide Researchers in the Field.](https://pubmed.ncbi.nlm.nih.gov/41589955/)**
	- Methodology: Supervised learning, Deep learning, Neural networks, Ensemble learning
	- Published: 2026Jan05
	- Summary: This review comprehensively surveys AI/ML methods for drug-drug interaction prediction, covering classical ML, deep learning, graph-based models, and biomimetic approaches.

- **[Advancing PROTAC Discovery Through Artificial Intelligence: Opportunities, Challenges, and Future Directions.](https://pubmed.ncbi.nlm.nih.gov/41471282/)**
	- Methodology: Deep learning, Supervised learning, Neural networks
	- Published: 2025Nov25
	- Summary: This review surveys AI/ML applications in PROTAC drug discovery, covering structure prediction, degradability prediction, linker design, and ADME property estimation.

- **[Advancing antibiotic discovery with bacterial cytological profiling: a high-throughput solution to antimicrobial resistance.](https://pubmed.ncbi.nlm.nih.gov/40018674/)**
	- Methodology: Deep learning
	- Published: 2025
	- Summary: This review surveys bacterial cytological profiling for antibiotic discovery and discusses how AI/deep learning techniques could enhance analysis of BCP data.

- **[Advancing drug development with "Fit-for-Purpose" modeling informed approaches.](https://pubmed.ncbi.nlm.nih.gov/40952534/)**
	- Published: 2025Sep15
	- Summary: This review surveys MIDD approaches across drug development stages and explores the evolving role of AI/ML in enhancing traditional pharmacometric modeling methodologies.

- **[Agents for Change: Artificial Intelligent Workflows for Quantitative Clinical Pharmacology and Translational Sciences.](https://pubmed.ncbi.nlm.nih.gov/40055986/)**
	- Methodology: AI Agents
	- Published: 2025Mar
	- Summary: This review explores how AI-powered agentic workflows can transform quantitative clinical pharmacology and translational sciences by automating routine tasks and streamlining analyses.

- **[Antimicrobial peptides and proteins: Mechanism of action and therapeutic potential.](https://pubmed.ncbi.nlm.nih.gov/41581931/)**
	- Published: 2026
	- Summary: This review discusses antimicrobial peptides and proteins as therapeutic solutions, briefly mentioning AI-based computational tools for peptide prediction and AMP discovery.

- **[Antimicrobial peptides: Bioinformatic advances and translational therapeutics to combat antibiotic resistance.](https://pubmed.ncbi.nlm.nih.gov/41581929/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2026
	- Summary: This review surveys machine learning and deep learning applications in antimicrobial peptide research for therapeutic development against antibiotic resistance.

- **[Application and research progress on artificial intelligence in the quality of Traditional Chinese Medicine.](https://pubmed.ncbi.nlm.nih.gov/41181603/)**
	- Methodology: Supervised learning, Unsupervised learning, Deep learning
	- Published: 2025
	- Summary: This review surveys AI/ML applications in Traditional Chinese Medicine quality control, covering machine learning and deep learning methods for quality assessment and safety evaluation.

- **[Application of Surface-Enhanced Raman Spectroscopy in Head and Neck Cancer Diagnosis.](https://pubmed.ncbi.nlm.nih.gov/39951652/)**
	- Methodology: Deep learning
	- Published: 2025Feb25
	- Summary: This review examines SERS applications in head and neck cancer diagnosis and explores its integration with AI including machine learning and deep learning for precision oncology.

- **[Approaches to Scaffold Hopping for Identifying New Bioactive Compounds and the Contribution of Artificial Intelligence.](https://pubmed.ncbi.nlm.nih.gov/41208066/)**
	- Methodology: Deep learning
	- Published: 2025Nov05
	- Summary: This review surveys AI/ML applications, particularly deep learning, in scaffold hopping strategies for identifying new bioactive compounds in drug development.

- **[Artificial Intelligence (AI) in Pharmaceutical Formulation and Dosage Calculations.](https://pubmed.ncbi.nlm.nih.gov/41304779/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov07
	- Summary: This review surveys AI/ML applications in pharmaceutical formulation and dosage calculations, covering ML, DL, and NLP for drug property prediction, PK/PD modeling, and precision medicine.

- **[Artificial Intelligence Models and Tools for the Assessment of Drug-Herb Interactions.](https://pubmed.ncbi.nlm.nih.gov/40143062/)**
	- Published: 2025Feb20
	- Summary: This review discusses AI approaches for predicting drug-herb interactions and associated adverse reactions by analyzing chemical structures and pharmacological properties.

- **[Artificial Intelligence and Predictive Modelling for Precision Dosing of Immunosuppressants in Kidney Transplantation.](https://pubmed.ncbi.nlm.nih.gov/41599762/)**
	- Methodology: Bayesian ML, Explainable AI, Hybrid mechanistic–ML models
	- Published: 2026Jan16
	- Summary: This review assesses AI/ML approaches including Bayesian models, machine learning, and hybrid AI frameworks for precision dosing of immunosuppressants in kidney transplantation.

- **[Artificial Intelligence in Ocular Drug Delivery: Precision Drug Delivery's New Horizon.](https://pubmed.ncbi.nlm.nih.gov/41388211/)**
	- Published: 2025Dec12
	- Summary: This review paper surveys AI applications in ocular drug delivery, focusing on optimizing drug combinations, designing smart delivery systems, and personalizing ophthalmic therapies.

- **[Artificial Intelligence in Pharmaceutical Drug Development: Transforming Formulation and Innovation.](https://pubmed.ncbi.nlm.nih.gov/40873220/)**
	- Methodology: Supervised learning
	- Published: 2025Aug25
	- Summary: This review surveys AI applications in pharmaceutical drug development, covering drug discovery, formulation design, PK/toxicity prediction, and personalized medicine approaches.

- **[Artificial Intelligence to Guide Repurposing of Drugs.](https://pubmed.ncbi.nlm.nih.gov/41592930/)**
	- Methodology: Supervised learning, Unsupervised learning, Deep learning
	- Published: 2026Jan
	- Summary: This review surveys AI/ML applications in drug repurposing, discussing how artificial intelligence can guide the identification of new therapeutic uses for existing drugs.

- **[Artificial Intelligence-Driven Nanoarchitectonics for Smart Targeted Drug Delivery.](https://pubmed.ncbi.nlm.nih.gov/40772340/)**
	- Methodology: Supervised learning, Deep learning, Mechanism-informed machine learning
	- Published: 2025Oct
	- Summary: This perspective introduces an AI-driven nanoarchitectonics framework for targeted drug delivery using ML for surface engineering and in silico modeling of delivery dynamics.

- **[Artificial intelligence and machine learning for precision warfarin dosing: a comprehensive narrative review.](https://pubmed.ncbi.nlm.nih.gov/41649565/)**
	- Methodology: Supervised learning
	- Published: 2026Feb06
	- Summary: This comprehensive narrative review surveys AI/ML methods for precision warfarin dosing to optimize anticoagulation therapy and improve patient outcomes.

- **[Artificial intelligence coupled to pharmacometrics modelling to tailor malaria and tuberculosis treatment in Africa.](https://pubmed.ncbi.nlm.nih.gov/41115876/)**
	- Methodology: LLM, Supervised learning
	- Published: 2025Oct20
	- Summary: Proposes coupling machine learning and LLMs with PBPK/NLME modeling to identify drug-gene pairs and optimize dosing for malaria/tuberculosis treatment in African populations.

- **[Artificial intelligence for radiopharmaceutical and molecular imaging.](https://pubmed.ncbi.nlm.nih.gov/41477342/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2025Dec
	- Summary: This review surveys AI/ML applications in radiopharmaceutical development and molecular imaging, focusing on deep learning methods for drug discovery and image analytics.

- **[Artificial intelligence guided dosing decisions: a qualitative study on health care provider perspectives.](https://pubmed.ncbi.nlm.nih.gov/41033693/)**
	- Published: 2025Sep30
	- Summary: A qualitative study examining healthcare providers' perspectives on AI-guided precision dosing, identifying barriers and enablers for clinical adoption.

- **[Artificial intelligence in clinical pharmacy-A systematic review of current scenario and future perspectives.](https://pubmed.ncbi.nlm.nih.gov/41146680/)**
	- Published: 2025Jan-Dec
	- Summary: A systematic review synthesizing current AI applications in clinical pharmacy, focusing on medication error reduction, drug dosing optimization, and personalized medicine implementation.

- **[Artificial intelligence in the development of small nucleic acid therapeutics: toward smarter and safer medicines.](https://pubmed.ncbi.nlm.nih.gov/41077123/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov
	- Summary: This review surveys AI methodologies for designing and optimizing small nucleic acid therapeutics, comparing approaches for improving drug stability and pharmacokinetics.

- **[Artificial intelligence to predict inhibitors of drug-metabolizing enzymes and transporters for safer drug design.](https://pubmed.ncbi.nlm.nih.gov/40241626/)**
	- Methodology: Supervised learning
	- Published: 2025May
	- Summary: This review paper surveys AI techniques for predicting inhibitors of drug-metabolizing enzymes and transporters to improve drug safety in development.

- **[Artificial intelligence-enabled nanomedicine: enhancing drug design and predictive modeling in pharmaceutics.](https://pubmed.ncbi.nlm.nih.gov/41353571/)**
	- Methodology: Deep learning, Reinforcement learning, Neural networks
	- Published: 2025Dec07
	- Summary: This review explores AI-driven methods integrated with nanomedicine for enhanced drug delivery, pharmacokinetic predictions, and personalized therapeutics development.

- **[Bioanalysis of antihypertensive drugs by LC-MS: a fleeting look at the regulatory guidelines and artificial intelligence.](https://pubmed.ncbi.nlm.nih.gov/40256889/)**
	- Published: 2025Apr
	- Summary: This review surveys LC-MS bioanalytical methods for antihypertensive drugs with only a brief mention of AI/ML potential in bioanalysis without specific applications or methods.

- **[Building Hybrid Pharmacometric-Machine Learning Models in Oncology Drug Development: Current State and Recommendations.](https://pubmed.ncbi.nlm.nih.gov/41104621/)**
	- Methodology: Hybrid mechanistic–ML models, Feature selection, Model selection, Explainable AI
	- Published: 2026Jan
	- Summary: This tutorial reviews hybrid pharmacometric-machine learning models in oncology drug development and proposes standardized workflows and reporting checklists for improved reliability.

- **[Can alternatives to animal testing yield useful information regarding biological mechanisms and drug discovery?](https://pubmed.ncbi.nlm.nih.gov/41542102/)**
	- Methodology: Supervised learning
	- Published: 2025Nov
	- Summary: This review surveys alternative methods to animal testing including machine learning approaches for drug discovery, PK/PD modeling, and predicting drug efficacy and interactions.

- **[Chemical risk assessment in food animals via physiologically based pharmacokinetic modeling - Part II: Environmental pollutants on animal and human health assessments.](https://pubmed.ncbi.nlm.nih.gov/40106874/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Apr
	- Summary: Review of PBPK models for environmental pollutants in food animals that discusses future integration of machine learning and AI to enhance human health risk assessment.

- **[Clinical and Quantitative Pharmacology Considerations of mRNA Therapeutics and Vaccine Development: Bridging Translational and Platform Gaps for Enhanced Decision Making.](https://pubmed.ncbi.nlm.nih.gov/41085467/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Dec
	- Summary: This paper proposes a framework integrating AI/ML with traditional modeling approaches for mRNA therapeutic development and decision making across the drug development lifecycle.

- **[Combining mechanistic modeling with machine learning as a strategy to predict inflammatory bowel disease clinical scores.](https://pubmed.ncbi.nlm.nih.gov/40070575/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: This perspective proposes combining QSP mechanistic models with machine learning to predict IBD clinical scores like CDAI and Mayo scores.

- **[Computational approaches for toxicology and Pharmacokinetic properties prediction.](https://pubmed.ncbi.nlm.nih.gov/40908375/)**
	- Methodology: Supervised learning
	- Published: 2025Sep04
	- Summary: This review surveys in-silico computational approaches and methodologies for predicting pharmacokinetic properties and toxicological endpoints in drug development.

- **[Computational approaches to DMPK: A realistic assessment of current methods and their practical impact. Part I: Physicochemical and in vitro properties.](https://pubmed.ncbi.nlm.nih.gov/40602659/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: This review assesses AI/ML computational approaches for predicting DMPK properties including physicochemical parameters and in vitro assay outcomes in drug discovery.

- **[Computational modeling of drug-eluting balloons in peripheral artery disease: Mechanisms, optimization, and translational insights.](https://pubmed.ncbi.nlm.nih.gov/40895288/)**
	- Methodology: Neural networks, Surrogate modeling, Mechanism-informed machine learning
	- Published: 2025
	- Summary: Review of computational modeling for drug-eluting balloons, examining ML methods including physics-informed neural networks for patient-specific predictions and surrogate modeling.

- **[Conquering PROTAC molecular design and drugability.](https://pubmed.ncbi.nlm.nih.gov/40114295/)**
	- Methodology: Supervised learning
	- Published: 2025Apr
	- Summary: This perspective explores PROTAC molecular design advancements, integrating AI-driven modeling with traditional approaches to accelerate drug development for precision medicine.

- **[Covariate Model Selection Approaches for Population Pharmacokinetics: A Systematic Review of Existing Methods, From SCM to AI.](https://pubmed.ncbi.nlm.nih.gov/39831409/)**
	- Methodology: Feature selection, Model selection
	- Published: 2025Apr
	- Summary: A systematic review comparing AI/ML and traditional methods for covariate selection in population pharmacokinetic modeling, finding ML-based approaches superior.

- **[Development and application of artificial intelligence in traditional Chinese medicine research and development.](https://pubmed.ncbi.nlm.nih.gov/41508020/)**
	- Published: 2026Jan08
	- Summary: This review paper surveys the integration of AI technologies into traditional Chinese medicine research and development to address formulation complexity and standardization challenges.

- **[Development of Prediction Capabilities for High-Throughput Screening of Physiochemical Properties by Biomimetic Chromatography.](https://pubmed.ncbi.nlm.nih.gov/41375127/)**
	- Methodology: Supervised learning
	- Published: 2025Nov24
	- Summary: This review surveys machine learning approaches for predicting pharmacokinetic and pharmacodynamic properties using biomimetic chromatography data in drug discovery.

- **[Digital pharmacological twins: Bridging multi-scale modelling and artificial intelligence for precision medicine: The DIGPHAT consortium.](https://pubmed.ncbi.nlm.nih.gov/41076365/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Sep26
	- Summary: This perspective paper explores digital pharmacological twins that integrate mechanistic and ML models for personalized treatment optimization in precision medicine.

- **[Emerging Approaches in Data-Driven Drug Discovery for Rare Diseases.](https://pubmed.ncbi.nlm.nih.gov/40873216/)**
	- Methodology: Machine Learning, Artificial Intelligence
	- Published: 2025Aug25
	- Summary: This review examines integration of AI/ML with PK data and multi-omics approaches for data-driven drug discovery in rare diseases to enable personalized therapeutic strategies.

- **[Evaluating the Impact of AI-Based Model-Informed Drug Development (MIDD): A Comparative Review.](https://pubmed.ncbi.nlm.nih.gov/40457118/)**
	- Published: 2025Jun02
	- Summary: This systematic review evaluates the impact of AI-based model-informed drug development methods compared to traditional approaches across different stages of drug development.

- **[Every Compound a Candidate: experience-led risk-taking approaches to accelerate small-molecule drug discovery.](https://pubmed.ncbi.nlm.nih.gov/40209934/)**
	- Published: 2025May
	- Summary: This perspective advocates for leveraging AI/ML alongside risk-taking approaches to accelerate small-molecule drug discovery through an 'Every Compound a Candidate' strategy.

- **[Exploring the Role of LLMs Like ChatGPT in Pharmacy Education for Supporting Students' Therapeutic Decision-making.](https://pubmed.ncbi.nlm.nih.gov/40617506/)**
	- Methodology: LLM
	- Published: 2025Aug
	- Summary: This study evaluates the utility of large language models like ChatGPT as training tools for pharmacy students in therapeutic decision-making and drug dosage adjustment.

- **[Food contaminants: mechanisms of toxicity, computational assessment, and mitigation.](https://pubmed.ncbi.nlm.nih.gov/41602274/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: This review surveys computational methods including machine learning frameworks for predicting food contaminant toxicity as alternatives to animal testing.

- **[Formulation Strategy of BCS-II Drugs by Coupling Mechanistic In-Vitro and Nonclinical In-Vivo Data with PBPK: Fundamentals of Absorption-Dissolution to Parameterization of Modelling and Simulation.](https://pubmed.ncbi.nlm.nih.gov/40244539/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Apr17
	- Summary: This review surveys AI/ML-linked PBPK approaches for BCS class II drug formulation design and discusses mechanistic modeling strategies for absorption and dissolution.

- **[From mechanism to application: Harnessing oxidative stress signaling for innovative food design.](https://pubmed.ncbi.nlm.nih.gov/41508505/)**
	- Methodology: Deep learning
	- Published: 2026Feb01
	- Summary: This perspective proposes a data-driven framework using deep learning and computational prediction for designing personalized functional foods targeting oxidative stress pathways.

- **[FtsZ as a novel target for antibiotics development: Promises and challenges.](https://pubmed.ncbi.nlm.nih.gov/40893674/)**
	- Methodology: Supervised learning
	- Published: 2025Aug
	- Summary: Review of FtsZ as antibiotic target that mentions leveraging machine learning with high-throughput screening for future drug development efforts.

- **[Future Prospects for Using Clinical Phenotypes in Tuberculosis Precision Medicine-An Approach for Clinical Management.](https://pubmed.ncbi.nlm.nih.gov/41537599/)**
	- Published: 2026Jan15
	- Summary: This perspective paper discusses future prospects for using AI-integrated algorithms alongside clinical phenotypes to enable precision medicine and stratified treatment approaches in tuberculosis.

- **[G protein-coupled receptor digital twins for precision and personalized medicine.](https://pubmed.ncbi.nlm.nih.gov/41357836/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: Reviews how AI and digital twin technologies can advance precision GPCR-based medicine by integrating multi-omics data to create patient-specific virtual models for personalized therapies.

- **[Harnessing AI for precision medicine and its applications in genomics, systems pharmacology, and drug discovery.](https://pubmed.ncbi.nlm.nih.gov/40983121/)**
	- Methodology: Supervised learning
	- Published: 2025Nov05
	- Summary: This review surveys how AI/ML accelerates drug development through target identification, compound design, ADMET modeling, and PK/PD simulations for precision medicine applications.

- **[Harnessing ChatGPT for digital tools in pharmacy practice.](https://pubmed.ncbi.nlm.nih.gov/40581507/)**
	- Methodology: LLM
	- Published: 2025Nov
	- Summary: This commentary demonstrates how pharmacists can use ChatGPT to create digital tools for practice tasks including pharmacokinetic calculators and drug interaction checks.

- **[Heterogeneity Assessment of Breast Cancer Tumor Microenvironment: Multiparametric Quantitative Analysis with DCE-MRI and Discovery of Radiomics Biomarkers.](https://pubmed.ncbi.nlm.nih.gov/40657027/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025
	- Summary: This review examines the integration of DCE-MRI quantitative analysis with radiomics machine learning approaches for discovering biomarkers to assess breast cancer tumor microenvironment heterogeneity.

- **[How AI Transforms Regulatory Submission: Current Clinical Implementation and Future Prospects.](https://pubmed.ncbi.nlm.nih.gov/41340328/)**
	- Published: 2025Dec
	- Summary: This perspective paper surveys AI's current applications and future prospects in transforming regulatory submissions and drug development processes.

- **[How to Expedite Drug Discovery: Integrating Innovative Approaches to Accelerate Modern Drug Development.](https://pubmed.ncbi.nlm.nih.gov/41047976/)**
	- Methodology: Supervised learning
	- Published: 2025Aug31
	- Summary: This review surveys how AI/ML methods including predictive modeling and machine learning algorithms are being integrated to accelerate drug discovery and development processes.

- **[In Silico Research Is Rewriting the Rules of Drug Development: Is It the End of Human Trials?](https://pubmed.ncbi.nlm.nih.gov/40364863/)**
	- Methodology: Explainable AI
	- Published: 2025May
	- Summary: This editorial argues that AI-driven in silico methods, including digital twins and explainable AI, are transforming drug development by replacing traditional animal and human trials.

- **[Integrative and Emerging Models in Antibody Research: A Comprehensive Review.](https://pubmed.ncbi.nlm.nih.gov/41367414/)**
	- Methodology: Supervised learning
	- Published: 2025Oct
	- Summary: This review surveys computational biology and machine learning approaches for accelerating antibody design, prediction, and therapeutic development across multiple disease areas.

- **[Interpretable multimodal learning for tumor protein-metal binding: Progress, challenges, and perspectives.](https://pubmed.ncbi.nlm.nih.gov/40701309/)**
	- Methodology: Supervised learning, Deep learning, Explainable AI
	- Published: 2025Oct
	- Summary: This review paper surveys ML applications for predicting tumor protein-metal binding in cancer therapeutics, focusing on multimodal data integration and interpretability challenges.

- **[Leveraging Artificial Intelligence for decision support in neonatal and pediatric pharmacotherapy: A scoping review.](https://pubmed.ncbi.nlm.nih.gov/41344999/)**
	- Methodology: Supervised learning
	- Published: 2026Feb
	- Summary: A scoping review systematically mapping AI applications in pediatric and neonatal pharmacology for precision dosing, drug efficacy prediction, and adverse event reduction.

- **[Leveraging In Silico and Artificial Intelligence Models to Advance Drug Disposition and Response Predictions Across the Lifespan.](https://pubmed.ncbi.nlm.nih.gov/40539740/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Jun
	- Summary: This review discusses the application of in silico models integrated with AI/ML to predict drug exposure and responses across different populations and lifespans.

- **[Leveraging artificial intelligence in antibody-drug conjugate development: from target identification to clinical translation in oncology.](https://pubmed.ncbi.nlm.nih.gov/41272032/)**
	- Methodology: Deep learning, Supervised learning, Unsupervised learning, Neural networks
	- Published: 2025Nov21
	- Summary: This review surveys AI/ML applications across the entire ADC development pipeline, from target discovery to clinical translation in oncology.

- **[Leveraging large language models to compare perspectives on integrating QSP and AI/ML.](https://pubmed.ncbi.nlm.nih.gov/40325298/)**
	- Methodology: LLM
	- Published: 2025May05
	- Summary: Uses Large Language Models to analyze and synthesize contrasting perspectives on integrating QSP and AI/ML methodologies in drug development.

- **[Leveraging machine learning models in evaluating ADMET properties for drug discovery and development.](https://pubmed.ncbi.nlm.nih.gov/40585410/)**
	- Methodology: Supervised learning
	- Published: 2025
	- Summary: This review surveys machine learning models for predicting ADMET properties to accelerate drug discovery and reduce experimental costs.

- **[Leveraging machine learning predicted confidence for boosting assay submission and decision-making efficiencies.](https://pubmed.ncbi.nlm.nih.gov/40639290/)**
	- Methodology: Supervised learning
	- Published: 2025Nov05
	- Summary: The paper describes Roche's experience using ML with uncertainty quantification to optimize pharmacokinetic assay submission decisions, reducing costs by excluding low-confidence predictions.

- **[Light sheet fluorescence microscopy for monitoring drug delivery: Unlocking the developmental phases of embryos.](https://pubmed.ncbi.nlm.nih.gov/39842696/)**
	- Methodology: Deep learning
	- Published: 2025Mar
	- Summary: This review examines LSFM applications in drug delivery monitoring during embryonic development, highlighting machine learning integration and AI-driven data analysis for tracking pharmacokinetics.

- **[Machine Learning and Artificial Intelligence in Nanomedicine.](https://pubmed.ncbi.nlm.nih.gov/40813104/)**
	- Methodology: Supervised learning, Deep learning, Machine learning
	- Published: 2025Jul-Aug
	- Summary: This review surveys AI/ML applications in nanomedicine development, covering nanoparticle design optimization, biodistribution prediction, and clinical translation challenges.

- **[Machine Learning for Multi-Target Drug Discovery: Challenges and Opportunities in Systems Pharmacology.](https://pubmed.ncbi.nlm.nih.gov/41012523/)**
	- Methodology: Supervised learning, Deep learning, Unsupervised learning
	- Published: 2025Sep12
	- Summary: This review surveys machine learning techniques including deep learning and graph-based methods for multi-target drug discovery in systems pharmacology applications.

- **[Machine Learning for Prediction of Drug Concentrations: Application and Challenges.](https://pubmed.ncbi.nlm.nih.gov/39901656/)**
	- Methodology: Tree-based models, Neural networks, Ensemble learning
	- Published: 2025May
	- Summary: This review surveys machine learning applications for predicting drug concentrations in pharmacokinetics, focusing on tree-based algorithms, neural networks, and ensemble methods.

- **[Machine Learning for Toxicity Prediction Using Chemical Structures: Pillars for Success in the Real World.](https://pubmed.ncbi.nlm.nih.gov/40314361/)**
	- Methodology: Supervised learning
	- Published: 2025May19
	- Summary: This perspective paper discusses machine learning approaches for predicting molecular toxicity from chemical structures in drug discovery applications.

- **[Machine learning in antimicrobial therapy for critically ill patients: optimizing early empirical regimens, individualized dosing, and de-escalation strategies.](https://pubmed.ncbi.nlm.nih.gov/41015133/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Dec
	- Summary: Review of ML applications in antimicrobial therapy for critically ill patients, covering resistance prediction, personalized dosing, and de-escalation strategies using hybrid ML-PopPK models.

- **[Machine learning in targeted protein degradation drug design: a technical review of PROTACs and molecular glues.](https://pubmed.ncbi.nlm.nih.gov/41318024/)**
	- Methodology: Deep learning, Supervised learning, Neural networks
	- Published: 2026Jan
	- Summary: This review surveys ML applications in targeted protein degradation drug design, covering predictive modeling, virtual screening, and generative design for PROTACs and molecular glues.

- **[Machine learning to predict food effects during drug development: a comprehensive review.](https://pubmed.ncbi.nlm.nih.gov/41372958/)**
	- Methodology: Supervised learning, Unsupervised learning, Reinforcement learning, Deep learning, Explainable AI
	- Published: 2025Dec10
	- Summary: This review evaluates machine learning methods for predicting food effects on drug absorption compared to traditional approaches in drug development.

- **[Mastering the complexities of cancer nanomedicine with text mining, AI and automation.](https://pubmed.ncbi.nlm.nih.gov/39848590/)**
	- Methodology: Unsupervised learning, Supervised learning
	- Published: 2025Mar10
	- Summary: Personal perspective on using text mining and AI to master complexities in cancer nanomedicine for hypothesis generation, drug combination optimization, and automated nanoparticle discovery.

- **[Metabolic phenotypes: Molecular bridges between health homeostasis and disease imbalance.](https://pubmed.ncbi.nlm.nih.gov/41245891/)**
	- Published: 2025
	- Summary: This review discusses metabolic phenotypes in disease and mentions future integration of AI and big data mining but does not survey specific AI/ML methodologies.

- **[Methodological Techniques Used in Machine Learning to Support Individualized Drug Dosing Regimens Based on Pharmacokinetic Data: A Scoping Review.](https://pubmed.ncbi.nlm.nih.gov/40810920/)**
	- Methodology: Supervised learning
	- Published: 2025Sep
	- Summary: A scoping review examining machine learning methodological approaches used in pharmacokinetic modeling for individualized drug dose optimization strategies.

- **[Mitigate Japan's Drug Loss With Model-Informed Drug Development.](https://pubmed.ncbi.nlm.nih.gov/41076586/)**
	- Published: 2025Nov
	- Summary: This perspective paper discusses how Model-Informed Drug Development enhanced with AI/ML can help mitigate Japan's drug loss problem, but doesn't specify particular AI/ML methods or applications.

- **[Modernizing Preclinical Drug Development: The Role of New Approach Methodologies.](https://pubmed.ncbi.nlm.nih.gov/40567279/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Jun13
	- Summary: This perspective paper proposes integrating AI/ML with mechanistic models in a structured workflow to improve preclinical drug development and translational success.

- **[Moving From Point-Based Analysis to Systems-Based Modeling: Knowledge Integration to Address Antimicrobial Resistance.](https://pubmed.ncbi.nlm.nih.gov/40751366/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025Oct
	- Summary: This perspective discusses integrating machine learning with pharmacometrics to build systems-level models for optimizing antibiotic therapy and addressing antimicrobial resistance.

- **[Nanomaterials in Drug Delivery: Leveraging Artificial Intelligence and Big Data for Predictive Design.](https://pubmed.ncbi.nlm.nih.gov/41303604/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov17
	- Summary: This review surveys AI/ML applications in nanomaterial drug delivery, focusing on predictive modeling for nanocarrier design, biodistribution, and clinical optimization.

- **[New Targets for Imaging in Nuclear Medicine.](https://pubmed.ncbi.nlm.nih.gov/40335357/)**
	- Methodology: Deep learning
	- Published: 2025Sep
	- Summary: This editorial surveys AI/ML integration in nuclear medicine for tracer development, image analysis, and personalized radiotheranostic strategies.

- **[Next-generation experimental and computational strategies for drug-drug interaction prophecy.](https://pubmed.ncbi.nlm.nih.gov/40945385/)**
	- Methodology: Supervised learning
	- Published: 2025Oct
	- Summary: This review surveys machine learning approaches alongside PBPK models for predicting drug-drug interactions to improve safety assessment in drug development.

- **[Ophthalmic drug discovery and development using artificial intelligence and digital health technologies.](https://pubmed.ncbi.nlm.nih.gov/40998989/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Sep25
	- Summary: Review of AI/ML applications across ophthalmic drug discovery and development phases, from target identification to personalized treatment monitoring.

- **[Opportunities and Challenges in Precision Neurotherapeutics.](https://pubmed.ncbi.nlm.nih.gov/41543941/)**
	- Published: 2026Jan16
	- Summary: Review examining precision neurotherapeutics approaches including AI convergence with computational modeling for personalized mental health care and biomarker development.

- **[Opportunities for machine learning and artificial intelligence in physiologically-based pharmacokinetic (PBPK) modeling.](https://pubmed.ncbi.nlm.nih.gov/41093240/)**
	- Methodology: Supervised learning, Unsupervised learning, Bayesian ML, Hybrid mechanistic–ML models
	- Published: 2025Dec
	- Summary: This review paper surveys ML/AI opportunities in PBPK modeling for parameter estimation, model learning, and uncertainty quantification to address current limitations.

- **[Optimized therapeutic drug monitoring: the role of machine learning models.](https://pubmed.ncbi.nlm.nih.gov/41460893/)**
	- Methodology: Supervised learning
	- Published: 2025Dec29
	- Summary: This review examines how machine learning models can enhance therapeutic drug monitoring to optimize dosing and minimize toxicity for drugs with narrow therapeutic indices.

- **[Optimizing vedolizumab therapy in ulcerative colitis: A critical synthesis of trial evidence and the emerging role of artificial intelligence.](https://pubmed.ncbi.nlm.nih.gov/41642870/)**
	- Published: 2026Feb
	- Summary: This review synthesizes trial evidence for vedolizumab therapy in ulcerative colitis and discusses the emerging role of AI in personalizing treatment strategies.

- **[Organoids in drug development: from predictive models to regulatory integration.](https://pubmed.ncbi.nlm.nih.gov/41577171/)**
	- Published: 2026Jan21
	- Summary: This review discusses organoids in drug development with mention of AI-driven modeling integration but does not focus on specific AI/ML methodologies or applications.

- **[Peptide-based drug design using generative AI.](https://pubmed.ncbi.nlm.nih.gov/41376388/)**
	- Methodology: Deep learning, Neural networks
	- Published: 2026Jan13
	- Summary: This review surveys AI/ML methods for peptide-based drug design, focusing on generative architectures like transformers and diffusion models for novel sequence generation.

- **[Personalizing Antidepressant Therapy: Integrating Pharmacogenomics, Therapeutic Drug Monitoring, and Digital Tools for Improved Depression Outcomes.](https://pubmed.ncbi.nlm.nih.gov/41440979/)**
	- Published: 2025Dec10
	- Summary: This review synthesizes evidence on integrating pharmacogenetics, therapeutic drug monitoring, and AI to enable model-informed precision dosing for antidepressant therapy in MDD.

- **[Pharmacokinetics and Customized Dosing of Vancomycin in Adult Patients With Hematological Malignancies: Status, Challenges, and Opportunities.](https://pubmed.ncbi.nlm.nih.gov/41618547/)**
	- Methodology: Supervised learning
	- Published: 2026Feb
	- Summary: This review surveys AI-guided customized dosing technologies for vancomycin in hematological malignancy patients, focusing on personalized pharmacokinetic approaches.

- **[Pharmacometrics in the Age of Large Language Models: A Vision of the Future.](https://pubmed.ncbi.nlm.nih.gov/41155911/)**
	- Methodology: LLM
	- Published: 2025Sep29
	- Summary: This perspective paper explores the potential applications of Large Language Models across pharmacometrics workflows, from data processing to model development and reporting.

- **[Physics-Informed Machine Learning in Biomedical Science and Engineering.](https://pubmed.ncbi.nlm.nih.gov/41281212/)**
	- Methodology: Deep learning, Neural networks, Hybrid mechanistic–ML models, Mechanism-informed machine learning
	- Published: 2025Oct06
	- Summary: This review surveys physics-informed machine learning frameworks (PINNs, NODEs, neural operators) that integrate physical laws with data-driven methods for biomedical applications.

- **[Pirana and Integrated PMX Tools, a Workbench for NONMEM, NLME, pyDarwin, and RsNLME.](https://pubmed.ncbi.nlm.nih.gov/40613737/)**
	- Methodology: Model selection
	- Published: 2025Aug
	- Summary: Tutorial on using Pirana workbench with integrated pyDarwin machine learning package for automated pharmacometric model structure and covariate selection.

- **[Progress of machine learning in the application of small molecule druggability prediction.](https://pubmed.ncbi.nlm.nih.gov/39808972/)**
	- Methodology: Supervised learning, Feature selection
	- Published: 2025Mar05
	- Summary: This review surveys machine learning applications for predicting small molecule pharmaceutical properties including solubility, activity, toxicity, and pharmacokinetics.

- **[Recent Advances in Machine Learning Models for Predicting Toxicity of Inorganic Nanoparticles.](https://pubmed.ncbi.nlm.nih.gov/41340632/)**
	- Methodology: Supervised learning, Ensemble learning, Feature selection
	- Published: 2025Nov27
	- Summary: A comprehensive review of machine learning models for predicting cytotoxicity of inorganic nanoparticles, covering ML-accelerated nanoQSAR, PBPK, and meta-analysis approaches.

- **[Recent Techniques to Improve Amorphous Dispersion Performance with Quality Design, Physicochemical Monitoring, Molecular Simulation, and Machine Learning.](https://pubmed.ncbi.nlm.nih.gov/41155888/)**
	- Methodology: Supervised learning
	- Published: 2025Sep24
	- Summary: This review surveys how machine learning and AI are transforming amorphous solid dispersion formulation design by enabling predictions of drug-polymer interactions and stability.

- **[Recent Trends in the Development and Clinical Translation of Polymer-based Targeted Therapeutic Nanoparticle.](https://pubmed.ncbi.nlm.nih.gov/41639361/)**
	- Methodology: Supervised learning
	- Published: 2026Feb04
	- Summary: This review discusses how AI/ML methods are being used to optimize polymeric nanoparticle formulations, predict drug release patterns, and accelerate clinical development.

- **[Recommended approaches for integration of population pharmacokinetic modelling with precision dosing in clinical practice.](https://pubmed.ncbi.nlm.nih.gov/39568428/)**
	- Published: 2025Apr
	- Summary: This review consolidates recommendations for integrating population PK modeling with precision dosing in clinical practice, with brief consideration of future ML applications.

- **[Redefining Breast Cancer Care by Harnessing Computational Drug Repositioning.](https://pubmed.ncbi.nlm.nih.gov/41011031/)**
	- Methodology: Supervised learning, Unsupervised learning, Deep learning, Neural networks
	- Published: 2025Sep10
	- Summary: This review surveys computational drug repositioning strategies for breast cancer, examining AI/ML methods including network-based approaches and machine learning techniques.

- **[Remote Monitoring Model Based on Artificial Intelligence to Optimize DOAC Therapy: A Working Hypothesis for Safer Anticoagulation.](https://pubmed.ncbi.nlm.nih.gov/41303819/)**
	- Methodology: Supervised learning
	- Published: 2025Nov05
	- Summary: Proposes an AI-integrated remote monitoring model for DOAC therapy that uses pattern recognition to identify high-risk clinical trends and enable early intervention for safer anticoagulation.

- **[Repositioning Antimicrobial Peptides Against WHO-Priority Fungi.](https://pubmed.ncbi.nlm.nih.gov/40884276/)**
	- Methodology: Deep learning
	- Published: 2025Oct
	- Summary: This review surveys antimicrobial peptides as antifungal therapeutics, discussing computational tools including machine learning and deep learning for rational AMP design.

- **[Review of Precision Medicine and Diagnosis of Neonatal Illness.](https://pubmed.ncbi.nlm.nih.gov/40002629/)**
	- Methodology: Supervised learning
	- Published: 2025Feb16
	- Summary: Review of precision medicine approaches for neonatal illness diagnosis, mentioning machine learning algorithms as ongoing research tools for NICU applications.

- **[Review on electrochemical sensors for anticancer drug susceptibility testing.](https://pubmed.ncbi.nlm.nih.gov/41526129/)**
	- Methodology: Supervised learning
	- Published: 2026Feb01
	- Summary: This review surveys electrochemical sensors for anticancer drug testing, briefly mentioning machine learning as one approach to boost sensor performance.

- **[Revolutionizing drug discovery: Integrating artificial intelligence with quantitative systems pharmacology.](https://pubmed.ncbi.nlm.nih.gov/40774584/)**
	- Methodology: Surrogate modeling, Explainable AI, Hybrid mechanistic–ML models
	- Published: 2025Sep
	- Summary: This review evaluates AI integration within quantitative systems pharmacology, highlighting surrogate modeling, virtual patients, and digital twins for enhanced drug discovery.

- **[Revolutionizing prostate cancer therapy: Artificial intelligence - Based nanocarriers for precision diagnosis and treatment.](https://pubmed.ncbi.nlm.nih.gov/39923922/)**
	- Methodology: Explainable AI
	- Published: 2025Apr
	- Summary: This review surveys AI applications in nanocarrier-based drug delivery for prostate cancer, covering design optimization, toxicity prediction, and personalized treatment approaches.

- **[Rising Role of Artificial Intelligence in Clinical Pharmacometrics and Model-Informed Precision Dosing in Pediatrics.](https://pubmed.ncbi.nlm.nih.gov/41675469/)**
	- Published: 2026Feb
	- Summary: This review examines the rising role of AI in clinical pharmacometrics and model-informed precision dosing specifically in pediatric populations.

- **[Role of Artificial Intelligence in Musculoskeletal Interventions.](https://pubmed.ncbi.nlm.nih.gov/40427114/)**
	- Methodology: Deep learning, Supervised learning
	- Published: 2025May10
	- Summary: This review explores AI/ML applications in musculoskeletal interventions, covering diagnostic processes, intervention guidance, and personalized treatment approaches.

- **[SERS-powered precision: revolutionizing therapeutic drug monitoring with nanoscale sensitivity.](https://pubmed.ncbi.nlm.nih.gov/41251787/)**
	- Methodology: Supervised learning
	- Published: 2025Nov18
	- Summary: This review surveys SERS-based therapeutic drug monitoring, including machine learning-assisted analysis approaches for improving analytical performance.

- **[Should LLMs be over empowered for high-stake regulatory research?](https://pubmed.ncbi.nlm.nih.gov/40576029/)**
	- Methodology: LLM
	- Published: 2025May01
	- Summary: This perspective critically evaluates the feasibility and challenges of implementing open-source LLMs for extracting pharmacokinetic information from FDA drug labels in regulatory research.

- **[Spatial proteomics in precision medicine: technologies, bioinformatics, and translational applications.](https://pubmed.ncbi.nlm.nih.gov/41647441/)**
	- Methodology: Deep learning, Neural networks, Unsupervised learning
	- Published: 2026Mar
	- Summary: This review surveys spatial proteomics technologies and their AI/ML computational methods including graph neural networks for precision medicine applications.

- **[State of Art of Dose Individualization to Support tacrolimus drug monitoring: What's Next?](https://pubmed.ncbi.nlm.nih.gov/40959818/)**
	- Methodology: Bayesian ML
	- Published: 2025
	- Summary: This review surveys tacrolimus dose individualization methods including emerging machine learning and AI technologies alongside traditional pharmacokinetic modeling approaches.

- **[Systems immunology: When systems biology meets immunology.](https://pubmed.ncbi.nlm.nih.gov/40977698/)**
	- Methodology: Hybrid mechanistic–ML models
	- Published: 2025
	- Summary: This mini-review surveys systems immunology approaches that integrate AI/ML with mechanistic models to understand immune networks and guide therapeutic innovation.

- **[Target-Controlled Infusion of Propofol: A Systematic Review of Recent Results.](https://pubmed.ncbi.nlm.nih.gov/40289063/)**
	- Methodology: Supervised learning
	- Published: 2025Apr28
	- Summary: Systematic review of PK-PD models for propofol target-controlled infusion, including studies that incorporate machine learning techniques for adaptive dosing strategies.

- **[The Emerging Role of Artificial Intelligence in Drug Discovery and Development: Implications for Cardiovascular Pharmacology.](https://pubmed.ncbi.nlm.nih.gov/41632854/)**
	- Methodology: Deep learning, Reinforcement learning, LLM, Neural networks
	- Published: 2026Feb03
	- Summary: This review surveys AI/ML applications across cardiovascular drug development, covering target identification, compound screening, PK/toxicity prediction, and clinical trial optimization.

- **[The Role of Artificial Intelligence in Drug Discovery and Pharmaceutical Development: A Paradigm Shift in the History of Pharmaceutical Industries.](https://pubmed.ncbi.nlm.nih.gov/40360908/)**
	- Published: 2025May14
	- Summary: This paper reviews the paradigm shift of AI integration across drug development stages, discussing applications in PK/PD modeling, toxicity prediction, and clinical trial acceleration.

- **[The dawn of a new era: can machine learning and large language models reshape QSP modeling?](https://pubmed.ncbi.nlm.nih.gov/40524056/)**
	- Methodology: Hybrid mechanistic–ML models, Surrogate modeling, LLM, AI Agents
	- Published: 2025Jun16
	- Summary: This perspective explores how AI/ML and LLMs can transform QSP modeling through hybrid models, surrogate modeling, and democratizing workflows for drug development.

- **[The predictive edge: modeling and simulation in drug product development.](https://pubmed.ncbi.nlm.nih.gov/41592638/)**
	- Methodology: Supervised learning, Deep learning, Machine learning
	- Published: 2026Mar
	- Summary: This review surveys AI/ML applications in drug product development, covering predictive modeling and simulation techniques for improving drug performance, safety, and success rates.

- **[The roles of biomarkers in Alzheimer's disease clinical trials.](https://pubmed.ncbi.nlm.nih.gov/41449005/)**
	- Published: 2025Dec24
	- Summary: This review discusses biomarkers in Alzheimer's disease clinical trials and briefly mentions AI/ML as a potential approach for enhancing biomarker data integration.

- **[Toward Integrated Clinical-Computational Nuclear Medicine.](https://pubmed.ncbi.nlm.nih.gov/41284557/)**
	- Methodology: Deep learning
	- Published: 2026Jan
	- Summary: This perspective paper surveys AI/ML applications in nuclear medicine, highlighting artificial intelligence's role in improving imaging quality, automating detection, and enabling personalized therapy.

- **[Toward Integration of Molecular Measures and Artificial Intelligence-Based Assessments With Clinical End Points in Inflammatory Bowel Disease.](https://pubmed.ncbi.nlm.nih.gov/41665578/)**
	- Published: 2026Feb10
	- Summary: This perspective paper outlines how AI-assisted tools can integrate molecular measures with clinical endpoints to improve IBD treatment assessment and enable precision medicine approaches.

- **[Toward indole postbiotics precision therapy via AI-powered drug delivery technologies.](https://pubmed.ncbi.nlm.nih.gov/41223607/)**
	- Published: 2026Feb
	- Summary: This review examines indole postbiotics and suggests using AI as a framework for translating these compounds into precision therapeutic applications.

- **[Towards Pharmaceutical Industry 5.0: Impact of Artificial Intelligence in Drug Discovery and Development.](https://pubmed.ncbi.nlm.nih.gov/41185503/)**
	- Methodology: Supervised learning, Deep learning, Neural networks
	- Published: 2025Nov03
	- Summary: This review surveys AI applications across drug discovery and development, covering machine learning, deep learning, and NLP for accelerating drug development in Industry 5.0.

- **[Tumor organoids on-a-chip and the role of AI in predictive oncology and personalized cancer medicine.](https://pubmed.ncbi.nlm.nih.gov/41512327/)**
	- Methodology: Deep learning
	- Published: 2026Jan09
	- Summary: This review surveys AI applications in tumor organoids-on-chip for predictive oncology and personalized cancer medicine, focusing on drug response prediction.

- **[Unlocking Antimicrobial Peptides from Marine Invertebrates: A Comprehensive Review of Antimicrobial Discovery.](https://pubmed.ncbi.nlm.nih.gov/41009902/)**
	- Methodology: Supervised learning, Deep learning
	- Published: 2025Sep12
	- Summary: This review examines antimicrobial peptides from marine invertebrates and highlights AI's role in accelerating AMP discovery, design, and production through predictive modeling.

- **[Use of Artificial Intelligence in Current Fight Against Antimicrobial Resistance.](https://pubmed.ncbi.nlm.nih.gov/40354275/)**
	- Methodology: Supervised learning
	- Published: 2025May12
	- Summary: This review surveys AI/ML applications in antimicrobial resistance, focusing on optimizing dosing through PK modeling and therapeutic drug monitoring to improve outcomes.

- **[Vancomycin resistance in gram-positive infections: evolutionary strategies of survival.](https://pubmed.ncbi.nlm.nih.gov/41563485/)**
	- Methodology: Supervised learning, Hybrid mechanistic–ML models
	- Published: 2026Jan21
	- Summary: This review examines vancomycin resistance mechanisms and highlights AI/ML applications in antimicrobial discovery, resistance surveillance, and rational drug design.
