# inDex (B.Tech CSE)
Do you usually find yourself in a situation where you are trying to find notes/PDFs of a particular chapter and asking your friends for them but nothing is found? I guess I have developed a solution for it. From now on, you can use my app and website to accesss all the notes and other material. Everything is hosted on a cloud server and a proper backup is maintained. Bandwidth is capable enough for supplying small PDFs and videos to few hundred people at a time and it is backed by Google & Cloudflare. Also, I will be hosting the data on my Local Desktop using my Fiber connection when there is a sudden outage or bug.

# About the App
My app is not a pure native app at the moment it is a combination of WebView and Native Elements in ratio (9:1).

# Thank You
Thank you YouTube, Jugal, Chirag & Raghav for helping me in the development.

Thank you Raghav for designing the app icon.

Thank you Shivesh, Chirag, Tanishq, Abha, Shristi, Sanjana, Raghav, Jugal & Namrata for testing the apps and helping me in solving the issues.

Thank you Sanjana & Namrata for supplying me with the database (notes etc).

Thank you everyone who helped me in achieving this. 

Thank you to the users of this app for the love and feedback.

# Screenshots

They can be found at: https://btechcse.tripathisarthak15.workers.dev/0:/BTech_CSE_21_25/Screenshots/

# General Issues

1. Blocked by Play Protect- App is 100% safe, this issue arises because of Google. Blame Google. You can click on Install Anyway.

2. Worker Threw Exception- Cloudflare sometimes crashes due to some errors in the backend. Reload and it will be gone. 

3. Not Loading or Downloading- Clear Data of app, if not solved reach me.

4. Not Connected to the Internet- Check your connection.

5. Asks for username/password- press Home and don't use that portion of the app it is not for users.

 
# How did I made this?
I dont know, to be honest I was just watching some YouTube Videos and got a idea to make something like this. I learnt very basic designing, used some online engines and the the good old AndroidStudio for the apk. For the website, everything is taken from GitHub and my Configs are applied on top of that. 

# Links

Web- https://btechcse.tripathisarthak15.workers.dev/


APK for Android - https://github.com/tripathisarthak15/btech-cse-index/releases/download/publish1.2/v1.2_stable_inDex.apk


v1 Release Page- https://github.com/tripathisarthak15/btech-cse-index/releases/tag/publish


# How to search for files quickly?
I have made a search option which can be found under the drop down menu in the top right corner.

Type your search query properly with the set syntax. For example, if you want to find the notes for Object-Oriented Programming on the topic Programming Paradigne which were discussed in class on 9th August, 2022 taken by a teacher named AJ. You can search for these using the file name of the PDFs which is written like:


 SubjectShortName.TopicName.DDMMYY.TeacherInitials
 
 For the above subject the code will be
 
 SubjectShortName:- OOP
 
 Topic Name:- Programming Paradigne
 
 DDMMYY:- 090822
 
 TeacherInitials:- AJ
 

FileName: - OOP.Programming.Paradigne.090822.AJ.pdf
 
            OOP.Programming.Paradigne.090822.AJ
 
            
You can either search using the File name or any of the code words mentioned above. FileName would give you exact file. CodeWords will give you all the files in that code.


For PDFs of Lab add "Lab" to your search query. Experiment with no. is written as Exp.num -> Example= DE.Lab.Exp0.Introduction


# Report
Report Bugs or give new ideas using the Contact Option in the APP.


# Why the Source code is not available completely?

The source code has my auth token and credentials and I am still learning that how they should be removed. 
