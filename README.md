<div align="center">

## Better IsOdd


</div>

### Description

Tell if a number is odd in one line of code. (and if its not odd its even, but i dont have to tell you that)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Dave Katrowski](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/dave-katrowski.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script, ASP \(Active Server Pages\) 
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/dave-katrowski-better-isodd__1-9362/archive/master.zip)

### API Declarations

```
'none
```


### Source Code

```
Function IsOdd(Var as integer)
IsOdd = -(Var And 1)
End Function
```

