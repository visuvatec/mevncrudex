# mevncrudex

## Project setup
Requirement: Make sure mongoDB server is running in local
if not start it eg: mongod --dbpath <path to your data directory> 
Open three Windows command prompt terminals
  
In the first CPT, start the mondodb server
  >mongod --dbpath <path to your data directory>
   
In the second CPT, Clone therepository and start nodemon server
  >git clone https://github.com/visuvatec/mevncrudex.git
  >cd mevncrudex\api
  >npm install
  >nodemon server
    ....Server is running on Port: 4000
    ....Database is connected
    
In the third CPT, start the VUE front end app
  >cd mevncrudex
  >npm install
  >npm run serve
  (this will take a while)
 ...  App running at:
  - Local:   http://localhost:<port>/
  - Network: http://192.168.1.51:<port>/
  
  Open a browser and enter the http://localhost:<port>



Other references:

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
