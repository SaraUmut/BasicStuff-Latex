# Miktex & LaTex & TexnicCenter – how to start
----------------------------
**Step1:** 
Download miktex : https://miktex.org/download 
Remember the path (you need to put it when you download editor) 
(can be found from properties of TeXworks app.. preferences, typesettings)
(me: `C:\Users\SARA\AppData\Local\Programs\MiKTeX 2.9\miktex\bin\x64`)

-----------------------------

**Step2:** download  editor (Texnic center): http://www.texniccenter.org/download/ 
Then when it opens it ask for prev path of miktex
Then it ask for Postscript-viewer:
e.g. mine is: `C:\Users\SARA\AppData\Local\Programs\MiKTeX 2.9\miktex\bin\x64\miktex-texworks.exe`

-----------------------------

**Step3:** download (Sumatra PDF) : https://www.sumatrapdfreader.org/download-free-pdf-viewer.html (SumatraPDF-3.1.2-64-install.exe)

add in texnic, Build-> Define Output Profiles -> Viewer -> Executable path: add the path of Sumatra.
e.g. mine is: `C:\Users\sara\AppData\Local\SumatraPDF\SumatraPDF.exe`

-----------------------------

**Step4:** open TeXnicCenter, `File->new-> file` and write your first document:


```
\documentclass{article}
\title{Document Title}
\author{your name}
\date{the date}
\begin{document}
   \maketitle
   Hello world!
\end{document}
```
 
Press save, create a folder called HelloWorld (you can put that in Documents or any other place)
Then write a name for your file “helloWorld” and press save 
Make the output profile: “LaTex  PDF”
Then press “build current file” it should give you 0 errors and 1 page
Press view output , to view your file
You can find your pdf file in the folder: HelloWorld 

-------------------------------
