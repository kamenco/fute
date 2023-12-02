# fute
project Stage School Theater
This is a web site that engages with teaching children and youths the art of music, dance and drama.
There are several screenshots from this website. Main page on a laptop - image.png.
Screenshot from IPhone SE - image.png and a screenshot from IPad mini - image.png.
The home page index.html presents information about this school and its purpose, goal and achievements.
On the right-hand side there is a photo composition of young artists.

The second page gives information about the castings, and timetable with the casting dates as well as
a gallery with photos of young artists performing on the scene. It provides data for contact and address.

The third page is a sign up page where the cutomers can fill the form with their details and submit the form.

All pages have been tested manually with https://validator.w3.org for html and css. All pages passed all right.
While working on the gallery part a bug was found, the fifth picture didn't show properly. This bug was solved by clearing the flow after the fourth picture. 
Print screen - image.png
There is also an unfixed bug. When checking the responsivness on different devices the castin.html page shows a bug for device galaxy fold 280 px. The table juts out of the frame. I checked the table width, it is 268px but still juts out.
For the rest devices the responsiveness is OK.
The site was checke with lighthouse with following report:
Performance: 26
Accessibility 95
Best practices 100
SEO 100. 
The reason for the bad performance is probably the gallery. I think the site can get better performance if the gallery is on the whole page not on the half.
The site was deployed on the github.io First I opened the repository, from settings  I chose pages from Code and automation bar. Chose main branch and root folder. And then save.

The code for the signup.html was taken from my love running project. The form is css validated with successful return of the input.
The code for the responsive navigation and the responsive gallery was learned from https://www.w3schools.com As the code for the gallery was modifies substantially.
All the images are taken from https://www.pexels.com and some were converted to .webp format using https://www.freeconvert.com