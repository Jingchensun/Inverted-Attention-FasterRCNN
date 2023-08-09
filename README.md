# Inverted Attention with Faster R-CNN

## This is an un-officially implementation of the paper 
[WACV'2020] Improving Object Detection with Inverted Attention
* https://openaccess.thecvf.com/content_WACV_2020/papers/Huang_Improving_Object_Detection_with_Inverted_Attention_WACV_2020_paper.pdf


### Step 1: Installation
Create a conda environment and install dependencies:
```bash
conda create -y -n torch171 python=3.8
conda activate torch171

pip3 install torch==1.8.2 torchvision==0.9.2 torchaudio==0.8.2 --extra-index-url https://download.pytorch.org/whl/lts/1.8/cu111
pip install pycocotools
pip install -r requirements.txt

```

### Step 2: Download Dataset
We use Pascal VOC2012 train/val dataset
```bash

wget http://host.robots.ox.ac.uk/pascal/VOC/voc2012/VOCtrainval_11-May-2012.tar
```


### Step 3: Train the model
Download the pretrained prompt from the [link](https://drive.google.com/file/d/1bfCXO9iE3ys3__xnOrC6bHAVXVcFXkyW/view?usp=share_link)
And decompress it under the folder `prompt_adapter/prompt_tensor_init`. 
```bash
tar -xvf prompt_tensor_init.tar
```

### Step 4: Evualate the model
Download the pretrained prompt from the [link](https://drive.google.com/file/d/1bfCXO9iE3ys3__xnOrC6bHAVXVcFXkyW/view?usp=share_link)
And decompress it under the folder `prompt_adapter/prompt_tensor_init`. 
```bash
tar -xvf prompt_tensor_init.tar
```

### Step 5: Visulize the feature map
Download the pretrained prompt from the [link](https://drive.google.com/file/d/1bfCXO9iE3ys3__xnOrC6bHAVXVcFXkyW/view?usp=share_link)
And decompress it under the folder `prompt_adapter/prompt_tensor_init`. 
```bash
tar -xvf prompt_tensor_init.tar
```