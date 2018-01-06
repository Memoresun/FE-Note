### Array 对象
1. 构造函数  
	Array是JS的内置对象，同时页是一个构造函数，可以用它生成新的数组。  

	直接使用数组字面量是更好的做法。

```
// bad
var arr = new Array(1,2);

// good
var arr = [1,2];
```

2. Array.isArray()  
	Array.isArray 方法用来判断一个值是否为数组。它可以弥补typeof运算符的不足。

3. Array实例的方法 
   valueOf()、toString()
	
	
	