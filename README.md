﻿<div align="center">

## Password generator


</div>

### Description

Very simple script which generates an 8 digit password consisting of letters and numbers and capital letters.
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Bhushan\-](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/bhushan.md)
**Level**          |Intermediate
**User Rating**    |3.8 (45 globes from 12 users)
**Compatibility**  |PHP 3\.0
**Category**       |[Algorithims](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/algorithims__8-29.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/bhushan-password-generator__8-732/archive/master.zip)





### Source Code

```
<php>
<?
//class BerekenWachtwoord() {
 $a="";$a="";
	function bereken() {
	while ($i<8) {
	$i++;
	$randomgetal = mt_rand(1,61);
	if ($randomgetal==1) {$a.="1";}
	if ($randomgetal==2) {$a.="2";}
	if ($randomgetal==3) {$a.="3";}
	if ($randomgetal==4) {$a.="4";}
	if ($randomgetal==5) {$a.="5";}
	if ($randomgetal==6) {$a.="6";}
	if ($randomgetal==7) {$a.="7";}
	if ($randomgetal==8) {$a.="8";}
	if ($randomgetal==9) {$a.="9";}
	if ($randomgetal==10) {$a.="a";}
	if ($randomgetal==11) {$a.="b";}
	if ($randomgetal==12) {$a.="c";}
	if ($randomgetal==13) {$a.="d";}
	if ($randomgetal==14) {$a.="e";}
	if ($randomgetal==15) {$a.="f";}
	if ($randomgetal==16) {$a.="g";}
	if ($randomgetal==17) {$a.="h";}
	if ($randomgetal==18) {$a.="i";}
	if ($randomgetal==19) {$a.="j";}
	if ($randomgetal==20) {$a.="k";}
	if ($randomgetal==21) {$a.="l";}
	if ($randomgetal==22) {$a.="m";}
	if ($randomgetal==23) {$a.="n";}
	if ($randomgetal==24) {$a.="o";}
	if ($randomgetal==25) {$a.="p";}
	if ($randomgetal==26) {$a.="q";}
	if ($randomgetal==27) {$a.="r";}
	if ($randomgetal==28) {$a.="s";}
	if ($randomgetal==29) {$a.="t";}
	if ($randomgetal==30) {$a.="u";}
	if ($randomgetal==31) {$a.="v";}
	if ($randomgetal==32) {$a.="w";}
	if ($randomgetal==33) {$a.="x";}
	if ($randomgetal==34) {$a.="y";}
	if ($randomgetal==35) {$a.="z";}
	if ($randomgetal==36) {$a.="A";}
	if ($randomgetal==37) {$a.="B";}
	if ($randomgetal==38) {$a.="C";}
	if ($randomgetal==39) {$a.="D";}
	if ($randomgetal==40) {$a.="E";}
	if ($randomgetal==41) {$a.="F";}
	if ($randomgetal==42) {$a.="G";}
	if ($randomgetal==43) {$a.="H";}
	if ($randomgetal==44) {$a.="I";}
	if ($randomgetal==45) {$a.="J";}
	if ($randomgetal==46) {$a.="K";}
	if ($randomgetal==47) {$a.="L";}
	if ($randomgetal==48) {$a.="M";}
	if ($randomgetal==49) {$a.="N";}
	if ($randomgetal==50) {$a.="O";}
	if ($randomgetal==51) {$a.="P";}
	if ($randomgetal==52) {$a.="Q";}
	if ($randomgetal==53) {$a.="R";}
	if ($randomgetal==54) {$a.="S";}
	if ($randomgetal==55) {$a.="T";}
	if ($randomgetal==56) {$a.="U";}
	if ($randomgetal==57) {$a.="V";}
	if ($randomgetal==58) {$a.="W";}
	if ($randomgetal==59) {$a.="X";}
	if ($randomgetal==60) {$a.="Y";}
	if ($randomgetal==61) {$a.="Z";}
	}
	return $a;
}
$b=bereken();
echo $b;
```

