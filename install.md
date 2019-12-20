Create conda virtual env:

```
conda create -n pointcnn python=3.6
```

Activate virtual env:

```
conda activate pointcnn
```

Install other dependencies:

```
conda install -c anaconda requests
conda install -c conda-forge tqdm
conda install -c conda-forge transforms3d
conda install -c conda-forge plyfile
conda install -c conda-forge matplotlib
conda install -c anaconda h5py
conda install -c anaconda tensorflow-gpu=1.13
```
