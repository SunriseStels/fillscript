Есть двухмерный массив, в котором числами нарисован некоторый замкнутый контур (1). 
Задача закрасить этот контур из точки X значением 2

```
0,0,1,1,1,0,0,0 
0,1,0,0,0,1,0,0 
0,0,1,0,0,0,1,0 
0,1,0,X,0,1,0,0 
0,0,1,1,1,0,0,0 
0,0,0,0,0,0,0,0 
```

при закрашивании в точке X должен получится результат 

```
0,0,1,1,1,0,0,0 
0,1,2,2,2,1,0,0 
0,0,1,2,2,2,1,0 
0,1,2,2,2,1,0,0 
0,0,1,1,1,0,0,0 
0,0,0,0,0,0,0,0
```
