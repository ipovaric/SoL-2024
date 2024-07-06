# Summer of LabVIEW - Wordle

The goal of Wordle is to guess the correct 5 letter word by making guesses and getting feedback about which letters are in the word and which letters are in the correct position. Unlike the real Wordle challenge that was run online, there is no limit to the number of guesses for each word. Your solver's final score will be the average number of guesses it took 

After your Solver.vi makes a guess, it will be called again with feedback so another guess can be made until the correct word is guessed. This feedback comes as the following characters corresponding to the positions of the letters in the guess that was made previously:

 '-' : The letter that was in this position is not in the word at all.

 '*' : The letter that was in this position is in the word but was not in the correct position.

 '+' : The letter that was in this position is in the correct location.

 ## Example:

 If the word to guess is "oomph" and the first guess is "whomp" the feedback on the next call would be "-****". Then if the next guess was "jumps" the feedback would be "--++-".
 
 When "oomph" is finally guessed your solver will never see "+++++" because the tester moves on to the next word.

 ## The Project & Submission

 **Ensure all of the code you create is placed in the "Submission" virtual folder. Anything that is not in this folder will not be included in the zip file that gets built to upload to the website.**

 Since file IO is among the list of functionality that is rejected in submissions, you can put any additional testing code that reads data sets from files or uses other forbidden functionality in the "Testers" folder which isn't included in the zip build.

 ### Implementing your solver

 In the "Submission" folder of the project is a "Solver.vi" file which is where you should build your solver. Feel free to create however many SubVIs you need to organize your logic but as noted, ensure they're put into the Submission folder for the zip build.

 ### Submitting your solver

 When you'd like to test your solver against the data set used for scoring, expand the Build Specifications section at the bottom of the project, right-click the Submission Zip listing, and select Build. This creates the Zip that can be uploaded to the challenge page on https://summeroflabview.com and it will soon be scored and you'll be able to see your score on the leaderboard when the challenge is active. There is no automatic scoring when the challenge is not active.

 ## Discord Server

 If you run into any troubles or questions about the challenge be sure to follow the Discord link in the navigation bar of the website. The Discord server is where all discussion and announcements during challenges happen and you're free to discuss strategies, LabVIEW questions, or other Summer of LabVIEW problems there.

 Thanks for playing and I hope you enjoy the challenge!