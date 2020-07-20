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
 


