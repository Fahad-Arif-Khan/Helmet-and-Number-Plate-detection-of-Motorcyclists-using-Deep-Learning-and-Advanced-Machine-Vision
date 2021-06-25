# Helmet-and-Number-Plate-detection-using-Image-Processing-Deep-Learning
1) This project detects motorcyclists with and without helmet and their corresponding number plate. Image processing techniques using computer vision library was used. Different darknet models yolov3-tiny, Yolov3, Yolov4 were modified and trained manually to detect the respective classes.
2) The dataset of images was collected online from different sources as well as manually captured images. Then it was pre-processed to a fixed resolution using keras. Data augmentation was used. Then different image processing techniques like Averaging filter,Bilateral filter, Gaussian filter, Mrdian filter, Block matching and 3D filter (BM3D) and fastNlMeans Denoising were used for image enhancement using cv2 (computer vision library).
3) Total number of images were 3000 (2200 in training, 400 in validation and 400 in testing).
4) Mean Average Precision metric (mAP) for yolov3 yield 98.26%, yolov3-tiny yield 93.92% and yolov4 yield 98.26% in training.

# Test images after processing:

![pred11](https://user-images.githubusercontent.com/85169246/123384700-5876ae80-d5b2-11eb-9445-9d50c4b716e9.jpg)
![pred12](https://user-images.githubusercontent.com/85169246/123384928-9d024a00-d5b2-11eb-8ed6-bc103ea4bbf5.jpg)
![pred20](https://user-images.githubusercontent.com/85169246/123384938-a25f9480-d5b2-11eb-89f4-8b24aeac4dd6.jpg)
![pred39](https://user-images.githubusercontent.com/85169246/123384950-a68bb200-d5b2-11eb-8c6b-9a0bb9bcf146.jpg)
![pred46](https://user-images.githubusercontent.com/85169246/123384961-aa1f3900-d5b2-11eb-9e81-2c51be9abc12.jpg)
![pred86](https://user-images.githubusercontent.com/85169246/123384993-b1dedd80-d5b2-11eb-973f-1bbc6b85f7a4.jpg)
![pred122](https://user-images.githubusercontent.com/85169246/123385003-b4413780-d5b2-11eb-8fff-578782d7f17d.jpg)
![pred270](https://user-images.githubusercontent.com/85169246/123385242-f66a7900-d5b2-11eb-85cb-eae390c73dbf.jpg)
# If anyone needs the raw datset, processed dataset, code for image processing with different filters, code for the training, testing of model, weights, for more information you can mail me here (fahad.khan2459@gmail.com)
