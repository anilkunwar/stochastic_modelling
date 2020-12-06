# Stochastic modelling of composites processing
A model for probabilistic modelling of a composite-tool system undergoing processing inside an autoclave given some noisy measurements of the material state is presented
<br>
<br>
Bootstrap particle filering method is coded for probabilistic modelling of composite-tool system. A composite material on a tool is going uncer a temperature cycle inside an autoclave. Some measurements are done during the processing at limited locations using some noisy sensors. The temperature and degree of cure are evolving based on the governing differential equations. We have uncertainties in:
1. all material properties  (18 material parameter)
2. air temperature inside the autoclave
3. initial temperature of the composite and tool (uncertainty in the room temperature)

We are finding the predictions of temperature at any location in composite and tool material and <br>


Inputs: <br>
1. Geometry of composite part and tool
2. All material properties and the uncersatinty in their values
3. Processing condition (temperature cycle)


Outputs: <br>
1. Mean value and unvertainty prediction of temperature at any location

<p align="center">
<img  align="center" src="https://github.com/saniaki/Gaussian-Process-for-Epoxy/blob/master/images/rod_variance.jpg" width="500"/>
  
  
Examples: <br>
1. sensor measurements at two locations
2. no sensor measurements
3. no sensor measurements, no uncertainty of air temperature
4. no sensor, only very high uncertainty in air temperature
5. no sensor, only very high uncertainty in air temperature, 30 elements (more number of elements for higher accuracy)
6. no sensor, only very high uncertainty in air temperature, constant temperature
