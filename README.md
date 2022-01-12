# Onboarding-Roadmap
Resources and exercices for future interns 



## Array manipulation 

```
let arrayReviews = [10, 35, 34, 20, 8, 50];
let arrayDates = ['01/01/2021', '02/01/2021', '03/01/2021', '04/01/2021', '05/01/2021', '06/01/2021'];




// 1) code a function that sort arrayReviews in ascending order
// 2) code a function that filter arrayReviews to have element above 30 only
// 3) code a function with reduce that makes the sum of all element in arrayReviews

// 4) create a function that sum only array element above 30 in arrayReviews (result should be 35 + 34 + 50 = 119)

// 5) replace 20 by 55 in array Reviews to get [10, 35, 34, 55, 8, 50]

// 6) add 78 and 87 to arrayReviews without mutating it (use spread operator), to get [10, 35, 34, 20, 8, 50, 78; 87]

// 7) destructuring and rest: how could you get [34, 20, 8, 50], the last 4 elements of arrayReviews, in a single line of code ? 

let a = // write code here
console.log(a) // [34, 20, 8, 50]
```


## Object manipulation 

```

let object = {
name: 'Elyazid', 
brand: 'Glanceable'
}

// 8) what are the 2 possible ways to get the object 'name' field value ? 
let a = // write code here
console.log(a) = 'Elyazid'

// 9) transform object to add a job field with value 'frontend engineer' like this, and without mutating it 

let object2 = {
name: 'Elyazid', 
job: 'frontend engineer',
brand: 'Glanceable'
}

console.log(object.job) // undefined
console.log(object2.job) // 'frontend engineer'

// 10) how to get object2 all keys in an array ? ['Elyazid', 
'frontend engineer', 'Glanceable']
// 11) how to transform object 2 in {
name: '# Elyazid', 
job: '# frontend engineer',
brand: '# Glanceable'
} (more difficult question, with reduce, string litteral)  ?

```


## Array of Object manipulation
```
// 12) code a function that creates the following array from arrayDates, without using a for loop (use map)

let arrayNew = [
  { day: '01/01/2021', brand: 'Glanceable' },
  { day: '02/01/2021', brand: 'Glanceable' },
  { day: '03/01/2021', brand: 'Glanceable' },
  { day: '04/01/2021', brand: 'Glanceable' },
  { day: '05/01/2021', brand: 'Glanceable' },
  { day: '06/01/2021', brand: 'Glanceable' },
];

// 13) code a function that build this array programmatically
let arrayNewWithReviews = [
  { day: '01/01/2021', reviews: 10 , brand: 'Glanceable'},
  { day: '02/01/2021', reviews: 35, brand: 'Glanceable' },
  { day: '03/01/2021', reviews: 34, brand: 'Glanceable' },
  { day: '04/01/2021', reviews: 20, brand: 'Glanceable' },
  { day: '05/01/2021', reviews: 8 , brand: 'Glanceable'},
  { day: '06/01/2021', reviews: 50, brand: 'Glanceable' },
];


// 14) code a function that sort arrayNewWithReviews by reviews in ascending order
// 15) code a function that filter arrayNewWithReviews to have element with reviews above 10
// 16) code a function with reduce that makes the sum of all element in arrayNewWithReviews with reviews above 10



Bracket notation, dynamically create keys :

// 17) code a function that creates the following array from array1 (more difficult one)

let array2 = [
  { dayOne: '01/01/2021', reviews: 10 },
  { dayTwo: '02/01/2021', reviews: 35 },
  { dayThree: '03/01/2021', reviews: 34 },
  { dayFour: '04/01/2021', reviews: 20 },
  { dayFive: '05/01/2021', reviews: 8 },
  { daySix: '06/01/2021', reviews: 50 },
];


```
