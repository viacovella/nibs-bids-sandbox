# Log of the changes


## 2024-06-12

* Fake Participants
    * Filled a **FAKE** participants.tsv file. Revised both the json sidecar and the table.
    * 8 sub-0* initialized. Each of them belongs to 1 group among those specified in the participants.tsv


## 2024-06-11
* Finalized the participants table schema. The rationale behind it is the following:
    * Standard columns (age, sex, handedness)
    * a column with a number from 1 to 8 reflecting the 8 different combinations of Electrode Configuration, Application and experiment 1- and 2- modality, current intensity and actual/sham application.