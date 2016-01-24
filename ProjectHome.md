phoc is a programmable calculator, which stand for **Programmable Hign-Order-Calculator**, and powered by script language, currently is JavaScript. But it's may language-independent, I'll add python later to pcalc.

phoc is look like this:

![http://phoc.googlecode.com/files/pcalc.png](http://phoc.googlecode.com/files/pcalc.png)
## Expression evaluation ##
phoc can of course do the normal compute such as expression evaluation:
```
(1+2)*8/6
sin(PI)*cos(PI/2)
```

## Define functions ##
also, phoc can support user-defined function, such as:
```
function add(x, y){
    return x + y;
}
add(3, 5)
```
or
```
function sum(){
//code to calc sum
}

sum(1, 3, 34, 566, 57, 6, 7, 78, 787)
```

![http://phoc.googlecode.com/files/funceditor.png](http://phoc.googlecode.com/files/funceditor.png)

## Plot function ##
and phoc can **_plot_** those functions too. such as:
```
plot2d(sin, {start:-PI, step:0.1, stop:PI})
```
will draw the function **_sin_** in the range(-PI, PI), step is 0.1.

![http://phoc.googlecode.com/files/sin.png](http://phoc.googlecode.com/files/sin.png)

I using the **_jmathtools_** library in phoc. You can check it out here:
http://jmathtools.berlios.de/doku.php?id=start, jmathtools is awesome. You can download them from http://code.google.com/p/jmathplot/.

[![](http://www.softpedia.com/images/softpedia_download_small.gif)](http://www.softpedia.com/get/Science-CAD/Programmable-Calculator.shtml)