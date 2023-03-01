# CS477-2023-03-Quiz03
1. What is the difference between settimeout and setImmediate?
2. What is the output of the following code?
setTimeout(() => {
    console.log(1)
}, 0);

process.nextTick(() => {
    console.log(2)
})

setImmediate(() => {
    console.log(3);
})
