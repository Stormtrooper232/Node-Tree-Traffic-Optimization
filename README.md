# Node-Tree-Traffic-Optimization
Uses a node tree to determine the fastest route to school in order to minimize travel time.

<h2>Background</h2>
School starts at 8:20 am, traffic begins around 8:00. <br>
It is assumed that traffic increases at (percent traffic) = (minutes since 8:00)^(1.5) / (89.443) <br>
Using this formula cars increases geometrically, peaking at 8:20. <br>
A random modifer is added to each road, this modifier is generated randomly from a normal distribution using the estimated standard deviation of the total cars on each road. <br>

<h2>Data</h2>
<table>
Road - Max Traffic
  #1 - 87
  #2 - 71
  #3 - 82
  #4 - 68
  #5 - 97
  #6 - 56
  #7 - 238
  #8 - 77
  #9 - 169
  #10 - 167
  #11 - 84
S of x = 57.05
