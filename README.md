# Text_Image_Segmentation_OCR
This project aims to recognize texts in imaged documents with Tesseract OCR. Different thresholding algorithms including Otsu global thresholding and adaptive thresholding are applied. Besides, image enhancement techniques such as histogram equalization, gamma correction and spatial filters are asopted to enhance the accuracy of recognition.  

The highest accuracy achieved is around 85% at word level. This is produced by adaptive thresholding, sharpening filter and Gaussian blurring filter.  

__sample01.png__  

Before:  
<img src = "https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/sample01.png" width = 483 height = 115>  

After:  
<img src = "https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/Figures/sample01_at.png" width = 483 height = 115>  

Output:  
Parking: You may park anywhere on the campus where there are no signs prohibiting par- king. Keep in mind the carpool hours and park accordingly so you do not get blocked in the afternoon  

Under Schoo! Age Children:While we love the younger children, it can be disruptive and inappropriate to have them on campus during schoo! hours. There may be special times that they may be invited or can accompany a parent volunteer, but otherwise we ask that you adhere to our —_ policy for the benefit of the students and staff.  


__sample02.png__  

Before:  
<img src = "https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/sample02.png" width = 500 height = 700>  

After:  
<img src = "https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/Figures/sample02_filter.png" width = 450 height = 700>  

Output:  
<img src = "https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/Figures/sample02_output.png" width = 500 height = 200>   

The complete codes and output can be found in ["Text_segmentation.ipynb"](https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/blob/main/Text_Segmentation.ipynb), and the generated images are in ["/Figures"](https://github.com/StephanieMussi/Text_Image_Segmentation_OCR/tree/main/Figures) folder.  

