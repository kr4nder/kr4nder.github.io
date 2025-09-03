<html>
<head>
<meta charset="utf-8">
</head>
<body>
<h4>krander</h4>
<input type="number" id="n1">x +
<input type="number" id="n2">y =
<input type="number" id="n3">
<br>
<input type="number" id="n4">x +
<input type="number" id="n5">y =
<input type="number" id="n6">
<br>
<p>Ответ:</p>
<br>
x =<input type="number" value="" id="result1">
y =<input type="number" value="" id="result2">
<br>
<button id="bt" onclick=" 
      /* извлечение данных */  
const n1 = Number(document.querySelector('#n1').value);
const n2 = Number(document.querySelector('#n2').value); 
const n3 = Number(document.querySelector('#n3').value);
const n4 = Number(document.querySelector('#n4').value);
const n5 = Number(document.querySelector('#n5').value);
const n6 = Number(document.querySelector('#n6').value);
      /* вычисления  */    
      const det = (n1 * n5) - (n2 * n4);
      const det1 = (n3 * n5) - (n6 * n2);
      const det2 = (n1 * n6) - (n3 * n4);
                         const result1 = det1 / det;
                         const result2 = det2 / det;
                             
       
       
       
      /* запись результата */ 
      document.querySelector('#result1').value = result1;                         document.querySelector('#result2').value = result2;                  
    ">Выполнить задание</button>
</body>
</html>
