# 42_Internship_1
In the 42 curriculum we have the opportunity to perform one (or two) internship. This repository contains a part of the work realised during the 6 months in Natixis Bank in the  Antifraud team. This internship was under the supervision of Benoit Gatien and Valéry Adeleine.

## Context
In january 2008, the french bank Société Générale lost 4.9 billions euros due to it trader Jerome Kerviel who had engaged around 60 billions in the market. He succeed to engage such an amount by hiding the risk with fictitious inverse position. After the case was revealled, the financial minister at the time Christine Lagarde conducted a repport in february 2008. Few years afer (2014) the governement adpoted a decree related to the intern control of the bank institutions having investment activities.

Since 2014, every bank having some activities on the financial market, has to develop intern control and improve it antifraud processes.
It is in the context of improving the antifraud tools that I realised my internship with a second intern Thomas Pillot.

## Presentation & Video
You can find in the directory "communications" the pdf of my final presentation and the video dedicated to the internship defense.


## Methodology
2 approaches were explored:
* Time series modelling with AR(p), MA(q), ARMA(p,q), ARIMA(p,d,q) and SARIMA(p,d,q,P,D,Q) models (SARIMAX also but not finished and presented here).
* Application of Isolation Forest algorithm.

Thomas leads the work on the isolation forest method, wheras I leads the work with time series modelisation.

### Isolation forest

🚧 redaction in progress 🚧

### Time series modelisation
🚧 redaction in progress 🚧

## Technical work
I retrieve 2 part of my works:
* The tricolor scale [Tern-CS](https://github.com/madvid/Tern_Color_Scale) made in Python
* A bunch of function to simplify some the interaction with the statsmodels and performs a kind of grid-search on the SARIMA model parameters, named [ModeTiS](https://github.com/madvid/ModeTiS)

## Bibliography
1. 📰 - [Fei Tony Liu, Isolation Forest](https://cs.nju.edu.cn/zhouzh/zhouzh.files/publication/icdm08b.pdf?q=isolation-forest)
2. 📰 - [Hariri, Extended Isolation Forest(Nov2018)](https://paperswithcode.com/paper/extended-isolation-forest)
3. 📺 - [PyData Amsterdam 2019 - Jan Van Der Vegt, A walk through the isolation forest](https://www.youtube.com/watch?v=RyFQXQf4w4w)
4. :books: [MOOC: Pratical Time Series Analysis](https://fr.coursera.org/learn/practical-time-series-analysis)
5. :books: [MIT 18.S096 Topics in Mathematics with Applications in Finance](https://ocw.mit.edu/courses/mathematics/18-s096-topics-in-mathematics-with-applications-in-finance-fall-2013/)

## Aknowledgement
I thank my supervisor Valéry Adeleine and Benoit Gatien, the developpers of the team Valentin Fabianski and Antoire Barruol. I am also grateful of the incredible work made by Alexandre Collemare and Pierre Leger who managed (at least at the time) the Lab42 x Natixis. 