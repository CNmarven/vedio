# vedio
vedio
下图是github在创建仓库后给的提示；按它一步步操作下去就可以了。


下图是在git命令行下操作：


我不是Linux高手，很多linux命令都不会。只会一些简单的操作；

cd 在linux下是进入某一文件夹的操作。当你看到CD的时候，我是在找我的目录，即要上传代码的目录。所以一直找到W_IMsg这个目录下时，算是找到了自己要上传的代码；

然后touch README.md。这命令是添加一个文件。文件名叫：README.md;

然后: git  init ：这时初始化一个仓库。 成功后会有下面的提示：Initialized empty Git repository in d:.......

然后：git add README.md 。这里是添加README这个文件；

然后 git add .  ：要注意后面的点。这里是添加整个目录，也可以像git add README.md一样。添加单个文件；



然后 git commit ......  
然后等这些文件全部提交到本地仓库后，再输入你要提交的仓库地址，如我的：https://github.com/kazeik/W_IMsg.git




然后： git push -u origin master 这里就开始准备提交到网络上了，
