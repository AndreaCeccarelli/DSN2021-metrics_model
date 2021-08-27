# DSN2021-metrics_model

Repository of the paper submitted at DSN 2021

We argue that object detectors in the safety critical domain should prioritize detection of objects that are most likely to interfere with the actions of the actor, especially when they can impact task safety and reliability. In the context of autonomous driving, we propose new object detection metrics that reward the correct identification of objects that are most likely to interact with the subject vehicle (i.e., the actor), and that can interfere on its driving decision. To achieve this, we build a criticality model to reward the detection of the objects based on proximity, orientation, and relative velocity with respect to the target vehicle. Then, we apply our model on the recent autonomous driving dataset nuScenes, and we compare eighth different object detectors. Results show that, in several settings, object detectors that perform best according to the nuScenes ranking are not the preferable ones when the focus is shifted on safety and reliability.

## Contents of the repository
- the modified nuScenes library
- notebooks to run our model and collect results

## Instructions to reproduce our setting
The easiest approach is the following:

1- instrall nuScenes data and libraries
2- install mmdetection3d
3- download the models from the model zoo of mmdetection3d

At this point, if everything has been installed correctly, you should be able to run the notebook XXX (you should just need to adjust paths), and collect results. Such notebook allows collecting the data that needs to be processed by nuScenes, so it is important that it runs smoothly.

Then:
- replace the nuScenes library with the library we provide i.e., with the folder YYY
- run the notebook YYY. You should just need to adjust paths, then it should run smootly.

At this point, you should see a results folders with some files. These files includes the novel metrics discussed in our work. The files are CSV and JSON, their content is straightforward, but if you have any kind of trouble just ask us for clarification.

If you arrived here, it means you are fully able to obtain the results we presented in our work. You can further play with the notebook, for example to test different parameters and different models.

## Contacts for further information and suggestions
(missing for double blind review)

## Link to submission
(missing for double blind review)

## How to cite our work
(missing for double blind review)
