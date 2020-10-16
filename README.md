# urls
Bookmarked urls collection

Convert timezone in Javascript  
https://www.youtube.com/watch?v=UT2dP447roo  

Auto Format Phone Number with SINGLE JavaScript sentence | Cleave.js Tutorial  
https://www.youtube.com/watch?v=q4N4baWZ4K0&list=PLbu98QxRH81LNY0PYN7s-71u8aYi6ozXs&index=12  
Create Game in 10 Minutes with JavaScript Physics Engine  
https://www.youtube.com/watch?v=PsL3iI61wl8&list=PLbu98QxRH81LNY0PYN7s-71u8aYi6ozXs  
https://www.youtube.com/c/RedStapler_channel/playlists  

Google Maps Javascript API Tutorial - Introduction
https://www.youtube.com/playlist?list=PLbu98QxRH81LGWXQIo4n76MLA31VNyhSD  
How Javascript Causes Memory Leak
https://www.youtube.com/watch?v=xrX_BtOUDls  

He's Dead Jim: Finding JS Memory Leaks with Chrome Dev Tools
https://www.youtube.com/watch?v=RJRbZdtKmxU  
Understanding and Debugging Memory Leaks in Your Node.js Applications [I]
https://www.youtube.com/watch?v=hliOMEQRqf8  
Node.js tutorial for Beginners: CPU and Memory Profiling Made Easy
https://www.youtube.com/watch?v=gL2GGcV_f20

MongoDB Timestamp tutorial (insert and retrieve based on Timestamp)
https://www.youtube.com/watch?v=1rr2j6Zta7A

<a href="https://stackoverflow.com/questions/40028377/is-it-possible-to-achieve-multithreading-in-nodejs" rel="noopener" target="_blank">is-it-possible-to-achieve-multithreading-in-nodejs</a>  
<a href="https://stackoverflow.com/questions/18613023/how-to-create-threads-in-nodejs" rel="noopener" target="_blank">how-to-create-threads-in-nodejs : </a>  
<a href="https://nodesource.com/blog/worker-threads-nodejs" rel="noopener" target="_blank">worker-threads-nodejs</a>  
<a href="https://flaviocopes.com/node-event-loop/#introduction" rel="noopener" target="_blank">introduction</a>  
<a href="https://flaviocopes.com/web-workers/" rel="noopener" target="_blank">web-workers</a>  
<a href="https://flaviocopes.com/websockets/" rel="noopener" target="_blank">websockets</a>  
<a href="https://medium.com/javascript-in-plain-english/javascript-what-are-stack-and-queue-79df7af5a566" rel="noopener" target="_blank">javascript-what-are-stack-and-queue</a>  
<a href="https://medium.com/javascript-in-plain-english/a-quick-guide-to-queues-in-javascript-4367354ca005" rel="noopener" target="_blank">a-quick-guide-to-queues-in-javascript</a>  
<a href="https://medium.com/javascript-in-plain-english/javascript-event-loop-y-promises-951ba6845899" rel="noopener" target="_blank">javascript-event-loop-y-promises</a>  
<a href="https://devcenter.heroku.com/categories/deployment" rel="noopener" target="_blank">Heroku Deployment</a>  

#10/15/2020

https://reactjs.org/docs/create-a-new-react-app.html
https://create-react-app.dev/
https://github.com/facebook/create-react-app

>npm install -g create-react-app

E:\Prabha\Local\mernApp>create-react-app client

>npm install mongoose express axios morgan concurrently -s

-----------

Remove a Git Remote
git remote rm https://github.com/kprabha25/BookmarkMERN.git

Below will reinitialize your local repo; also clearing remote repos (ie origin):
git init

below is used to a add a new remote, Then below, will create 'origin' if it doesn't exist:
git remote add origin [repo-url]
git remote add origin https://github.com/kprabha25/BookmarkMERN.git

below is used to change the url of an existing remote repository:
git remote set-url origin [repo-url]

below will push your code to the master branch of the remote repository defined with origin and -u let you point your current local branch to the remote master branch:
git push -u origin master

git remote -v

