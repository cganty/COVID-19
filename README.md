# COVID-19
Some data about COVID-19 disease

This repository aims to gather some (potentially) interesting data for COVID-19 Data Managers. The main file of this repository is covid19_events.xlsx.

This file is build as followed:
- id
- parentid
- iso2
- start
- stop
- label
- type
- description
- tag : tags that can help to group informations according to some criteria (complementary to label and type). The tags used are listed below (with XX as any number):
        * man/woman : gender information about the death person;
        * XXs : ten in which is the age of the person;
        * XXc : number of positive-cases reported;
        * oXXc : number above which is the number of actual positive-cases;
        * XXd : number of total death-cases reported.
- level
- confidence
- source: source of the event information ;
- logtime: date of source's consultation and event logging.
