echo off
set /p dummy = press F
md Morozov
cd Morozov
md Dmitriy
cd Dmitriy
md Alexseevich
set /p dummy = press F
cd C:\Users\mrdmi\Desktop
cd Morozov
echo > 01062002.txt
cd Dmitriy
cd Alexseevich
echo > NOTEBOOK.txt
set /p dummy = press to del files
cd C:\Users\mrdmi\Desktop
del Morozov /S /Q /F
set /p dummy = press to del
cd Morozov
cd Dmitriy
rd Alexseevich
cd ..
rd Dmitriy
cd ..
rd Morozov
pause