# core-code-upskilling-readme

Solution to first challenge: "Ensure Question"
```
const ensureQuestion = (str)=>{
    return (str.charAt(str.length-1)=="?") ? str:(str+"?");
}
```


Solution to second challenge: "Reverse Words"
```
const reverseWords = (str) => {
    return Array.from(str.split(' ')).reverse().join(' ');
}
```
