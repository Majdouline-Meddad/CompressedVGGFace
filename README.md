# CompressedVGGFace
CompressedVGGFace is a compress model of VGGFace model that contains 8 layers.

>The compressed VGGFace model is in compressedvgg folder.

>The Databases used in this paper are in Databases folder (VidTIMIT and Extended Yale Face B databases).

>All feature vectors extracted from Inception V3, VGGFace and our CompressedVggFace models are in Feature Folder.

All the feature files are saved in binary format and can be read by using the Python Object Serialization Pickle module.
```
# Python 3:
vecteur_train = open('img1.txt', "rb")
train=pickle._Unpickler(vecteur_train)
train.encoding='latin1'
train=train.load()
```
