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
--------------
https://www.hopetutors.com/wp-content/uploads/2019/02/MEAN-Stack-Syllabus-compressed.pdf
-------------
Find Open Source By Searching
https://awesomeopensource.com/
fullstack-apollo-express-mongodb-boilerplate
https://github.com/the-road-to-graphql/fullstack-apollo-express-mongodb-boilerplate

graphql-mongodb-projection
https://github.com/du5rte/graphql-mongodb-projection

How to reference another schema in my Mongoose schema?
https://stackoverflow.com/questions/29078753/how-to-reference-another-schema-in-my-mongoose-schema?answertab=oldest#tab-top

Custom Scalars in GraphQL
https://uptoskill.com/graphql-custom-scalars/
Learn date-fns: A Lightweight JavaScript Date Library
https://www.sitepoint.com/date-fns-javascript-date-library/?utm_content=buffer6ab54&utm_medium=social&utm_source=facebook.com&utm_campaign=buffer

Quick Tour of date-fns, a Simple JavaScript Date Library
https://www.digitalocean.com/community/tutorials/js-date-fns

moment utc, does date-fns have something similar?
https://stackoverflow.com/questions/52833680/moment-utc-does-date-fns-have-something-similar

https://www.hopetutors.com/wp-content/uploads/2019/02/MEAN-Stack-Syllabus-compressed.pdf


-----------

https://www.techandstartup.org/tutorials
https://www.techandstartup.org/tutorials/build-a-graphql-api-with-node-and-apollo-server
https://www.techandstartup.org/tutorials/build-a-react-app-with-graphql
https://developer.aliyun.com/mirror/npm/package/mongo-to-gql/v/1.6.2

serveo, localhost.run, ngrok

https://dev.to/alvarojsnish/graphql-mongodb-the-easy-way-ngc
https://dev.to/denislav__/how-to-use-socket-io-not-the-chat-3l21
https://dev.to/dip15739/how-to-share-localhost-anywhere-in-to-the-world-36gn

Subdocuments
https://mongoosejs.com/docs/subdocs.html#subdocuments-versus-nested-paths

Populate
https://mongoosejs.com/docs/populate.html

https://alexanderzeitler.com/articles/mongoose-referencing-schema-in-properties-and-arrays/
https://alexanderzeitler.com/articles/mongoose-tojson-toobject-transform-with-subdocuments/
https://alexanderzeitler.com/articles/getting-all-registered-routes-in-express-js/
https://alexanderzeitler.com/articles/expressjs-dynamic-runtime-routing/

https://www.toni-develops.com/2018/08/01/adding-config-file-and-babel-loader/
https://www.toni-develops.com/2018/12/11/using-graphqlschema-to-construct-schema-programmatically/

http://blog.stevenlevithan.com/archives/date-time-format

https://www.npmjs.com/package/dateformat

https://codehandbook.org/javascript-date-format/

https://codehandbook.org/setting-node-js-project/

https://codehandbook.org/promise-inside-loop/

https://codehandbook.org/category/nodejs/express/

https://codehandbook.org/implementing-passport-authentication-in-express/

https://codehandbook.org/build-app-using-express-sequelize-and-mysql/

https://codehandbook.org/learn-react-from-scratch-creating-web-app-using-react/


https://www.toni-develops.com/2018/08/01/adding-config-file-and-babel-loader/
https://www.toni-develops.com/2018/12/11/using-graphqlschema-to-construct-schema-programmatically/
https://www.youtube.com/watch?v=7k03jobKGXM
https://code.tutsplus.com/tutorials/paypal-integration-part-1-paypal-payment-buttons--cms-22916
https://code.tutsplus.com/categories/paypal

23/10/2020  
----------
Deploy a MERN App to Heroku
https://www.youtube.com/watch?v=qXIG8iKO7Fo
https://github.com/hannahpatellis/reactnotesapp/blob/master/server.js

How to Deploy React Express, Node App to Heroku - 2020
https://www.youtube.com/watch?v=xgvLP3f2Y7k
https://github.com/mujibsardar/fcb_react_express_heroku_example

how to set unique indentifier in react
https://www.google.com/search?q=how+to+set+unique+indentifier+in+react&oq=how+to+set+unique+indentifier+in+react&aqs=chrome..69i57j33i22i29i30l2.12276j0j7&sourceid=chrome&ie=UTF-8

What is URL Encoding? - URL Encode/Decode Explained - Web Development Tutorial
https://www.youtube.com/watch?v=lkAeX3T6A9I

