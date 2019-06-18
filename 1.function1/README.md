## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：将一个字符串逆序输出。

```
function reverseString(message){
  // wirte your code here
}
reverseString('hello'); // should return 'olleh'
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>fun1</title>
</head>
<body>
<script>
    function reverseStr(str) {
        var result = '';
        for (var i = str.length-1;i>=0;i--){
            result += str.charAt(i);
        }
        return result;
    }
    var str = "hello";
    console.log(reverseStr(str))
</script>
</body>
</html>

