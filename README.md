# udemy-bootstrap-TinDog
Dribble is an amazing site to look upto for inspirations for your own website
Sneakpeekit is a site for making your own prototypes


So if you had two stylesheets e.g. styles1.css and styles2.css which both target the same element e.g.

styles1.css

body {
background-color: red;
}
styles2.css

body {
background-color: blue;
}
If inside the head section if your HTML, you list your links as this:

<link rel="stylesheet" href="styles1.css">
<link rel="stylesheet" href="styles2.css">
The resulting page will be blue.

But if you listed your links like this:

<link rel="stylesheet" href="styles2.css">
<link rel="stylesheet" href="styles1.css">
The resulting page will be red.

Essentially both styles are being applied, but the one that's visible at the end is the one applied last.



So following that logic, if your custom styles are not overriding the bootstrap styles, all you need to do is move the link to your custom stylesheet to a line after the bootstrap CDN link:

<link href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" rel="stylesheet">
<link rel="stylesheet" href="css/styles.css">
This means that you first load the default bootstrap styles, then you can override some of those components with your own custom CSS.

Unlike CSS and JavaScript, HTML code is executed from top to bottom so the order of your code matters.

###### use font awesome website to use fonts in buttons etc######

@@@@ Bootsnipp for taking snips of interesting codes for a part of your project @@@@@

^^^^^for using z-index you need to stack the elements/divs and for that use position:absolute for the parent element
also z-index=1 is topmost 0 is middle and -1 is bottom div ^^^^

**laptop's screen size: 1200 X 264 px tablet's screen size: 880 X 264 px**

CODE REFACTORING
1. Readability
2. Modularity
3. Efficiency
4. Lenght

For selectors of the same heirachy : selector1, selector2 {  } 
For heirachial selectors: selector1 selector2 {  } read from right to left  
The selector on right is the child of the selector on left.
For combined selectors: selector1.selector2 {  } OR selector1#selector2 {  }


**Refactoring part 2 is based on whether the section is coloured or has a white background**
**On this basis all the sections are given a related class**

---Adobe color pallete can be used for better understanding of the color theory----
|||||Use colorhunt.co for even better color palette suggestions|||||

The ideal size of a block is approximately ~34 characters in a line.

Site link: https://distracted-euler-c6526d.netlify.app/
