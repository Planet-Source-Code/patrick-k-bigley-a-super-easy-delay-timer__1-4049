<div align="center">

## A Super Easy Delay Timer


</div>

### Description

A delay timer so easy, this paragraph is longer. I had to submit this easy code because it is not on this website. Uses no API, and it is very handy!!
 
### More Info
 
Make a form with a command button ont it. Paste the code into the command button. This sample has a 3 second delay, then you hear a beep.


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Patrick K\. Bigley](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/patrick-k-bigley.md)
**Level**          |Unknown
**User Rating**    |4.2 (42 globes from 10 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0, VB Script
**Category**       |[Math/ Dates](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/math-dates__1-37.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/patrick-k-bigley-a-super-easy-delay-timer__1-4049/archive/master.zip)





### Source Code

```
Private Sub Command1_Click()
 Dim Start As Long
 Start = Timer
  Do While Timer < Start + 3 'a 3 second delay (Change to any numer you want)
   DoEvents  ' Yield to other processes.
  Loop
 Beep
End Sub
```

