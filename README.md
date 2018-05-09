# -Kim817765787
This is the github for my CompE561 Final Assignment.
Everything you need to grade this is in the Kim817765787.zip file.
There were problems with publishing so please run the project locally.
The other files are there incase you wanted to view the individual files
Please do note that a large chunk of my code is from documents found online
I am not plagiarizing, but there was simply too many lines of code from
all different sorts of sources for me to go over and mark each one with a comment
saying that it's not from me.
P.S I barely used GitHub since I was working alone. I do have prior experience using github however, for
a personal project I did with friends for making games.

Challenges:
Here I will be listing the Challenges I faced while working on this app

My first challenge started while I was following one of the tutorials that was linked on BlackBoard. Originally, I planned
on following this tutorial's code line to line, to get a better understanding of how to create an app with CRUD interface
and then to use that knowledge to create my own app. However, I quickly faced my first wall when the tutorial asked me
to open a command window in the project directory. I searched online for how to do this, but I kept getting vague answers.
The closest answers I received was to shift + right click on the project after having opened the file that it's located at,
however, I only had the option of opening powershell, which wouldn't work on my computer for some reason. 
After countless hours of research, I found out that you cannotopen command window from the project directly by shift + right
clicking as of some windows patch way back when. Therefore,I looked up a tutorial on how to bring the option back and 
managed to continue on with the tutorial. 

However, my second challenge quickly came after, as even after I opened the command prompt and typed in the following
necessary code, the build kept giving me severe errors. According to the tutorial it's some kind of bug that occurs
due to asp.net core upgrades, however, the solution tutorial in the corresponding pages they provided for the bug did 
not work for me and gave me an extremely different error message as compared to the one they had. After countlessly 
searching yet again for what causes my error, I stumbled upon a comment made by some random user that seemingly fixed 
my problem. However, it only worked once, and for some magical annoying reason, when I turned on my visual studios again 
the next day, not only did the scaffolding code not work, but now my error message was completely different yet again so
the new solution I found did not work a second time. I tried to look up new solutions again, but most of them said that
I would have to do a clean wipe of my visual studios, which wasn't too viable, since my laptop takes an obscene amount
of time to redownload programs, not to mention the fact that the tutorials for doing a clean wipe for my laptop to get
rid of visual studios temporary files were convoluted.

Eventually, I moved on to simply using MVC (which was 500x easier) and managed to get the CRUD interface working for my
project. My third major challenge came when I tried how to find out how to do admin privileges. The creating of roles
and assigning them weren't tricky since there were a lot of tutorials online on how to do them. The problem was that most
of these tutorials that had the code would give an error when used on my project. And the errors I would get were either
too different from their solutions or simply didn't exist in theirs. Finally, I managed to find a code that worked
in my project for assigning an admin role.

My last major challenge came when I had to publish my website. It wouldn't publish with the code that I was using to
assign roles. Furthermore, even if I got rid of the code, I could not use the same login credentials as my local project.
Reading online, I found out that it's because the hashtables they use for passwords are different for their server
as compared to the one used by my project to keep my account data. However, the only solution I managed to find used
completely different files such as web.config, which I could not find, to fix it.

It's important to note that there were several minor challenges, which when all added up, amount to a great amount of time.
However, these 4 major challenges took up a lot of time themselves individually. I had to experiment with so many different
codes and look for help online on how to debug problems. And the sheer fact that my laptop is incredibly slow, especially
every single time that I had to build and re-run the program to see if it was working, took up a lot of time. I even
contemplated going back for a day or two to my hometown in order to use my computer and see if I would have better luck
with some of the errors and speed on it instead, but did not go through with it since I had finals. The 2nd and 4th, I
couldn't do much about, and 1st and 3rd I managed to overcome. I also had other "major" challenges, but I cannot really
recall them.
