# microplastic-classification
## Classification model 

This github is contain model after train of paper  `Characterization and Classification of Microplastic in Wastewater Treatment Plants using Convolutional Neural Networks and Transfer-Learning Approach` . 
<br />
<br />
Before using model must be install library.
```
!pip install timm
!pip install lightning
```
Using model for inferance 
```
model = torch.load('efficientnet_microplastic.py')
```

You can acess and download our model at link below. 
```
https://drive.google.com/drive/folders/1g3mSrKGwTnhs2qMXj_oH8mMF9X72iYFT
```
You can also see our example code for inferance model at Example.ipynb in this github. 

Note: 
For using in colab you can download model by using command !gdown

```
#This thie command for download efficientnet_microplastics.pt
!gdown --id 1DaAVWmf2eT9wyOpKWaJoJwf-86plA7Uq
```

```
#This thie command for download resnetv2_50_microplastics.pt
!gdown --id 1Ny4V0wPQpfGGwY1DS49CEra6gcbE7WYU
```

```
#This command for download resnetv2_101_microplastics.pt
!gdown --id 1ZrzUTp5I8f4p-95h2QRFN-NjWqguyfpI
```

```
#This command for download mobilenetv3_microplastics.pt
!gdown --id 1joTlwgAFvy4WxwOI3MKeuAglT6XS0H5e
```

```
#This command for download inception_v3_microplastics.pt
!gdown --id 1iOJXl9EWHp6WaklErG_USWubpScqWZtU
```
