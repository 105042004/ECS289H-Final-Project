## Functionalities
Visualizations of input volume mapped with output segmentation labels

<img width="825" alt="4" src="https://user-images.githubusercontent.com/76392270/158356434-504abae0-e94a-40c1-816c-102fb9e58107.png">



Visualization of segmented organs only 

<img width="812" alt="1" src="https://user-images.githubusercontent.com/76392270/158356476-90b8baf3-c82e-48f0-8d05-7321a8e3914d.png">


Useful transfer function from itkwidget, supports slice view 

<img width="755" alt="3" src="https://user-images.githubusercontent.com/76392270/158356517-da772633-0879-4155-8bba-2c31e365c5bd.png">



## User Instuctions

Implementations are in the ```./UNETR/BCTV``` folder


### Install UNETR

1. Inside the folder, follow instructions to install dependencies of UNETR.
2. Then, download pretrained models (link provided) and put into ```./pretrained_models``` folder
3. For repository's space sake, I've uploaded 1 abdominal CT scan volume with corresponding label. Check ```./dataset``` folder

### Install Jupyter Notebook and itkwidget

```
pip install notebook 
pip install itkwidgets
```

### Run

To see results, simply run the ```./test.ipynb``` file.


## Reference
UNETR: https://github.com/Project-MONAI/research-contributions/tree/master/UNETR/BTCV

itkwidget: https://github.com/InsightSoftwareConsortium/itkwidgets

