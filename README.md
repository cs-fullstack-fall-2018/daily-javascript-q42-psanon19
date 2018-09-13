# daily-javascript-q42

You have the following HTML page: 
```html
<!DOCTYPE html> 
<html> 
<head> 
      <title>Intro to JavaScript</title> 
          	<meta charset="utf-8" /> 
</head> 
<body> 
      <script> 
           var arr = []; 
           for (var i = 0; i < 3; i++) { 
                arr.push([i, i+2, 2*i-1]); 
           } 

           arr.forEach(function (item, i, arr) { 
                console.log(item.reverse().join('|')); 
           }); 

      </script> 
</body> 
</html> 
```
What will show in the console when the page is loaded in the browser?

Choose the correct answer
```
Option 1:
-2|2|0 
0|3|1 
2|4|2
```
```
Option 2:
1|3|1 
3|4|2 
5|5|3
```
```
***Option 3:***
0|2|-1 
1|3|1 
2|4|3
```
```
Option 4:
-1|2|0 
1|3|1 
3|4|2
```
Answer is 3
