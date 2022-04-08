# Excel
## Autofill A B C D...AA AB... 
```
=LEFT(ADDRESS(1, ROW(A1), 4, TRUE), (ROW(A1)>26)+(ROW(A1)>702)+1)
```
