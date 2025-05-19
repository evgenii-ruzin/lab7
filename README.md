# Evgenii Ruzin

1. The best practice is to include all the tests in Github Actions, since it automates testing for everyone who would work on this project, not only me. Tests on GHA ensure that every single push would be tested, what prevents pushing buggy code.
2. No
3. Navigation analyzes the loading of the page - that is, time span between opening the page and it being fully loaded. Snapshot analyzes the page at a particular time - that is, at a single moment. So, the difference between Navigation and Snapshot is the time when test starts and longivity of test period
4. 
   1) store images in WebP format instead of PNG or JPEG, since WebP files are much lighter
   2) use ```<meta name="viewport"> ``` tag, which allows to set the rendering of the page based on the screen size, which optimizes user experience for mobile users
   3) preconnect to sites where images are taken from, making rendering faster





