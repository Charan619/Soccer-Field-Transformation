# Football - Field of Play Detection and Mapping

Soccer, also known as football, stands as the most popular sport worldwide, with millions of players spanning more than 200 countries and commanding the largest global television audience. This immense popularity, combined with the rapid technological advancements in recent years, has catalyzed the development of numerous computer vision applications aimed at automating the analysis of soccer matches. These applications hold value not only for the audience but also for referees, coaches, analysts, and players, offering insights that were once difficult to obtain manually.

This project explores the methodologies and challenges involved in achieving accurate football field mapping, focusing on the computational techniques that enable robust perspective-to-top-down transformations. By addressing these challenges, this work contributes to the broader effort of integrating advanced computer vision solutions into soccer, ultimately revolutionizing how the sport is analyzed, experienced, and understood.

## Folder structure
    .
    ├── ...
    ├── player-detection                              # Contains code for player detection
    │   ├── Player_detection_YOLO_trained.ipynb       # Player detection using trained YOLO
    │   └── Player_detection_YOLO.ipynb               # Player detection using untrained YOLO
    └── pitch-transformation
        ├── Homography_calculation_resnet.ipynb       # Pitch tranformation using Resnet-18
        ├── HomographyTransform_note.ipynb            # Notebook to modify ground truth homography matrices
        └── Homography_calculation_yolo.ipynb         # Pitch tranformation using Yolo


## Model weights
The model weights along with segmented images, modified ground truth as a JSON file and an example of group_coordinates.txt are present if the following google drive : [CV_finalProj](https://drive.google.com/drive/folders/11NgF9xnMxJK8Qa00Q5wpijpiYfgOvlRq?usp=sharing).
-   In the folder the weights for Homography_calculation_resnet is present in the folder out
-   weight for Homography_calculation_yolo.ipynb is last.pt
-   weight for Player_detection_YOLO.ipynb is best.pt