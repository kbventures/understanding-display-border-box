# understanding-display-border-box

Understanding why a lot of people use display: border-box

# Youtube:

Courty Of Web Dev Slimplified
https://www.youtube.com/watch?v=rIO5326FgPE

# Theory:

Default box model: margin collapses when next to other elements.
Ie: they share the one with the largest margin.

Default box model, calculating height/width of box includes
Height/Width, padding and border \_ 2(assuming they are the same);
Margin doesn't account into the size of an element.

Display: border box on the other hand makes the height and width the property that make the the size of the element. The padding and border are substracted instead of added. So your dimensions of height and widht don't change and your element inside gets the remainder of the space stemming from the substraction.
