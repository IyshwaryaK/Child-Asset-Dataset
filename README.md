The dataset contains surveillance footage recorded with te Hikvision DS-2CD3T56G2-ISU/SL camera and the Dahua DH-IPC-HFW2531S-S-S2 camera.
This dataset is the first to encompass a broad spectrum of collections of surveillance footage with including both children and adults. 
It addresses real-time environmental challenges. It includes images with various poses like standing upright, sitting, and bending; partial occlusions; 
different ground levels (flat and over a platform); and subjects across multiple motion conditions like walking, bending, and running. 
Also, the images are taken at various angles, depicting the subjects in different camera views.
The in-house dataset contains the statistical measurements of the camera setting, namely, the tilt angle (θ), the focal length (f), the camera height (h_c), 
the ground truth height (h_gt) of the subject and the object distance (d). Thirty-five volunteers, selected to represent a diverse age group, were included in the study. 
This group comprised individuals ranging from 5 to 35 years old, with a subset of participants aged 5 to 13 representing children (17 participants),
and the remaining participants aged 13 to 35 representing adults (18 participants). The average distribution of children's height is between 85cm and 160 cm,
whereas adults are between 160cm and 180 cm. Among the 35 participants, there were 15 male and 20 female individuals, elucidating the gender distribution within the study. 
The CCTV footage is available in a range of resolutions, with the highest resolution being 2592x1944 and the lowest resolution at 1280 x 1024, all in PNG format. 
The resolutions of the web-crawled data vary from 638 x 358 to 609 x 336. Manual annotations for four object classes were carried out using Roboflow. 
The children in the images were categorized into two groups, "Girl" and "Boy," based on their gender. 
The annotations were meticulously applied, with adults labelled as "Adult" and images depicting an adult carrying a child labelled as "Adult carrying a child."
An additional 250 background images were incorporated, making up approximately 5% of the training data. Data augmentation techniques, leveraging Albumentation transforms, 
were also employed on the training set. This strategic approach aimed to reduce false positive rates and improve the model's efficiency. Before beginning the study, 
participants were given a thorough description of the study methods. Researchers took great care to obtain informed permission from all individuals.
