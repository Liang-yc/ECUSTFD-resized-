# ECUSTFD-resized-
# Background
------
Obesity is a medical condition in which excess body fat has accumulated to the extent that it may have a negative effect on health.  Obesity treatment requires the patients to eat healthy food and decrease the amount of daily calorie intake. For those patients, it is helpful that calories can be estimated from photos.
<br><br>
    Many methods based on computer vision have been created to estimate calories. There are three steps in calorie estimation: capturing food image(s), detecting food and calibration object, estimating calorie of each food.
<br><br>
    For those methods, especially deep learning methods, they need a corresponding image dataset to train and test. However, most of the image datasets concentrate on the food detection and just provide different categories of objects, which is not helpful in visual measurement. That's why we create our food image dataset named ECUSTFD(ECUST Food Dataset).
# Introduction
------
ECUSTFD is a free public food image dataset. Our dataset has 19 types of food as shown in the figure . The number of food images is 2978. The number of images and the number of objects for the same type are shown as follows:
![food samples](https://github.com/Liang-yc/images4readme/blob/master/food_sample.jpg)
<br><br>
    For a single food portion, we took several groups of images by using smart phones; each group of images contains a top view and a side view of this food. For each image, there is only one coin as calibration object and no more than two foods in it. If there are two food in the same image, the type of one food is different from another. We provide two datasets for researchers: one includes original images and another includes resized images. The size of each image in resized dataset is less than 1000*1000.<br> 
![coin](https://github.com/Liang-yc/images4readme/blob/master/coin%20sides.jpg)
<br><br>
    As you see, the diameter of the One Yuan Coin is 25.0mm. In ECUSTFD, only 2 kinds of plates are used when taking photos: a white plate and a red plate. If you want to use the circle plate as the calibration object, you may need the diameter of each plate.The white plate's diameter is about 20.7cm and its height is about 2.0cm; the red plate's diameter is about 18.7cm and its height is about 2.0cm.
<br><br>
![white plate](https://github.com/Liang-yc/images4readme/blob/master/white_plate.JPG)
![red plate](https://github.com/Liang-yc/images4readme/blob/master/red_plate.JPG)
<table>
    <thead>
        <tr>
            <th><strong><code>Linux CPU</code></strong></th>
            <th><strong><code>Linux GPU</code></strong></th>
            <th><strong><code>Mac OS CPU</code></strong></th>
            <th><strong><code>Windows CPU</code></strong></th>
            <th><strong><code>Android</code></strong></th>
            </tr>
            </thead><tbody>
            <tr>
            <td><a href=""><img style="max-width: 500;" alt="Build Status" src="https://github.com/Liang-yc/images4readme/blob/master/red_plate.JPG" ></a></td>
            <td><a href=""><img style="max-width: 500;" alt="Build Status" src="https://github.com/Liang-yc/images4readme/blob/master/white_plate.JPG" ></a></td>
        </tr>
    </tbody>
</table>
# Assessment
---------
The dataset with original images and no annotations is publicly available at this [BaiduYun](http://pan.baidu.com/s/1dF866Ut). The small image dataset including annotations, volume and quality information is available at this [github](https://github.com/Liang-yc/ECUSTFD-resized-) or [BaiduYun](http://pan.baidu.com/s/1o8qDnXC). 
<br><br>
    For ECUSTFD with original images, we only provide images as referred. But we provide the food's weight information in [ECUSTFD_WEIGHT](http://pan.baidu.com/s/1dF866Ut#list/path=%2Fcalorie%20estimation%2FECUSTFD_origin%2FECUSTFD_WEIGHT&parentPath=%2Fcalorie%20estimation) folder. If you are interested in character recognition, you can use those images. 
<br><br>
    For the small-size ECUSTFD, The annotations of images are saved in the folder named Annotations and images are saved in the JPEGImages folder. `density.xls` saves food's volume and quality information.
