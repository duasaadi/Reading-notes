 CSS Layouts:
Css traets each element from HTML as a box that run in two ways inline element flows in between surronding text and  block-level element starts a new line ,usualy one block level elment positioned inside another block element then outer block-element known as a container o parent element and this help targeting all elements inside.
**position**
CSS allows you to control a layout of the page by specific schemes those are normal flow ,relative and absolute 
![position](/img/position.PNG)
as an indication of box's position, those positions are :
* Fixed position :This is a form of absolute positioning that positions the element in relation to the browser window.
* Floating :Floating an element allows you to take that element out of normal flow and position it to the far left or right of a containing box

moving element from normal flow, boxes can overlap. The `z-index` property allows you to controlwhich box appears on top.
# Screen Sizes:
Different visitors to your site will have different sized screens that show different amounts of information, so your design needs to be able to work on a range of different sized screens.Because screen sizes and display resolutions vary so much, web designers often try to create pages of around 960-1000 pixels wide.
Fixed width layout designs do not change size as the user increases  or decreases the size of their browser window. Measurements tend to be given in pixel and it has advantages and disadvantages:
**Advantages**
* pixels are accurae to control size and position
* designer can control apperance and postion ith liquid layout.
* controling the lengths of lines of text regardless of the size of the user's window
* size off images always remain the same.

**Disadvantages**
* ending with big gaps around the edges of pages.
* user's screen's resolution is higher so page can end up with smaller text which is harder to read.
* if user want to icrease the size of font it might not fit in the space.
* design works best on devices that have a site or resolution similar to that of desktop or laptop computers.
* The page will often take up more vertical space than a liquid layout with the same content.

# Liquid Layout Design 
Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window. They tend to use percentages.
main advantages that the page expand to fill all beowser's gaps, and if user's have smaller window they don't have to contract or scroll the sides ,and the designer will have results that are tolerant and larger than the intendation.
Howver this also have disadvantages, designa differ from intendation if you didn't control the width of the elements,lines of text cn be longer with user making it harder to read.