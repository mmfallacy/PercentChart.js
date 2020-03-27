# PercentChart.js

PercentChart.js is a Javascript library for creating circular percent graphs.

## Installation
Download the js and css files and include in source code

## Dependencies

Jquery.js

## Usage
```Javascript
let options =  {
            delay: '.2s',
            textDuration: '.1s',
            chartDuration: '2s',
            easing: 'linear',
            data:{
                percent:0,
                actual:0,
                unit:"UNIT"
            },
            enableHover:true,
        }
var chart = new PercentChart("container", options)
```