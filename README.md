# Stochastic modelling of composites processing
A model for probabilistic modelling of a composite-tool system undergoing processing inside an autoclave given some noisy measurements of the material state is presented
<br>
<br>
Bootstrap particle filering method is coded for probabilistic modelling of composite-tool system. A composite material on a tool is going under a temperature cycle inside an autoclave. Some measurements are done during the processing at limited (multiple) locations using some noisy sensors. The temperature and degree of cure are evolving based on the governing differential equations. We have uncertainties in:
1. all material properties  (18 material parameters)
2. air temperature inside the autoclave
3. initial temperature of the composite and tool (uncertainty in the room temperature)
We are prediction temperature at any location in composite and tool material and uncertainties associated to those temperature values. <br>
<br>
<p align="center">
<img  align="center" src="https://github.com/saniaki/Stochastic_modelling_composites_processing/blob/main/images/imge01.jpg" width="750"/> <br>
<br>

Inputs: <br>
1. Geometry of composite part and tool
2. All material properties and the uncersatinty in their values
3. Processing condition (temperature cycle)
Outputs: <br>
1. Mean value and unvertainty prediction of temperature at any location
<br>

An exmaple of predictions <br>
<p align="center">
<img  align="center" src="https://github.com/saniaki/Stochastic_modelling_composites_processing/blob/main/images/image2.jpg" width="650"/>  <br> 

Available examples: <br>
1. sensor measurements at two locations
2. no sensor measurements
3. no sensor measurements, no uncertainty of air temperature
4. no sensor, only very high uncertainty in air temperature
5. no sensor, only very high uncertainty in air temperature, 30 elements (more number of elements for higher accuracy)
6. no sensor, only very high uncertainty in air temperature, constant temperature
<br>
<br>
Reference <br>
https://www.cs.ubc.ca/~arnaud/doucet_johansen_tutorialPF.pdf <br>
https://link.springer.com/chapter/10.1007/978-1-4757-3437-9_1 <br>
https://stats.stackexchange.com/questions/237468/bootstrap-filter-particle-filter-algorithmunderstanding <br>
<br>
<br>

**Acknowledgement** <br>
This model is developed with support of <br>
<br>
<p align="center">
<img  align="center" src="https://github.com/saniaki/active_learning/blob/main/images/image02.png"/> 
