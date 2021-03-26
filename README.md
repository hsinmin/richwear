RichWear Dataset
=================
321,698 images, year: 2017-2019, img size:500x667

classes.txt           # 41 unique classes appeared in clothing patterns, colors, and categories

photos.txt            # List of image filenames
                      # Note that the first 3,868 files are from the verified
                      # subset in the following order: 3,043 training, 325 validation, and 500 test
                      # images. The rest of images does not have verifed
                      # labels. These images only have noisy labels.

date.txt              # Date uploaded to wear.jp (in the same order as photos.txt)

brands.txt            # Clothing brands (in the same order as photos.txt)

gender.txt            # Gender of users (in the same order as photos.txt)

hashtags.txt          # User-created hashtags (in the same order as photos.txt)

label_verified.txt    # Human-verified labels (for the first 3,868 filenames in photos.txt)

label_noisy.txt       # User-provied noisy labels (in the same order as photos.txt)

Note that 'nan' represents missing data.



RichWear Dataset + Revised Fashion550k Dataset  
=================
# Data will be released upon the acceptance of our paper.

### RichWear Dataset
321,698 images; **year**: 2017-2019    **img size**:500x667

* `labels.txt`            #41 classes (clothing colors & categories & patterns)
* `photos.txt`           #image filenames
* `date.txt`              #upload date (in the same order as image filenames)
* `brands.txt`           #clothing brands (in the same order as image filenames)
* `gender.txt`           #gender of users (in the same order as image filenames)
* `hashtags.txt`         #user-created hashtags (in the same order as image filenames)
* `verified_color_category.npy`   #verified labels of clothing color & category #training set 3,043 & valid set 325 & test set 500   
* `verified_pattern.npy`   #clothing pattern annotation #training set 3,043 & valid set 325 & test set 500
* `noisy_labels`      #noisy labels of clothing color & category (in the same order as image filenames)
* `trainidx.npy`      #training set index in the photos.txt
* `valididx.npy`      #validation set index in the photos.txt
* `testidx.npy`       #test set index in the photos.txt
* `noisyidx.npy`      #noisy set index in the photos.txt

### Revised Fashion550k Dataset
4,307 images  #labels of 2,657 images were manually corrected #img size:256x384

* `photos_fashion550k.txt`           #image filenames
* `verified_color_category_fashion550k.npy`   #verified labels of clothing color & category (in the same order as image filenames)  
* `verified_pattern_fashion550k.npy`   #clothing pattern annotation (in the same order as image filenames)
* `noisy_labels_fashion550k.npy`      #noisy labels of clothing color & category (in the same order as image filenames)


                                       
