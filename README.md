Mine Sweeper Game
======================================

A Minesweeper game written in JavaScript, HTML and CSS.

## FEATURES
--------

* Configurable grid size
* Configurable number of mines


## HOW TO USE
---------------
 
 ```
     just include `minesweeper.js` in html file. 
     
```

## EXAMPLE USAGE:
-------------------
 ```
<div id="mine-sweeper"></div>

<script src="minesweeper.js" type="text/javascript"></script>
<script type="text/javascript">
    MineSweeper.draw({
		container: 'mine-sweeper',
		grid: 5,
		noOfBombs: 5
	});
</script>

```

## CONFIG
---------------

* container // id of element 
* grid // it always show as n * n size grid box
* noOfBombs // No of boms in grid 



 
