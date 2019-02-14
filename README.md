# portfolio
## 1.	Responsive design

I created three media queries as follows:	 (max-width: 700px), (min-width: 1200px), (orientation: landscape). 

When the viewer’s device-width is under 700px, every item is list in one column,the position of Header and Navigator bar moved to the center.
When the viewer’s device-width is between 700px and 1200 px, the header and the nav-bar is list on the left and right side of the page. And all the item of main page is placed in two columns.
When the viewer’s device-width is larger than 1200 px, the main content is list three to four columns and the title and nav-bar moved to the center.
When User use cellphone and change the orientation to landscape, the main content will change and the column will increase to two.

Besides that, the selfie under the contact page will disappear when the viewer’s device-width is less than 700px.

## 2.	Grid and flex box.

Grid Location: header and navigation bar in four page, The first paragraph in contact page, the lightbox in travel page.
Flex: the main content in app and tech page.

Grid was implemented to separate the different part for nav-bar and header. And under the navbar container, the position of four nav a tag was arranged by using flex. By doing that, the header and nav bar is on the same row on left and right side of the page while the nav tag have the same distance to each other. 

All the image of the main content is displayed with flex. Flex was implemented to adjust the main content automatically so that the page will display suitable columns to corresponding device’s width.

## 3.	javaScript/ jQuery

1.	lightbox of the travel page (improved based on the Homework)
On the travel page, I used JavaScript code from Homework and wrote CSS html by myself. By click the button, the image will display on different groups/order. And by click each picture, the image will display individually.

2.	contact container of the contact page (wrote myself)
The contact form only shows when the button(Interested in contact) is clicked.

## 4.  Checked with W3C and aXe. There are some aXe Color contrast issues that have a "We are not sure".

## Extras:

Ligtboxes: I have to learn the mixitup functions so that I can rearrange the displayed orders of photos and also I have to figure out how to add the correct title for each images as well as how to separate them in different groups. And at first I didn’t notice that we should attach the a tag and image tag with the same img-url.


