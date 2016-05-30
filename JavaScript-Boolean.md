# JavaScript Boolean 对象

## 应用
表示两个值："true" 或 "false"


## 创建 Boolean 对象
```
new Boolean(value);	//构造函数
Boolean(value);		//转换函数
```
当作为一个**构造函数**调用时，Boolean() 将把它的参数转换成一个布尔值，并且返回一个**包含该值的 Boolean 对象**。

如果作为一个**普通函数**调用时，Boolean() 只将把它的参数转换成一个原始的布尔值，并且返回**这个值**。

**如果省略 value 参数，或者设置为 0、-0、null、""、false、undefined 或 NaN，则该对象设置为 false。否则设置为 true（即使 value 参数是字符串 "false"）**


## Boolean 对象属性

**constructor** 返回对创建此对象的 Boolean 函数的引用

**prototype**使您有能力向对象添加属性和方法。

## Boolean 对象方法

**toString()** 把逻辑值转换为字符串，并返回结果。
* 不改变原始对象值
 
  ```
    var b = new Boolean();
    b; //Boolean {[[PrimitiveValue]]: false}
    b.toString(); //false
    b; //Boolean {[[PrimitiveValue]]: false}
  ```
  
**valueOf()**	返回 Boolean 对象的原始值。
    
    
**在 JavaScript 中，布尔值是一种基本的数据类型。Boolean 对象是一个将布尔值打包的布尔对象。**

**Boolean 对象主要用于提供将布尔值转换成字符串的 toString() 方法。
当调用 toString() 方法将布尔值转换成字符串时（通常是由 JavaScript 隐式地调用），JavaScript 会内在地将这个布尔值转换成一个临时的 Boolean 对象，然后调用这个对象的 toString() 方法。**
