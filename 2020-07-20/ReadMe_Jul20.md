## July 20th Challenges
-----------------------------------------------
[No Conditionals?](https://edabit.com/challenge/WjXHgXLAvMxNvD6h2)
    function flip(y) {
	return 1-y;
	}

[Filter out Strings from an Array](https://edabit.com/challenge/b2NdDSdkjqFnCTfS8)
    function filterArray(arr) {
	return arr.filter(word=>(typeof(word)!="string"))
	}

[Repeating Letters](https://edabit.com/challenge/Mc6Xi4PRw7fDzeMDB)
    
    function doubleChar(str) {
	return str.split('').map(x=>x=x.repeat(2)).join('');
    }

[Repeat String N number of times](https://edabit.com/challenge/MjqneMZ7aZa8AxXZG)

    function repetition(txt, n) {
	return txt.repeat(n);
	}
	
   

[Highest Digit](https://edabit.com/challenge/YJuhHKSmNCaKNHcD3)

    function highestDigit(number) {
	return Math.max(...(number+''.split('')));
	}
 

[Scrable Hand](https://edabit.com/challenge/i6YqzHcSiPiEQKjeX)

    function maximumScore(tileHand) {
	return tileHand.reduce((acc,red)=>acc+red.score,0)
	}

[Sums of cubes](https://edabit.com/challenge/XdAR3KohR5w7rjrFg)

    function sumOfCubes(nums) {
	return nums.reduce((acc,red)=>acc+Math.pow(red,3),0); 
	}


[Factorial](https://edabit.com/challenge/Ju7AK9rAGjz86hjxo)

    function factorial(z) {
	if(z<0) return ;
	if (z === 0) return 1;
	return z * factorial(z - 1);
	}

[Alogrithm-Intro to recrusion](https://edabit.com/challenge/vtDnynHfWCnMaKYym)

    function factorial(num) {
	if(num<0) return ;
	if (num === 0) return 1;
	return num * factorial(num - 1);
	}

[Summing a slice](https://edabit.com/challenge/B3FR3P7g8NyTg7t8b)

    function sliceSum(arr, n) {
	return arr.slice(0,n).reduce((acc,red)=>acc+red,0);
	}


