# Inverted Attention with Faster R-CNN

### This is an un-officially implementation of the WACV'2020 paper ['Improving Object Detection with Inverted Attention'](https://openaccess.thecvf.com/content_WACV_2020/papers/Huang_Improving_Object_Detection_with_Inverted_Attention_WACV_2020_paper.pdf).


### Step 1: Installation
Create a conda environment and install dependencies:
```bash
conda create -y -n torch200 python=3.8
conda activate torch200
pip install torch==2.0.0+cu118 torchvision==0.15.1+cu118 torchaudio==2.0.1 --index-url https://download.pytorch.org/whl/cu118
pip install pycocotools
pip install -r requirements.txt

```

### Step 2: Download Dataset
We use Pascal VOC2012 train/val dataset
```bash
wget http://host.robots.ox.ac.uk/pascal/VOC/voc2012/VOCtrainval_11-May-2012.tar
```


### Step 3: Train the model
```bash
python train_res50_fpn.py
```

### Step 4: Evualate the model
And decompress it under the folder `prompt_adapter/prompt_tensor_init`. 
```bash
tar -xvf prompt_tensor_init.tar
```

### Step 5: Visulize the feature map
```bash
tar -xvf prompt_tensor_init.tar
```