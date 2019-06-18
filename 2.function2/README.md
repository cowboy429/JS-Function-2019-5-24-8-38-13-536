## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：判断一个字符串是否是回文串。（回文，一个字符串从前面读和从后面读都一样，例如：abcba就是回文串。）

```
function palindrome(message){
  // wirte your code here
}
palindrome('hello'); // should return false
palindrome('abcba'); // should return true
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
         //判断是否回文数
         if (str==result){
             return true;
         }
         else {
             return false;
         }
    }
    var str = "hello";
    console.log(reverseStr(str));
    var str2 = "ouuo";
    console.log(reverseStr(str2));
</script>
</body>
</html>
