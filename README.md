# Lite HTTP Error :sailboat:

A minimalist error class for nodeJS 

## Getting Started
- Install the package `npm i lite-http-error`
- Then use it like any Error in JS but with Http Status code as second param.


```javascript

  import HttpError from 'lite-http-error';

   if(thisIsMistake){
    throw new HttpError('Some dreadful message' , 500);
   }
```

- Next add a middleware (if in express) it will catch this error and do the needful.


> Refrence from [Daniel Wagener's Blog](https://medium.com/@SigniorGratiano/express-error-handling-674bfdd86139) 
