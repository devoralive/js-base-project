##How to start

###Project installation :

**Install nodejs and npm**

http://nodejs.org/


**Install grunt-cli and bower**

```
npm install -g grunt-cli bower
```
Rename package.json as package.json.old.

**Manage development dependenies**
```
npm init
```
Copy devDependencies section from package.json.old into package.json.

Delete package.json.old.

**Install development dependencies**
```
npm install
```

**Manage front end dependenies**
```
bower init
```

**Install front end dependenies**
```
bower install --save packageName
```

##Test your project

###Grunt commands :
**Checking the code**
```
grunt test
```
**Run only the test with coverage**
```
grunt jasmine:coverage
```
**Check code syntax**
```
grunt jshint
```
or
```
grunt jslint
```
