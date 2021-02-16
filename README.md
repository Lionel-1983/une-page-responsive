# une-page-responsive


HEADER


Header, a background image in the header, slogan and menu are arranged via the absolute position. 

The menu is in fixed position with zero as top, left, right and bottom values.

The use of vh and vw values is interesting in this case, as it adapts to all the actual sizes of the screens that display 

the page.


MAIN, SECTION "specialites"


From here we use a layout grid made with the Flexbox model.

In the classes of each article their behaviour is defined exactly according to the screen width : 

So the first element occupy 12 units wide for a small and medium but 6 units for the widest screen size.

One element occupy six units in medium and four for the widest screen, 

whereas another can use four in medium and three for the widest screen.

The grid allows us to vary very easily the place occupied by our elements.


MAIN FORMULAIRE


A background image on the form and a clear background on the actual area of the form with transparency and border-radius.

Here again the grid is a great help for our layout.


FOOTER


The grid allows us to vary the layout according to the width of the screen.

we will note the border-left to make the left square and the transparent color to highlight the text zones.



GRILLE VERTICALE ( VERTICAL GRID )


the basic unit is 1.25 em, that we can divide between the high and low margin as on the form.

We multiply as for the title tags.


MEDIA QUERY

Two media queries : the first starts at 655px and the second at 955px.








