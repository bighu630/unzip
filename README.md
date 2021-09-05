### unzip

解决在linux上解压来自windows的zip压缩包出现乱码的情况

### 使用方法：

下载压缩包后得到一个名为*nz*的文件

```
#在这个文件夹里
sudo mv nz /bin  ###随便那一个环境目录也可以(这样可以直接在终端中使用nz)
```

使用：

```
nz zfile1.zip zfile2.zip zfile3.zip .....
```

### 依赖问题：

```
pip install argparse
pip install zipfile
pip install cchardet
pip install shutil
```

