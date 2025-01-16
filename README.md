# Q-A--JS

#Q1.Find the Missing Number in an Array
Input: [1, 2, 4, 5]
Output: 3 (The missing number)

let arr=[1, 2, 4, 5]
let n=arr.length + 1
let expSum=(n*(n+1))/2
let sum=0
for(let num of arr){
  sum+=num
}
console.log(expSum,'expSum', sum,' sum')

let getNum=expSum-sum

console.log(getNum, 'is missiong')


