# Project:      Ski Club
# Developer:    Maksim Popov

Testing details: 

[main README.md file](/README.md)
[Github website:](https://github.com/maxgray7-dev/ski-club_project.git)


### Project functionality testing

- Each future was manually tested within the project to ensure the app performs as expected.
- Visually tested to ensure there are no placed buttons or content in wrong position on the pages.

### Usability

- Navigation bar and other buttons function correctly and work as expected.
- Each Navigation option forward a user on the right page.

### Media Queries

- Each page was tested on different media queries to ensure it performs as intended on different screens.

## Lighthouse

Test with Lighthouse showed next results for About Us Page:
![Lighthouse general results](https://i.ibb.co/SwQB9MB/Lighhouse-general.png)

# Validator Testing HTML:

**INDEX.HTML Page**

On the first Pages Validator showed next errors : 

1. Error - **Trailing Slash**. ![Error 1](https://i.ibb.co/Xsk89f9/Error-1.png)
   Solution: Trailing Slash removal. <br>
2. Error **h3** element not allowed as a child element of **ul** ![Error 2](https://i.ibb.co/7KV65qp/Error-2.png) 
    Solution: Moved **h3** element up before **ul** element. <br>
3. Error - The element **a** placed incorrectly in **button** element.[Error 3](https://i.ibb.co/K9fnHyJ/error-3.png)
   Solution: Updated code, and placed **button** inside anchor element. 
   However, it seems this did not solve the issue. <br>
4. Another Warning, was in regards that the code has lack of heading.
   Solution: Created another heading **h3** and set as a hidden one. The issue has been fixed.<br>
5. Gallery Section - Incorrect placement of size measurement for favicon [Error 5](https://i.ibb.co/q5Sg32k/Error-5.png)
    Solution: placed it correctly and checked other html pages to avoid this issue in the future.<br>
6. Error in Services page - lack of heading. [Error 6](https://i.ibb.co/RT1Rmwp/Error-6.png)
   Solution added heading. As occured the page looked better with the heading, therefore **h1** element has been used for advertising equippment. <br>
7. 
   
