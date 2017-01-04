# Padilla, Ruginski, & Creem-Regehr, 2016 - Ensemble Display Cognition
#### Data for manuscript submission to Cognitive Research: Principles and Implications

There are three files corresponding to separate analyses in the manuscript:
-  SizeData.csv (analysis for size judgments, Experiment 1)
-  IntensityData.csv (analysis for intensity judgments, Experiment 1)
-  EnsembleFollowup_LogisticData.csv (analysis for Experiment 2)

#### Variables (columns) in SizeData.csv
1. *ResponseID*: Participant number.
2. *Hurricane*: Indicates hurricane which data was based off in visualization. We had two for diversity of stimuli.
3. *StartSize*: Starting size of the hurricane provided to participants.
4. *Location*: Location in kilometers that the oil rig was located from the center of the hurricane.
5. *value*: Size judgment provided by the participant.
6. *VisType*: String variable indicating visualization type (between-participants variable)
7. *Encoding*: Marks this data as size or intensity data, in case you want to combine with intensitydata.csv.
8. *Side*: Dummy code indicating if the oil rig was left (0) or right (1) of the hurricane forecast visualization.
9. *LocationAbs*: Absolute value of distances, divided by 10. Indicates a 10 kilometer change in a regression modeling framework. This is the distance variable included in manuscript analyses.
10. *change*: Difference between value and StartSize. Indicates whether participant thought hurricane became larger (positive), stayed the same (0), or became smaller (negative). Dependent variable utilized in regression analyses.
11. *VisTypeD*: Dummy code of the VisType variable where 0 corresponds to the cone visualization and 1 corresponds to the ensemble visualization.

#### Variables (columns) in IntensityData.csv
1. *ResponseID*: Participant number.
2. *Hurricane*: Indicates hurricane which data was based off in visualization. We had two for diversity of stimuli.
3. *StartSize*: Starting size of the hurricane provided to participants.
4. *Location*: Location in kilometers that the oil rig was located from the center of the hurricane.
5. *value*: Size judgment provided by the participant.
6. *VisType*: String variable indicating visualization type (between-participants variable)
7. *Encoding*: Marks this data as size or intensity data, in case you want to combine with sizedata.csv.
8. *Side*: Dummy code indicating if the oil rig was left (0) or right (1) of the hurricane forecast visualization.
9. *LocationAbs*: Absolute value of distances, divided by 10. Indicates a 10 kilometer change in a regression modeling framework. This is the distance variable included in manuscript analyses.
10. *change*: Difference between value and StartSize. Indicates whether participant thought hurricane became more intense (positive), stayed the same (0), or became less intense (negative). Dependent variable utilized in regression analyses.
11. *VisTypeD*: Dummy code of the VisType variable where 0 corresponds to the cone visualization and 1 corresponds to the ensemble visualization.

#### Variables (columns) in EnsembleFollowup_LogisticData.csv
1. *id*: Participant number.
2. *image*: Image number (could also be considered "trial").
3. *Damage*: 1 indicates participant chose far oil rig will receive more damage, 0 indicates participant chose close oil rig to receive more damage.
4. *OnLineC*: Contrast code indicating whether the close or far oil rig was touching an ensemble line. .5 corresponds to far oil rig touching an ensemble track, -.5 corresponds to close oil rig touching an ensemble track.
5. *LinesC*: Number of lines from the ensemble visualization overlapping with the oil rig. This variable was not included in manuscript analyses. .5 corresponds to 2 lines overlapping, while -.5 correponds to 1 line overlapping.

There are three supplementary files corresponding to follow-up question analysis in the manuscript:
-  SizeData_questions.csv (analysis for size judgments, Experiment 1)
-  IntensityData_questions.csv (analysis for intensity judgments, Experiment 1)
-  EnsembleFollowup_questions.csv (analysis for Experiment 2)


#### Variables (columns) in SizeData_questions.csv,  IntensityData_questions.csv, and EnsembleFollowup_questions.csv
1. *id*: Participant number.
2. *Strategy*: Verbal description of self-reported strategy used for task.
3. *Forecasts*: "Do you have experience with hurricane forecasts?"" 1 indicates yes, 2 indicates no.
4. *Threats*: "Have you lived or do you live in an area that experiences hurricane threats?" 1 indicates yes, 2 indicates no.
5. *Red_Dot*: What did you think the Red Dot Represented? 1 indicates The position of the center/eye of the hurricane, 2 indicates A position within the hurricane, 3 indicates The outer edge of the hurricane, 4 indicates other
6. *Red_Dot_TEXT*: If answered 4 for Red_Dot, this is what was filled in
7. *Larger*: The display shows the hurricane getting large over time. 1 indicates yes, 2 indicates no.
8. *Variable*:  The display indicates that the forecasters are less certain about the path of the hurricane as time passes. 1 indicates True, 2 indicates False.
9. *Hit*: Areas on the map not covered by the visualization will not be hit by the hurricane. 1 indicates True, 2 indicates False
10. *VisType*: Visualization Type
11. *Age*: Age as numeric
12. *Gender*: 1 is male, 2 is female
