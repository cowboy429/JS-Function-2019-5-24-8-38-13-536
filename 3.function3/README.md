## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：按字母表顺序输出传入的参数字符串。

```
function alphabetSort(message){
  // wirte your code here
}
alphabetSort('hello'); // should return 'ehllo'
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>fun3</title>
</head>
<body>
<script>
    function sortByLetter(str) {
        var arr = str.split('').sort();
        return arr.join('');
    }
    var str = "hello";
    console.log(sortByLetter(str));
</script>
</body>
</html>
