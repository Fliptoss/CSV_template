#**How to import dataseet from Kaggle**
```
from google.colab import files
files.upload()
```
You will be asked to *Choose File* from your folders. You need to download the Kaggle API key and upload there. 

##Use Command for creating directory
```
!mkdir -p ~/.kaggle
!cp kaggle.json ~/.kaggle/
!chmod 600 ~/.kaggle/kaggle.json
```

##Link the dataset from kaggle 
```
!kaggle dataset download -d [your_dataset_path]
```

**Note: I am just making this for myself so that I do not forget which I tend to always do :")
