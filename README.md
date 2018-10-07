# MeaslesJapan2018

Supporting materials for Akhmetzhanov AR, Lee H, Jung S-M, et al (2018) Real time forecasting of measles using generation-dependent mathematical model in Japan, 2018. *Accepted for PLoS Currents Outbreaks*

**Background:** Japan experienced a multi-generation outbreak of measles from March to May, 2018. The present study aimed to capture the transmission dynamics of measles by employing a simple mathematical model, and also forecast the future incidence of cases. 

**Methods:** Epidemiological data that consist of the date of illness onset and the date of laboratory confirmation were analysed. A functional model that captures the generation-dependent growth patterns of cases was employed, while accounting for the time delay from illness onset to diagnosis. 

**Results:** As long as the number of generations is correctly captured, the model yielded a valid forecast of measles cases, explicitly addressing the reporting delay. Except for the first generation, the effective reproduction number was estimated by generation, assisting evaluation of public health control programs. 

**Conclusions:** The variance of the generation time is relatively limited compared with the mean for measles, and thus, the proposed model was able to identify the generation-dependent dynamics accurately during the early phase of the epidemic. Model comparison indicated the most likely number of generations, allowing us to assess how effective public health interventions would successfully prevent the secondary transmission.

---

Code scripts consists of two notebooks:
* "[*A. Main analysis [R].ipynb*](https://nbviewer.jupyter.org/github/aakhmetz/MeaslesJapan2018/blob/master/A.%20Main%20analysis%20%5BR%5D.ipynb)" presents the code that was used to run simulations and generate the results in the main part paper,
* "[*B. Considering also time varied delay function [R].ipynb*](https://nbviewer.jupyter.org/github/aakhmetz/MeaslesJapan2018/blob/master/B.%20Considering%20also%20time%20varied%20delay%20function%20%5BR%5D.ipynb)" shows the code that was used to perform additional analysis for time-varying delay function (see Appendix B).

Additionally, there is data-file "data.xlsx" used in our study.
