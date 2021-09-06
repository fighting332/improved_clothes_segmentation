This project for clothes segmentation was built by Xianyao Chen, 
when serving for the e-commerce company (MiX:D, 믹스디 주식화사) in South Korea.
The project was built based on the opensource project: 
https://github.com/fighting332/cloths_segmentation.
Some advanced features were added for the company use.
The project was successfully tested on Amazon SageMaker platform.

[1] Target: clothes segmentation

[2] Background: Remove background of clothes image and remove the hanger.

[3] Techniques:

A. Deep learning framework: PyTorch

B. Data-preprocessing: Augment data and normalize data.

C. U2-net model: Remove the background of clothes image.

D. U-net model: Remove the hanger.

E. cv2.GaussianBlur: Smooth the clothes border and remove the jagged edge.

[4]. Result: Input a original clothes image, output a clothes image just with clothes.
