# Inverted Attention with Faster R-CNN

### This is an un-officially implementation of the WACV'2020 paper ['Improving Object Detection with Inverted Attention'](https://openaccess.thecvf.com/content_WACV_2020/papers/Huang_Improving_Object_Detection_with_Inverted_Attention_WACV_2020_paper.pdf).


### Step 1: Installation
Create a conda environment and install dependencies:
```bash
conda create -y -n torch113 python=3.8
conda activate torch113
pip install torch==1.13.0+cu117 torchvision==0.14.0+cu117 torchaudio==0.13.0 --extra-index-url https://download.pytorch.org/whl/cu117
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