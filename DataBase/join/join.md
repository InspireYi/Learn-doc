# join语法
下面所有例子，默认A是左表，B是右表

![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/all%20join.jpg 'all join')

## inner join 语法
相当于求A与B的交集

![MyImage](https://github.com/InspireYi/Learn-doc/blob/master/DataBase/join/img/inner%20join.jpg 'inner join')
```
SELECT 
    *
FROM A
INNER JOIN B ON A.RELATEKEY = B.RELATEKEY 
```

## left join 语法
left join 是left outer join的缩写，他们代表的意义一样
相当于A表的数据在left join后必然会存在
根据where 条件进行过滤

