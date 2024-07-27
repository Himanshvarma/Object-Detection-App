commands to install Ultralytics

cd {PATH_TO_BACKEND_DIRECTORY}
git clone https://github.com/ultralytics/ultralytics
cd ultralytics
git reset --hard 2071776a3672eb835d7c56cfff22114707765ac
pip install ultralytics==8.0.196
pip install -e .
wget https://gist.githubusercontent.com/Y-T-G/8f4fc0b78a0a559a06fe84ae4f359e6e/raw/17b1407fefeac86d089c4cf14f174c8bb44948af/add_head.patch
git apply add_head.patch
