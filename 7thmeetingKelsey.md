In the last week
* A lot of challenges with Reach! See challenges section
* Have fix for #193 on t2-docs
* Added quick link to pin diagram in t2-docs

Challenges
* Very limited documentation on ESP, the documentation that there is for the Arduino board. Don't want to use Arduino IDE! It causes problems.
* Brihi found another tutorial showing how to install toolchain from scratch. Mostly working, except it doesn't push code... also doesn't work on the Windows machine (works ok on Mac)
* Went through a whole process– to get it to recognize the board properly, had to install USB to UART bridge, a few other issues, wrote some hello world code, trying to learn make (which is new for them) in the command line
* It shows all of the steps, but in the end when it should be connecting, it fails.
* Pinged in coach group/channel, but no one has replied on this
* Posted screenshot in Tessel reach channel, but nobody seemed to know how to help
* There is a senior at their college who hasn't used ESP but has done similar things, they are finding a time to get her help
* Maybe @tcr can help with this?
* ESP chip was heating up pretty quickly (5-10 minutes)
* Is it supposed to have a power LED when plugged in? There is an LED that turns on for just a second when it gets plugged in but then it turns off
* Kelsey worried that maybe there is something wrong with the hardware, suggest checking with a schematic & multimeter for shorts
* Board doesn't seem to match names of ESP boards listed at http://esp-idf.readthedocs.io/en/latest/get-started/index.html but not sure. Not the Devkit-C, possible that it's the Robokit?
* In the PRD, show a few use cases, the audience, not sure what to write for "hardware implementation", not sure what you would need (Kelsey advises some ways of thinking about defining what features are needed, what considerations are explicitly not constraints)
* ESP feels like it's slowing progress a bit, not quick commits and hard slog for documentation. Maybe this is how it is to do hardware development, but will try resolving other issues if still stuck after a couple more days

In the next week
* Kelsey suggests they make an issue on reach-wg with links to different ESP getting-started tutorials & their experiences with each, on both Mac and Windows
* Kelsey- send another ESP board to them! This will help with checking hardware vs. software issue
* Kelsey look at PRD!
* Try reviewing/testing a technical pull request from @rwaldron
* Try out the toolchain for locally compiling t2-firmware
* Find an issue that takes some javascript to resolve and fix it!
* RGSoC supervisor suggested doing a presentation about RGSoC and Tessel at a local meetup, they are looking at presenting at Linux Chicks soon
* Have been to a lot of meetups, but nobody does any live hardware demos, this will be a treat!
