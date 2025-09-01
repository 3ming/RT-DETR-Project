配置环境
conda creatr -n rtdetr python=3.9
pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cu126  （这个新版本，也可以使用旧版本的）
pip install -r requirements.txt
pip install einops
pip install efficientnet_pytorch
pip install pywavelets
pip install timm
pip install dill


使用
python train.py

