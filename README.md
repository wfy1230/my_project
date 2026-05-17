步骤1：

按照 requirements.txt 的要求安装好环境，并进入到当前项目文件夹下

步骤2：

将数据集下载到dataset里面，并解压，设置好对应数据集里面的Visdrone2019.yaml文件中的path路径，你的数据集放在哪，路径就是哪里。![image-20260517220115820](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517220115820.png)

然后将对应数据集中的Visdrone2019.yaml文件路径复制到train.py的data中,将mymodel中的模型路径也复制到这里，如下所示：

<img src="C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517220525940.png" alt="image-20260517220525940" style="zoom:80%;" />

然后就可以在在命令行中输入python train.py进行训练了，其中模型要训练哪个就把对应的文件路径复制到train.py中：

![image-20260517221046061](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221046061.png)

val.py是验证程序，操作和train.py是一样的，其中model_path就是训练好的best.pt路径![image-20260517221223578](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221223578.png)

detect.py是测试程序，将对应的训练好的模型路径复制过来，同时数据集的路径复制过来，在命令行中运行即可：

![image-20260517221508553](C:\Users\admin\AppData\Roaming\Typora\typora-user-images\image-20260517221508553.png)

