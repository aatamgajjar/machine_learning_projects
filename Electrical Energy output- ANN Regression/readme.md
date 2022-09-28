# Predicting Electrical energy output using Artificial Neural Network Regression


#### This is a case study that shows how to build an ANN Regression model to predict the electrical energy output of a Combined Cycle Power Plant.

A combined-cycle power plant is an electrical power plant in which a Gas Turbine (GT) and a Steam Turbine (ST) are used in combination to produce more electrical energy from the same fuel than that would be possible from a single cycle power plant.

The gas turbine compresses air and mixes it with a fuel heated to a very high temperature. The hot air-fuel mixture moves through the blades, making them spin. The fast-spinning gas turbine drives a generator to generate electricity. The exhaust (waste) heat escaped through the exhaust stack of the gas turbine is utilized by a Heat Recovery Steam Generator (HSRG) system to produce steam that spins a steam turbine. This steam turbine drives a generator to produce additional electricity. CCCP is assumed to produce 50% more energy than a single power plant.

The objective is to create a data model that predicts the net hourly electrical energy output (EP) of the plant using available hourly average ambient variables.


**Tools:** Tensorflow 2.0

**Dataset:** [UCI Machine Learning Repository: Combined cycle power plant](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)

**Features**:
- Temperature (T) in the range 1.81°C and 37.11°C,
- Ambient Pressure (AP) in the range 992.89-1033.30 milibar,
- Relative Humidity (RH) in the range 25.56% to 100.16%
- Exhaust Vacuum (V) in teh range 25.36-81.56 cm Hg
- Net hourly electrical energy output (EP) 420.26-495.76 MW
The averages are taken from various sensors located around the plant that record the ambient variables every second. The variables are given without normalization.


**Relevant Papers:**

Pınar Tüfekci, Prediction of full load electrical power output of a base load operated combined cycle power plant using machine learning methods, International Journal of Electrical Power & Energy Systems, Volume 60, September 2014, Pages 126-140, ISSN 0142-0615, [Web Link]. ([Web Link])

Heysem Kaya, Pınar Tüfekci , Sadık Fikret Gürgen: Local and Global Learning Methods for Predicting Power of a Combined Gas & Steam Turbine, Proceedings of the International Conference on Emerging Trends in Computer and Electronics Engineering ICETCEE 2012, pp. 13-18 (Mar. 2012, Dubai)


_Credits: _[Hadelin de Ponteves | Udemy](https://www.udemy.com/course/linear-regression-with-artificial-neural-network/)
