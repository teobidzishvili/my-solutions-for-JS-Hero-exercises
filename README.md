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


