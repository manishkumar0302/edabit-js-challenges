July 18th
------------
a. [ Find the Smallest and Biggest Numbers](https://edabit.com/challenge/Q3n42rEWanZSTmsJm)
function minMax(arr) {
	
	return [Math.min(...arr),Math.max(...arr)];
}

b. [Check if One Array can be Nested in Another](https://edabit.com/challenge/Gpy2qSFnfhGJnWMMj)

    function canNest(arr1, arr2) {
	 return (Math.min(...arr1)>Math.min(...arr2) && Math.max(...arr1)< Math.max(...arr2))?true:false;
}


c. [Which Function Returns the Larger Number?](https://edabit.com/challenge/o7TwicAHWuMkjbDqQ)
            
            function whichIsLarger(f, g) {
	if(f()>g()) return "f";
	else if(g()>f()) return "g";
	else return "neither";
}

d. [Convert a Number to Base 2](https://edabit.com/challenge/3kcrnpHk7krNZdnKK)
      
      function binary(decimal) {
	return decimal.toString(2);
}
e. [Largest Swap](https://edabit.com/challenge/hD3euqPHM82Cbr7R8)
    
    function largestSwap(num) {
	return parseInt(num.toString().split('').reverse().join(''))<=num;
}
f. [Find Number of Digits in Number]( https://edabit.com/challenge/yFJzLfYghz7ZtsyAN)
   
    function num_of_digits(num) {
	 return Math.max(Math.floor(Math.log10(Math.abs(num))), 0) + 1;
}

g. [Is it Time for Milk and Cookies?](https://edabit.com/challenge/hPWnaSckJke5FXNEH)
           
    function timeForMilkAndCookies(date) {
	return (date.getMonth()==11)?(date.getDate()==24?true:false):false;
}

h. [RegEx XIV: Group Ranges x|y]([https://edabit.com/challenge/7KbZc8QvzqrJPaE6Q)

    const REGEXP = /blue flag|red flag/g

i. [Count Instances of a Character in a String](https://edabit.com/challenge/kbFhwaDyrd79JrgeB)

    function charCount(myChar, str) {
	return str.split('').filter(word=> word==myChar).length;
}

j. [Promises III: Native Promise, Introducing the Executor](https://edabit.com/challenge/8kTQqoWYQXRsKuYEf)

    let promise = new Promise( (resolve, reject) => {
     setTimeout(( ) => {
     resolve("sample")
     }, 1000)
     })
