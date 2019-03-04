# What is ApolReady?

In my first year of Speech and Debate, I was constantly struggling to write good Apologetics speeches that could be easily edited and even more easily shared with others. Using Microsoft Word suffices at times, but formatting the cards to be of proper proportions was beginning to be a great burden upon my time frame! Overall, I wanted a solution that helped format Apologetics cards, so that I could focus on the rhetoric rather than the physical appearance of the notecard.

This is why I created ApolReady. Using web technology, one can access ApolReady from anywhere, and write their answer card with less worrying about physical properties and more about the card that they are creating.

# How to use:

We are hard at work creating a Alpha testing version of this application for Windows. After Alpha testing, complete versions will be released for Windows, Mac, and Linux. Currently, testing is done through [NPM (Node Package Manager)](https://www.npmjs.com/get-npm) commands in terminal.

# But I really want to use ApolReady right now!!!

Alright... This is going to get technical... Real technical... Don't be afraid to look up some YouTube videos on these topics:

**Prequisites:** Make sure to have Node.JS installed. If you need help doing that, follow this link: [Node.JS](https://nodejs.org)

**Step One:** [Download the repository .zip file. This is self explanitory, but i've included a link in case, well, it isn't.](https://stackoverflow.com/questions/2751227/how-to-download-source-in-zip-format-from-github)

**Step Two:** Unzip the .zip file to whatever folder you want. Again, self explanitory.

**Step Three:** Open the unzipped folder. */ApolReady-master/Desktop*

**Step Four:** Delete the node_modules folder. This is important because all systems function differently than my custon Ubuntu machine.

**Step Five:** Open the */ApolReady-master/Desktop* in your terminal. In Windows, this can be done by holding down shift while right-clicking in a blank space in the folder, then clicking *Open in Powershell*. If you run Mac, I'm sorry, Macs confuse me. If you run Linux, (Like me!) you should be proficient in this kind of stuff anyway. :P

**Step Six:** Run in terminal: npm install

**Step Seven:** Run in terminal: npm install pdfkit --save

**Finally:** In order to start ApolReady, type: npm start
