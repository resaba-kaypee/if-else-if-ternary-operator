# if-else-if-ternary-operator
//single condition operator(if, else)
function checkEqual(a, b) {
  return a !== b ? false : true;
}

console.log(checkEqual(1, 2));

//multiple condition operator(if, else if, else)
function checkSign(num){
return (num > 0) ? "positive" : (num < 0 || num) ? "negative" : "zero";
}

checkSign(10)
