# Scope
Good software leads you to understanding. It's navigation shows the topology of the system. It's abstractions, generalized concrete details, make it easy to view power, meter, weather, and trend data with a statistical bent. The forms contain enough, not too much, actionable intelligence for their purpose. It is chunked up so that you can quickly move from one view to another equally relevant view. The views are within a context that makes sense.
## Products
The following are applications that I created and use:
* Job Tracking
* Load Estimation
* Facility Ratings
* Switching
  Job Tracking has been in use for over a decade, Load Estimation since 2015, Facility Ratings are something I'm presently working, and Switching is coming up. There are many users of Job Tracking, and a handful of users for Load Estimation.
## Road Map
I quit developing Job Tracking except for minor updates. The navigation system for Load Estimation has become default for all electrical systems. It is based on Buses and Node-Breakers. This aligns closely to Supervisory Control and Data Aquisition (SCADA) systems. Therefore, it is easy to locate information for a particular electric node or piece of equipment. This system is used in the Facility Ratings and the Switching framework.
## Summer School
What tools can be created out of the Wolfram Language to progress these products?
How can System Modeler combined with scripting in Wolfram Language to analyze new views of the data?
## Statistical Analysis
The frequentist approach assigns probabilities to data, not to hypotheses, whereas the Bayesian approach assigns probabilities to hypotheses. I believe I used Bayesian statistics to determine the peak flows on our system. Here are a few hypothesis:
* Peak flows occur because HVAC load increases linearly with temperature. This adds to the typical daily loads.
* If gas is the HVAC backup, then only gas loads increase as the temperature goes down in the winter.
* Since HVAC loads are primarily motors in the Summertime you can estimate the reactive power.