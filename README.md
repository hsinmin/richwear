RichWear Dataset
=================
321,698 images, year: 2017-2019, img size:500x667
============

* `classes.txt`           # 41 unique classes appeared in clothing patterns, colors, and categories.

* `photos.txt`            # List of image filenames. Note that the first 3,868 files are from the verified\
                            subset in the following order: 3,043 training, 325 validation, and 500 test images. \
                            The rest of images does not have verifed labels. These images only have noisy labels.

* `date.txt`              # Date uploaded to wear.jp (in the same order as photos.txt).

* `brands.txt`            # Clothing brands (in the same order as photos.txt).

* `gender.txt`            # Gender of users (in the same order as photos.txt).

* `hashtags.txt`          # User-created hashtags (in the same order as photos.txt).

* `label_verified.txt`    # Human-verified labels (for the first 3,868 filenames in photos.txt).

* `label_noisy.txt`       # User-provied noisy labels (in the same order as photos.txt).

Note that 'nan' denotes missing data.

Download the dataset here: http://www.im.ntu.edu.tw/~lu/data/richwear/richwear.tgz

If you are using this dataset, please consider citing our work: 
### Fu-Hsien Huang, Hsin-Min Lu, and Yao-Wen Hsu, (2021, Mar.). From Street Photos to Fashion Trends: Leveraging User-Provided Noisy Labels for Fashion Understanding, IEEE Access, Forthcoming, https://doi.org/10.1109/ACCESS.2021.3069245

                                       
