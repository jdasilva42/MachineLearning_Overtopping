## Purpose

<i>The overtopping discharge is usually computed from an empirical method explain in the Eurotop manual (http://www.overtopping-manual.com).
  
Based on the CLASH dataset (explaned below), Gradient Boosting Regressor and SVR regression have been trained for predict opvertopping discharges from specific inputs.</i>

## Project structure
```
MachineLearning_Overtopping :
    |   Use_case.ipynb
    |
    +---DataBase
    |       Database_20050101v2.xls
    |       Features_inputs.jpg
    |
    \---models
            model_GBR.pkl
            model_SVR_reg.pkl
```
```
Use_case.ipynb
```
<i>Contains the jupyter notebook describing the project. GBR model (Gradient Boosting Regressor) and SVR model are used for overtopping prediction on the test set.</i>
````
+---DataBase
|       Database_20050101v2.xls
|       Features_inputs.jpg
````
<i>Contains the Clash Database.<br/><br/> 
The data is the database created within the framework of
the European project CLASH. This database includes tests
collected from several laboratories. Results from about 10,000 overtopping tests are included in
the database. Each of these tests is described by a number of
parameters that represent hydraulic information (i.e. incident
wave characteristics and measured overtopping discharges) as
well as structural information (i.e. parameters characterising the test sections).<br/><br/> 
Moreover, the database includes some general
information regarding the reliability of the test and the
complexity of the structure. The reliability of each test was
estimated and defined in terms of a Reliability Factor (RF). In
the present database the values of the RF ranged from RF=1 for
a ‘very reliable’ test to RF= 4 for a ‘non-reliable’ test. RF=1
was given to tests for which all required information was
available in the corresponding reports and no variable
estimation was needed, while RF=4 was given to tests for
which the estimation of some parameters was not acceptable
and for which the measurements included many uncertainties.In a similar way, the complexity of each test was estimated and
defined in terms of a Complexity Factor (CF). CF=1 was given
to tests with a ‘very simple’ structure in which the parameters
describe the cross-section exactly, while CF=4 was given to
tests with a ‘very complex’ structure in which the cross-section
cannot accurately be described by the chosen parameters.</i>

```  
\---models
        model_GBR.pkl
        model_SVR_reg.pkl
 ``` 
<i>Contains the prediction models and the features train and test. </i>
