# Final_Ruohao_Li

The framework of using YOLOv9 and Cloud to potentially predict storm damages.
![image](https://github.com/ruohaoli/Final_Ruohao_Li/assets/151061808/d7d256fe-4007-4f34-bcd2-f0bdb63aa5c1)

Here is a cloud-based YOLO framework for storm damage prediction. All datasets are stored in Cloud Storage, model training and testing process is in Cloud AI Platform.

The selected area is "San Juan" from Poteu Rico, and satellite images are split into patches. Then they were annotated in OpenCV, formatted, and stored in Cloud Bucket.
<img width="229" alt="image" src="https://github.com/ruohaoli/Final_Ruohao_Li/assets/151061808/1cffaeb1-93b3-44f4-9b55-ba4222350372">

The model could read the data with "cloud client". And the output is also stored in a new bucket.

All buckets has an index table to query data with bigquery.
