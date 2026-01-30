# AmphiHip-Dataset
The AmphiHip dataset contains four folder named on-land daily, on-land rehabilitation, underwater daily, and underwater rehabilitation, respectively, 
with 157 trails of 15 kinds of lower limb motion from 24 participants in total. 

The on-land daily folder includes data of 14 participants performing Flat walk (FW), Incline walk (IW), Running (Run), Jumping (Jump), Lifting (Lift), 
and Stairs climbing (Stairs). 
The on-land rehabilitation folder includes data of 14 participants performing Slow walk (SW), Sit-to-stand transition (STS), and Squat (SQ). 
The underwater daily folder includes data of 10 participants performing Butterfly (BF), Backstroke (BAS), Breaststroke (BRS), and Front crawl (FC). 
The underwater rehabilitation folder includes data of 4 participants performing Underwater walk (UW) and Underwater squat (USQ). 

There are 14 sub-folders in each on-land motion folders, while 10 sub-folders and 4 sub-folders exist in underwater daily and underwater rehabilitation folder, 
independently. 

Each sub-folder is named by "Participant+ID". The collected data are named by "Motion+GroupID" and are saved in Excel format. 
For example, the first group of FW data could be found in "on-land daily/Participant_1/flatwalk_1.csv". 

The data categories in each Excel file are explained as follows:

    Label: The corresponding motion of the file, using the abbreviations.

    Left-Hip-q, Right-Hip-q (°): The reference joint trajectory of left and right hip.

    Left-Hip-qd, Right-Hip-qd (°/s): The reference joint velocity of left and right hip.

    SampleTimeFine: The time frame of data.


The dataset descriptions including the gender, age, height, weight, motions, and the personal setting of each participant, are as follows:
<img width="1322" height="935" alt="image" src="https://github.com/user-attachments/assets/8a370322-e0c4-4108-b073-2be1074a6f60" />


Notes: 

1. AmphiHip is primarily designed for supervised deep learning methods to conduct IP tasks, where the supervision is provided by task labels rather than
laboratory-grade global kinematics. The signals should be interpreted as sensor-fused reference hip states, not as optical motion captured ground-truth.

2. Ethical approval for the AmphiHip dataset acquisition experiments is obtained from the Ethics Committee of Xiangya Hospital, Central South University 
(Ethics Review Number: 2021111249).
