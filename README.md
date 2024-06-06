# Eye Gaze During Conversation


This repository contains a dataset of eye-tracking data aquired during remote video conversations. The dataset can be used to train models that generate novel eye movement for animated avatars. For details please see the scientific publication


```
David Dembinsky, Ko Watanabe, Andreas Dengel, and Shoya Ishimaru.  
2024. Eye Movement in a Controlled Dialogue Setting.  
In 2024 Symposium on Eye Tracking Research and Applications (ETRA ’24), June 04–07, 2024,
Glasgow, United Kingdom. ACM, New York, NY, USA, 7 pages.
https://doi.org/10.1145/3649902.3653337
```
The publication can be found [here](https://www.researchgate.net/publication/379226792_Eye_Movement_in_a_Controlled_Dialogue_Setting)

## Data
The [data](data/) is collected from 19 participants, each found in a seperate folder.  
- `gaze.csv` data, from which fixations are extracted. For more details on preprocessing please refer to the publication or to [this script](move_data.html).
- `fixations.pkl` contains the extracted fixations.

The [data_example](data_example.html) shows how to load and process the data and explains the data format further.


## Cite
If you want to use the data  or find the code useful for your research, please cite the following paper:

```
@inproceedings{10.1145/3649902.3653337,
author = {Dembinsky, David and Watanabe, Ko and Dengel, Andreas and Ishimaru, Shoya},
title = {Eye Movement in a Controlled Dialogue Setting},
year = {2024},
isbn = {9798400706073},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3649902.3653337},
doi = {10.1145/3649902.3653337},
booktitle = {Proceedings of the 2024 Symposium on Eye Tracking Research and Applications},
articleno = {10},
numpages = {7},
keywords = {Animated Avatars, Data Collection, Eye Movement, Gaze Synthesis},
location = {<conf-loc>, <city>Glasgow</city>, <country>United Kingdom</country>, </conf-loc>},
series = {ETRA '24}
}
```
