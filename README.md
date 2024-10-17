# OBJECT DETECTION FINETUNING TUTORIAL
This is another PyTorch tutorial to frame pedestrinas in a box

## Data
### Let’s write a dataset for the PennFudan dataset. First, let’s download the dataset and extract the zip file:

    wget https://www.cis.upenn.edu/~jshi/ped_html/PennFudanPed.zip -P data
    
    cd data && unzip PennFudanPed.zip

### We have the following folder structure:

PennFudanPed/

  PedMasks/

  FudanPed00001_mask.png
    
  FudanPed00002_mask.png
    
  FudanPed00003_mask.png
   
  FudanPed00004_mask.png
    
  ...
  
  PNGImages/
  
  FudanPed00001.png
    
  FudanPed00002.png
    
  FudanPed00003.png
  
  FudanPed00004.png
