Crack dataset can be found here: https://www.kaggle.com/datasets/lakshaymiddha/crack-segmentation-dataset/data
(Download images along with black & white masks)

Input are 448 * 448 RGB images, with same size masks of black and white where white area indicates cracks

unet_bwmask: training unet models

resnet_bwmask: traning resnet50 with deeplabhead

vgg16_bwmask: training vgg16 with image size 224*224

vgg16_bwmask_origin_img_size: traning vgg16 with original image size from above dataset: 448 * 448

The prediction result is a black white image where the white area indicates cracks
