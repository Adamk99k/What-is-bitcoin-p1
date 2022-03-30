# Time to learn about Bitcoin !

## Hello there and welcome to my first portfolio project for my [Code Institute Course.](https://codeinstitute.net/)

## Want to have a look at my deployed project?   [What is Bitcoin](https://adamk99k.github.io/What-is-bitcoin-p1/)

<br>

The aim of my site is to simply educate and teach people about what Bitcoin and Altcoins are.  I wanted to create a website that has only the main information about Bitcoin and other crypto currencies without the over-the-top information that is out there on the internet today. <br><br>
I decided to make this website with the intent to make it as simple and easy to follow along as possible. To make this idea possible I made three pages to my [What is Bitcoin? Website.](https://adamk99k.github.io/What-is-bitcoin-p1/)<br>
The first page being the home page. This page includes two informational text sections and another section for quotes about bitcoin. <br>
The second page is about altcoins, this page is made up of just one easy to follow section on altcoins that educate the user. <br>
The final page is a contact page adding even more value to any user who may need help or have questions to ask.
<br><br>
The target audience for my website are all types of people, from the younger generation such as college kids to the older generation such as parents and grandparents that simply want to learn about Bitcoin.
<br>
The idle user for my site would be someone who has never learned about bitcoin and who is a complete newbie to this space as these users will gain the most value from this site. <br>


#

![image](assets/images/readme.img/am-i-responsive.png)

# Features

* Title.  <br> Each page shares the same level 1 title. This is Huge Bold text that tells the user exactly what the page is about, this provides clarity for the user.

* Navigation bar.  <br> All three pages have the same navigation bar with three links referring to each page, Home / Altcoins and contact, this allows the user to have easy navigation throughout the website without having to use the back button on the site.


* Hero image.  <br>All three pages have the same Hero Image that has a 10 
seconds Zoom effect when the website is loaded, This eye catching animation grabs the attention of the user.
![image](assets/images/readme.img/hero-image-readme.png)

#

* Footer section. <br> Each pages footer section has four links to different social media's, These are large icons so that the user will acknowledge them, for the purpose of this project the links take you to the landing page for each social media used.
![image](assets/images/readme.img/site-footer.png)
#

* Hero image text. <br> On all three pages, overlapping the hero image is a text section, Each pages text is different but correlated to what each page is about. These sections provide quick value to the user and gives them a feel for the page there about to check out. 
![image](assets/images/readme.img/hero-image-cover-text.png)
 #


## Home Page

* Clickable link. <br> On the home page there is a question that asks the user if they want to read the original bitcoin whitepaper, if they do there’s a "Click me ..." link that takes you out of the website to the whitepapers site. This grabs the user’s attention by asking them a question then gives them value by making the whitepaper available for them to read.
![image](assets/images/readme.img/question-home-page.png)
#

* Quote section. <br> The Home pages quote section lists five quotes about Bitcoin from some of the biggest CEOs and Co CEO’s in the world. This section is interesting to the user as familiar, influential names are taking positively about the subject there wanting to learn more about, Bitcoin.
![image](assets/images/readme.img/quote-section.png)
#

* Bitcoin, What is it? Text section. <br> The text that is within this section is the fundamental basics of Bitcoin, what it is and how it works. The aim of this section is to educate the user on Bitcoin without over complicating things as bitcoin for newbie's can be confusing. This section also becomes scrollable on extra large desktop screens.
* Facts and Points about Bitcoin, Text section. <br>The aim of this section is to give interesting facts and points about Bitcoin that grab the users attention and fill in some of the questions they may have after reading the first Bitcoin section, such as who Satoshi Nakamoto is. There also is a short story of a pizza worth 10,000 BTC, this is a attention grabbing story that keeps the user interested.
![image](assets/images/readme.img/home-page-text-sections.png)


## Altcoin Page

* Altcoins text section. <br> The Altcoins Page is made up of just one simple text section, this section aims to educate the user on altcoins only providing useful information such as what makes up the word "Altcoin" and not providing useless information such as a list of all the altcoins there are available today.
![image](assets/images/readme.img/Altcoins-text-section.png)

## Contact Page

* Form : <br>The contact page has a form section where the user can ask any type of question in regards to all things Crypto. The value of this is that users who are new most defiantly have questions they need answering, so by adding this feature to my site it gives the complete package feeling, Users come, Learn about Bitcoin, then Altcoins then there able to ask anything they want. This encourages the user to ask freely and makes the learning experience more lasting. For the purpose of this project the form doesn’t have any action, meaning filled in forms are not sent anywhere but these details once submitted do display up in the URL. <br>
<img src="assets/images/readme.img/form-page.png" width=500>

## Responsive Design
* The whole website has responsive Css media queries added that allow users to view it on all device screens such as large desktop's down to a small iPhone 5 sized screen. This is demonstrated with the image above this features section.

#

## Features not implemented  

* One of the ideas I couldn’t implement is on the home pages quote section I wanted to make the quotes move around every 10 seconds and switch between other quotes until the user hovers over them.

* I also wanted to make the navigation bar a button that users have to click to release a drop down navigation bar.

* I also wanted to add a button that sticks to the page as the user scrolls down that once clicked takes users back up to the navigation bar.
<br> <br> The reasons I couldn’t implement these were I haven’t yet learnt how to do so.

#

# Testing my site 
After completing my website I had to test and make sure my code were up to standard and no errors where hidden inside. To do this I first checked Code Validator's for both HTML and CSS then once I checked the validator on each page and fixed the issues I then went on to check lighthouse for a general report on my site.

## Validator code testing

#### HTML [W3C validator](https://validator.w3.org/) - When running this for the first time there was a few warnings and errors. Here they are with how I solved them. <br> 
* Issue One: <br>
On the Home page the "Facts and point about bitcoin" section had a un closed < ul > tag, To solve this I added a closing </ ul> tag to line 188 on Index.html.<br><br>
* Issue Two : <br>
Warning: Consider using h1 elements for top level headings only:   All sections on all pages had a < h1 > headings to start them of. There should be only one for the main header heading so to solve this issue I changed all h1 tags on all pages to h2 tags leaving just one h1 on each page for the main header logo text. <br><br>
* Issue Three: <br>
Error: end tag </ nav> seen on line 39 but there was no open < nav> tag. To solve this issue I added an opening < Nav > tag on line 27 on index.html.<br><br>
* issue Four: <br>
Warning : Section id Hero-outer on index.html page lacks heading: To solve this issue I changed the < p > tag to a < h4 >tag, I then did this on all pages , index.html, Altcoins.html and contact.html as this was a warning that came up for all pages.<br><br>
![image](assets/images/readme.img/hero-outer-error.png)

* issue Five: <br>  For the < li> elements within the home pages "Facts and points about bitcoin" section I used < br> tags to give line brakes under each < li> element, This wasn’t the correct way to do so and it's not good practice to use < br> tags to space < li> elements. To solve this issue I targeted the < li> elements using Css and gave margin to them, This solved the error that was flagged on the html validator.

#### CSS [CSS Validation](https://jigsaw.w3.org/css-validator/) - When running the css validator for the first time there was only one error. <br>
* Error: <br> There was a useless and not effective line of code in my CSS, I had a ( position: center; ) rule on line 532 style.css. To solve this I simply removed the CSS rule.
![image](assets/images/readme.img/css-code.png)

Now when you run both CSS and HTML validators no errors or warnings show up.
#

## Testing different Browsers and screen size responsiveness.
### Once my site was finished, I checked my site works on different web browsers and tested the sites screen size responsiveness. Here are the browsers I tested my site on.

* [Google Chrome](https://www.google.co.uk/chrome/)
<br>* Browser test :  No issues were found, The site loaded first time as it should.
 <br>* Screen size test :   No issues were found when using Chromes (   Inspect element ) feature to test different sized screens. The CSS media queries work as they should. <br>
 <img src="assets/images/readme.img/chrome-responsive-design.png" height=500 width=500>

* [Firefox](https://www.mozilla.org/en-GB/firefox/features/)
<br>* Browser test :  No issues were found, The site loaded first time without fault.
 <br>* Screen size test : Using Firefox’s built in developer inspector I used the Responsive design mode and tested different screens sizes out, No issues were found.

* [Microsoft Edge](https://support.microsoft.com/en-gb/microsoft-edge)
<br>* Browser test :  No issues were found, The site loaded first time.
 <br>* Screen size test :   No issues were found when using Microsoft edges developer tool's to test screen sizes.

* [Brave](https://brave.com/)
<br>* Browser test :  No issues were found. Site loads.
<br>* Screen size test :   No issues were found using braves developer responsive design tool. The site is responsive to all screen sizes.

#


## Lighthouse Testing 
### Once I had tested my site on different browsers and ensured it was responsive on all different screen sizes I generated a Lighthouse report within google chrome to identify and fix common problems that affect my sites performance.
<br>
* The only issue it identified was that throughout my webpage the < em> tags contents were not visible as much with the background I had choose, To solve this I simply changed the colour of < em> tags in CSS from black to #fff (White). This boosted my lighthouse score. Here is a photo of the finished report that i am happy with.<br>
<img src="assets/images/readme.img/Lighthouse-report.png" height=700 width=500>

#
# Technology’s used
## [HTML 5](https://en.wikipedia.org/wiki/HTML5)
* Main structure language.
## [CSS](https://en.wikipedia.org/wiki/CSS)
* Main styling language.
## [FONT AWESOME](https://fontawesome.com/)
* Used to get icons for social media links
## [GITHUB](https://github.com/)
* Used for hosting website and keeping work in a remote place and to deploy my site.
## [GITPOD](https://www.gitpod.io/)
* GitPod was used for the development of my site.
## [TECHSINI](http://techsini.com/multi-mockup/index.php)
* Used to crate a mock up image displaying my site on different screen sizes.
## [TINYPNG](https://tinypng.com/)
* Used to shrink images from online down to smaller sizes making my site faster.
## [BALSAMIQ](https://balsamiq.com/)
* Used for wireframes of my site before I started on it.

#
# Deployment

## Before the website was deployed,
I had to use a temporary site ( Http.server ) to see the live changes while coding, To do this I used the ( Python3 -m http.server ) command in GitPod and that allowed me to see a live preview of my site while coding.

## The project was deployed on GitHub Pages. 
I used Gitpod as a development environment where I then committed all changes to github, I used (Git commit -m "" ) then (Git push)  command in Gitpod to save changes to GitHub.
<br>

## Once my site was ready to deploy online I had to: <br>
Log in to GitHub and click on repository to deploy (What-is-bitcoin-p1)
select Settings and find GitHub Pages section at the very bottom of the page
from source select none and then change the branch from "none" to "main" then once that was done I clicked save and the site was deployed after a refresh of the page.
<br><br>
View my deployed site here : [What is Bitcoin?](https://adamk99k.github.io/What-is-bitcoin-p1/)

#

# CREDITS


* Hero Image - This was the image used at the top of each page. This copyright free image was taken from [Pixabay.](https://pixabay.com/photos/bitcoin-cryptocurrency-of-technology-6278312/) The contact page also has a separate image, This image that sits behind the form also came from PixaBay.

* Whitepaper - For the whitepaper link on the home page I used [this website here.](https://bitcoinwhitepaper.co/)

* Quotes about bitcoin - These quotes from my sites home page were taken from [InspirationFeed.](https://inspirationfeed.com/bitcoin-quotes/)

* For some of the facts about Bitcoin I used this page [Iconic Holding](https://iconicholding.com/50-bitcoin-facts/) to get new facts I didn't know.


I want to thank [Code Institute](https://codeinstitute.net/) as anytime I was stuck on creating this project I would go back to the Code institute learning library and find information that could help me, I also took the idea for the hero image and quote section from Code institute, Love Running project. 
#

I also want to thank the amazing [Slack](https://slack.com/intl/en-gb/) Community for helping me when I had any sort of questions.
#

My mentor @gbenga_mentor on Slack, was amazing, He helped to guide me in the right direction, He also helped me figure out what needs to be done such as ( Adding more comments in my code ) and removing useless code such as my form on the contact page having an action tag that was not needed for this project.

#

I also want to thank my brother, Alex for helping me put the information for the Bitcoin and Altcoins sections into neat and newbie friendly order. He went through everything I wrote and told me if it was too hard to understand, this resulted in more easy to follow sections as whatever was too complicated was removed from the site.

