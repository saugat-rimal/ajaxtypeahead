# Filter City State and population

![image](https://user-images.githubusercontent.com/86593756/180128867-f7647a3e-b41a-450a-85f1-e9d882b94b7e.png)


## Ajax Type Ahead

The first thing I learned was fetch() method, which is an experimental method that can replace ajax request. 

```
fetch(endpoint) // returns a promise  
.then(res => res.json()) // also returns a promise  
.then(data => data); // return an array of objects
```
fetch() takes one argument which is the endpoint’s url. This returns a promise which several method that you can use to process the data. For this example we used .json() which also returns a promise (I know) so we need to use .then() once again. Now we finally have our data! 
