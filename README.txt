So you want free gucci wearables... here is the masterworks

Steps
-----------
1. Download and install Node.js   https://nodejs.org/en/
2. Open this website https://www.npmjs.com/package/nodemailer
3. Type in the install command on node.js
4. Open up your IDE, I'm using Visual Studio Code, but you need to download extensions to use javascript/java/C etc...
    a. If you need help, I can show you how to do it on Visual Studio just hmu :)
5. Put my shit on your IDE
6. On line 16 of index.js, change the info to your email account. Ideally, Make a new one if you want to spam
7. Lines 20 - 30 are the actual email content that you are sending to each college. ( Change contents in "From","Subject" and "Text"
8. line 44 -> contacts.slice (Starting index, ending index). -> You can only send a bunch of emails at a time. so I made it ito a set of 50, so change it by 50 every time you finish. So to start, make it (0,50). then, (50,100)... etc.
9. Save that shit and Open your Terminal
10. Use your unix commands (cd) to where your ide holds the files you put in it.
11.Now that you are at the right directory, type the command 'node index.js' ( not including the ')
