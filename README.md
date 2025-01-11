# js_objects
Javascript objects


## what is objects
* Is used to store various keyed collections and more complexed collections.
 `Objects` in js can have properties and things they can do 

 *example*
>   `A user`: `Property` ||  `Methods`
>>          Email      ||    Login
>>          Username   ||    Logout
>>          Gender     ||   


```js
const car = {type: "Fiat", model: "500"; color: "white"};
car.type;

```

# Create object

```js
// An object literal is  list of property name and values inside a curly braces.It also called object initializer.
const person  = {
    firstName:`Abdiqani`,
    lastName:`Hashi`,
    age:35,
};
// invoke
person.firstName;
```

__ 

```js

// Create an empty javascript object and add four properties.

// create an empty object.

    const person ={};

    // add properties
    person.firstName = `Abdiqani`;
    person.lastName = `Hashi`;
    person.age = 50;

    person.firstName;

```




```js

// create an empty javascript object using new object()
// creat object
 const car = new object();
 // add properties.
 car.name = `Volsksvagen`;
 car.model = `Golf`;
 car.moellår = `2016`;

 car.model;
```
*NOTE*
> There is no need use `new object`.It is better to use `object literal` for simplicity and readability.


