# 411w8b
user@TI-308:~$ hello
The program 'hello' can be found in the following packages:
 * hello
 * hello-debhelper
Ask your administrator to install one of them
user@TI-308:~$ echo hello
hello
user@TI-308:~$ echo hello world
hello world
user@TI-308:~$ echo 'hello world'
hello world
user@TI-308:~$ echo a.txt
a.txt
user@TI-308:~$ echo 'hello world'
hello world
user@TI-308:~$ echo 'hello world' > a.txt
user@TI-308:~$ echo 'hello world' > b.txt
user@TI-308:~$ ls
a.txt  c.txt	   Desktop    Downloads  octave-core  Public	 Videos
b.txt  c.txt.save  Documents  Music	 Pictures     Templates  w4.sh
user@TI-308:~$ echo "hello world" >ryta.txt
user@TI-308:~$ ls
a.txt  c.txt.save  Downloads	Pictures  Templates
b.txt  Desktop	   Music	Public	  Videos
c.txt  Documents   octave-core	ryta.txt  w4.sh
user@TI-308:~$ ls -l
total 60
-rw-rw-r-- 1 user user   12 Mar 20 11:06 a.txt
-rw-rw-r-- 1 user user   12 Mar 20 11:07 b.txt
-rw-rw-r-- 1 user user   13 Feb 20 15:44 c.txt
-rw-rw-r-- 1 user user   26 Feb 20 16:23 c.txt.save
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Desktop
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Documents
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Downloads
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Music
-rw-rw-r-- 1 user user  262 Mar 13 16:47 octave-core
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Pictures
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Public
-rw-rw-r-- 1 user user   12 Mar 20 11:09 ryta.txt
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Templates
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Videos
-rwxrwxr-x 1 user user  162 Feb 20 15:21 w4.sh
user@TI-308:~$ ls -lt
total 60
-rw-rw-r-- 1 user user   12 Mar 20 11:09 ryta.txt
-rw-rw-r-- 1 user user   12 Mar 20 11:07 b.txt
-rw-rw-r-- 1 user user   12 Mar 20 11:06 a.txt
-rw-rw-r-- 1 user user  262 Mar 13 16:47 octave-core
-rw-rw-r-- 1 user user   26 Feb 20 16:23 c.txt.save
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Documents
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Music
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Pictures
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Public
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Videos
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Downloads
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Templates
drwxr-xr-x 2 user user 4096 Feb 20 15:58 Desktop
-rw-rw-r-- 1 user user   13 Feb 20 15:44 c.txt
-rwxrwxr-x 1 user user  162 Feb 20 15:21 w4.sh
user@TI-308:~$ date
Fri Mar 20 11:17:42 EET 2015
user@TI-308:~$ cal
     March 2015       
Su Mo Tu We Th Fr Sa  
 1  2  3  4  5  6  7  
 8  9 10 11 12 13 14  
15 16 17 18 19 20 21  
22 23 24 25 26 27 28  
29 30 31              
                      
user@TI-308:~$ R

R version 2.14.1 (2011-12-22)
Copyright (C) 2011 The R Foundation for Statistical Computing
ISBN 3-900051-07-0
Platform: i686-pc-linux-gnu (32-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> a=22
> a<-22
> a
[1] 22
> b<-"22"
> b <- "22"
> b<-22
> b <-"22"
> b
[1] "22"
> > c<-c(a,b)
Error: unexpected '>' in ">"
> c <-c(a,b)
> c
[1] "22" "22"
> int
Error: object 'int' not found
> int
integer           interaction       interactive       intToBits
integrate         interaction.plot  intersect         intToUtf8
> interger
Error: object 'interger' not found
> integer
function (length = 0L) 
.Internal(vector("integer", length))
<bytecode: 0x8917058>
<environment: namespace:base>
> ?integer
                                                        

user@TI-308:~$ x <-c(1,4,5)
bash: syntax error near unexpected token `('
user@TI-308:~$ x<-c(1,4,5)
bash: syntax error near unexpected token `('
user@TI-308:~$ R

R version 2.14.1 (2011-12-22)
Copyright (C) 2011 The R Foundation for Statistical Computing
ISBN 3-900051-07-0
Platform: i686-pc-linux-gnu (32-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> x<-c(1,4,5)
> x
[1] 1 4 5
> y<-c(1,16,25)
> y
[1]  1 16 25
> plot(x,y)
> plot(x,y,"l")
There were 23 warnings (use warnings() to see them)
> plot(x,y,"l"lwd=3)
Error: unexpected symbol in "plot(x,y,"l"lwd"
> plot(x,y,"l" ,lwd=3)
> plot(x,y,"l" ,lwd=3,col=red)
Error in plot.xy(xy, type, ...) : object 'red' not found
> plot(x,y,"l" ,lwd=3,col='red')
> plot(x,y,"l" ,lwd=3,col='red'xl)
Error: unexpected symbol in "plot(x,y,"l" ,lwd=3,col='red'xl"
> plot(x,y,"l" ,lwd=3,col='red'xlab)
Error: unexpected symbol in "plot(x,y,"l" ,lwd=3,col='red'xlab"
> plot(x,y,"l" ,lwd=3,col='red'xlab="Argument"
Error: unexpected symbol in "plot(x,y,"l" ,lwd=3,col='red'xlab"
> plot(x,y,"l" ,lwd=3,col='red'xlab="Argument")
Error: unexpected symbol in "plot(x,y,"l" ,lwd=3,col='red'xlab"
> plot(x,y,"l" ,lwd=3,col='red',xlab= "Argument")
> plot(x,y,"l" ,lwd=3,col='red',xlab= "Argument" ,ylab="function value" ,main="")
> 
> 
> 
> 
> 
> plot(x,y,"l" ,lwd=3,col='red',xlab= "Argument" ,ylab="function value" ,main="function")
> plot(x,y,"s" ,lwd=3,col='red',xlab= "Argument" ,ylab="function value" ,main="function")
> x<-c(1:10)
> x
 [1]  1  2  3  4  5  6  7  8  9 10
> y<-^2
Error: unexpected '^' in "y<-^"
> y<-x^2
> y
 [1]   1   4   9  16  25  36  49  64  81 100
> plot(x,y,"s" ,lwd=3,col='red',xlab= "Argument" ,ylab="function value" ,main="function")
> c(0:20) >c(0:1000)
   [1] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [13] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [25] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [37] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [49] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [61] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [73] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [85] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
  [97] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [109] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [121] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [133] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [145] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [157] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [169] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [181] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [193] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [205] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [217] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [229] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [241] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [253] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [265] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [277] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [289] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [301] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [313] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [325] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [337] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [349] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [361] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [373] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [385] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [397] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [409] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [421] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [433] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [445] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [457] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [469] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [481] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [493] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [505] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [517] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [529] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [541] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [553] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [565] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [577] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [589] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [601] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [613] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [625] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [637] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [649] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [661] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [673] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [685] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [697] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [709] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [721] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [733] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [745] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [757] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [769] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [781] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [793] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [805] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [817] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [829] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [841] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [853] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [865] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [877] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [889] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [901] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [913] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [925] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [937] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [949] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [961] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [973] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [985] FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE FALSE
 [997] FALSE FALSE FALSE FALSE FALSE
Warning message:
In c(0:20) > c(0:1000) :
  longer object length is not a multiple of shorter object length
> xy<-sqrt(x)
> xy
 [1] 1.000000 1.414214 1.732051 2.000000 2.236068 2.449490 2.645751 2.828427
 [9] 3.000000 3.162278
> ?plot
