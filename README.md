Product-Dev-Test
=====================
Test for potential OptiRTC Product developers.

Welcome
-------
This repository is the starting point for a new OptiRTC Product developer. It includes a Requirements section defining the expectations for the work and static resources for use in the work.

Getting Started
---------------
1. Clone this repository to your local system.
2. Build your application in accordance with the Requirements section, checking in code to your local clone of this repository.
3. Attach a zip file of your complete repository along with your job application, or send it to your contact at OptiRTC.

Requirements
------------
A facility being monitored is a 6 inch thick, rectangular, homogenous soil media with a porosity of 0.25 and 12600 square feet of surface area. A week of soil moisture (m^3 water /m^3 soil media) and precipitation (inches) observations is contained in the file GreenRoofStorms.json. Please develop an algorithm that:

1. Separates individual "instantaneous" precipitation readings (all of the rain that fell since the previous reading, so 5-minute cumulative readings effectively treated as instantaneous readings) into individual storm events.
2. Identifies the point in time at which each soil moisture sensor appears to have first detected the response to each identified storm event.
3. Computes a running 15-minute change in stored water content within each storm event.
4. Reports these results to the user.

Additionally, the implementation must:

1. Be executable from a command line interface, taking the input data file as an argument.

How you will be evaluated
-------------------------
We are looking for concise and readable code that meets the specified Requirements. Where the Requirements are ambiguous or lacking, we are looking to see you make a decision that allows you to move forward without compromising the basic functionality of the application (hint: we want to talk to you about how you made these decisions during the in-person interview). We are expecting this task to take you 30 minutes to 3 hours; please do not spend more than 5 hours on this task.
