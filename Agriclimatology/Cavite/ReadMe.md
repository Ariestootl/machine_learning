# RADAR: Regression-Based Agricultural Drought Analysis and Risk Prediction in Cavite Using Multi-Year NASA POWER Climatological Data, Random Forest, SHapley Additive exPlanations (SHAP), and Accumulated Local Effects (ALE)

🚧 **WORK IN PROGRESS:** *This research project and its accompanying codebase are currently under active development. Methodologies, data pipelines, and predictive models are subject to ongoing refinement and validation.*

**Category:** Mathematics and Computational Science  
**Level:** Senior High School (STEM)

## 👥 About the Researchers
This research proposal is being developed by:
*   **Elle Rheign Maxeen P. Padilla**
*   **Judiel Kyle I. Ladero**
*   **Bianca Rheizel T. Abelieto**

``The team operates under my technical guidance``. To ensure the students build a robust foundational skillset in computational science, **I, Jose Aries E. De Los Santos, M.Sc., provide hands-on mentorship in Python programming and applied machine learning**. This includes teaching the students how to code in Python, utilize standard libraries like Scikit-learn, and implement Explainable AI (XAI) tools.

Through live coding demonstrations, step-by-step guidance on running predictive models, and rigorous validation of their output code, I am equipping these students to address real-world agricultural problems through advanced computational methods—bridging the gap between data science and actionable local governance.

## 🌾 Project Overview
Agricultural resilience relies heavily on accurate, timely, and understandable climate forecasting. This project utilizes meteorological data (harvested via the NASA POWER API) to predict root-zone soil moisture depletion—a primary indicator of agricultural drought. 

Instead of relying on isolated municipal models, this study trains a **Unified Machine Learning Model (Random Forest)** across multiple municipalities. This approach allows the algorithm to learn macro-level climatological patterns (e.g., monsoon cycles, humidity thresholds, and solar radiation impacts) while maintaining the ability to output highly accurate, localized municipal predictions.

## 📊 Data Dictionary (NASA POWER Climatology Features)
The predictive model utilizes the following meteorological and satellite-derived features to assess agricultural drought risk:

| Feature Code | Parameter Name | Description |
| :--- | :--- | :--- |
| **RH2M** | Near-Surface Relative Humidity | The ratio of actual water vapor to the saturation vapor pressure at 2 meters above the surface. |
| **T2M_MAX** | Maximum Temperature (2m) | The maximum dry bulb temperature at 2 meters above the surface. |
| **T2M_MIN** | Minimum Temperature (2m) | The minimum dry bulb temperature at 2 meters above the surface. |
| **ALLSKY_SFC_SW_DWN** | Downward Shortwave Radiation | The downwelling shortwave solar radiation at the surface under all sky conditions. |
| **PRECTOTCORR** | Bias-Corrected Precipitation | The bias-corrected average precipitation (rainfall). |
| **TS** | Earth Skin Temperature | The average land surface temperature. |
| **GWETROOT** | Root Zone Soil Saturation | The amount of water retained in the root zone (Primary Target Variable). |
| **EVLAND** | Land Surface Evaporation | The total evaporation from the land surface. |

## 🧠 Explainable AI (XAI): Moving Beyond the "Black Box"
A major limitation of modern machine learning is the "black box" problem—algorithms can make highly accurate predictions, but they cannot explain *why* they made them. In agriculture and public policy, trust is paramount. Local Government Units (LGUs) and farmers cannot risk resources on a prediction they do not understand.

To solve this, our methodology heavily integrates **Explainable Artificial Intelligence (XAI)**, specifically using **SHAP (SHapley Additive exPlanations)**. XAI transforms our predictive model from a simple warning system into a diagnostic tool. 

Through XAI, we provide transparency at two critical levels:

### 1. Global Explainability (Provincial Climatology)
We utilize SHAP Beeswarm and Dependence plots to uncover the governing laws of the model across the entire province. XAI allows us to:
*   **Rank Climatological Drivers:** Mathematically prove which weather features (e.g., Relative Humidity vs. Temperature) have the strongest impact on soil moisture.
*   **Identify Tipping Points:** Discover non-linear thresholds, such as the exact humidity percentage where atmospheric moisture begins to actively prevent soil evaporation.
*   **Validate Physics:** Ensure the model's logic aligns with actual hydrological laws and local seasonal cycles (e.g., the Philippine *Habagat* and *Amihan* monsoons).

### 2. Local Explainability (Municipal Case Studies)
Using SHAP Waterfall plots, XAI breaks down individual predictions for specific municipalities on a month-by-month basis. If the model predicts a severe drought risk for a specific town, XAI provides an exact "receipt" of that decision.
*   *Example:* Rather than simply stating, "Town A is at High Risk," XAI clarifies, "Town A is at High Risk primarily due to a 20% deficit in precipitation combined with abnormally high surface solar radiation, despite cooler-than-average temperatures."

## 🎯 Research Impact
By combining a robust predictive algorithm with the transparency of Explainable AI, this research provides agricultural stakeholders with an early-warning system that is not only mathematically sound but physically interpretable, actionable, and trustworthy.