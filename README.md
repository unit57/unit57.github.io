

#ABOUT ME#
__________

To make this page I used HTML and CSS


##Set Up##
__________

First I whitedboarded it (without a white board, but paper and post-its so same thing)

I wrote up the layout I wanted(based mostly on the first example given in the homework) and thought about what images I needed.
I needed icons for the contact info on the bottom and pulled some pictures from my desktop for some other ideas I had for the projects section.

Next I set up my folders and files.

After that I used emmet in sublime text to make the structure - a lot changed as I went along but here is the initial code:

!>nav>p+a*3^div#about>article.text+div#picture^div#projects>article.text+div.notsureyet^footer

It took about 2 hours from starting to this point.

-------------------------------------

##The site##
____________


###Navbar###
____________
I have a fixed nav bar that links to the Id for About and for Contact

I tried linking Projects the same way but the css wouldnt work on that div. I'm not sure why. I ended up using class instead so I can style the projects div, but then I could not link it to the nav bar. So right now that link is empty.

Also I had a lot of trouble setting this up. I had a white space above it where you would see the body when scrollling. On stack overflow I fould th best way to fix that was to get rid of the body margin and padding. and while that worked to cover the space the nav was floating over the about. 

Initialy I found that if I added a top marging to body it leveled out and the about didn't collapse under the nav. I dont know why but after continuing to style, that stopped working. I had to add a empty div as a spacer to keep that from collpsing again.

I dont like the spacer because when I hit the about nav link, the nav will cover the top of the about again! 

I was happy however to have the hover psuedo code work on the nav bar.



-------------------------------------

###about###
___________
I have an About div that contains one article and one image. The image is floated right. 

I had to give the article a fixed height because the about div was collpaing to the text height and the image was sticking out into the div underneath it. I tried using clearfix, but it didn't work, I'm not sure what I was doing wrong. 

It was at this point that I realised I really need some help with positioning in general.


###Projects###
______________

The next box is projects. Probably not the best title. My idea here is that eventually I would link to projects on git hub. For now I noted my propherial skills related to web design. 

The video on the right is one that I edited. I had trouble - like with the image above - with positioning it next to the text ( I still dont like how they colapse when I make the page smaller).

I added links in the text to show off some other related work that I've done. I dont think it was the best way to show it, but I wanted to see if relative links worked in this form. I was happy to see that it did. Also, since I was having such trouble with positioning the images and the other divs, I just wanted to leave everything where it was.

###Contact###
_____________
These were pretty easy to link and size, I got them from iconmonstr.com


It took about 6 hours to do the layout and initial style
and about another 4 add some content and re-style it

So total time not including figureing out githubpages again and writing this up was ~ 12 hours



| Wins            | Losses               |
| --------------- |:--------------------:|
|emmit            |div positioning       |
|styling css      |clearfix              |
|html organization|css organization      |
|googling things  |getting any JS to work|


One last note. I had initially had a div wrapping the whole thing with the Id of container.

I added some css to it but decided later that I did't want to use it. I deleted it from the HTML and had no problems, but if I delete the css for the id the lay out changes.  

