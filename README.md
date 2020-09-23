<div align="center">

## One liner code


</div>

### Description

One line code to display:

1 Display Control panel

2 View the display settings

3 Display Mouse settings

4 Display the Keyboard settings

5 Display Modem settings

6 Display Printer settings

7 Display time/date settings

Reposted from : "Stringer" (jstringer@fsmail.net)
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Glen van Niekerk](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/glen-van-niekerk.md)
**Level**          |Intermediate
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/glen-van-niekerk-one-liner-code__1-46109/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
'Display control panel
Call Shell("rundll32.exe shell32.dll,Control_RunDLL", _
 vbNormalFocus)
End Sub
Private Sub Command2_Click()
'View the display settings!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL desk.cpl,,0", vbNormalFocus)
End Sub
Private Sub Command3_Click()
'
'Display Mouse settings with 1 line!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL main.cpl @0", vbNormalFocus)
End Sub
Private Sub Command4_Click()
'Display the Keyboard settings with 1 line!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL main.cpl @1", vbNormalFocus)
End Sub
Private Sub Command5_Click()
'Display Modem settings!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL modem.cpl", vbNormalFocus)
End Sub
Private Sub Command6_Click()
'Display Printer settings!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL main.cpl @2", vbNormalFocus)
End Sub
Private Sub Command7_Click()
'Display time/date settings!
Call Shell("rundll32.exe shell32.dll,Control_RunDLL timedate.cpl", vbNormalFocus)
End Sub
Private Sub Form_Load()
Command1.Caption = "Display Control panel"
Command2.Caption = "View the display settings"
Command3.Caption = "Display Mouse settings"
Command4.Caption = "Display the Keyboard settings"
Command5.Caption = "Display Modem settings"
Command6.Caption = "Display Printer settings"
Command7.Caption = "Display time/date settings"
End Sub
```

