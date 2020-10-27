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

23Oct-Office
==========
Stripe GraphQL - BenAwad
https://www.youtube.com/playlist?list=PLN3n1USn4xllF5t1GZhEwFQNDnStgupdB

Set up Subscription ( Recurring ) Stripe Payment with React and Express
https://www.youtube.com/watch?v=CqXjp1vtNwk

Build an Ecommerce Site Using Stripe and Gatsby — Learn With Jason
https://www.youtube.com/watch?v=g4aCBNt5Pcg

Building a faster checkout experience at PayPal with GraphQL (VISHAKHA SINGH)
https://www.youtube.com/watch?v=JneBBbDWiVs

Test Card Numbers : 
https://stripe.com/docs/testing#cards

How to configure your Stripe account and get API keys for your marketplace
https://help.sharetribe.com/en/articles/1055989-how-to-configure-your-stripe-account-and-get-api-keys-for-your-marketplace

Stirpe Developers 
https://stripe.dev/

React-stripe-checkout : Load stripe's checkout.js as a react component.Easiest way to use checkout with React.
https://github.com/azmenak/react-stripe-checkout

Deploy MERN STACK App with AWS EC2
https://www.youtube.com/watch?v=HtWgb_vbyvY
https://github.com/jaewonhimnae/deploy-mern-aws-ec2

Building a Real-time To Do List in React
https://www.youtube.com/watch?v=OfE0jJn3qs0&list=PLN3n1USn4xlkc2LlMIUUT1nZCh20iqgW_

Facebook OAuth GraphQL with Node.js
https://www.youtube.com/watch?v=qjKZYQih288&list=PLN3n1USn4xlnz0a96Ex0F5x-mpxCIh315

jQuery - Form Builder 
https://formbuilder.online/#top

formBuilder-Github
https://github.com/kevinchappell/formBuilder
Angular Ng2FormBuilder
https://github.com/KhaledSMQ/Ng2FormBuilder

Business Analysis Techniques
https://www.digiteum.com/business-analysis-techniques-it

Apollo Directive

git credential-manager delete https://github.com  


