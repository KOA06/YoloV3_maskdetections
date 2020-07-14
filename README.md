| **Title**      | COVID-19 MASK DETECTION |
| ---------- |-------------------|
| **Team**       | Khoa Tang - tangkn.0604@gmail.com  
| **Predicting** | The Goal was to detect if someone was wearing a mask or not
| **Data**       | cocodataset -  https://cocodataset.org/#download - Created my own dataset from download images from google extension and labeling tool call labelImg 
| **Features**   | Images shape(416x416x3)
| **Models**     | Yolo V3 (Darknet 53)
| **Results**    | Haven't train enough images yet to see how accurate the model is. 
| **Discussion** | I got the model to work but it wasn't as fast as what i expected. The webcam fps was very low. However, i trying using using downloaded weights and classes the accuracy was 95% of predicting objects.  
| **Future**     | In the future, i would want to try a faster model like YoloV5 and input more images for my model to be more accurate. I would also want to add a feature where it would predict a person body temperature, to see if someone walking in to a public area is sick or not. 
|**References**  | https://github.com/qqwweee/keras-yolo3

