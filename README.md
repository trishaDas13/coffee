# coffee
<hr>
<h1>hosting link: </h1>
https://trishadas13.github.io/coffee/
<hr>

![image](https://github.com/trishaDas13/coffee/assets/126088849/3a50e1b3-3458-40ed-b6de-a55d823358a5)
![image](https://github.com/trishaDas13/coffee/assets/126088849/cc03c68b-5b7d-44bf-b130-7e3a79daf70e)

The provided HTML code represents a "div" element with the class "top." This element can be used to create a container or section within a webpage. However, since this code snippet is very short, it doesn't contain any content or attributes to provide further context about its purpose or styling. It's common to see such elements used as placeholders or markers for future content or layout.

![image](https://github.com/trishaDas13/coffee/assets/126088849/b31f8cd2-df29-4218-8e6c-052e85063284)

The universal selector (*):

Resets margins, padding, and box-sizing to ensure consistent styling across elements.
Sets the default font family to 'Roboto', a sans-serif font.
The .container class:

Sets the width to 100vw (viewport width) and the height to 100vh (viewport height).
Creates a container that spans the entire width and height of the viewport.
The .top class:

Sets the width to 100% and the height to 25% of the container's height.
Applies a background color of RGB(254, 254, 254), which is a very light shade of gray.

![image](https://github.com/trishaDas13/coffee/assets/126088849/8a0fe88a-34c6-4d5c-bd87-53e089f171f1)
![image](https://github.com/trishaDas13/coffee/assets/126088849/de3e8995-ec00-4b44-9165-5c95d5375712)

The given HTML code includes a "div" element with the class "bottom." Inside this "div," there's another "div" with the class "img," and within the inner "div," an "img" element is used to display an image.

Here's a breakdown of the code:

The outermost "div" with the class "bottom":

This div serves as a container for its contents.
Inside the "bottom" div, there's a nested "div" with the class "img":

This inner div can be used for styling purposes or additional layout control.
Inside the "img" div, there's an "img" element:

The "img" element displays an image.
The "src" attribute specifies the image file's source (./coffee.webp).
The "alt" attribute provides alternative text that is displayed if the image cannot be loaded.
This code structure appears to be a part of a webpage layout, possibly displaying an image related to coffee or some other content.

![image](https://github.com/trishaDas13/coffee/assets/126088849/9871798d-c534-4733-aa64-7d952f88ad18)

The .bottom class:

Sets the width to 100% and the height to 75% of the container's height.
Applies a background color of RGB(240, 197, 11), which is a shade of yellow.
Uses the position: relative; property, which makes the element a reference point for positioned child elements.
The img element:

Sets the width to 30% of its containing block.
Sets the height to 95% of its containing block.
Uses position: absolute; to position the image within its nearest positioned ancestor (in this case, the .bottom element).
Uses top: -15%; to move the image upward by 15% of its own height.
Uses left: 5%; to move the image to the right by 5% of its own width.
These styles add a .bottom section with a yellow background color and position an image within it. The position: absolute; property is used to control the precise positioning of the image relative to its containing block, and the top and left properties adjust its placement.


![image](https://github.com/trishaDas13/coffee/assets/126088849/8017b41e-fb60-41b8-8503-9c0fda743e05)
![image](https://github.com/trishaDas13/coffee/assets/126088849/2831ad20-db97-4147-9f9e-75c36053048b)

The "div" element with the class "para":

This div serves as a container for the content in this section.
Inside the "div," there's an "h1" element:

This heading displays the text "Certified Coffee Courses."
Following the "h1" element, there's a "p" element:

This paragraph contains Lorem Ipsum text, serving as a placeholder for actual content.
It talks about courses and other details.
After the first "p" element, there's a line break ("<br>") to create some space.

Another "p" element follows:

This paragraph provides attribution information for the image source, mentioning "Image from Freepik."
Another line break ("<br>") is used.

There's a "button" element:

This button can be used for actions like "LEARN MORE."

![image](https://github.com/trishaDas13/coffee/assets/126088849/e77fb5fb-a110-4f88-a043-c6759aeb8fc7)
![image](https://github.com/trishaDas13/coffee/assets/126088849/bf660c4c-86b9-41b3-8340-dfa904ce7f1c)

The .para class:

Uses position: absolute; to position the element absolutely within its containing block.
Uses top: 40%; and left: 65%; to position the element 40% from the top and 65% from the left of its containing block.
Uses transform: translate(-50%, -50%); to horizontally and vertically center the element using a translate transform.
Sets the font size to 20px.
Sets the width to 30% of its containing block.
Uses text-align: center; to center-align the text content.
The h1 element within .para:

Sets the font size to 40px.
Sets the font weight to 500.
Adds a margin at the bottom of 20px.
The p element within .para:

Sets the font size to 12px.
Sets the font weight to 700.
Sets the line height to 23px.
Uses the span selector to target and style the underlined text with a cursor pointer.
The button element:

Removes the default border and outline styles.
Sets the background color to black and text color to white.
Adds padding of 3% vertically and 10% horizontally.
Sets the font weight to 300.
Sets the cursor to a pointer.
Adds a black border of 2px.
On hover, changes the background color to transparent, the text color to black, increases the font weight to 600, and adds a transition effect.

<h2>Media Quarry</h2>

![image](https://github.com/trishaDas13/coffee/assets/126088849/a6e80dff-da1f-45b4-96f7-9da633155e80)

@media screen and (max-width: 700px) { ... }:

This media query targets screens with a maximum width of 700 pixels, indicating smaller screens or mobile devices.
.bottom within the media query:

Overrides the height property to make the .bottom section take up the full height of its containing block.
img within the media query:

Overrides the width property to make the image width 80% of its containing block.
Overrides the height property to make the image height 40% of its containing block.
Adds a margin-left of 3% to provide some spacing on the left side of the image.
.para within the media query:

Overrides the left property to center-align the .para element horizontally by setting it to 50%.
Overrides the width property to make the .para width 80% of its containing block.
Overrides the top property to position the .para element 45% from the top of its containing block.
.para > p within the media query:

Overrides the font-weight property to set the font weight of the paragraph to 400.

<hr>
<h1>Full webpage view:</h1>

[screen-capture.webm](https://github.com/trishaDas13/coffee/assets/126088849/6602c73b-63da-44d9-897d-d0d32e4e58d8)
