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

____________________________________________________________________________________________________________________________________________________________
| Participant |  Gender   |  Age   | Height    | Weight  |            Motions            |                     Personal Settings                              |
____________________________________________________________________________________________________________________________________________________________
|    01      |     M     |   28    |   1.78   |    79    |  FW, IW, Run, SW, SQ          |    FW: speed = 4.5 km/h, IW: speed = 3 km/h, incline = 7           |
|            |           |         |          |          |                               |    Run: speed = 9 km/h,      SQ: 5 kg load                         |
|    02      |     M     |   26    |   1.76   |    88    |  FW, IW, Run, SW              |    FW: speed = 4.2 km/h, IW: speed = 3 km/h, incline = 5           |
|            |           |         |          |          |                               |    Run: speed = 8.5 km/h                                           |
|    03      |     F     |   24    |   1.61   |    50    |  FW, IW, Run, SW, SQ          |    FW: speed = 3.5 km/h, IW: speed = 2.7 km/h, incline = 4         |
|            |           |         |          |          |                               |    Run: speed = 7 km/h, SQ: no load                                |
|    04      |     M     |   29    |   1.82   |    89    |  FW, IW, Run, SW, SQ          |    FW: speed = 5 km/h, IW: speed = 3.5 km/h, incline = 8           |
|            |           |         |          |          |                               |    Run: speed = 10 km/h, SQ: 10 kg load                            |
|    05      |     M     |   30    |   1.71   |    77    |  FW, IW, Run, SW, SQ          |    FW: speed = 5 km/h, IW: speed = 3 km/h, incline = 6             |
|            |           |         |          |          |                               |    Run: speed = 10 km/h, SQ: 5 kg load                             |
|    06      |     M     |   25    |   1.83   |    93    |  FW, IW, Run, SW              |    FW: speed = 5.2 km/h, IW: speed = 4 km/h, incline = 10          |
|            |           |         |          |          |                               |    Run: speed = 11 km/h                                            |
|    07      |     F     |   25    |   1.66   |    47    |  FW, IW, Run, SW              |    FW: speed = 3.8 km/h, IW: speed = 2.5 km/h, incline = 5         |
|            |           |         |          |          |                               |    Run: speed = 8.5 km/h                                           |
|    08      |     M     |   26    |   1.73   |    61    |  FW, IW, Run, SW              |    FW: speed = 4.5 km/h, IW: speed = 3.4 km/h, incline = 6         |
|            |           |         |          |          |                               |    Run: speed = 9.5 km/h                                           |
|    09      |     F     |   24    |   1.60   |    53    |  FW, IW, Run, SW              |    FW: speed = 3 km/h, IW: speed = 2.5 km/h, incline = 6           |
|            |           |         |          |          |                               |    Run: speed = 8.5 km/h                                           |
|    10      |     F     |   27    |   1.56   |    51    |  FW, IW, Run, SW              |    FW: speed = 3.5 km/h, IW: speed = 3 km/h, incline = 4           |
|            |           |         |          |          |                               |    Run: speed = 8.5 km/h                                           |
|    11      |     M     |   25    |   1.64   |    60    | Lift, Jump, Stairs, STS, SQ   |    Lift: 10 kg load,  SQ: 10 kg load                               |
|    12      |     M     |   28    |   1.77   |    81    | Lift, Jump, Stairs, STS, SQ   |    Lift: 20 kg load,  SQ: 10 kg load                               |
|    13      |     M     |   31    |   1.75   |    64    | Lift, Jump, Stairs, STS, SQ   |    Lift: 20 kg load,  SQ: 10 kg load                               |
|    14      |     M     |   30    |   1.70   |    78    | Lift, Jump, Stairs, STS, SQ   |    Lift: 20 kg load,  SQ: 10 kg load                               |
|    15      |     M     |   18    |   1.73   |    70    | BAS, BF, BRS, FC              |    Swimming skill level: Elite                                     |
|    16      |     M     |   21    |   1.85   |    76    | BAS, BF, BRS, FC, UW, USQ     |    Swimming skill level: Elite, USQ: 2.5 kg load                   |
|    17      |     M     |   22    |   1.67   |    69    | BAS, BF, BRS, FC, UW, USQ     |    Swimming skill level: Rookie, USQ: no load                      |
|    18      |     F     |   22    |   1.60    |    43   | BAS, BF, BRS, FC, UW, USQ     |    Swimming skill level: Elite, USQ: 2.5 kg load                   |
|    19      |     F     |   19    |   1.62    |    47   | BAS, BF, BRS, FC, UW, USQ     |    Swimming skill level: Medium, USQ: no load                      |
|    20      |     M     |   20    |   1.87   |    82    | BAS, BF, BRS, FC              |    Swimming skill level: Elite                                     |
|    21      |     M     |   24    |   1.76   |    74    | BAS, BF, BRS, FC              |    Swimming skill level: Medium                                    |
|    22      |     M     |   22    |   1.82   |    78    | BAS, BF, BRS, FC              |    Swimming skill level: Elite                                     |
|    23      |     F     |   18    |   1.62   |    50    | BAS, BF, BRS, FC              |    Swimming skill level: Elite                                     |
|    24      |     F     |   19    |   1.68   |    52    | BAS, BF, BRS, FC              |    Swimming skill level: Elite                                     |
____________________________________________________________________________________________________________________________________________________________

Notes: 

1. AmphiHip is primarily designed for supervised deep learning methods to conduct IP tasks, where the supervision is provided by task labels rather than
laboratory-grade global kinematics. The signals should be interpreted as sensor-fused reference hip states, not as optical motion captured ground-truth.

2. Ethical approval for the AmphiHip dataset acquisition experiments is obtained from the Ethics Committee of Xiangya Hospital, Central South University 
(Ethics Review Number: 2021111249).
