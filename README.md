
Step 1:
Install the environment according to requirements.txt and enter the current project folder

Step 2:
Download the data set into the dataset, unzip it, and set the path in the Visdrone2019.yaml file corresponding to the data set. The path will be where your data set is placed.![image-20260517220115820](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517220115820.png)

Step 3:
Then copy the Visdrone2019.yaml file path in the corresponding data set to the data of train.py, and copy the model path in mymodel here as well, as shown below:
<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517220525940.png" alt="image-20260517220525940" style="zoom:80%;" />

Step 4:
Then you can enter python train.py on the command line for training. If the model you want to train, copy the corresponding file path to train.py:
![image-20260517221046061](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221046061.png)

Step 5:
val.py is the verification program, the operation is the same as train.py, where model_path is the trained best.pt path![image-20260517221223578](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221223578.png)

Step 6:
detect.py is a test program. Copy the corresponding trained model path and the data set path, and run it on the command line:
![image-20260517221508553](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221508553.png)

