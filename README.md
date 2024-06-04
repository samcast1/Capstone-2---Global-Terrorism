# Executive Summary

This is an end-to-end project using real world data from the Global Terrorism Database. The deliverable is an interactive dashboard that allows the user to quickly see the most probable targets and forms of attack given a certain motive or societal circumstance, and it comes with a bonus Tableau Dashboard that I created to enhance the Exploratory Data Analysis process (if you know EDA, you know it could use some enhancing...). 
 
The dashboard relies on an NLP model built on Microsoft's LightGBM binary classification algorithm. If that doesn't mean much to you, it's an extremely efficient means of making complex predictions based on hundreds of thousands of language-based features. All progress - including 180 degree project shifts, intensive EDA, and markdown commentary - can be seen in the [notebooks](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/notebooks).

Thorough report and presentation are now viewable in the [reports](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/reports).

# Table of Contents
## [Data](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/data)
- interim
- raw
## [Notebooks (Generalized by Series)](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/notebooks)
- 1.0: Initial Exploration and Data Wrangling
- 2.0: Exploratory Data Analysis, reworked multiple times
- 3.0: Preprocessing and Feature Engineering
- 4.0: Model Evaluation, Selection, and Plotly Dashboard
## [References](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/references)
- GTD Codebook
## [Reports](https://github.com/samcast1/Capstone-2---Global-Terrorism/tree/main/reports)
- Presentation
- Written Report
- Project Proposal
- Snapshot: Plotly Dashboard
- Snapshot: Tableau Dashboard
_______________________________________________________

# A Little Glimpse . . .

Pressed for time? So here's a few key visualizations from the reports to give you a little glimpse:

**Total incidents since 1970**  
*The GTD has recorded over 200,000 terrorist incidents and attempts since 1970.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/eac84911-c5ee-4ab1-a5c6-1ea27fb90eb4" alt="Total incidents since 1970" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**Cumulative deaths and injuries**  
*These events have taken over half a million innocent lives.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/a454a198-7b15-41c5-828e-7f37528840bf" alt="Cumulative deaths and injuries" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**Tableau Dashboard Spotlight.**  
*The dashboard helped me break down the large Global Terrorism Database into a manageable visualization of event types and success metrics.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/923855b6-0482-41c0-9686-00dc3f843316" alt="Dashboard Ex." style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>
**Basic Workflow**  
*This represents my basic workflow for this project once I cleaned and prepared the dataset.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/61b28fbd-05b0-4832-93a7-fff835907b02" alt="Basic Workflow" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**Motives**  
*The predictive capacity of my model relies on NLP analysis of the 'motive' feature due to its predictive nature. See a few examples here.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/0908b913-ca62-4c79-8b9e-ba139314c720" alt="Motives" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**NLP Word Cloud**  
*Attack types and target-specific events are prone to involve key words and phrases in the 'motive' feature. See the below for attacks on educational institutions.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/2cffc904-585b-4dc2-bdee-2c152c330b29" alt="NLP Word Cloud" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**NLP Workflow**  
*This represents my workflow of Natural Language Processing on the 'motive' feature to produce a predictive model.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/70aacdd8-2d2c-4f7d-8c8b-14eadf6a44b4" alt="NLP Workflow" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**LightGBM Model Performance**  
*I evaluated potential models based on area under the precision-recall curve. LightGBM won by a small margin. But it still won.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/44b0dc72-2cc6-4076-96c3-3e03acf0ebef" alt="LightGBM Model Performance" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**User Interaction**  
*Interaction with the model is a simple input of the current sociopolitical circumstances that may potentially lead to a terrorist event (i.e., a motive). The model returns the target and attack types that have the greatest probability of succeeding given the user input.*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/d3897975-5f15-4bb9-87dc-b8a83f407c63" alt="User Interaction" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

**Plotly Dashboard**  
*Results are presented in an interactive dashboard that helps users navigate the many possibilities of a terrorist event..*

<br>

<div style="text-align:center;">
  <img src="https://github.com/samcast1/Capstone-2---Global-Terrorism/assets/152037421/b9cf1dcf-549e-446b-a0a3-2a7dedfd486b" alt="Plotly Dashboard" style="width:600px; border:1px solid black; display: block; margin: 0 auto;">
</div>

<br><br>

_____________________________________________________________________________________

# Conclusion and Further Work

In summary, this project provides an interactive implementation of the Light Gradient Boosting Machine Classifier to predict probabilities of terrorist events through NLP analysis of a user-defined description of the current sociopolitical climate. Future iterations may involve more extensive hyperparameter tuning via Bayesian Optimization or even new models built on recurrent neural networks. Overall, this project is a solid foundation for
future predictive models built on the Global Terrorism Database to aid in threat prevention and response.

Please email me if you have any questions or would like to collaborate on future projects.

Thank you!

<castillosam27@gmail.com>


