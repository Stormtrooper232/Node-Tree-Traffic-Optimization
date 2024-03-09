# Node-Tree-Traffic-Optimization
Uses a node tree to determine the fastest route to school in order to minimize travel time.

<h2>Background</h2>
School starts at 8:20 am, traffic begins around 8:00. <br>
It is assumed that traffic increases at (percent traffic) = (minutes since 8:00)^(1.5) / (89.443) <br>
Using this formula cars increases geometrically, peaking at 8:20. <br>
A random modifer is added to each road, this modifier is generated randomly from a normal distribution using the estimated standard deviation of the total cars on each road. <br>

<h2>Data</h2>
<table>
Road - Max Traffic <br>
  #1 - 87<br>
  #2 - 71<br>
  #3 - 82<br>
  #4 - 68<br>
  #5 - 97<br>
  #6 - 56<br>
  #7 - 238<br>
  #8 - 77<br>
  #9 - 169<br>
  #10 - 167<br>
  #11 - 84<br> <br>
S of x = 57.05
