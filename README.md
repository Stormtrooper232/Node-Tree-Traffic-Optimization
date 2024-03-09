# Node-Tree-Traffic-Optimization
Uses a node tree to determine the fastest route to school in order to minimize travel time.

<h2>Background</h2>
School starts at 8:20 am, traffic begins around 8:00. <br>
It is assumed that traffic increases at (percent traffic) = (minutes since 8:00)^(1.5) / (89.443) <br>
Using this formula cars increases geometrically, peaking at 8:20. <br>
A random modifer is added to each road, this modifier is generated randomly from a normal distribution using the estimated standard deviation of the total cars on each road. <br>

<h2>Data</h2>
<table>
| Road   | 1  | 2  | 3  | 4  | 5  | 6  | 7   | 8  | 9   | 10  | 11 |
|--------|----|----|----|----|----|----|-----|----|-----|-----|----|
| Number | 87 | 71 | 82 | 68 | 97 | 56 | 238 | 77 | 169 | 167 | 84 |
</table>
S of x = 57.05
