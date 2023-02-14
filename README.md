# all-operations-function-of-Map-

### -// Maps in javascript

### -// Maps is key value pair like dictionaries
let myMap = new Map();

myMap.set(1,"Bhushan")
myMap.set(2,"Raju")
myMap.set(3,"gauri")
myMap.set(4,"ggdfg")
myMap.set(5,"tghhy")

### -// printing all keys
console.log(myMap.keys());


### -// printing all values
console.log(myMap.values());


### -// printing all keys by using for loop
for(let key of myMap.keys()){
  console.log("keys are "+ key);
}

### -// printing all values by using for loop
for(let value of myMap.values()){
  console.log("values are "+ value);
}

### -// printing all keys and values by using for loop
for([key,value] of myMap){
  console.log("key is "+key+" value is "+value)
}


### -// detele specific key,value
myMap.delete(2);
console.log(myMap);

### -// Delete all key,value and make map empty
myMap.clear();
console.log(myMap);


### -// print all entries(key,value) 
myMap.entries();
console.log(myMap);


### -// print specific value of given key
console.log(myMap.get(1));

### -// check value of given key is present or not (in true or false)
console.log(myMap.has(2));

### -// print size of map (length)
console.log(myMap.size);




