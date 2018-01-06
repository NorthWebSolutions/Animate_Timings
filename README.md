# CSS3 Animation timer

This css file will allow you to manipulate animation timing with 100ms precision.
This is pure CSS, nothing else, so it may require a modern browser to run.

more info on browser support, and usage: https://www.w3schools.com/cssref/css3_pr_animation-delay.asp  



## features
If you are using CSS3 Animations in your project, at some point you will need to time when the animation start and end.

Delay animation:
With this <code>del-#Second-#TenthsOfaSecond</code> you can delay the start of the animation

Change the Duration of an animation:
With this <code>dur-#Second-#TenthsOfaSecond</code> you can set the duration for your animation



## usage

example:

1. if you want to delay the start of the animation with 2.3 sec you need to add a new css3 class to your animated item like:
(where animated_div is your predefined animation)
<code>
<div class="animated_div del-2-3"></div>
</code>

2. if you want to delay the start of the animation with 0.1 sec and Change the animation length to 3sec:
(where animated_div is your predefined animation)
<code>
<div class="animated_div del-0-1 dur-3" ></div>
</code>

## setup
implement the /generated_css/animations_timer.css to your HTML head like a regular CSS file
<link rel="stylesheet" href="YOUR_PATH_TO_ANIMATIONS_TIMER.CSS">



## requrements
- a modern browser what can handle animations, and that's all. :)
Enjoy
