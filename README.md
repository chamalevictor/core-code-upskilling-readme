# core-code-upskilling-readme

Challenge 1: "Ensure Question"
```
const ensureQuestion = (str)=>{
    return (str.charAt(str.length-1)=="?") ? str:(str+"?");
}
```


Challenge 2: "Reverse Words"
```
const reverseWords = (str) => {
    return Array.from(str.split(' ')).reverse().join(' ');
}
```

Challenge 3: "Smallest int"
```
class SmallestIntegerFinder {
  findSmallestInt(arr) {
    return arr.sort((a,b) => {return a-b;})[0];
  }
}
```
