# high_resolution

## enviroment
Python >= 3.7 
PyTorch >= 1.7
torchvision==0.8.2

## Installation
```
wget https://github.com/xinntao/Real-ESRGAN/releases/download/v0.1.0/RealESRGAN_x4plus.pth -P experiments/pretrained_models
pip install basicsr
# facexlib and gfpgan are for face enhancement
pip install facexlib
pip install gfpgan
pip install -r requirements.txt
python setup.py develop
```


## Inference
```
python inference_realesrgan.py --model_path experiments/pretrained_models/RealESRGAN_x4plus.pth --input inputs --face_enhance
```
