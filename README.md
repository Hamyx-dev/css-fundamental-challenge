### CSS Fundamentals — Exercises & Reflections

This is what I did after completing the lessons on HTML and CSS.

## CSS Method Showdown

# Exercise 1

1. The paragraph currently displays "orange". This is because CSS follows a strict format called specificity prioritizing the direct styling in the html which overrides the internal and external styling so therefore inline css wins the rule.
2. I added the line of code to an external CSS file and it overrided the inline CSS because I used the !important declaration to increase the specificity of the external CSS.
3. It is not possible because inline CSS overrides internal CSS and this is because inline CSS targets the element directly, so the color still remains orange.

## The Broken Stylesheet

# Exercise 2

1. I added the opening curly bracket to body selector in the css
2. I added a semi-colon to the color styling in the h1 selector inside the css
3. I added colon to the font-size styling in the h1 selector inside the css
4. I added href attribute in the css styling link inside the html
5. I added comma to seperate the numbers of the rgb in the color styling in the p selector iside the css
6. he relation in the google font link was given a style so I changed it to stylesheet for the font to take effect

## Color Format Detection

# Exercise 3

1. color: #ff0000;
   color: rgb(255, 0, 0);
   color: hsl(0, 100%, 50%);
2. rgb(255, 0, 0) gives a fully red background meaning it gives 0% transparency and 100% solid color and also the channels are red, green and blue while rgba(255, 0, 0, 0.5) gives a 50% semi transparent and has a see through red and it also has red, green and blue but has the alpha channel which is the level of opacity for the color.
3. color: #000000 is black and its RGB is color: rgb(0, 0, 0)
   color: #ffffff is white and its RGB is color: rgb(255, 255, 255)

## Styling A Press Release

# Exercise 4

The line through added to the h2 cancelled it out and its wrong because it indicates deletion or cancellation.

## Predicting The Output Of The Codes

# Exercise 5

- Scenario A

1. The color of the text is blue
2. Yes, the text is underlined
3. The text is aligned right
4. h1 is a header with a sentence say "Hello World" color:blue changes the text color to blue, underlines the text and shifts it to the right side of the screen

- Scenario B

1. It uses poppins
2. Hex=33 Math=(3\*16)+3 =51, All three pairs are 33 so result is rgb(51, 51, 51).
3. The p will use the poppins font because the p sits inside the body and the body is using the poppins font

- Scenario C

1. h1 ends up with the blue color
2. This is where the cascading rule comes in. The browser reads from top to buttom and the rule written last overwrites the previous one
3. This demonstrate Cascading rule

body {
background: #e8f4f8;
}

## Conceptual Deep Dive

1. HTML is the structure, CSS is the decoration in a sense that html is a markup language so it uses tags like <p>, <h1>, <em> and attributes like href for links and it the foundation or backbone of every webpage. CSS on the other hand makes the webpage look appealing allowing you to seperate content from design.
   If you are trying to build a house using only css it would not work. This is because css is just a styling language and not a structure language. It cannot create elements, it can only describe how existing elements should look. So if you try building a house with no foundation or walls, it would not be possible because there are no walls to decorate.
2. So lets say I am a developer at Bank Of Ghana and a website of 200 pages contains documents, press releases and the others. Now each of the page has a navbar and all the navbars has inline css. One afternoon the supervisor just walks in to tell me I should redesign everything with let say mediumgray instead of brown.
   Now what happens is that I have to open all the 200 html files one by one, find every single place I styled the background and change each manually. So one line has about 30 inline style attributes and I miss like 7 of them. Now some of the pages show pink, some show red. The website looks broken and the Governor keeps calling.
   But with the external I open one file and name it (style.css) and just change one line. I will just save and all the 200 pages updates in seconds.
3. The color here will be green because CSS uses the cascading rule which means the rule written last overrites the previous one.

4. - For the named colors it is easily read

- For hex is a universal language between designers and developers making it easy to copy straight from the brand guide into the css
- For RGB you can manipulate each channel with logic so you dynamically change a color unlike hex which cannot do that without conversion
- For hsl, it matches how we think about colors. We have the hue, saturation and how dark or light a color is. It makes building consistency theme much easier

None of the formats wins in every situation.
