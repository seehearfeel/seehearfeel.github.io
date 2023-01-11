---
layout: default
---

### 01 Growth and Development
No matter where you are,   
please understand the importance   
of personal growth and development.

### 02 Smile and Silence
Smile and silence are two powerful tools,   
smile is the way to solve many problems,   
silence is the way to avoid many problems.

### 03 Rest and Exercise
Early to bed and early to rise   
makes a man healthy, wealthy and wise.   
If you keep exercising, you will be strong.   
We must struggle against our own laziness   
and stay with our training, rain or shine.

### 04 Rules for Happiness
Something to do,   
someone to love,   
something to hope for,   
spirits of independence,   
thoughts of freedom.

### 05 Walking for Peace
True inner peace is independent of   
external conditions and circumstances,   
it can be acquired through proper training.

<html>
	I have been walking over 6 km every day<br>
	for the past <span id="walk_days"></span> days since Jan 01, 2023,<br>
	the total distance is more than <span id="walk_dist"></span> km.<br><br>

	If you are interested, you can get<br>
	<a href="https://github.com/seehearfeel/seehearfeel.github.io/tree/master/walks">
	the complete records of daily walk</a>,<br>
	here is the latest walk:<br>
	<img src="" id="latest_walk" style="width:50%" alt="walk screenshot"><br>
	
	<script type="text/javascript">
		var imgsrc = new Array();

		imgsrc[0] = "/walks/walk20230101.png";
		imgsrc[1] = "/walks/walk20230102.png";
		imgsrc[2] = "/walks/walk20230103.png";
		imgsrc[3] = "/walks/walk20230104.png";
		imgsrc[4] = "/walks/walk20230105.png";
		imgsrc[5] = "/walks/walk20230106.png";
		imgsrc[6] = "/walks/walk20230107.png";
		imgsrc[7] = "/walks/walk20230108.png";
		imgsrc[8] = "/walks/walk20230109.png";
		imgsrc[9] = "/walks/walk20230110.png";
		imgsrc[10] = "/walks/walk20230111.png";

		document.getElementById("walk_days").innerHTML = imgsrc.length;
		document.getElementById("walk_dist").innerHTML = imgsrc.length * 6;
		document.getElementById("latest_walk").src = imgsrc[imgsrc.length - 1];
	</script>
</html>