Validating & Structuring JSON over WebSockets - JavaScript Tutorial
https://www.youtube.com/watch?v=mmZmtOUIBsg&list=PLVvjrrRCBy2I4V6nsCxwO03Y8GHaT-izr

TODO REST APP in Express ( NodeJS )
https://www.youtube.com/playlist?list=PLxoOrmZMsAWwTIKAJTOUpS9US5YkRuhrq

AWS Lambda Using NodeJS
https://www.youtube.com/playlist?list=PLxoOrmZMsAWyBy3qwWdNhtAi-J4yLK1k9

Understanding Express web framework in NodeJS
https://www.youtube.com/playlist?list=PLxoOrmZMsAWxC3BaEeSvKkqtZmfzUk367

Part 14 - Body parameters in express HTTP request
https://www.youtube.com/watch?v=7-zLcsfR1q0

HTTP Explained: The HTTP Request Status Code Guide (Complete)
https://www.youtube.com/watch?v=VLH3FMQ5BIQ

Simple search form in REACT using hooks
https://dev.to/asimdahall/simple-search-form-in-react-using-hooks-42pg

form submit for search in react functional component
https://react-hook-form.com/advanced-usage/
https://stackoverflow.com/questions/59771401/react-component-with-just-a-form-form-submit-action-differs-depending-on-consu

How to search for text or expression in multiple fields
https://stackoverflow.com/questions/31859800/how-to-search-for-text-or-expression-in-multiple-fields

Search multiple fields for multiple values in MongoDB
https://stackoverflow.com/questions/21417711/search-multiple-fields-for-multiple-values-in-mongodb

Install AdminLTE Template in React.js
https://www.youtube.com/watch?v=mIecTxfqo1M

admin-lte
https://www.npmjs.com/package/admin-lte

Deploy a MERN App to Heroku
https://www.youtube.com/watch?v=qXIG8iKO7Fo
https://github.com/hannahpatellis/reactnotesapp/blob/master/server.js

How to Deploy React Express, Node App to Heroku - 2020
https://www.youtube.com/watch?v=xgvLP3f2Y7k
https://github.com/mujibsardar/fcb_react_express_heroku_example

how to set unique indentifier in react
https://www.google.com/search?q=how+to+set+unique+indentifier+in+react&oq=how+to+set+unique+indentifier+in+react&aqs=chrome..69i57j33i22i29i30l2.12276j0j7&sourceid=chrome&ie=UTF-8

What is URL Encoding? - URL Encode/Decode Explained - Web Development Tutorial
https://www.youtube.com/watch?v=lkAeX3T6A9I

Validating & Structuring JSON over WebSockets - JavaScript Tutorial
https://www.youtube.com/watch?v=mmZmtOUIBsg&list=PLVvjrrRCBy2I4V6nsCxwO03Y8GHaT-izr

TODO REST APP in Express ( NodeJS )
https://www.youtube.com/playlist?list=PLxoOrmZMsAWwTIKAJTOUpS9US5YkRuhrq

AWS Lambda Using NodeJS
https://www.youtube.com/playlist?list=PLxoOrmZMsAWyBy3qwWdNhtAi-J4yLK1k9

Understanding Express web framework in NodeJS
https://www.youtube.com/playlist?list=PLxoOrmZMsAWxC3BaEeSvKkqtZmfzUk367

Part 14 - Body parameters in express HTTP request
https://www.youtube.com/watch?v=7-zLcsfR1q0

HTTP Explained: The HTTP Request Status Code Guide (Complete)
https://www.youtube.com/watch?v=VLH3FMQ5BIQ

Simple search form in REACT using hooks
https://dev.to/asimdahall/simple-search-form-in-react-using-hooks-42pg

form submit for search in react functional component
https://react-hook-form.com/advanced-usage/
https://stackoverflow.com/questions/59771401/react-component-with-just-a-form-form-submit-action-differs-depending-on-consu

How to search for text or expression in multiple fields
https://stackoverflow.com/questions/31859800/how-to-search-for-text-or-expression-in-multiple-fields

Search multiple fields for multiple values in MongoDB
https://stackoverflow.com/questions/21417711/search-multiple-fields-for-multiple-values-in-mongodb

Install AdminLTE Template in React.js
https://www.youtube.com/watch?v=mIecTxfqo1M

admin-lte
https://www.npmjs.com/package/admin-lte

Ecommerce with NodeJS
https://www.youtube.com/watch?v=ri0XSiWCdkY&list=PLcpL2kgfJqjn0zKf-daHwWWWM42bgCMiw
