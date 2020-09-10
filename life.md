---
layout: default
---

### Part 1: Growth and Development
No matter where you are,   
please understand the importance   
of personal growth and development.

### Part 2: Smile and Silence
Smile and silence are two powerful tools,   
smile is the way to solve many problems,   
silence is the way to avoid many problems.

### Part 3: Rest and Exercise
Early to bed and early to rise   
makes a man healthy, wealthy and wise.   
If you keep exercising, you will be strong.   
We must struggle against our own laziness   
and stay with our training, rain or shine.

### Part 4: Rules for Happiness
Something to do,   
someone to love,   
something to hope for,   
spirits of independence,   
thoughts of freedom.

### Part 5: Walking for Peace
True inner peace is independent of   
external conditions and circumstances,   
it can be acquired through proper training.

<html>
	I have been walking over 5 km every day<br>
	for the past <span id="walk_days"></span> days since Sep 01, 2020,<br>
	the total distance is more than <span id="walk_dist"></span> km.<br><br>

	If you are interested, you can get<br>
	<a href="https://github.com/seehearfeel/seehearfeel.github.io/tree/master/walks">
	the complete records of daily walk</a>,<br>
	here is the latest walk:<br>
	<img src="" id="latest_walk" style="width:50%" alt="walk screenshot"><br>
	
	<script type="text/javascript">
		var imgsrc = new Array();

		imgsrc[0] = "/walks/walk20200901.png";
		imgsrc[1] = "/walks/walk20200902.png";
		imgsrc[2] = "/walks/walk20200903.png";
		imgsrc[3] = "/walks/walk20200904.png";
		imgsrc[4] = "/walks/walk20200905.png";
		imgsrc[5] = "/walks/walk20200906.png";
		imgsrc[6] = "/walks/walk20200907.png";
		imgsrc[7] = "/walks/walk20200908.png";
		imgsrc[8] = "/walks/walk20200909.png";
		imgsrc[9] = "/walks/walk20200910.png";

		document.getElementById("walk_days").innerHTML = imgsrc.length;
		document.getElementById("walk_dist").innerHTML = imgsrc.length * 5;
		document.getElementById("latest_walk").src = imgsrc[imgsrc.length - 1];
	</script>
</html>
