Bekzhan Yessengeldy
1) You would fit your automated tests within a Github Action that runs whenever code is pushed in the Recipe project development pipeline. Automatically running tests on every push catches bugs the moment they are introduced. If a bug is detected, the team is immediately notified. This makes it easier to address the problem instead of digging through the code to find the issue later.
2) No, you would not use and end to end test to check if a function is returning a correct output because a unit test would be more effective. End to end tests are more useful for simulating user experience and making sure the interactive elements of the page function correctly.
3) Navigation mode analyzes the page immediately after it loads, capturing performance metrics like load speed and JS execution time. Snapshot mode analyzes the page at a single moment in time, making it best for finding accessibility issues. However, unlike Navigation mode, Snapshot mode cannot measure JS performance or track any changes to the DOM. 
4) Three improvements that could be made to the CSE 110 Shop webpage are: 
   1) Give the HTML element a lang attribute
   2) Give the document a meta description
   3) Decrease loading time by rendering elements faster, and avoid chaining critical requests. 





