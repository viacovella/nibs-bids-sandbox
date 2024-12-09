# Log of the changes

## 2024-11-21
* Inserted an attempt of representing the 2 main situations of the dataset: Offline / Online (sub-03), Online / Offline (sub-01)
* For now, there are no "intervention" directories (see BEP section 2.4), in that here the offline period is in combination with the presentation of an audiobook

## 2024-06-13
* Sessions
    * defined the sessions sequence (audiobook; experiment)
    * updated the sessions{tsv,json} files
    * created the audiobook session behavioral files

## 2024-06-12

* Fake Participants
    * Filled a **FAKE** participants.tsv file. Revised both the json sidecar and the table.
    * 8 sub-0* initialized. Each of them belongs to 1 group among those specified in the participants.tsv


## 2024-06-11
* Finalized the participants table schema. The rationale behind it is the following:
    * Standard columns (age, sex, handedness)
    * a column with a number from 1 to 8 reflecting the 8 different combinations of Electrode Configuration, Application and experiment 1- and 2- modality, current intensity and actual/sham application.
