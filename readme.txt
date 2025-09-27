#https://hub.ultralytics.com/models/H7IMEul2mft9vBDrDBlY?tab=deploy
#https://app.roboflow.com/learning-mdxqc/camera_custom_dataset-evhhj/2/export

--Sistemas operativos Linux
sudo apt-get install libgtk2.0-dev pkg-config libgtk-3-dev

conda create -n yolo python=3.9
conda activate yolo
conda install jupyter
pip install "numpy<2.0"
pip install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu121
pip install opencv-python
pip install ultralytics
pip install matplotlib pillow
pip install roboflow