Last couple of weeks
* Had a lot of events last-last week, so couldn't work much
* One issue with I2C tutorial in the last week– @tcr commented to suggest checking out accelerometer code. Tested locally and got familiar.
* Spent time exploring & selecting issues to work on

Challenges
* There are some pieces of code in the accelerometer that they don't understand. getAcceleration function, copied into local demonstration. Have been asked to explain a few lines, but not really sure what all the pieces are doing. Some register shifting. Kelsey sends https://github.com/Frijol/SGNext_demos which should hopefully explain. Suggests going through that repo & trying it with a logic analyzer
* Was trying to figure out why printing in issue #93 was returning a buffer of 88. Needed to learn how to print a buffer (hex to string), then didn't really understand why the value was 88. @hipsterbrown helped, suggesting it's an OK value for SAMD21. Kelsey suggests searching for hex value of 88 in the SAMD21 datasheet
* Investigating the CLI speed enhancement during update. Decided this might not be the most valuable use of time since no one is really upset about it.

In the next week
* Issue #93 fix should be done and ready to merge by tonight
* Go through accelerometer tutorial slides & try using a logic analyzer a la Kelsey's SGNext presentation
* Thinking about doing the 3G Dongle support
* Need to try pushing code to the new ESP module
* In the last three weeks, would really like to accomplish a big technical PR. Seems like 3G dongle support is an appropriate scope for the time remaining.

How do you feel about your work this summer?
* Really expanded knowledge: using Github, understanding how to send PR's, applying knowledge e.g. learned about registers in class, but now actually need to use it, learned a lot about using JS, weekly updates help a lot to analyze what's done and what's left to achieve
* Haven't felt like have made strong technical contributions. Would really like to get the 3G dongle PR done before end of summer program.
* Spent a lot of time trying to figure out how to make the project more accessible to newcomers, ended up making a lot of tutorials, which helped them learn a lot about how the tech stack works
* Want to keep working on stuff after summer ends!