To push your changes into your remote repo execute the git push <remote> <branch> command :
#git push my_awesome_new_remote_repo

Remove branch from git local repo. Force Delete the Local Branch: "-D" is force delete option.
git branch -D client

Pull branch
git pull https://github.com/kprabha25/BookmarkMERN.git <client>

Update a Remote
git remote set-url origin https://github.com/career-karma-tutorials/web-tutorials

----------
"start": "concurrently \"command1 arg\" \"command2 arg\""

npm test, npm start, npm restart, and npm stop are all aliases for npm run xxx.

For all other scripts you define, you need to use the npm run xxx syntax.

-------------
Cross-Origin Resource Sharing (CORS) – What is it?
http://definitiontech.co/cross-origin-resource-sharing-cors-what-is-it/

MERN App : https://www.techandstartup.org/tutorials


---  
How to Fix Git fatal: The current branch has no upstream branch  

If you constantly get the following git error message after attempting a git push with a new local branch:

fatal: The current branch <branchname> has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin <branchname>
	
Then the issue is that you have not configured git to always create new branches on the remote from local ones.


The permanent fix if you always want to just create that new branch on the remote to mirror and track your local branch is:

 git config --global push.default current


----  
git clone --single-branch --branch <branchname> <remote-repo>  
git clone --single-branch --branch Start https://github.com/abc/bookmark.git  

https://github.com/abc/bookmark.git  

How to clone all remote branches in Git?

$ git clone git://example.com/myproject  
$ cd myproject

$ git branch
* master

$ git branch -a
$ git checkout origin/experimental

$ git checkout experimental
$ git branch
* experimental
  master


-----  
git clone https://github.com/abc/bookmark.git  

>git branch
* main

>git branch -a
* main
  remotes/origin/HEAD -> origin/main
  remotes/origin/Start
  remotes/origin/main

>git checkout Start
Switched to a new branch 'Start'
Branch 'Start' set up to track remote branch 'Start' from 'origin'.

>git branch
* Start
  main

>git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.  

>git merge Start  

git push origin FirstAPI  
-----------  

git credential-manager delete https://github.com  

git config --list  

git config user.name = "abc"  
git config user.email= "abc@gmail.com"  

-----------
16/10/2020

MONGODB_URI
mongodb+srv://adminprabha:Atlas123@cluster0.c0uc9.mongodb.net/bookmark?retryWrites=true&w=majority

Deploy your application to Heroku
After you commit your changes to git, you can deploy your app to Heroku.


git add .
git commit -m "Added a Procfile."
heroku login
Enter your Heroku credentials.
...
heroku create
Creating arcane-lowlands-8408... done, stack is cedar
http://arcane-lowlands-8408.herokuapp.com/ | git@heroku.com:arcane-lowlands-8408.git
Git remote heroku added
git push heroku master
...
-----> Node.js app detected
...
-----> Launching... done
       http://arcane-lowlands-8408.herokuapp.com deployed to Heroku
To open the app in your browser, type heroku open.


https://devcenter.heroku.com/articles/deploying-nodejs

rm -rf .git

Heroku
ab

https://stackoverflow.com/questions/28318217/port-34037-is-already-in-use-heroku-nodejs-express-websockets
https://coursework.vschool.io/deploying-mern-with-heroku/
https://forum.freecodecamp.org/t/mern-heroku-deployment-works-locally-but-not-on-heroku/259988/3
https://www.newline.co/fullstack-react/articles/using-create-react-app-with-a-server/
https://www.youtube.com/watch?v=xxua85cCiT0
https://devcenter.heroku.com/articles/deploying-nodejs
https://devcenter.heroku.com/articles/node-best-practices
https://devcenter.heroku.com/changelog-items/1557
https://devcenter.heroku.com/articles/logging#view-logs
http://definitiontech.co/cross-origin-resource-sharing-cors-what-is-it/
https://www.youtube.com/playlist?list=PLurIMwd6GdCj_VlnKVceR66Sxfcb37VU8
https://github.com/accimeesterlin/mernapp_youtube/blob/master/server.js
