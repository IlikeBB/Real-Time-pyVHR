<h3>Build Virtual Environment(Using Conda) </h3>

```text
conda create --name vhrfix python=3.6

conda activate vhrfix
```


<h3>Environment configuration</h3>

```text
pip install jupyter
pip install tensorflow==2.2.0
pip install tensorflow-estimator==2.2.0

#If device has a gpu that supports CUDA.
pip install tensorflow-gpu==2.2.0
#---------------------------------------

pip install matplotlib==3.2.0
pip install opencv-python
pip install scipy==1.4.1 
pip install plotly==4.8.2
pip install tqdm
pip install mtcnn==0.1.0
```

<h3>Reference</h3>
<a href='https://github.com/phuselab/pyVHR'> pyVHR</a>
