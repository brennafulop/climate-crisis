### Overview
* [Live Website](https://zingy-sprite-1239c1.netlify.app/)
* [GitHub Repo](https://github.com/brennafulop/climate-crisis)

### Description
Our project is called “Cats for Climate Change”. We created a website for a fake non-profit 
organization that informs people about the different wildcats threatened by climate change. The 
goal of the website is to get visitors to donate to our cause. Therefore, we have a prominent 
“Donate” button that is always present at the top-right hand corner of the website. This is the 
main action we want our visitors to take, so it is valuable to display this action button at all 
times. 

We included a fixed anchor in the lower right hand corner of the website which takes the user to 
the top of the page. We decided to include a link like this because the page we created has a lot of 
content, and on desktop, a user might need to spend a lot of time scrolling up to get to the top of 
the page. On mobile browsers, hitting the navigation bar scrolls the user to the top of the page 
(using built-in functionality), so we do not display this anchor on mobile screens. Additionally, 
this is to save space on the smaller screen. 

Another design choice we made is to alternate the image and text content of the article post 
preview. This is because we want to keep the user engaged with the page content, and the images 
and text have equal importance – therefore, we want to encourage the audience to scan the entire 
post content. However, we do not want to make it difficult to access the full page of each post – 
this is the reason that we keep the “Read More” button available in the same position of the 
article preview. 

On mobile, we display the content posts in stacked sections (using flexbox). On a small screen, it 
would be very difficult to see the post image and text, as well as interact with a button, if the 
content were side-by-side. 

One other interesting design choice that we made is to generate a color palette using Coolor. We 
provided an image of Joe Exotic, the infamous cat-lover/entertainer to the Coolor service, and 
received a color palette based on this image. We call it the Exotic Theme, and it is composed of 
these five colors: #53693E, #BDCD7D, #558B3D, #F6F6F5, #67443C. 

A technically challenging portion of implementing the site was to use a hidden checkbox creating 
a CSS-only mobile menu. We did not need to rely on JavaScript for any portion of the site. 
