# Activity_One_Code_Refactor

The purpose of this project is to fix a website that is not accessible to all end users, in addition to cleaning up some legacy code. The code ,while working for the most part, is not clean and has many duplicate css classes that cause confusion and slow down the ability to rapidly deploy information. 

I have made the following updates: 

HTML: 
1.) <head> I added in the charset, meta name and scaling, in addition to providing a content description of what Horiseon Social Solution Services does. 
2.) Added a wrapper to encompass the benefits sidebar which allows it to go down to the footer. 
3.) <header> I cleaned up the links in the code itself and fixed the search engine optimization link that was not working. I also added in an accessibility title to help understand what this portion was and to encompass it as a navigation element. 
4.) .Hero I changed to a more descriptive banner image and provided the accessibility description of the picture. 
5.)  <Content> I changed it to have a consolidated class, since all of them were the same CSS, added in alt description for the images. I also changed the spacing in the HTML for the paragraph, to make it easier to read the HTML. 
6.) Benefits I consolidated into a single class, added in alt descriptions for the images and changed the spacing in the HTML paragraph to more easily read it. 
7.) <Footer> I made it into an actual footer element and changed the H2 to H3, since elements above it were already H3. 
  
 
 CSS: 
 1.) Consolidated the content classes from 3 down to 1
 2.) Consolidated the benefit classes from 3 down to 1
 3.) Removed the float/left right classes and just assigned the specific elements their float properties. 
 4.) Added in a wrapper, so that the benefits sidebar could reach the footer. 
 5.) Consolidated the triplicate H1,H2,H3 classes into single H1, H2, H3 classes
 6.) Added padding as necessary to clean up the text on the benefits sidebar
 7.) Added additional margin to benefits sidebar, so it was closer to the content and had a matching width on both sides. 
 8.) Changed ids to classes where appropriate
 9.) Renamed hero to bannerimage for clarity
 
