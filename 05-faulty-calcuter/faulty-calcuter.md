/*
this is a faulty calcuter

It preform wrong operation 10% of the times 
*/

```javascript
let random = Math.random()
console.log(random)
let a = prompt("Enter first number")
let c = prompt("Enter operation number")
let b = prompt("Enter secound number")

let obj ={
    "+": "-",
    "*": "+",
    "-": "/",
    "/": "**"
}
if (random > 0.1){
    // perform the currect operation
    alert(`the reuslt is ${eval(`${a} ${c} ${b}`)}`)

}

else {
        // perform the worng operation
    c = obj[c]
    alert(`the reuslt is ${eval(`${a} ${c} ${b}`)}`)
}
```
