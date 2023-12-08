---
Title: Load
Description: This is the load page.
Template: single-analysis
---

Load
==========================

The purpose of this small report is to analyze three websites. The main focus will be the loading times of the website.  

Selection
-----------------------

The web sites I have chosen all fall under the same category - music. I have chosen this category because it's another interest of mine - just like I chose exercise-related pages for my color analysis.

### Web sites

#### Roland
_Manufacturer of musical instruments and softwares._

[![RolandImg](%assets_url%/img/Roland_snapshot.png){.load-img}](https://www.roland.com/)
_Roland front page, top section. Click on the image to visit the site._

#### Steinberg
_Manufacturer of musical softwares and hardwares._

[![SteinbergImg](%assets_url%/img/Steinberg_snapshot.png){.load-img}](https://www.steinberg.net/) 
_Steinberg front page, top section. Click on the image to visit the site._

#### Zoom
_Manufacturer of electronic devices for music. Not to be confused with the communication platform with the same name._

[![ZoomImg](%assets_url%/img/Zoom_snapshot.png){.load-img}](https://zoomcorp.com/)
_Zoom front page, top section. Click on the image to visit the site._

Method
-----------------------

To carry out the analysis, I will use the browser's 'inspect' tool. I will also use [Google Pagespeed](https://pagespeed.web.dev/).
Finally, I will use Microsoft's [Excel](https://www.microsoft.com/sv-se/microsoft-365/excel) to document the results.

Results
-----------------------

The results from the analysis can be seen in the table below.
 
<iframe width="402" height="346" frameborder="0" scrolling="no" class="excelResults" src="https://studentbth-my.sharepoint.com/personal/caas23_student_bth_se/_layouts/15/Doc.aspx?sourcedoc={49856f33-7782-4760-a441-be84ef48197b}&action=embedview&wdAllowInteractivity=False&wdHideGridlines=True&wdHideHeaders=True&wdDownloadButton=True&wdInConfigurator=True&wdInConfigurator=True"></iframe>
_Table 1. Analysis results._

Analysis
-----------------------

As can be seen in table 1, the loading time for all Roland pages is super slow, compared to the other two websites. When performing the analysis using dev tools, it can be seen that the DOM loads within a few seconds, while a 'loading wheel' is seen around the favicon for a significant amount time (a little less than two minutes, according to the results). This is suprising as Roland is a large and established company, where one would think that there should be more than enough financial means to maintain a high quality website, from all aspects. However, a temporary problem on the website cannot be ruled out and with the arguments that Roland is a large and established company, I would say it is more likly than unlikely that the site is currently experiencing some issues causing the long loading time.

Looking at Steinberg and Zoom, the loading speeds are around what one would have expected, within a few seconds. However, both of these websites do (as do Roland) perform quite poorly on a mobile, when having page speed in mind. On a desktop, Zoom performs the best with really good numbers on the two subpages.
According to the standards set by PageSpeed Insights, any score < 50 is considered poor, and any score between 50-90 is considered in need of improvements. With this, it can be seen that Zoom is really the only site passing the test (even though the landing page could use some improvements to meet the standards).

When looking at the results on PageSpeed Insights, it seem that the most recommended actions for improvement are  
o defer loading of images that do not appear on the screen  
o reduce JavaScript that is not used  
o send images in more modern image formats  

### Ranking
When ranking the sites, the loading time has primarily been decisive, but also the page speeds. 
Looking at the results, Zoom takes first place, this is because no other page is near the high page speed of > 90, which was seen twice on Zoom. 
Last place goes to Roland, as discussed earlier the load times are quite alarming and the page speed, especially on mobile, is really slow.
This obviously leaves Steinberg in the middle, which regardless of the outcome on Roland, seems about right. The page speed results on Steinberg all fall somewhere in between, although on a mobile they are bit slow and could use some improvement.

As for my own preferences regarding load time, I have to say I haven't really reflected on this before, but I would say that around three seconds give or take, as seen on Steinberg and Zoom, feels legit.  But since we live in a society where the demand for efficient webbsites are increasing day by day, I can imagine that even less than three seconds can be considered a minimun requirement, if not already, soon.

References
-----------------------

[Google Pagespeed](https://pagespeed.web.dev/)  
[Google Pagespeed docs](https://developers.google.com/speed/docs/insights/v5/get-started)  
[Excel](https://www.microsoft.com/sv-se/microsoft-365/excel)  
[Dbwebb](https://dbwebb.se/kurser/design-v3/kmom05)  

Other
-----------------------

Written by Calle Andersson (caas23).

_Last updated 2023-12-08_
