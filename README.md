# Purpose
<br/><i>
The overtopping discharge estimations are computed from an empirical method explain in the Eurotop manual (http://www.overtopping-manual.com/).  These equations have been setup from the CLASH database (see below). However, the accuracy of theses equations is problematic when the inputs parameters are closed from the validation domain (who happens very often). 
<br/><br/>
The access to the CLASH database can allow the ML and DP utilizations for increase the accuracy of the overtopping discharges.<br/><br/>
The first step, here, is to define the possibilities given by the ML algorithms regressor. A simple Decision tree regressor and more complex model Gradient Boost regressor have been setup and compared. </i>
<br/><br/>
<br/> 

#CLASH DataBase
<i>
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
and for which the measurements included many uncertainties.<br/><br/> 
In a similar way, the complexity of each test was estimated and
defined in terms of a Complexity Factor (CF). CF=1 was given
to tests with a ‘very simple’ structure in which the parameters
describe the cross-section exactly, while CF=4 was given to
tests with a ‘very complex’ structure in which the cross-section
cannot accurately be described by the chosen parameters.</i> 
