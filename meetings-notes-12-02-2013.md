#Meeting Notes 12-02-2013

1. Weekend Recap
  * OOP baseline for WP theme Friday night & Sunday
  * Design Stuff yay
2. Should we have a vertical and horizontal nav? Should we have a secondary navigation bar?
  * Yes, one nav deep
  * Specific vs unspecific content
  * Main nav is straight text, not accordion
  * Keep secondary nav on page 
  * Template parts/modules - can create a links template
  * Quick links study - putting content at the top
  * Instructions on how to hide it!
3. Should we have an option for sidebar to fall in line?
  * JQuery does do the sidebar animations, even pretty far back in IE
  * Transition from theme customizer option to comment in/out
4. IE8 Implementation
  * Percentage of users: 35% of IE users are on IE8 (15-20% of internet)
  * Should we ignore this? Same % of people that are using WP...
  * Respond.js, CSS Pie (?) to fake it at first, but this makes it heavy
  * Preference: Mobile first strategy (constrained width single column layout)
  * Give developers a head start with a vanilla theme, supporting IE8 is too much (you can always do it yourself if you want to)
  * Modernizr/Media Queries
    * If IE8 display warning/update, also test media query support and add class to wrapper div that constrains the width to ~600px 
5. "Leading the Trend"
  * Supporting best practices in speed, OOP, design, etc
  * Josh on performance: "I have an old phone, it's not even 3G, it can't be slow"
    * Think about global/internet implications as well
    * Minimize use of JQuery as well for page load
    * Sping theme on our servers: 80/100 Google Page Speed goal for mobile and desktop (under 250ms response time)
6. Tangent about support! Woo!
7. Sassquatch in use/launched in the real world!
