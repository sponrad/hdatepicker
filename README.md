hdatepicker
===========

hDatePicker - horizontal javascript datepicker

## About
hDatePicker is a javascript library that creates a datepicker that lays out flat horizontal and is responsive. 

It is used in [Daypage](http://www.daypager.com).

## Features
* Automatic current day selected
* Forward and backward month buttons
* Days in month are calculated
* Adds CSS classes for most of the elements
* CSS class for current day
* CSS class for selected day
* CSS class for weekend days, for styling

## Usage
Initialize it on any div:

'''html
<div id="hDatepicker"></div>
'''

'''javascript
hDatepicker( $("#hDatepicker") ):
'''

Provide some actions for what happens when a date is selected:
'''javascript
hDatepicker( $("#hDatepicker"), {
  onDateSelect: function(date){
    //Do stuff
  }
});
'''