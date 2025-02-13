# Experimental-Design-Summary
This STA305H5S – Experimental Design project at the University of Toronto examines the effects of cocaine, cannabis, methamphetamine, and morphine on running endurance, blood oxygen levels, and blood pressure in a simulated environment (The Islands), applying experimental design and statistical modelling techniques.
# Effects of Substances on Athletic Performance  
📊 *University of Toronto | STA305H5S – Experimental Design & Statistical Modeling*  

## 📌 Project Overview  
This project investigates the effects of **cocaine, cannabis, methamphetamine, and morphine** on **athletic performance metrics** using a simulated environment (*The Islands*). The study examines how these substances influence:  
- 🏃 **Running endurance** (250m sprint time)  
- 🩸 **Blood oxygen levels** (SpO2 before & after run)  
- 💓 **Blood pressure** (before & after run)  

## 🔬 Experimental Design  
- **Controlled Simulation:** Environmental conditions kept constant.  
- **Blocking Variables:** Age & BMI to reduce confounding effects.  
- **Statistical Analysis:**  
  - Two-Way ANOVA  
  - ANCOVA (to adjust for covariates)  
  - Balanced Incomplete Block Design (BIBD)  
- **Replication:** 30+ observations per treatment.  

## 🛠 Tools & Technologies  
- **Programming:** R (Quarto/LaTeX) for data analysis & visualization.  
- **Statistical Methods:** Hypothesis testing, regression modeling, multivariate analysis.  

---

## 📜 Technical Report  

### **Abstract**  
This study investigates the influence of **cocaine, cannabis, methamphetamine, and morphine** on athletic performance. Using a simulated environment (*The Islands*), we measured **running endurance (250m sprint), blood oxygen levels, and blood pressure**. Our findings provide insights into the physiological effects of these substances under controlled conditions.  

### **Introduction**  
The effects of drugs on physical performance have been widely studied, particularly in **endurance, strength, and reaction time**. Substances like **cocaine** (stimulant) increase alertness, **cannabis** may reduce stamina, **methamphetamine** boosts endurance, and **morphine** decreases pain sensitivity. This study explores how these substances affect key physiological metrics during a 250m sprint.  

**Research Questions:**  
1. How do different substances impact **running endurance**?  
2. How do they influence **blood oxygen levels**?  
3. How do they affect **blood pressure**?  

### **Methodology**  
- **Experimental Units:** Virtual participants in *The Islands*, categorized by **age and BMI**.  
- **Independent Variables:**  
  - **Type of Substance:** Cocaine (50mg), Cannabis (250mL), Methamphetamine (10mg), Morphine (50mg).  
  - **Covariates:** Age (years), BMI (kg/m²).  
- **Response Variables:**  
  - **Running Time:** Time to complete a **250m sprint**.  
  - **Blood Oxygen Level:** Measured **before and after** the sprint.  
  - **Blood Pressure:** Measured **before and after** the sprint.  
- **Experimental Design:**  
  - **Control:** Standardized environmental conditions.  
  - **Blocking:** Participants grouped by **age and BMI**.  
  - **Randomization:** Assignment of treatments within each group.  
  - **Replication:** 30+ observations per treatment.  

### **Data Analysis & Statistical Methods**  
- **Two-Way ANOVA:** Assesses interactions between drugs and physiological responses.  
- **ANCOVA:** Adjusts for age/BMI covariates.  
- **Balanced Incomplete Block Design (BIBD):** Accounts for non-uniform participation.  

### **Results & Discussion**  
- **Key Findings:**  
  - **Stimulants (cocaine, methamphetamine)** improved sprint times but negatively affected oxygen levels and blood pressure.  
  - **Cannabis users** showed reduced endurance.  
  - **Morphine users** maintained endurance but had significant drops in oxygen levels.  
- **Implications:** Understanding how substances affect performance can inform **sports regulations, medical research, and athletic safety policies**.  

### **Limitations & Future Work**  
- **Sample Size:** Limited to 30 per treatment; expanding data could improve reliability.  
- **Simulation Constraints:** Virtual environment may not fully replicate real-world conditions.  
- **Future Research:** Investigate **long-term** effects and include **additional physiological metrics**.  



