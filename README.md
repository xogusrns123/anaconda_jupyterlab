# anaconda_jupyterlab
## Anaconda에서 jupyter lab 개발환경 설치 및 커스텀 방법

### 1. Install Anaconda
#### Installing on Linux
https://docs.anaconda.com/free/anaconda/install/linux/
위 링크에 들어가서 확인
### 2. Create environment
```
conda create -name my_env
```
```
conda activate my_env
```

만약 conda command not found error
bash shell로 실행하기
'''
bash
'''

### 3. Install Jupyter lab
```
conda install -c conda-forge jupyterlab
```
```
jupyter lab
```
만약 ssh연결로 사용하고 있으면
```
jupyter lab --ip=0.0.0.0
```
