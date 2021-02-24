r_present
========================================================
author: 
date: 
autosize: true
font-import : http://fonts.googleapis.com/css?family=Caveat
font-family: "Caveat"
css: spec.css

First Slide
========================================================
type: exclaim
transition: fade
transition-speed: slow
incremental: true
For more details on authoring R presentations please visit <https://support.rstudio.com/hc/en-us/articles/200486468>.

- Bullet 1
<li class="fragment fade-in"> hello </li>
- Bullet 2
- Bullet 3

```r
summary(cars)
```

```
     speed           dist       
 Min.   : 4.0   Min.   :  2.00  
 1st Qu.:12.0   1st Qu.: 26.00  
 Median :15.0   Median : 36.00  
 Mean   :15.4   Mean   : 42.98  
 3rd Qu.:19.0   3rd Qu.: 56.00  
 Max.   :25.0   Max.   :120.00  
```

Slide With Code
========================================================
 first column 

```r
1:10
```

```
 [1]  1  2  3  4  5  6  7  8  9 10
```
***
second column

```r
(1:10)^2
```

```
 [1]   1   4   9  16  25  36  49  64  81 100
```


Slide With Plot
========================================================

$$\sin(\frac{3\pi}{2})=-1 $$

![plot of chunk unnamed-chunk-4](r_present-figure/unnamed-chunk-4-1.png)


Slide With Plotly
========================================================


<style>
  .p_iframe iframe {
    width:70%;
    height:576px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>

