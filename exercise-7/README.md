## Conceptual Deep Dive
1. HTML is the structure, CSS is the decoration in a sense that html is a markup language so it uses tags like <p>,<h1>,<em> and attributes like href for links and it the foundation or backbone of every webpage.Css on the other hand makes the webpage look appealing allowing you to seperate content from design .

If you are trying to build a house using only css it would not work. This is because css is just a styling language and not a structure language.
It cannot create elements ,it can only describe how existing elements should look.So if you try building a house with no foundation or walls, is would not be possible beacause there are no walls to decorate.

2. So lets say I am a developer at Bank Of Ghana and a website of 200 pages contains documents,press releases and the others.Now each of the page has a navbar and all the navbars has inline css.One afternoon the supervisor just walks in to tell me I should redesign everything with let say meduimgray instead of brown.
Now what happens is that I have to open all the 200html files one by one ,find every single place I styled the background and change each manually.So one line has about 30 inline style attributes and I miss like 7 of them.Now some of the pages show pink,some show red.The website looks broken and the Governor keeps calling.

But with the external I open one file and name it (style.css) and just change one line . I will just save and all the 200 pages updates in seconds

3. The color here will be green because CSS uses the cascading rule which means the rule written last overrites the previous one

4. - For the named colors it is easily read
- For hex is a universal language between designers and developers making it easy to copy straight from the brand guide into the css
- For RGB you can manipulate each channel with logic so you dynamically change a color unlike hex which cannot do that without conversion
- For hsl,it matches how we think about colors.We have the hue,saturation and how dark or light a color is.It makes building consistency theme much easier

None of the formats wins in every situation

