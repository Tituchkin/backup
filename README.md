# backup
backup with bat rar windows

@echo off


- set rar_path="C:\Program Files\WinRAR\Rar.exe"
- set source1="D:\Docs"
- set source2="C:\mult"
- set destination="C:\"
- set passwd="xxxxxx"
- set _my_datetime=%date%_%time%
- set _my_datetime=%_my_datetime: =_%
- set _my_datetime=%_my_datetime::=%
- set _my_datetime=%_my_datetime:/=_%
- set _my_datetime=%_my_datetime:.=_%
- "C:\Program Files\WinRAR\Rar.exe"  a -r -m2 -dh -ow -hpxxxxxx -r0 %destination%backup_rarLq_%_my_datetime%.rar %source1% %source2%
