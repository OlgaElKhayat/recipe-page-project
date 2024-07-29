<a href="recipe-page.html"></a>
<a href="recipe-stylesheet.css"></a>


1. First I began by setting the structure by using divs. First I made one div ('container') that will hold the rest of the divs together, and center them in the middle. I divided this div to 5 divs all together: there was a div each for the imgae, header, preperation time, ingredients, instructions and nutrition. 
2. To structure my page as shown on the reference picture I set the body to display: flex, and then centered it both vertically and horizontally.
3. I then edited the contair div so that it was also a display flex and gave it a column direction.  
4. Then  insertied the recipe image and editing it until it looked fairly similar to the image. I changed the width and border-radius, also it margins. 
5. I downloaded the fonts: Origin and young serif and inserted it into my html.
6. I edited my second div, which was the header diveded intp to <p></p>, one of which was the title and the other was the intro. 
7. I edited their font-families, sizes, color, weight and height lines, until they looked like in the reference. 
8. When creating the preperation-time section I had to make another container div so that I can edit the rest of my <div>s and <p> without affecting the overall structure of the title and bullet list. I also used a special <ul> unorganised list element to crate my bullet list. 
9. // cpoy 6 but this time for my third <div>.
10. I yet again created a <p> <ul> for my ingredients secion into my fourth div. I also edited this one using css so that it looks like in the image.
! to edit bullet points is li-name::marker.
10. I then created a new <div> so that I can place my <hr> (divider line) in. 
then I used css to edit it as following: 
hr {
  border: none;
  border-top: 1px solid  hsl(30, 18%, 87%);
  width: 680px;
  margin-top: 0px;

} and it looked pretty accurate,
11. I mostly repeated the steps for Ingredients to create my Instructions section, but instead of using a <ul> (bullet list) I used <ol> to create a number list. 
12. Created another <hr>, divider line.
13. Nutritions was the section that I ran into a brick wall. For some reason I struggled to create the items in the grid to align between the <hr> lines. In the end I settled on a similar but not exact copy of the table. <!--Will come back to it, when my skills have broadened-->


Colors: 

- Nutmeg: hsl(14, 45%, 36%) - ingredients, instructions, nutritions
- Dark Raspberry: hsl(332, 51%, 32%) - preperation time
- Rose White: hsl(330, 100%, 98%) - 
background of preperation time
- Eggshell: hsl(30, 54%, 90%) - 
body background color
- Light Grey: hsl(30, 18%, 87%) - 
divider lines
- Wenge Brown: hsl(30, 10%, 34%) 
not bold text in <ul></ul>
- Dark Charcoal: hsl(24, 5%, 18%) -  highlighted parts (bold)

Font-families: 

1. Young serif, arial
     <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Young+Serif&display=swap" rel="stylesheet">

2. "Outfit", sans-serif;
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Outfit">

    !Remember to use ""