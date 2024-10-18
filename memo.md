## install

| Name | Version |
| --- | --- |
| Python | 3.8 |
```bash
sudo pip install torch==1.8.1+cu111 -f https://download.pytorch.org/whl/torch_stable.html &&\
sudo pip install -r requirements.txt
```
```bash
cd ops &&\
python setup.py develop
```

```bash
export CUDA_HOME=/usr/local/cuda &&\
export PATH=$CUDA_HOME/bin:$PATH
```

```bash
export TORCH_CUDA_ARCH_LIST="8.6"
```