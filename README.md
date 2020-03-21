# COVID-19
Some data about COVID-19 disease

This repository aims to gather some (potentially) interesting data for COVID-19 Data Managers. The main file of this repository is covid19_events.xlsx.

This file is build as followed:
- id : primary key
- parentid : id of an event, that could be extracted from several sources ;
- iso2 : code ISO2 of worldwide countries ;
- start : start date of the event ;
- stop : stop date of the event (empty if ponctual event) ;
- label : label of the event. Can be:

    - lockdown : information about a quarantine ;
    - restriction : information about a restriction of access, less binding than a lockdown ;
    - cancellation : information about an event cancelled because of COVID-19 risk ;
    - report : information about a report made by a country or the WHO ;
    - control : information about rise in control operations ;
    - law : information about a law modification linked to COVID-19 ;
    - research : information about scientific research linked to COVID-19.
    
- type : separated from each other with a ";" ;
- description
- number : number associated to the label and type
- tag : tags that can help to group informations according to some criteria (complementary to label and type). The tags used are listed below (with XX as any number) and separated from each other with a ";":

        - man/woman : gender information about the death person;
        - n-a : tag linked to the number saying that it is an average (average);
        - n-o : tag linked to the number saying that the real number is over the referenced one(over);
        - n-l : tag linked to the number saying that the real number is below the referenced one (lower).

- level
- confidence
- source: source of the event information ;
- logtime: date of source's consultation and event logging.
