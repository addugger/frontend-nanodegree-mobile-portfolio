To run the application, copy the code into your local webserver or your domain webspace.

Navigate to the index.html file (or index_minified.html) to view the main page.  Click on the
pizza link to view the pizza page.

The new method of submitting projects, while much better than the email process, is lacking a
way to leave comments or communicate with the graders, so I'm just going to add that in here.

Submission 2:

First off, the original project description was lacking a lot of the specific details of what
needed to be done (I know it may have changed by this point, but I'm referring to the project
description as it was when I began the optimization project).  This is why I turned in such an
incomplete project initially, just so I could get some feedback on what actually needed to be
done.  I would have instead just asked for some clarifications, but, as I mentioned, there is
no good way to add communications with project submissions.  Thankfully I did receive the more
specific feedback I needed to move forward, so I tried to go off of that with this submission.

Now I will specifically reference feedback from my first submission:

CRP: The feedback claims that I had not achieved a page speed of 90 for mobile and desktop for
index.html, but as far as I can tell, this part is incorrect.  When I run the pagespeed
program, i get over 90 for both each time (see added screenshots in the /img directory:
mobileSpeed.png and desktopSpeed.png).

Framerate: I had not done anything to fix the framerate for the pizza.html page.  I have now, per
the feedback, gone back to the pizza page, found the two choke points in main.js, and edited
main.js to be more efficient (which, according to the console.log statements both parts have
gotten about 100x faster), but using the framerate meter in Google Chrome it still shows to
be generally below the required framerate, so I'm not sure what else I'm supposed to do there.

Content Efficiency: I made sure to provide a more minified version of index.html.  I also gzip'd the
main.js file used by pizza.html and edited pizza.html to use the gzip version.  As far as optimizing
images goes, I used www.smushit.com/ (provided by yahoo) to try to losslessly compress a number
of the images (some of these optimzations were added to the codebase, some were not), but it never
seemed to make a difference to pagespeed insights: it always said I needed to compress some image
or another better.  If more needs to be done in this respect, I might require a bit more guidance.

Thanks for reading! :)