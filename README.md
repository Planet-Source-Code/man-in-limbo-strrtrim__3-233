<div align="center">

## strrtrim


</div>

### Description

Removes trailing spaces from the end of a string. See "trim" to remove leading spaces.
 
### More Info
 
the string

the trimmed string


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Man In Limbo](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/man-in-limbo.md)
**Level**          |Beginner
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |C, C\+\+ \(general\)
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/man-in-limbo-strrtrim__3-233/archive/master.zip)





### Source Code

```
/* strrtrim : removes trailing spaces from the end of a string*/
static char* strrtrim( char* s)
{
 int i;
 if (s) {
  i = strlen(s); while ((--i)>0 && isspace(s[i]) ) s[i]=0;
 }
 return s;
}
```

