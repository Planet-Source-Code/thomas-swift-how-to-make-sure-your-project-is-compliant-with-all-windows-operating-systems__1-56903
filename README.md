<div align="center">

## How to make sure your project is compliant with all windows operating systems


</div>

### Description

How to make sure your project is compliant with all windows operating systems.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Thomas Swift](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/thomas-swift.md)
**Level**          |Beginner
**User Rating**    |5.0 (15 globes from 3 users)
**Compatibility**  |VB 3\.0, VB 4\.0 \(16\-bit\), VB 4\.0 \(32\-bit\), VB 5\.0, VB 6\.0
**Category**       |[Coding Standards](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/coding-standards__1-43.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/thomas-swift-how-to-make-sure-your-project-is-compliant-with-all-windows-operating-systems__1-56903/archive/master.zip)





### Source Code

<p><font face="Arial" size="2"><b>The most important factor of knowing that your
project is compliant is API. Before publishing you particular project be sure to
go to MSDN at Microsoft &amp; cross reference all your API calls. At the bottom
of each API description page at MSDN is a list that shows what operating systems
that particular API call is valid on. It is OK to implement both if you use a
operating system detection API to fire or not to fire the correct API for the
detected operating system.</b></font></p>
<p><font face="Arial" size="2"><b>The second factor is null filtering on NT
operating systems. Be sure to debug your application on either windows 2000 or
XP to find out if any of your code generates any null characters when returning
data. Null characters are indicated by a empty square box or boxes in your
string data. If null characters do exist be sure to use a null filter in those
areas of your code. Windows NT operating systems are famous for generating null characters.
This is why most programmers now days either work in windows 2000 or XP.</b></font></p>
<p><font face="Arial" size="2"><b>Their you have it, its as simple as that !!!</b></font></p>

