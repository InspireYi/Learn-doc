# join语法
下面所有例子，默认A是左表，B是右表

![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/all%20join.jpg 'all join')

## inner join 语法
相当于求A与B的交集

```
SELECT 
    *
FROM A
INNER JOIN B ON A.RELATEKEY = B.RELATEKEY 
```

![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/inner%20join.jpg 'inner join')


## left join 语法
left join 是left outer join的缩写，他们代表的意义一样
相当于A表的数据在left join后的结果集中必然存在

```
SELECT 
    *
FROM A
LEFT JOIN B ON A.RELATEKEY = B.RELATEKEY 
```

![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/left%20join.png 'left join')

带where子句过滤
```
SELECT 
    *
FROM A
LEFT JOIN B ON A.RELATEKEY = B.RELATEKEY 
WHERE B.RELATEKEY IS NULL
```
![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/left%20join%20where%20is%20null.png 'left join')