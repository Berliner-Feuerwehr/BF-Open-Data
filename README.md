# BF-Open-Data

<img src="https://github.com/Berliner-Feuerwehr/BF-Open-Data/blob/main/img/BF_logo.png" alt="x" width="600"/>
<!--![](https://github.com/Berliner-Feuerwehr/BF-Open-Data/blob/main/img/Bfw_Logo_M_DE_PW_RGB.png)-->
The Open Data Platform of the Berlin Fire Brigade
<!--(Für die deutsche Version bitte herunterscrollen)-->

## Introduction:
<!--Briefly describe the purpose and scope of your open data platform.-->
In an effort to become a modern city, Berlin published its Open Data strategy in 2012. In the same year, a city-wide open data portal, called daten.berlin.de was launched. Meanwhile over 3000 datasets are available for the public and the number keeps growing. 
    

The Berlin Fire Brigade offers critical services like fire rescue, ambulance service as well as technical assistance. 
The quality of emergency services makes the difference between a tragedy and a narrow escape. 
Therefore, it is crucial for each citizen to be well informed about the quality of emergency services available to them. 
In this repository, we will publish datasets relevant to our operations for everyone to use.  

<!--Explain what kind of data is available and its significance.-->

The datasets contains aggregated information about missions and alarms. 
Our data contains information about:

- the demand for emergency services of different kinds 
- the quality of our services offered, e.g. in terms of response times
- the situation on a city-wide scale or in your specific neighborhood  
    
This is an ongoing project number and types of datasets will grow continously. 


## Disclaimers:

This is a machine-generated data set.
There may be differences to the annual report of the Berlin Fire Brigade, which may stem from a case-by-case consideration of the missions. 
Differences arise primarily in the classification of missions as "other" or internal missions.

On New Year's Eve ( turn of the year 24/25), there were temporary restrictions on the 112 emergency number, meaning that emergency calls were briefly answered at the fallback level. These calls were not documented in the system, thus the emergency call numbers shown here are not complete. The emergency control center was able to process emergency calls at all times, emergency calls were accepted and all missions were processed.

## Getting Started:
<!--<Provide instructions on how to access the data.-->
All data is provided as csv-files in this repository. You can simply search for the data that suits your interest and download it.
    
<!--Explain any prerequisites (e.g., software, tools, or APIs) needed to work with the data.-->
No special software is required to work with our data. 

<!--Data Sources and Formats:-->
<!--List the sources of your data (e.g., government agencies, research institutions).-->
<!--Specify the data formats (CSV, JSON, XML, etc.) available for download.-->

## Data Catalog: 
| Name | Content | Spacial Resolution | Temporal Resolution | Update frequency
|------|--------|--------|--------|--------|
|  Kiez Data | Mission counts and response times |Based on the [Living Spaces (LOR)](https://www.berlin.de/sen/sbw/stadtdaten/stadtwissen/sozialraumorientierte-planungsgrundlagen/lebensweltlich-orientierte-raeume/) concept of Berlin. Either 58 prediciton rooms, 143 district areas or 542 planning rooms  |  1 year    | daily |
| Daily Data | Mission counts,response times, call counts, answer times  | The entire city of Berlin   | 1 day, 1 month, 1 year   | daily |  |   |
| Mission Data | Detailed information about our missions | The entire city of Berlin   | 1 mission | daily |   |
|  Dispatchcodes | A mapping of dispatchcodes to resource requierements| N.A.  | N.A.   | irregularly |   |   |


<Create a table or list of available datasets.>
<Include a brief description for each dataset.>
<Mention any relevant metadata (e.g., date of collection, geographical coverage).>

## Usage Examples:
You can find visualiziations derived from our data on our website:

https://www.berliner-feuerwehr.de/service/open-data/
<!-- -Showcase how users can utilize the data (e.g., data analysis, visualization, research).>
<Provide code snippets or examples demonstrating data retrieval and manipulation.

You could use our data to make pretty plots or train your own statstical models.

![https://datawrapper.dwcdn.net/Xg6aR/1/](https://datawrapper.dwcdn.net/Xg6aR/full.png) -->

### Types of missions
#### EMS
EMS stands for Emergency Medical Service. It contains all mission where a person is in need of medical assistance.
#### Critical EMS
Critical EMS missions are EMS mission of highest priority.
#### Critical EMS CPR
Critical EMS missions that seem to require Cardiopulmonary resuscitation. This assumption is based on the information obtained from the emergency call. 
#### Fire 
Mission where a fire is at least suspected. The missions range from smoke detectors alarming us to structure fires. 
#### Technical Rescue
Missions where special equipment is required. Examples are opening doors, assistance in the event of storms and floods and dangerous good operations. 

### Types of calls
#### Call
Includes all calls to the control center. That is, emergency calls (112), automatic calls, emergency relocations, calls by the fire stations etc. 

#### Emergency call
Calls where people dialed 112.


### Types of measures
#### Mission Count
The number of missions
#### Reponse Time
The response time (Hilfsfrist) is the time from mission creation until the first vehicle arrives at the scene. 2 minutes are added to this time for the emergency call and dispatch.
#### Time to first Pump
Time to first pump is the time from mission creation until the first water carrying vehicle arrives at the scene. 2 minutes are added to this time for the emergency call and dispatch.
#### Time to first Ladder
Time to first Ladder is the time from mission creation until the first ladder carrying vehicle arrives at the scene. 2 minutes are added to this time for the emergency call and dispatch.
#### Time to full Crew
Time to full crew is the time from mission creation until at least 14 firefighters arrive at the scene. 2 minutes are added to this time for the emergency call and dispatch.
#### Answer Time
The time it takes the control center to answer a ringing phone. 

## License and Terms of Use:
<!--Clearly state the licensing terms for using the data (e.g., Creative Commons, Open Data Commons).
Include any restrictions or requirements (e.g., attribution, share-alike). -->
[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


If you use our data we kindly ask you to cite us like so
e.g. if you use data from Daily_Data/BFw_mission_data_daily.csv in 2024: 

"BFw Mission Data Daily, Berliner Feuerwehr, Berlin 2024"

## Contributing:
<!--Encourage contributions from the community (e.g., data updates, bug fixes).>
<Explain how users can submit new datasets or improve existing ones.-->
Did you spot an error? Do you have questions? Do you have any ideas for useful information or aggreagtion thereof?
Feel free to contact us. We will be glad to help. 

## Contact Information:
<!--Provide contact details for inquiries, feedback, or collaboration.>
<Link to relevant social media profiles or mailing lists.-->
You can contact us under
datenmanagement[at]berliner-feuerwehr.de

