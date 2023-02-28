# javascript_snipets

### Destructuring 
  ```js 
  const arr1 = [1,2,3]; 
  
  const arr2 = [4,5,6];
  
  arr3(...arr1,...arr2);
  
  console.log(arr3); // 1 2 3 4 5 6
  
  // Object Destructuring 
  
  obj1 = {
    name: 'Ganesh',
    age:2;
  }
  
  obj2={
    name:'Hardik',
    age:20
  }
  
  obj3={
     ....obj1,
     ...obj2
  }
  
  console.log(obj3); // { name: 'Hardik', age: 20 }
  
  ```
  
  ### Arrow Functions
  ```js
  // with argument
  
  const addtwonum = (a,b) => {
    return a+b;
}

console.log(addtwonum(4,5)); //9

// without argument

const two = (a) => {
  return ++a ;
}

console.log(two(5));
```

### Template Literals

```js 
const person = {
    name: 'Ganesh',
    age:21
}

console.log(`My name is  ${person.name} and my age is ${person.age}`) //My name is  Ganesh and my age is 21
```