(https://).*?(.com)
(  .*).*?
(.com).*? => double space

(">).*?(</A>)
(.*).*?(">) - > before title  

Forms, File Uploads and Security with Node.js and Express
https://www.sitepoint.com/forms-file-uploads-security-node-express/

How to Create an Ecommerce Site with React
https://www.sitepoint.com/how-to-create-an-ecommerce-site-with-react/
https://github.com/sitepoint-editors/React-Ecommerce

Formage- Form Builder NPM
https://github.com/node4good/formage
What's a good node.js / mongoose form builder?
https://stackoverflow.com/questions/13481138/whats-a-good-node-js-mongoose-form-builder

BxJS - Using Worker threads in Node.js : https://www.youtube.com/watch?v=eFJ7Q03jEVY
https://www.youtube.com/results?search_query=how+promise+await+and+async+in+node+js
Ecommerce with NodeJS : https://www.youtube.com/playlist?list=PLcpL2kgfJqjn0zKf-daHwWWWM42bgCMiw
Code-lab : TharunSharma : https://www.youtube.com/c/TarunSharma7372/playlists
Nodejs Microservice : https://www.youtube.com/c/TarunSharma7372/playlists
Serverice Worker Tamil : https://www.youtube.com/results?search_query=Service+Worker+in+tamil
Push Notifications Using Node.js & Service Worker :  https://www.youtube.com/watch?v=HlYFW2zaYQM
https://www.youtube.com/results?search_query=ecommerce+in+nodejs
NamasteProgramming / X-Store : https://github.com/NamasteProgramming/X-Store/tree/day_44
https://www.youtube.com/results?search_query=heroku+mern+deploy+

Heroku Deply : https://www.youtube.com/c/EsterlingAccime/playlists
React Tamil : https://www.youtube.com/playlist?list=PLyYcNnaAVG5LbuPubpTEuHz29i5CB4SHe
MongoDB On SSL : https://stackoverflow.com/questions/42159175/connecting-heroku-app-to-atlas-mongodb-cloud-service

Express skeleton :  https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website  


Heroku : https://www.youtube.com/watch?v=NX3jqtwfzVY
https://www.youtube.com/watch?v=5PaUiPyBDJY

How to host a RESTful Node.js server with MongoDB Atlas database on Heroku
https://dev.to/cpclark360/how-to-host-a-restful-node-js-server-with-mongodb-atlas-database-on-heroku-1opl

Connecting Heroku App to Atlas MongoDB Cloud service SSL 
https://stackoverflow.com/questions/42159175/connecting-heroku-app-to-atlas-mongodb-cloud-service
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website


Now there are actually two big problems with the way that this is implemented right now and so this way, it wouldn't really work at all. So first one, 
1. this function call here has no way of knowing request, response, and next. We did not pass them into catchAsync here, and so really there's no way for the function to know the values of these parameters. And second is that right here 
2.we are actually calling the async function. And to see this a bit better, let's just get completely rid of this code. So here we have catchAsync and we are then calling it using the parentheses of course. And then inside of catchAsync we are also then right away calling the fn function, and that's not how it is supposed to work.

https://medium.com/javascript-in-plain-english/creating-enum-types-with-express-apollo-6c59665e95d4
************
Mongoose converting stored UTC dates to local time?

Mongoose and node.js aren't doing anything to your dates, it's simply that the JavaScript Date type produces a local time string when you call toString() on it even though it actually contains the time in UTC.

Explicitly call toUTCString() on your Date object if you want a UTC time string.

https://stackoverflow.com/questions/17596804/mongoose-converting-stored-utc-dates-to-local-time
----
how to change date timezone in mongoose?
https://stackoverflow.com/questions/35672248/how-to-change-date-timezone-in-mongoose
------
https://www.apollographql.com/docs/apollo-server/schema/scalars-enums/
https://dimitr.im/custom-scalar-types-graphql-apollo
-----
Why does JavaScript Date.getTimezoneOffset() consider “-05:00” as a positive offset?

https://stackoverflow.com/questions/21102435/why-does-javascript-date-gettimezoneoffset-consider-0500-as-a-positive-off#:~:text=Because%20that's%20how%20it's%20defined,negative%20if%20it%20is%20ahead.


The time-zone offset is the difference, in minutes, between UTC and local time. Note that this means that the offset is positive if the local timezone is behind UTC and negative if it is ahead.
----
https://en.wikipedia.org/wiki/List_of_tz_database_time_zones
---
https://ayushgp.github.io/date-and-time-in-javascript/


https://www.techrepublic.com/article/convert-the-local-time-to-another-time-zone-with-this-javascript/

https://www.apollographql.com/docs/apollo-server/schema/creating-directives/

JavaScript Date Object and Time Zones
https://www.youtube.com/watch?v=oKFb2Us9kmg

https://www.youtube.com/watch?v=UT2dP447roo

"utf8": "There are many javascript libraries that allow you to convert the timezone with ease.  "
      "utf8": "However, you might don't want to include the whole library if you just want to convert a couple times. "
      "utf8": "So this video will talk about converting timezone in pure javascript. It's short and easy too!"
      "utf8": "Let's start with creating a new Date object"
      "utf8": "This will get us a local time. Let's put it on console to see"
      "utf8": "Currently I'm in SE Asia timezone which is +7 hours from UTC"
	  
      "utf8": "If we want to convert the local time to any timezone, we need to convert it to UTC time first. Then add the destination timezone offset to the converted UTC time"
      "utf8": "To convert local time to UTC time- we need to get the local timezone offset from UTC with getTimezoneOffset() "
	  
      "utf8": "I'm going to display the offset to the console"
      "utf8": "It returned -420 which is our local timezone offset from UTC in \"minutes\" (-420 / 60 = 7 hours)"
      "utf8": "Minus sign means this timezone is ahead of UTC"
      "utf8": "Now we'll add UTC offset to our local time"
      "utf8": "which we'll get the UTC time as a result"
      "utf8": "To add or subtract minutes from Date object - use setMinutes() and getMinutes()"
      "utf8": "Now our Date object contains the UTC time"
      "utf8": "Noted that we only changed the time of our Date object. If you display the Date object, you'll still see the original timezone"
      "utf8": "Now we have the UTC time, we can convert it to any timezone"
      "utf8": "Suppose we want to convert it to Mumbai time which is +5.5 from UTC"
      "utf8": "We'll just add the destination timezone offset to the UTC time"
      "utf8": "Let's multiply 5.5 with 60 to get the offset in minutes"
      "utf8": "then add (or subtract) the offset to the UTC time. Same way as we did previously"
      "utf8": "Done! We've just successfully converted the local time to Mumbai time"
      "utf8": "This technique is quick and easy if you know the offset of destination timezone"
      "utf8": "However, if you want to convert the timezone dynamically - using the library is recommended"
      "utf8": "In our next video release, we'll talk about interesting timezone library call moment.js"
      "utf8": "Stay tune for more tips - subscribe if you like us :)"
      
      function getTimezone() { 
            offset = new Date().getTimezoneOffset(); 
            formatted = -(offset / 60); 
            document.querySelector('.output').textContent 
                    = formatted; 
} ; getTimezone()


var str = "2016-11-22T17:14:00";
var dt = new Date(str + "Z");
console.log("UTC string:");
console.log(dt.toUTCString());
console.log("Local string");
console.log(dt.toString());
console.log("Hours UTC:   " + dt.getUTCHours());
console.log("Hours local: " + dt.getHours());

https://stackoverflow.com/questions/40768606/i-have-a-utc-string-and-i-want-to-convert-it-to-utc-date-object-in-javascript/40768745#40768745

https://www.cluemediator.com/convert-the-local-time-to-another-timezone-using-javascript#gcltim

Offset
+09:00 in UTC+09:00 means the local time is 9 hours ahead than the UTC standard time. 


parseISO

*Parse the given string in ISO 8601 format and return an instance of Date.
*Function accepts complete ISO 8601 formats as well as partial implementations.
*If the argument isn't a string, the function cannot parse the string or the values are invalid, it returns Invalid Date.

// Convert string '2014-02-11T11:30:30' to date:
var result = parseISO('2014-02-11T11:30:30')
//=> Tue Feb 11 2014 11:30:30


format(new Date(2016, 0, 1), "yyyy-MM-dd'T'HH:mm:ss.SSSxxx")



https://forum.freecodecamp.org/t/git-pull-how-to-override-local-files-with-git-pull/13216
git reset --hard Hmis

git fetch --all

git checkout Hmis

Javascript uses the browser time zone for date object 
----------------

why-you-shouldnt-use-moment-js
https://inventi.studio/en/blog/why-you-shouldnt-use-moment-js

We're distinguishing between errors in development  and in production.  When we're in production, we send the error  using this function here,  which will then send as many details as possible  to the client,  so that we really get all the information  in order to get rid of the bug.  If it's a programming error,  or if it's an operational error,  then we still really want to see anything that's going on.  
When we're in production,  which is arguably the most important part  of our application, then we distinguish  between operational errors,  so errors that we know and trust,  and to other errors, that might be kind of unexpected.  

If the error is operational, so for example 
1.the user  tried to access a route that doesn't exist,  
2.or tried to input invalid data
all of these are operational errors.Then we can send appropriate error messages,  for the client to know what went wrong.

On the other hand, we have these unknown errors/unexpected errors
For example : Coming from MongoDB, which we do not mark as operational.  In this case, they would right now simply be handled  using this generic error message here.  For example, a validation error.  Right now, that's an error that's coming from MongoDB  and not from our own app error class.  We do not create these errors by ourselves.  Again, they are right now not marked as operational,  but we of course need to mark them as operational  so that we can then send the appropriate error message  back to the client.  In the example that I was just mentioning,  that the input data is invalid.  There are two or three other errors that we need to mark  as operational ourselves.  So we will do that  down here.  So in this else block,  we will do that over the next couple of lectures.

Three type of Errors in MongoDB : 400 - Bad Request

1. Invalid ID (We have to show it as Operational Errors)  - (error.name === 'CastError')
2. Duplicate Name In DB (error.code == 1100)
3. ValidationError [Max Value] - (error.name == 'ValidationError')

500 - Internal Server Error

Steps: 
=======
We can directly create the middleware in "index.js"
app.all('*', (req, res, next) => {
  
  res.status(404).json({
    status: 'fail',
    message: `Can't Find URL${req.originalUrl} on the server`
  })
  
  // const err = new Error(`Can't find ${req.originalUrl} on this server !`)
  // err.status = 'fail';
  // err.statusCode = 404;
  // next(err);

  
})

app.use((err, req, res, next)=> {
  err.statusCode = err.statusCode || 500;
  err.status = err.status || 'error';

  res.status(err.statusCode).json({
    status: err.status,
    message: err.message
  });
})

2. we're gonna build a couple of different functions for handling with different types of errors,and so I want all of these functions to be all in the same file, all right ? Controlling errors (appController.js)

# move the middleware from index.js to appController.js

module.exports = (err, req, res, next)=> {
  err.statusCode = err.statusCode || 500;
  err.status = err.status || 'error';

  res.status(err.statusCode).json({
    status: err.status,
    message: err.message
  });
}

4. import "appController" into the "index.js" file
const globalErrorHandler = './appController.js'

app.all('*', (req, res, next) => {
  next(new AppError(`Can't Find URL${req.originalUrl} on the server`, 404));
})

app.use(globalErrorHandler)

3. Add the AppError Class

class AppError extends Error {
    constructor(message, statusCode){
        super(message);
        this.statusCode = statusCode;
        this.status = `${statusCode}`.startsWith('4') ? 'fail':'error';
        this.isOperational = true;

        Error.captureStackTrace(this, this.constructor);
    }
}

module.exports = AppError;
 
4. import "AppError" into the "index.js" file

app.all('*', (req, res, next) => {
  next(new AppError(`Can't Find URL${req.originalUrl} on the server`, 404));
})

5.Modify the async await functions
# async function return promises so receive the error in catch part.
const catchAsync = fn => {
	return (req,res,next) => {
		fn(req, res, next).catch(err=> next(err))
	}	
}

export.createTour = catchAsync(async(req,res,next) => {
	const newTour = await Tour.create(req.body)
	
	res.statu(201).json({
		status: 'Success',
		data: {tour: newTour}
	})
})

6. Move the catchAsync to new file 
module.exports =  catchAsync = fn => {
	return (req,res,next) => {
		fn(req, res, next).catch(err=> next(err))
	}	
}

7. Import catchAsync into controller.js and use it


---------------  
27/10/2020  


Proxying API Requests in Development
https://create-react-app.dev/docs/proxying-api-requests-in-development/

ReactSecurity - Attach a JSON Web Token in an Axios Request
https://www.youtube.com/watch?v=-u04JD5Eo-c
https://stackoverflow.com/questions/57085493/getting-data-from-response-headers-in-axios

 React Security Fundamentals by Ryan Chenkie 
 https://courses.reactsecurity.io/courses/react-security-fundamentals/302432-handling-auth-state/864657-persist-auth-state-on-page-refresh
 Advanced React Security Patterns Preview
 https://www.youtube.com/playlist?list=PLlRapu2ErjJ-qSQT9fhh3wdgLU8nynzeN

differs from this approach " axios.defaults.headers.common['Authorization'] = AUTH_TOKEN;" ? Does this headers also sends with every request?
---------
If our API endpoints are secured with JSON Web Tokens, we need to get those JWTs to the endpoints when making requests from our React 

applications. A common way to do this is to send the JWT as an Authorization header.

Let's see how to use Axios HTTP interceptors to send JWTs in our requests for data.
----------------------
What's the best way to store the bearer token? Can it be stored in context some how and we use a custom hook to grab the bearer token every 

time? Some places I've read have mentioned that storing the bearer token in local storage or a cookie is a security flaw because then it's 

exposed to other websites you visit.?

 I think the best place to keep it is in your React state somewhere. Local storage and even cookies are indeed susceptible to attacks. 


The only downside is that you'll need to get a new token each time the page is refreshed. If you don't have a way of refreshing your tokens 

easily without an additional login, this can lead to a poor user experience. 

--------------
Is it okay to have token exposed in your code like this? token value in a variable  ?
 in practice, you'll need a different token for every user and they will expire regularly so you'll need them to get new tokens often. you'll 

need to store them somewhere in your React app. My recommendation for storage is browser memory or an HttpOnly cookie :)

----------
how can you display any header that's being sent towards ReactJS? For example, in NodeJS you can do something like "req.headers" and this 

would display all the possible headers in a certain request, is there a way to do the same within ReactJS?

Ans :
 If you're using Axios, you can usually read the response headers. Check out this post for more info: 

https://stackoverflow.com/questions/57085493/getting-data-from-response-headers-in-axios
----------

I already tried doing a "res.headers", however I don't see the headers that I hope for in this field. 

I go under Network using the Chrome tools and I can see the headers there and on Postman.

This is what I'm doing with ReactJS:

const backendApi = axios.create({

    baseURL: 'http://localhost:3010',

    withCredentials:true,
})


//This is under a class object
backendApi.post('/users/register', {

            authCode: data.code

        }).then((response) => {

            console.log(response);

        }).catch((error) => {

            console.log(error);

        })

//Backend
//the backend sends this essentially
//but I can't see the 'Authorization' header that I expect
res.setHeader('Content-Type', 'application/json');

res.setHeader('Authorization', "Bearer " + accessToken);
res.status(200)

res.json({success:true}).end() 

Ans :
I fixed the issue! The problem was that I wasn't including the 'exposedHeaders' configuration option for cors in the backend. Once I included 

the header with the right name, it worked!

-------------
ReactJS JWT token | Authentication using web api in Tamil | Cheetah Media
https://www.youtube.com/watch?v=l5DsNB_0Kw0

Redux | Redux in tamil | Redux for beginners | Cheetah media
https://www.youtube.com/watch?v=jEs6X_MweBA

What is Redux ? | #11 React JS Tamil Tutorial for Beginners
https://www.youtube.com/watch?v=yUSLt2f0UXw

React JS Tamil Tutorial for Beginners
https://www.youtube.com/playlist?list=PLfD4W8QfMd5DbFccLzRFeG0QjWWHGTT3-

How to handle authentication in React using JWT & Cookies | Hooks. Best To Do List App #14.
https://www.youtube.com/watch?v=B7y7UXA4Wd4

Secure JWT Authentication - Where to store the JWT Token. How to store JWT token in httpOnly cookies
https://www.youtube.com/watch?v=894seNhONF8

oAuth Step by Step : 

React Login, Logout and Handling JWT Token | React Authentication #2
https://www.youtube.com/watch?v=XWj18K4Uhg8

React Authentication Full Course | Login, Logout, Forgot and Reset Password
https://www.youtube.com/watch?v=6sLh_5iFnFc


How To Connect React To A Backend (Express.js) - React for beginners #7
https://www.youtube.com/watch?v=kJA9rDX7azM

Building app with React and Redux
https://www.youtube.com/playlist?list=PLuNEz8XtB51K-x3bwCC9uNM_cxXaiCcRY

Simple Passport Local Authentication w/ React & Node.js
https://www.youtube.com/watch?v=IUw_TgRhTBE

Fix CORS Error [SOLVED] | React Tutorial
https://www.youtube.com/watch?v=hxyp_LkKDdk

React Automatically Refresh Tokens
https://www.youtube.com/watch?v=3qLJPLN33DE

Authentication With Refresh Tokens Implementation - Ben Awad
https://www.youtube.com/watch?v=UA0AIkjI85c&t=16s

154 Adding Interceptors to Execute Code Globally
https://www.youtube.com/watch?v=MKMD9IYGliM

React Hooks | React Hooks in tamil | Cheeta Media
https://www.youtube.com/watch?v=db0s0SHcoFA


An NPM module to reinstall missing dependencies.
https://www.npmjs.com/package/npm-install-missing

Proxying API Requests in Development
https://create-react-app.dev/docs/proxying-api-requests-in-development/

ReactSecurity - Attach a JSON Web Token in an Axios Request
https://www.youtube.com/watch?v=-u04JD5Eo-c
https://stackoverflow.com/questions/57085493/getting-data-from-response-headers-in-axios

 React Security Fundamentals by Ryan Chenkie 
 https://courses.reactsecurity.io/courses/react-security-fundamentals/302432-handling-auth-state/864657-persist-auth-state-on-page-refresh
 Advanced React Security Patterns Preview
 https://www.youtube.com/playlist?list=PLlRapu2ErjJ-qSQT9fhh3wdgLU8nynzeN
 
 https://www.youtube.com/channel/UCfKDDL3Tck4SZ2jsMTUcEpA/videos
 
 https://www.youtube.com/playlist?list=PLlRapu2ErjJ-qSQT9fhh3wdgLU8nynzeN
 
 https://www.youtube.com/watch?v=-u04JD5Eo-c
