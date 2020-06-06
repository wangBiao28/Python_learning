### Python 变量

* python 变量不需要声明
  * 整数 `int_val = 10`
  * 长整数 `long_val = 1000L`
  * 浮点数 `float_val = 1.0`
* list,tuple,dict
* list类似于C++或Java语言的数组，一个有序可变集合的容器。支持内置的基础数据结构甚至是列表，列表是可以嵌套的。不同的数据结构也可以放在同一个列表中，没有统一类型的限制。

```
list_a = ["str", 1, ["a", "b", "c"], 4]
list_b = ["hello"]
print list_a[0]
print list_a[1:3]
print list_a[1:]
print list_b * 2
print list_a + list_b
```

* tuple可视为不可变的列表

```
tuple_a = ("str", 1, ["a", "b", "c"], 4)
tuple_b = ("hello",)
print tuple_a[0]
print tuple_a[1:3]
print tuple_a[1:]
print tuple_b * 2
print tuple_a + tuple_b
```

* dict类似C++语言中的map

```
dict_a = {
    "name": "Alan",
    "age": 24,
    1: "level_1"
}
print dict_a["name"]
print dict_a["age"]
print dict_a[1]
print "name" in dict_a
print "xxx" in dict_a
print dict_a.keys()
print dict_a.values()
print dict_a.items()
```

hello world













