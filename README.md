# count-no.-of-vowels-in-given-string.js
//js to count no. of vowels in given string.
//js to count no. of vwels in given string
const countVow=(str)=>{
    let count=0;
    for(const char of str){
           if (char==="a" || char==="e" ||char==="i" ||char==="o" ||char==="u")
           {
           ++count;
           }
           return count;
    }
};
