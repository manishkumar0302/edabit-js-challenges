[RegEx XVII : Quantifiers - x{n}, x{n,}, x{n,}](https://edabit.com/challenge/5vsYNXXQ7aXzQMMpQ)

    const REGEXP = /\.{3,5}/g

[RegEx: Boundary Assertions](https://edabit.com/challenge/AWENJSwyhcceiKvQX)

    function isJS(path) {
	return path.match(/.js/g)?true:false
	}
[RegEx XV : Group Ranges - Negated Character Sets](https://edabit.com/challenge/rHtS59yApEQbANPcx)

     const REGEXP = /[^/\s^0-9^a-z]/gi

[How Many Vowels?](https://edabit.com/challenge/3EQGHyiYTNc9LPmhF)

    function countVowels(str) {
	return str.match(/[a,e,i,o,u]/gi).length;
	}
[Regex Series: Even Number?](https://edabit.com/challenge/pQh6uEM2Dp3BjAyzS)

    let x = /^\d+[02468]$/

[Remove Every Vowel from a String](https://edabit.com/challenge/DbLp2kHgwQbridSSy)

    function removeVowels(str) {
	var regex=/[aeiou]/gi;
	return str.replace(regex,'');
	}

[Hashes and Pluses](https://edabit.com/challenge/ydBcGvv3n447nbxCy)

     function hashPlusCount(str) {
	 var arr=[];
	 arr.push((str.match(/#/g)|| []).length);
	 arr.push((str.match(/\+/g) || []).length);
	 return arr; }

