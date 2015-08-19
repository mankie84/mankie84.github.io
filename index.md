---
title       : Sleepy App
subtitle    : An App for sleepy Coursera Heroes
author      : Manuel Kiewisch
job         : 
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs:
  transition: cube
  center: "true"
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : default      # 
widgets     : []      # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
url: {lib: "."}
bootstrap:
  theme: amelia
---


## Sleepy App
### by Manuel Kiewisch
<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.9.1/jquery.min.js"></script>
<div style='text-align: center;'>
    <img height='480' src='C:\Users\ElitebookHP\Desktop\R_Work\Sleepy App\sleepy.png' alt="Smiley face" style="background:none; border:none; box-shadow:none;" />
</div>


--- ds:alert
### Do you routinely stay up too long, punching R code, studying online...?
.fragment Do you suffer from any or multiple of the following?
<br><br>

> - <font color=red><b>General Tiredness</b></font>
> - <font color=red><b>Red Eyes</b></font>
> - <font color=red><b>Hallucination</b></font>
<br><br>

.fragment Then, this App is for **YOU**!


--- ds:blackout
### Sleepy App tells you how to sleep

The self-explanatory interface guides you trough the input panels, covering:
<br><br>

> - .grow Your Age
> - .grow Your usual sleep duration
> - .grow Your usual sleeping and waking times
<br><br>

In return, sleepy App calculates your sleep difference and optimal waking time!


--- ds:soothe &vertical
### The heart of sleepy App is the sleep-graph!
#### constructed from over one thousand sleep-samples in controlled experiments with happy sleepers
Here at the example of 50 years (<font color=red><b>Arrow Down</b></font> for more)

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1-1.png) 


*** &vertical
### Check out Sleepy App at
#### (www.sleepyApp.com)

If you have this nagging feeling that you don't get the most out of your sleep: Sleepy App will help you feel fitter!

![plot of chunk unnamed-chunk-2](assets/fig/unnamed-chunk-2-1.png) 


</section>

<script>
$('ul.incremental li').addClass('fragment')
</script>

