This repository contains the official implementation of the paper "Religion and International Private Law: How Faith Impacts Global Child Abduction Outcomes." It includes statistical models and analyses related to acceptance of partnerships between different countries. It is written in R language and uses the packages “margins” and “xtable,” among others.

<p align="center">
  <h1 align="center">Religion and International Private Law: How Faith Impacts Global Child Abduction Outcomes</h1>
  <p align="center">
    <a href="http://www.columbia.edu/~rws2162/"><strong>Ryan W. Safiry</strong></a><br>
    Advisor:<a href="https://en.wikipedia.org/wiki/Andrew_J._Nathan" style="margin-left:0.3cm"><strong>Andrew J. Nathan</strong></a>
</p>

<p align="center">
  <img src="http://www.columbia.edu/~rws2162/thesis/survivalcurvethesis.png" alt="teaser" width="400px">
</p>



<h2>Statistical Models</h2>

The code includes the following statistical models:

- **Logistic model for acceptances with same religions
- **Logistic model for acceptances with different religions
- **Logistic model for acceptances where both countries are Muslim
- **Logistic model for acceptances where the accepting country is Muslim
- **Logistic model for acceptances where the acceding country is Muslim
- **Logistic model for acceptances where at least one of the countries in the dyad is Muslim
- **Logistic model for acceptances where neither of the countries in the dyad is Muslim
- **Cox proportional hazard model for acceptances with same religions
- **Cox proportional hazard model for acceptances with different religions
- **Cox proportional hazard model for acceptances where both countries are Muslim
- **Cox proportional hazard model for acceptances where the accepting country is Muslim
- **Cox proportional hazard model for acceptances where the acceding country is Muslim
- **Cox proportional hazard model for acceptances where at least one country in the dyad is Muslim
- **Cox proportional hazard model for acceptances where neither country in the dyad is Muslim

<h2>Additional Features</h2>
The code also includes calculation of average marginal effects and plotting of the marginal effects for the logistic model where pairs have a different specific religion. It also generates tables summarizing the results for some of the models using 'xtable'.

<h2>Dataset and Variables</h2>
As reflected in the code, the dataset includes variables such as acceptance of refugees, religion, country of origin and destination, rule of law, population, distance, migrant stock, GDP per capita, regulatory quality, and divorce rates among women aged 40-44 years old.

<br>Please reach out to me for the full code, dataset, or any other info.
