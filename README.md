<div align="center">

## Basic FileExist


</div>

### Description

Check to see if a File exists, simple code
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[samon\_18](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/samon-18.md)
**Level**          |Beginner
**User Rating**    |4.3 (30 globes from 7 users)
**Compatibility**  |VB 6\.0
**Category**       |[Files/ File Controls/ Input/ Output](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/files-file-controls-input-output__1-3.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/samon-18-basic-fileexist__1-64093/archive/master.zip)





### Source Code

```
Dim Script As Object
Set Script = CreateObject("Scripting.filesystemobject")
If Script.FileExists("C:\My Documents\Prog.exe") = True Then
'True code here
Else
'False code here
End if
```

