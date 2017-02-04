## Nodejs, angularjs1, socketIO

### Pay attention to mongo-connect's MongoStore new code
1. decompress db.zip
1. run `npm install`
1. run `bower update` to install angularjs into public/lib. bower installtion folder is in .bowerrc
1. run `mongod --dbpath=/Users/derek/Work/Bitbucket/nodejs.mea1n3.socket/db --port=27020`
1. run `node server`
1. register username and password

> note: if need newest packages, replace package.json version to *, and `npm update --save`
> currently only passport-local works

### Package List

| package | version | usage |
| --- | --- | --- |
| body-parser | ^1.16.0 | request.body parser, json |
| compression | ^1.6.2 | compress in production |
| connect-flash | ^0.1.1 | error, info message pass |
| ejs | ^2.5.5 | template engine |
| express | ^4.14.1 | high level http server |
| express-session| ^1.15.0 | session management, default in memory |
| method-override| ^2.3.7 | http get post delete put |
| mongoose| ^4.8.1 | mongodb schema, connect to mongodb |
| morgan| ^1.7.0 | error info log |
| passport| ^0.3.2 | login |
| passport-facebook | ^2.1.1 | |
| passport-google-oauth | ^1.0.0 | |
| passport-local | ^1.0.0 | |
| passport-twitter | ^1.0.4 | |
| connect-mongo | ^1.3.2 | store expression session into mongodb, so socketIO can read session from db |
| cookie-parser | ^1.4.3 | read sessionId |
| socket.io | ^1.7.2 | realtime communication |
