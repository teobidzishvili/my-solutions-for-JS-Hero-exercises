# My solutions for [JS Hero exercises](https://www.jshero.net/en/success.html) 


[26. String: replace()](https://www.jshero.net/en/koans/replace.html)
```
function normalize(date){
  let slash = date.replaceAll('-', '/');
  return slash;
}
```
[34. Math.PI](https://www.jshero.net/en/koans/pi.html)
```
function area(r){
  return Math.pow(r, 2) * Math.PI; 
}
```
[35. Rounding](https://www.jshero.net/en/koans/round.html)
```
function round100(a){
  var ten = Math.round(a/100) * 100;
  return ten;
}
```
[36. Random numbers](https://www.jshero.net/en/koans/random.html)
```
function dice(){
  let n = Math.floor(Math.random() * 6) + 1;
  return n;
}
```
[39. NOR](https://www.jshero.net/en/koans/nor.html)
```
function nor(x, y){
  let nor = x || y;
  return !nor;
}
```
[40. XOR](https://www.jshero.net/en/koans/xor.html)
```
function xor(a, b){
  let dif = (a || b) && (!(a && b));
  return dif; 
}
```
[49. else if](https://www.jshero.net/en/koans/elseif.html)
```
function addWithSurcharge(a, b){
  let surchargeA;
  let surchargeB;
  if (a <= 10){
    surchargeA = a + 1;
  }else if(a > 10 && a <= 20){
    surchargeA = a + 2;
  }else{
    surchargeA = a + 3;
  }
  if (b <= 10){
    surchargeB = b + 1;
  }else if(b > 10 && b <= 20){
    surchargeB = b + 2;
  }else{
    surchargeB = b + 3;
  }
  return surchargeA + surchargeB;
}
```
[54. Sorting arrays](https://www.jshero.net/en/koans/arraysort.html)
```
function sort([a, b, c]){
  let array = [a, b, c];
  array.sort(function (a, b){return a - b});
  return array;
}
```
[56. Array: indexOf()](https://www.jshero.net/en/koans/arrayindexof.html)
```
function add(array, c){
  let a = array.indexOf(c);
  if (a < 0){
    array.push(c);
    return array;
  }else{
    return array;
  }
}
```
[58. Array: slice()](https://www.jshero.net/en/koans/slice.html)
```
function halve(array){
  let L = array.length;
  let N = Math.ceil(L / 2);
  return array.slice(0, N);
}
```
[60. Array of arrays](https://www.jshero.net/en/koans/dimarray.html)
```
function flat(array){
  let zero = array[0];
  let one = array[1];
  let two = array[2];
  let zo = zero.concat(one);
  let zot = zo.concat(two);
  return zot;
}
```
[63. null](https://www.jshero.net/en/koans/null.html)
```
function cutComment(line){
  let index = line.indexOf('/');
  let comment = line.substr(index + 3);
  if (index === -1){
    comment = null;
  }
    return comment;
}
```
[67. while loop](https://www.jshero.net/en/koans/while.html)
```
function spaces(n){
  let space = '';
  while (space.length < n){
    space = space + ' ';
  }
  return space;
}
```
[69. gcd](https://www.jshero.net/en/koans/ggt.html)
```
function gcd(a, b){
  let x = Math.min(a, b);
  while (a % x !== 0 || b % x !== 0){
    x--;
  }
  return x;
}
```
