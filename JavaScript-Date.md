# JavaScript Date 对象

## 应用

用来处理日期和时间

## 创建

```
var myDate=new Date();//默认为当前日期和时间
```

## 属性

constructor : 返回对创建此对象的 Date 函数的引用

prototype : 使您有能力向对象添加属性和方法


## 方法

Date() 返回当日的日期和时间字符串.

getFullYear() 以四位数字返回年份

getMonth() 返回月份 (0 ~ 11)

getDate() 返回一个月中的某一天 (1 ~ 31)

getDay() 返回一周中的某一天 (0 ~ 6) //0是周日

getHours():getMinutes():getSeconds().getMilliseconds()

getTime() 返回 1970 年 1 月 1 日至今的毫秒数

toString() // "Tue May 31 2016 00:25:37 GMT+0800 (中国标准时间)"

toTimeString() // "00:25:37 GMT+0800 (中国标准时间)"

toDateString() // "Tue May 31 2016"

toLocaleString() // "2016/5/31 上午12:25:37"

toLocaleTimeString() // "上午12:25:37"

toLocaleDateString() // "2016/5/31"

d.valueOf() === d.getTime(); // true

new Date("July 21, 1983 01:15:00") 设定具体时间

parse() 方法可解析一个日期时间字符串，并返回 1970/1/1 午夜距离该日期时间的毫秒数。 **Date.parse() 是 Date 对象的静态方法。==Date.parse("Jul 8, 2005")==**
