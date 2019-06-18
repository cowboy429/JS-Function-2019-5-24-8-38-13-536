## 要求 
    
- 新建main.js文件，编写一个函数，实现以下功能：计算出一个字符串共有多少个单词组成。

```
function countWords(message){
  // wirte your code here
}
countWords('Good morning, I love JavaScript.'); // should return 5
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>fun4</title>
</head>
<body>
<script>
    function getWordCount(str) {
        var temp = str.split(/[ , ''.]/g);
        var num=0;
        for(var i=0;i<temp.length;i++){
            if(temp[i]!=''){
                num++;
            }
        }
        return num;
    }
    var str = 'Good morning, I love JavaScript.';
    confirm(getWordCount(str))
</script>
</body>
</html>
