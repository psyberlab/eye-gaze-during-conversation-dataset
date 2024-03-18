# Eye Gaze During Conversation


This repository contains a dataset of eye-tracking data aquired during remote video conversations. The dataset can be used to train models that generate novel eye movement for animated avatars. For details please see the scientific publication


```
Eye Movement in a Controlled Dialogue Setting
D. Dembinksy, K. Watanabe, S. Ishimaru, A. Dengel
```
The publication can be found [here](https://foo.bar/foobar)

## Data
The [data](data/) is collected from 19 participants, each found in a seperate folder.  
- `gaze.csv` data, from which fixations are extracted. For more details on preprocessing please refer to the publication or to [this script](move_data.html).
- `fixations.pkl` contains the extracted fixations.

The [data_example](data_example.html) shows how to load and process the data and explains the data format further.


## Cite
If you want to use the data  or find the code useful for your research, please cite the following paper:

```
@bibtext{
    foo = {bar}
}
```
