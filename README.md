# 
`conda create --prefix=./env python=3.9`<br>
`conda install pytorch torchvision torchaudio pytorch-cuda=11.7 -c pytorch -c nvidia`<br>
`conda install -c dglteam/label/cu117 dgl`<br>
`conda install -c conda-forge nvtx`<br>

运行：`python3 node_classification.py`
