# anaconda_jupyterlab
## Anaconda에서 jupyter lab 개발환경 설치 및 커스텀 방법

### 1. Install Anaconda
```
wget https://mm.kaist.ac.kr/share/Anaconda3-2021.11-Linux-x86_64.sh
```
```
bash Anaconda3-2021.11-Linux-x86_64.sh
```
### 2. Create environment
```
conda create -name my_env
```
```
conda activate my_env
```

### 3. Install Jupyter lab
```
conda install -c conda-forge jupyterlab
```
```
jupyter lab
```
