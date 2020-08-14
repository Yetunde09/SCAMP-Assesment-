# SCAMP-Assesment-

function fibonacciSeq(n){
   let arr = [0, 1]
   
  if (n === 0) arr = `Invalid Fibonacci operation`
  if (n === 1) arr = [0]
  if (n === 2) arr = [0, 1]
  
  for (let i = 2; i < n; i++){
     let result = arr[arr.length - 1] + arr[arr.length - 2] 
      arr.push(result)
  }
  return arr
}

const answer = fibonacciSeq(10)
console.log(answer)
