# Disease Java Se based application

Program consisting of disease.jar file and few files consisting of 
class viewed in html, so you can see commented classes.

In this problem I implemented simulation of microorganisms behaviour in human body. 

 reproduction ability of microorganisms is

(1) 	(random number between 0 and 1) * (microorganism birth  probability 0.1)*(1-population), 

So reproduction is function of population, birth probability and random number between (0-1)

Microorganism is cleared if  


(2)	(random number between 0 and 1) < (Microorganism clear constant 0.1)

The method getCurrentDensity method updates the amount of microorganisms, first we clear some microorganisms and after rest microorganisms reproduce if condition (1) is met. 

instantiation:

microorganisms, create a list of 100 Microorganisms
maximum population 1000
microorganism birth probability 0.1
microorganism clear probability 0.1
300 time steps
