# cp
    语法：
        cp [-adfilprsu] 来源文件 目标文件
        cp [option] 来源文件1 来源文件2 来源文件3 ... 目标文件夹
    参数：
        -a 相当于-pdr
        -i 若目标已存在，在覆盖时先询问是否覆盖
        -p 连同文件的属性一并复制过去
        -r 递归复制文件、文件夹
    速记：copy
    作用：拷贝文件或文件夹至目标
    如：
        cp ~/.bashrc tmp/bashrc //将home目录下的.bashrc复制到/tmp下，并命名为bashrc
        cp -i ~/.bashrc tmp/bashrc //将home目录下的.bashrc复制到/tmp下，并命名为bashrc，覆盖前先询问