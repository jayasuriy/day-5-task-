# day-5-task-
print odd number in array
let arr = [1,2,3,4,5,6,7,8,9,10,11,12]

let odds = arr.filter(n => n%2)

console.log(odds)

convert all the string to title caps strings 

(iString.prototype.toTitle = function() {
  return this.replace(/(^|\s)\S/g, function(t) { return t.toUpperCase() });
}

console.log('all lower case ->','all lower case'.toTitle());
console.log('ALL UPPER CASE ->','ALL UPPER CASE'.toTitle());
console.log("I'm a little teapot ->","I'm a little teapot".toTitle());) convert string to title caps 

sum all the number in array
sum aonst sum = [1, 2, 3].reduce(add, 0); 

function add(accumulator, a) {
  return accumulator + a;
}

console.log(sum); // 6ll the number in array 

prime number in to arrray 

let arr = [3, 12, 50, 23, 0];
arr.forEach(function (element) {
  const isPrime = checkPrime(element);
  if (isPrime) {
    console.log(`${element} is a prime number`);
  } else {
    console.log(`${element} is NOT a prime number`);
  }
});

remove duplicates from an array

let chars = ['A', 'B', 'A', 'C', 'B'];

chars.forEach((c, index) => {
    console.log(`${c} - ${index} - ${chars.indexOf(c)}`);
});

















