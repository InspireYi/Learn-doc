# nl
    语法：nl [-bnw] 文件
    参数：
        -b a：无论是否空行，都列出行号（类似cat -n）
        -b t：空行不列出行号
        -n ln: 行号居左显示
        -n rn：行号居右显示
        -n rz：行号居右显示且加0
        -w [n]：设置行号位数，n为数字
    速记：number of lines
    作用：将输出的文件内容加上行号
    示例：
        nl -b a -n rz -w 3 test //显示test内容并显示居右所有行号3位