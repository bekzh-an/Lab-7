Bekzhan Yessengeldy
1) You would fit your automated tests within a Github Action that runs whenever code is pushed in the Recipe project development pipeline. Automatically running tests on every push catches bugs the moment they are introduced. If a bug is detected, the team is immediately notified. This makes it easier to address the problem instead of digging through the code to find the issue later.
2) No, you would not use and end to end test to check if a function is returning a correct output because a unit test would be more effective. End to end tests are more useful for simulating user experience and making sure the interactive elements of the page function correctly.





