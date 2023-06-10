# robocup2023-image-captioning
Image Captioning and Person Describtion for EIC RoboCup@Home 2023.
Prior to using image captioning, BLIP need to be cloned and installed

## Install
    [Clone and cd to this repo]
    conda create -n image-captioning python=3.9.16
    conda activate image-captioning
    pip install -r requirements.txt

    [Cloning BLIP]
    git clone https://github.com/salesforce/BLIP.git
    cd BLIP
    pip install -r requirements.txt
    cd ..

Get age and gender caffemodel from https://drive.google.com/file/d/1RcEI4lk6FesPCBwHi5xAY_svZ8It7XtF/view?usp=sharing

Download and extract age_caffe.caffemodel and gender_caffe.caffemodel to age_gender_recog folder

## Run
### Server
    conda activate image-captioning
    python3 main.py
### Live Client
    python3 client.py
