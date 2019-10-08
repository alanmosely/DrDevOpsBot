## greet
* greet
  - utter_greet
  - utter_goodday

## goodbye
* goodbye
  - utter_goodbye

## greet+goodbye
* greet
  - utter_greet
  - utter_goodday
* goodbye
  - utter_goodbye

## happy
* greet
  - utter_greet
  - utter_goodday
* affirm
  - utter_great
* area{"area": "builds"}
  - slot{"area": "builds"}
  - utter_doctor
* goodbye
  - utter_goodbye

## unhappy
* greet
  - utter_greet
  - utter_goodday
* deny
  - utter_shame
* affirm
  - utter_dochelp
  - utter_area
* area{"area": "releases"}
  - slot{"area": "releases"}
  - utter_doctor
* goodbye
  - utter_goodbye

## superunhappy
* greet
  - utter_greet
  - utter_goodday
* deny
  - utter_shame
* deny
  - utter_area
* area{"area": "ci/cd"}
  - slot{"area": "ci/cd"}
  - utter_doctor
* goodbye
  - utter_goodbye
  