# mv
    语法：
        mv [-fiu] source destination
        mv [options] source1 source2 source3 ... destination
    参数：
        -f 强制，如果目标文件已存在，不会询问而直接覆盖
        -i 若目标文件已存在时，会询问是否覆盖
        -u 若目标文件已存在，且source比较新时，才会覆盖
    速记：move
    作用：移动文件或目录至目标，若来源为多个，则目标必须是目录
    示例：
        mv mytest1 mytest2 //将mytest1移至mytest2
