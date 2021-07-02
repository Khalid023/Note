# Basic of R
## Data Types
### Objects
five basic objects  
- character
- numeric(实数)
- integer
- complex
- logical(True/Flse)

**向量vector 是最基本的对象但只能包含一种形式的对象。使用vector()创建**  
**列表list 可以包含多种对象**

### Attributes
R objects can have attributes  
- names，dimanames
- dimensions
- class
- length
- metadata
- etc
  
**使用attributes()创建属性**

### Vectors
c() function to create vectors of objects
```r
x<-(0.5,0.6)
```
vector() function to create vectors of objects too
```r
>x<-vector("numeric",length=10)
>x
 [1]0000000000
```

### List
