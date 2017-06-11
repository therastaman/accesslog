# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Big data access log
* V.0.1
* [Learn mongodb](https://www.mongodb.com/)
* [Lern node js](https://nodejs.org/en/)

This is the access log big data storage using node js, expreww & mongo db

### How do I get set up? ###

* run npm -v (make sure you have npm & node installed)

```
#!sheel

npm init
```


```
#!sheel

npm install express --save
```


```
#!sheel

npm install nodemon --save-dev

```

```
#!sheel

npm install mongodb --save
```

```
#!sheel

./node_modules/.bin/nodemon server.js
```
* to make auto run when develop it

```
#!json

"scripts": {
     "dev": "nodemon server.js"
    }
```

* add step 6 so you can run "npm run dev" instead "./node_modules/.bin/nodemon server.js"

### How do I get deploy? ###
* run sudo npm install pm2@latest -g
* then run 

```
#!sheel

pm2 server.js
```

*if you got problem then run 

```
#!sheel

/usr/local/n/versions/node/<your_node_version>x.x.x/bin/pm2 start server.js
```
* for centos 7 run

```
#!sheel

sudo /usr/local/n/versions/node/8.0.0/bin/pm2 startup systemd
```

*for centos 6 run


```
#!sheel

sudo /usr/local/n/versions/node/8.0.0/bin/pm2 startup systemd
```

* install nginx

```
#!sheel

sudo yum install epel-release
```

```
#!sheel

sudo yum install nginx
```

* Configure nginx

```
#!sheel

sudo vim /etc/nginx/nginx.conf
```




### Contribution guidelines ###

* not yet

### Who do I talk to? ###

* nabil@dewatasoft.com
* nablerbobrastaman@gmail.com