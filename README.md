# Football Player Segmentation and Classification

In this project, we used a deep leaning based sematic segmentation algorithm (UNet) to detect the players at a pixel level. Also, we provided additional information about the players role, team and football field side in each image, based on traditional computer vision techniques. Finally, we used a pretrained deep learning for human pose estimation called MoveNet to show a skeletal key-point data on the players on each frame, which could be used in future work for further analysis.
The dataset we used provided 512 images from a football match and a json file contains annotations with pixel-level binary masks that indicate the player's location and segmentation boundaries.

## METHODOLOGY

We divided the project into the following sub-tasks:
1. Multiclass Mask Generation.
2. Training A Multiclass Unet Algorithm.
3. Player Role and Team Classification.
4. Ball Possession Estimation.
5. Player Pose Estimation.

   
