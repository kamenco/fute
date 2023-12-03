# Stage School Theater

https://kamenco.github.io/fute/

## Introduction

This is a web site that engages with teatching children and youths the art of music, dance and drama. 


## Screenshots

There is a screenshot from from http://ami.responsivedesign.is 
Here is the result for responsiveness. https://ui.dev/amiresponsive?url=https://kamenco.github.io/fute/

Here is the printscreen image.

<img src = "assets/images/prinscreen_one.jpg" alt="Print screen">

## Here are some screenshots of all the main fetures of the site


The home page index.html presents information about this school and its purpose, goal and achievements.
On the right-hand side there is a photo composition of young artists.

<img src = "assets/images/glava.jpg" alt="Home page">

The second page casting.html gives information about the castings, and timetable with the casting dates as well as a gallery with photos of young artists performing on the scene. It provides data for contact and address.

<img src = "assets/images/casting.jpg" alt="Casting page">

The casting.html with the timetable.

<img src = "assets/images/casting_table.jpg" alt="Casting page table">


The third page is a sign up page where the cutomers can fill the form with their details and submit the form.

<img src = "assets/images/signup.jpg" alt="The signup page">

## Testing

All pages have been tested manually with https://validator.w3.org for html and https://jigsaw.w3.org/css-validator/ for css. All pages passed all right.

While working on the gallery part a bug was found, the fifth picture didn't show properly. This bug was solved by clearing the flow after the fourth picture. 

<img src = "assets/images/bug.jpg" alt="The signup page">

There is also an unfixed bug. When checking the responsivness on different devices the casting.html page shows a bug for device galaxy fold 280px. The table juts out of the frame. I checked the table width, it is 268px but still juts out.
For the rest devices the responsiveness is OK.

The site was checked with lighthouse with following report:
Performance: 33

Accessibility 94

Best practices 95

SEO 92

<img src = "assets/images/performance.jpg" alt="Testing outcome">

The reason for the bad performance is probably the gallery. I think the site can get better performance if the gallery is on the whole page not on the half.

## Deployment


The site was deployed on the github.io First I opened the repository, from settings  I chose pages from Code and automation bar. Chose main branch and root folder. And then save.

## Credits

The code for the signup.html was taken from my Love Running project. The form is css validated with successful return of the input.

The code for the responsive navigation and the responsive gallery was learned from https://www.w3schools.com As the code for the gallery was modifies substantially.
All the images are taken from https://www.pexels.com and some were converted to .webp format using https://www.freeconvert.com 

## Languages used

HTML, CSS. Hover CSS was used for the for the fields of the signup.html. The border changes to red while being hovered over. Google fonts are used "Roboto, sans-serif" throughout the project. Font awesome was used to add icons. Git Hub was used to store the projects code after being pushed from Git.

Applications like Photoshop, Illustrator, Corel Draw have not been used.