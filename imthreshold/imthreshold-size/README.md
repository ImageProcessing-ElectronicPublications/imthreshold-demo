# ImThreshold-demo

ImThreshold.  
Linux fork BookScanLib.ru (http://djvu-soft.narod.ru/bookscanlib/).  
It's a set of command line tools to create color images of djvu.  

```sh
imthreshold-size
```

origin:  
![](../../orig/lena.png)

---

`-f biakima -r 4` (x4, crop center):  
![](./lena.size.x4.biakima.png)  
`-f biakima -r 4 -p -1` (x4, IRIS, crop center):  
![](./lena.size.x4.biakima.i.png)

`-f bicont -r 4` (x4, crop center):  
![](./lena.size.x4.bicont.png)  
`-f bicont -r 4 -p -1` (x4, IRIS, crop center):  
![](./lena.size.x4.bicont.i.png)

`-f bicubic -r 4` (x4, crop center):  
![](./lena.size.x4.bicubic.png)  
`-f bicubic -r 4 -p -1` (x4, IRIS, crop center):  
![](./lena.size.x4.bicubic.i.png)

`-f biline -r 4` (x4, crop center):  
![](./lena.size.x4.biline.png)  
`-f biline -r 4 -p -1` (x4, IRIS, crop center):  
![](./lena.size.x4.biline.i.png)

`-f gsample -r 4` (x4, crop center) :  
![](./lena.size.x4.gsample.png)

`-f nearest -r 4` (x4, crop center) :  
![](./lena.size.x4.nearest.png)

---

 2022 zvezdochiot.  
 Website: https://sourceforge.net/projects/imthreshold/  
 BookScanLib.ru Website: http://djvu-soft.narod.ru/  
 Email: zvezdochiot@users.sourceforge.net  
