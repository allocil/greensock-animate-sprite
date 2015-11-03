# Greensock animate sprite
jQuery plugin for animating an spritesheet using greensock library.

## Usage

Add jQuery script.
Add halloween-me.js script.
Use it `$("#container").halloweenme();`

## Options

###image
image url

###speed
animation speed in ticks

###array
spritesheet positions array.

###rotateSpeed
Sprite sheet rotation speed in ticks.


## Example
```javascript		
$("#container").halloweenme();
```
```javascript		
$("#container").halloweenme({
	image:"img/ghost.png", 
	imageWidth: "32px",
	imageHeight: "50px",            
	array: ["0px 0px", "-32px 0px", "-64px 0px", 
			"0px -50px", "-32px -50px", "-64px -50px",
			"0px -100px", "-32px -100px", "-64px -100px",
			"0px -150px", "-32px -150px", "-64px -150px"],
	speed: 10,
	rotateSpeed: 2
});
```
```javascript	
$("#container").halloweenme({
	image:"img/bcat2.png", 
	imageWidth: "400px",
	imageHeight: "200px",            
	array: ["0px 0px", 
			"0px -200px", 
			"0px -400px", 
			"0px -600px",
			"0px -800px",
			"0px -1000px",
			"0px -1200px",
			"0px -1400px",
			"0px -1600px",
			"0px -1800px",
			"0px -2000px",
			"0px -2200px"
		],
	speed: 3,
	repeatDelay: 5,
	rotateSpeed: 0.4
});
```
