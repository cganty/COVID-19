# COVID-19
Some data about COVID-19 disease

This repository aims to gather some (potentially) interesting data for COVID-19 Data Managers. The main file of this repository is covid19_events.xlsx.

This file is build as followed:
- id
- parentid : 
- iso2
- start
- stop
- label
- type : separated from each other with a ";" ;
- description
- tag : tags that can help to group informations according to some criteria (complementary to label and type). The tags used are listed below (with XX as any number) and separated from each other with a ";":

        - man/woman : gender information about the death person;
        - sXX : ten in which is the age of the person concerned by the event;
        - cXX : number of positive-cases reported;
        - XXa : number around which is the number of actual positive-cases or death (around);
        - XXo : number above which is the number of actual positive-cases or death (over);
        - XXl : number under which is the number of actual positive-cases or death (lower);
        - dXX : number of total death-cases reported.

- level
- confidence
- source: source of the event information ;
- logtime: date of source's consultation and event logging.
