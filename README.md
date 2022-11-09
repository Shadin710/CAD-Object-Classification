# CAD Object Classification

A Deep-Learning model that can help us to classify 3D object using PoinNet Architecture

## Dataset

The dataset was taken from [Princeton Modelnet](https://modelnet.cs.princeton.edu/).

[Modelnet10 Download ](http://3dvision.princeton.edu/projects/2014/3DShapeNets/ModelNet10.zip) 
![alt text](https://github.com/Shadin710/CAD-Object-Classification/blob/main/Images/A-sample-model-from-each-category-of-the-ModelNet10-dataset.png?raw=True)

## Language & OS
1. **Python 3.10.4**
2. **Windows 10 home**

## Modules
1. [Numpy](https://numpy.org/)
2. [Matplotlib](https://matplotlib.org/)
3. [Tensorflow](https://www.tensorflow.org/resources/learn-ml?gclid=CjwKCAiAx8KQBhAGEiwAD3EiP0Wav3hoBTDA2BAbRNg8ywxS4RaavvWUXxrV0dL72h3iwK0Zx2B4EhoCbK4QAvD_BwE)
4. [Pickle](https://www.synopsys.com/blogs/software-security/python-pickling/#:~:text=Pickle%20in%20Python%20is%20primarily,transport%20data%20over%20the%20network.)
4. [Glob](https://docs.python.org/3/library/glob.html)
5. [trimesh](https://trimsh.org/trimesh.html)

## Installation of modules
Please create a virtual environment then install the modules
To create virtual environment open command tab in that folder and run the command
``` bash
py -3.X venv -m name_of_env
```
X is refering a python version
To activate the virtual environment

```bash
.\name_of_env\Scripts\activate
```


To install all these modules copy the requirement.txt file and run the below command
```bash
pip install -r requirment.txt
```
## CAD to Point-Cloud
To Predict 3D object classification we need to transform the 3D Object to a **Point-Cloud**
![alt text](https://github.com/Shadin710/CAD-Object-Classification/blob/main/Images/point_cloud.png?raw=True)
Then we will be able to run [**PointNet**](https://github.com/charlesq34/pointnet) Architecture.
## Accuracy & Loss 
Epoch Size: 20\
Batch size: 32\
Learning rate: 0.001\
Train Accuracy: 91.54%\
Validation Accuracy: 88.54%\
Accuracy: 94.03%

<!-- ![alt text](https://github.com/Shadin710/Brain-Tumor-Prediction/blob/main/images/accuracy_loss.png?raw=true) -->



## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)