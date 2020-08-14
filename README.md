# CBDB-BIO-to-xml
This file is a python package that converts BIO tagged files(in txt format) into xml files. The output files will be uploaded to the website Markus(https://dh.chinese-empires.eu/markus/beta/index.html) for further investigation conducted by experts.

STEP1:

The tagged txt files should be saved in a document folder named "bio_input". Xml files output will be stored in folder 'markus_output'. At the same time, the folders shall be put under the same directory with bio2markus.py

STEP2:

You could run the main function bio2markus_main.py or simply import this module. In both ways, this python package will read the txt files and output xml files.

At the start of the main function, bio2markus.self_check() will be called to perform a self-checking. If you have not set up the 'bio_input' and 'markus_output' folder,
an error will be thrown. Thus, please make sure that both folders have been set up.

At the same time, self_check() function will DELETE ALL FILES in the 'markus_output' folder, so please make sure you have back up all files in this folder if you would not like to delete them.

STEP3:

The output files are of .html format. All output files generated by this package will be saved in a document folder named "markus.output" which is also placed in the same directory.

PS.

1.Please make sure that the txt files you would like to parse are of .txt format

2.My Python version is 3.7.4

3.Samples of input txt and output xml are attached.


#Chinese Version

第一步：

这一Python模块接收的BIO标注文件必须是txt格式。与此同时，这些txt格式文件应当被保存在文件夹"bio_input"中。而所有的输出文件则被保存在markus_output文件夹中。这些文件夹需要与bio2markus.py位于同一目录下

第二步：

你可以直接用bio2markus_main.py执行main函数，也可以用import命令将bio2markus.py作为模块导入

在main函数的第一步，函数self_check()将被执行以进行开机自检。如果同目录下的文件中没有包含'bio_output'与'markus_output'文件夹，那么程序将会抛出异常。因此请您务必确保在程序执行前这两个文件夹已经创建完毕。

与此同时，self_check()函数将删除markus_output文件夹中的所有文件，以便加入新的数据。因此如果您有相关的需求，请在执行程序前先备份该文件夹。

第三步：

程序输出的文件格式为 .html。所有输出的文件都被存放于相同目录内名为”markus“的文件夹内。

PS.

1.请确保所有的输入文件为BIO格式

2.我的Python版本为3.7.4

3.一份输入的txt文件和输出的xml文件样板已经附在该仓库内
