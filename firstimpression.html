<!DOCTYPE html>
<html>
  <head>
    <meta charset="UTF-8">
    <style>
    </style>
  </head>
  <body>
  	<script src="http://d3js.org/d3.v3.min.js" charset="utf-8"></script>
    <script>
    	var chart_area = 
	    	d3
	    		.select('body')
	    		.append('div')
	    		.classed("chart_area", true)
	    	;

    	var RANDOM_MIN = 0; var RANDOM_MAX = 100;
    	var CHART_WIDTH = 500, CHART_HEIGHT = 300;


    	function irand(lo, up){
    		return Math.floor(Math.random()*(up-lo+1)+lo);
    	};

    	var data = [];

    	for (i=0; i <10; i++){
    		data.push(irand(RANDOM_MIN, RANDOM_MAX));
    	}


    	var widthScale = d3.scale.linear()
    		.domain([
    			d3.min(data, function(d, i){return d;}),
    			d3.max(data, function(d, i){return d;})
    		])
    		.range([0, CHART_WIDTH])
    		.nice()
    	;

    	chart_area
    		.selectAll('div')
    		.data(data)
    		.enter()
    		.append('div')
    		.classed('bar_area', true)
    		.style('background-color', 'hsl(240,50%,75%)')
			.style('height', '20px')
			.style('margin', '2px 0px')
			.style('width', 0)
			.transition()
			.duration(750)
			.style('width', function(d,i) { return widthScale(d) + 'px'; } )
			.text('String')
    	;

    	var hAxis_area =
    		d3
    			.select('body')
    			.append('div')
    			.style('position', 'absolute')
    		;

    	var ticks = widthScale.ticks(10);

    	hAxis_area
    		.selectAll('span')
    		.data(ticks)
    		.enter()
    		.append('span')
    		.style('position', 'absolute')
    		.style('left', function(d,i) { return widthScale(d) + 'px'; } )
    		.text(String)
    	;



    </script>
  </body>
</html>
