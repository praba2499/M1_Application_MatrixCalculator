## **Table no: High level test plan**

|**Test ID**|**Description**|**Exp I/P**|**Exp O/P**|**Actual Out**|**Type Of Test**|
| :-: | :-: | :-: | :-: | :-: | :-: |
|H\_01|tested addition of two matrices|matrix1, matrix2, n|SUCCESS|SUCCESS|Technical|
|H\_02|tested subtraction of two matrices|matrix1, matrix2, n|SUCCESS|SUCCESS|Technical|
|H\_03|tested multiplication of two matrices|matrix1, matrix2, n|SUCCESS|SUCCESS|Technical|
|H\_04|tested determinant of a matrix|matrix1, n|SUCCESS|SUCCESS|Technical|
|H\_05|tested transpose of a matrix|matrix1, n|SUCCESS|SUCCESS|Technical|
|H\_06|tested inverse of a matrix|matrix1, n|SUCCESS|SUCCESS|Technical|
|H\_07|tested power of -1 function|3|-1|-1|Technical|
|H\_08|tested power of -1 function|2|1|1|Technical|
## **Table no: Low level test plan**

|**Test ID**|**HLT ID**|**Description**|**Exp IN**|**Exp OUT**|**Actual Out**|**Type Of Test**|
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
|L\_01|H\_01, H\_02, H\_03|Tested on functions which accept two matrices as input|matrix1, matrix2, n|SUCCESS|SUCCESS|Technical|
|L\_02|H\_04, H\_05, H\_06|Tested on functions which accept single matrix as input|matrix1, n|SUCCESS|SUCCESS|Technical|
|L\_03|H\_07, H\_08|Tested on function which returns an integer value|3|-1|-1|Technical|

