# VolitilitySchool
Using Volitility in project for school using this as a note book


my file locations and commands. (MAC os) 

dwarfdump -arch x86_64 /Library/Developer/KDKs/KDK_10.15.6_19G71a.kdk/system/library/Kernels/kernel.dSYM> 10.12.3_x64.dwarfdump
-- creates dump file to be anylized 

___
09/09/2020
I found out that Volitility does not support newer versions of mac os I have to decide whether or not to anylize profiles people have on git hub or 
use windows 10. 

python volatility-master//tools/mac/convert.py 10.12.3_x64.dwarfdump converted-10.12.3_x64.dwarfdump -- State machine broken! level 0!
