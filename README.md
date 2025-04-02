# **Climate Change Impact on Agriculture Analysis**  

## **Overview**  
This project analyzes a synthetic dataset of **10,000 observations** to assess climate change impacts on crop yields (1970-2023). It combines:  
- **Exploratory analysis** (EDA) of climate and agricultural trends  
- **Predictive modeling** (linear regression, Random Forest)  
- **2030 yield forecasts**  

## 📊 **Key Findings**  
1. **Yield influencers**:  
   - **Negative**: CO₂ (-0.0064 t/ha per MT), extreme weather (>5/year)  
   - **Positive**: Investments (+0.0017 t/ha per M$), moderate temps (15-25°C)  

2. **Key risks**:  
   - Potential **20% yield decline by 2030** in vulnerable regions (Siberia, Patagonia)  
   - **Critical threshold**: >3 extreme weather events/year → significant yield drops  

3. **Model performance**:  
   - **Random Forest** (RMSE = 0.48) outperformed linear regression (RMSE = 0.67)  

## 🛠 **Recommendations**  
- **Priority regions**: Target areas with:  
  - CO₂ > 25 MT  
  - Temperatures > 27°C  
  - >3 extreme weather events/year  
- **Actions**:  
  - Adopt **resilient crops** and **precision irrigation**  
  - Invest in **early warning systems**  

## 📂 **Files**  
- **Processed data**: `climate_agriculture_processed.csv`  
- **RF model**: `randomforest_model.rds`  

## 🔍 **Next Steps**  
- Incorporate climate projections (RCP 4.5/8.5)  
- Refine analysis by crop type (wheat, corn, rice)  

---  
**Contact**: [Kanne Tamibe Kochiake] | **Date**: April 2025
