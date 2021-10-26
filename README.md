<h1>ASSIGNMENT 4:</h1>

<h2>Please find below the pointers that I have worked on as part of this assignment;</h2>


<h3>Important NOTE:</h3>
<b>* Since this is a single web page, all the anchor elements are pointing to the same webpage.</b><br>
<b>* Since there is no server side component to this webpage, all the forms in the webpage are using the "GET" method instead of the "POST" method, since "POST" won't be     	   supported.</b><br><br> 


1. Learnt about styling elements using `sass` and `scss`.

2. `scss` constructs used are as follows;
	* <b>mixins():</b>
	  * I used mixins in sections where I found that a lot of attributes had to be re-writted. So, I made the below mixins;
		* `@mixin positionRelatively($top, $left)`: This mixin positions the element relatively in the document.
		* `@mixin resize($width, $height)`: This mixin resizes the element based on the values of height and width provided.
		* `@mixin transitionHoverColor($delay)`: This mixin add a bit of transition on hover effects. It is mostly used for consmetic purpose and is optional.
		* `@mixin borderCreator($border, $border-radius, $fillcolor)`: This mixin will create a border for the element based on the input parameters.
		* `@mixin buttonHover($button-type)`: This mixin will add a customer hover effect to the button based on the type of the button.

	* <b>functions():</b>
	  * I used functions in sections where I found that a some logic would be required to return the required attribute;
		* `fetchShadeOfBlue($shade)`: This functions fetches different shades of blue.

    * <b>control-statements():</b>
       I used `@if`, `@else if` and `@else` statements in <b>functions</b> and <b>mixins</b> to add a conditions based on the input parameters.

    * <b>variables:</b>
       I used variables for the attributes that were most commonly used such as  `font-family`, `color` etc..
       
    * <b>Maps:</b>
       I used maps in order to group some similar set of variables together.
       
    * <b>Loops:</b>
       I used `for` loop to iterate over all the sections of the page and add a padding value to them.
       
    * <b>Math Operations:</b>
       I used addition and subtraction operations in the footer element to keep the anchor links there equidistant from each other at all times.
      
3. `Layouts` used are as follows;
	* <b>Grid Layout:</b>
	  * I used `grid-layout` to position all the sections of the page which are `header`, `section-1`, `section-2`, `section-3`, `section-4`, `section-5` and the `footer`.
	  * Further divided a few sections into grids for laying out each elements in each section.
	
    * <b>Flex Layout:
      * Used flex layout for the main form.
