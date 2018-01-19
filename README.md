# D3_GDPAndLifeExp
The purpose of this project is to recreate the GapMinder World visualisation	using	d3.js
The project incorporates:
* A	bubble plot representing the countries of the world
* Countries of the world described by GDP and Life Expectancy, and mapped	to x-axis and y-axis positions
* The	population of each country mapped to bubble area
* Continents differentiated by colour and labelled via tooltips

The user can:
* View data	for a particular year
* Animate	the	change in	country	statistics from	year to	year (Edit: Data for 10 year periods up to 1950)

The	data required to drive this visualisation is available in the file:	
**Gapminder_All_Time.csv**

The	fields in	this file are	as follows:
* Country:	The	country	name
* Year:	The	year	for	this	data	observation
* Population:	The	population	of	the	country	in	this	year	
* LifeExp:	Average	life	expectancy	in	years
* GDP:	Average	GDP	in	inflation	adjusted	dollars
* Code:	The	country	code
* Region:	The	region	in	which	the	country	belongs	(similar	to	continent)
* Area:	The	area	of	the	country	in	square	kilometres
* Coastline:	the	number	of	kilometres	of	coastline	belonging	to	the	country
* Government:	The	type	of	government	in	the	country

Two	bar charts to the right of the visualisation show:
* **number of countries	per	region** 
* **number	of countries with each government	 type**

These	update as	the year is changed (changes are minimal however).
