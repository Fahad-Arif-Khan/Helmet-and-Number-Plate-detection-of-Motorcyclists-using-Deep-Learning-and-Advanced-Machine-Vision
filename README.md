# Helmet-and-Number-Plate-detection-using-Image-Processing-Deep-Learning
This project detects motorcyclists with and without helmet and their corresponding number plate. Image processing techniques using computer vision library was used. Different darknet models yolov3-tiny, Yolov3, Yolov4 were modified and trained manually to detect the respective classes.
The dataset of images was collected online from different sources as well as manually captured images. Then it was pre-processed to a fixed resolution using keras. Data augmentation was used. Then different image processing techniques like Averaging filter,Bilateral filter, Gaussian filter, Mrdian filter, Block matching and 3D filter (BM3D) and fastNlMeans Denoising were used for image enhancement using cv2 (computer vision library).
Total number of images were 3000 (2200 in training, 400 in validation and 400 in testing).
Mean Average Precision metric (mAP) for yolov3 yield 98.26%, yolov3-tiny yield 93.92% and yolov4 yield 98.26% in training.
Test images after processing:
![pred11](https://user-images.githubusercontent.com/85169246/123384700-5876ae80-d5b2-11eb-9445-9d50c4b716e9.jpg)
