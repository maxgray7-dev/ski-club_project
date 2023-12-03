# Project:      Ski Club
### Developer:    Maksim Popov

Test details: 

[main README.md file](/README.md)
[Github website:](https://github.com/maxgray7-dev/ski-club_project.git)


# Project functionality testing

- Each future was manually tested within the project to ensure the app performs as expected.
- Visually tested to ensure there are no placed buttons or content in wrong position on the pages.

## Usability

- Navigation bar and other buttons function correctly and work as expected.
- Each Navigation option forward a user on the right page.

# Media Queries

- Each page was tested on different media queries to ensure it performs as intended on different screens.
- In Particular the site was tested on devices with screens 280px, 768px and 992px. It was shown expected responsiveness on all screens.

## Lighthouse

This test was performed on google chrome bowser.
Test with Lighthouse showed next results for About Us Page.
This was tested for mobile 280px and 992px screens:
![Lighthouse general results](https://i.ibb.co/HVmBrfx/Lighthouse-mobile.png)
- Performance - 99
- Accesability - 94
- Best practices - 100
- SEO - 100


# Testing HTML by Validator :

### __HTML Validator showed the next errors:__
1. ![Error 1](https://i.ibb.co/Xsk89f9/Error-1.png)<br>
   Error - __Trailing Slash__.
   Solution: Trailing Slash removal. <br>
2. ![Error 2](https://i.ibb.co/7KV65qp/Error-2.png) <br>
   Error **h3** element not allowed as a child element of **ul**.<br>
    Solution: Moved **h3** element up before **ul** element. <br>
3. ![Error 3](https://i.ibb.co/K9fnHyJ/error-3.png)<br>
   Error - The element __a__ placed incorrectly in __button__ element.<br>
   Solution: Updated code, and placed **button** inside anchor element. 
   However, it seems this did not solve the issue. But all works correctly. <br>
4. Another Warning, was in regards that the code has lack of heading.<br>
   Solution: Created another heading **h3** and set as a hidden one. The issue has been fixed.<br>
    
       **Gallery Page**
   
5. ![Error 5](https://i.ibb.co/q5Sg32k/Error-5.png) <br>
    __Incorrect placement__ of size measurement for favicon. <br>
    Solution: placed it correctly and checked other html pages to avoid this issue in the future.<br>

       **Services page** 
         
6. [Error 6](https://i.ibb.co/RT1Rmwp/Error-6.png) <br>
   Error in  - __lack of heading__.
   Solution: added heading. As occured the Service page looked better with the heading, therefore **h1** element has been applied and used for advertising equippment. <br>

   **No other errors were found in the HTML code**

AS a result: there are 2 errors left in regards to "weather" and "livecam" buttons. 
Nevertheless, after testing buttons were working correctly and there were no issues noticed related to those buttons. Therefore buttons were left as it is.
__

### __CSS Validator showed the next issues:__

CSS Validator showed 2 errors related to font-size in main content: 

![Errors](https://i.ibb.co/FhGmyrn/css-errors.png) <br>
Solution: errors were deleted. <br>
![No further errors](https://i.ibb.co/v4cVC3r/CSS-alright.png)<br>
As a result CSS code did not show any further errors.<br>


