@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@
@	Fridge Magnets
@	========================================
@	Written by: Kevin Yu, 2016
@	link: https://github.com/everynewyear/FridgeMagnets
@
@	
@	Movable HTML elements. Positioned/movable browser-side via
@	JavaScript, stored and reaccessed via AJAX and PHP.
@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@
@	Table of Contents
@	========================================
@	1. Change Log
@	2. Specifications
@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@

========================================
1. Change Log
========================================

June 5, 2016
- initial build, wrote up all the important things for note
- created basic HTML page with elements
- will need to give everything positional etc’s via CSS next


========================================
2. Specifications
========================================

HTML
- has several elements on page
- all movable elements have class “fridge”

JavaScript
- can move elements with DOM, click and drag
- catches new position of element, updates element

AJAX
- when element position is changed, sends to mySQL to store location

PHP
- on page load, check which user is on page
- if user has custom element positions, load them from mySQL

SQL
- stores user information and their element positions
