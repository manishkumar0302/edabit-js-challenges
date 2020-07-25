
[Multiply by Length](https://edabit.com/challenge/LMhRTq3hccz2D9Lax)
 
    function multiplyByLength(arr) {
	return arr.map(num=>num*arr.length)
	}

[Convert Year to Century](https://edabit.com/challenge/H3fKTSK4dgwXRbfTP)
              
    function centuryFromYear(year) {
	return Math.ceil(year/100);}

[Matchstick Houses](https://edabit.com/challenge/tYHkTdFrEmWfxpPKF)

    function matchHouses(step) {
	return step==0?0:(step*6)-(step-1);}

[Friday the 13th](https://edabit.com/challenge/98CAqzDToJdx5LGFm)
 
      function hasFriday13(month, year) {
	return (new Date(year,month-1,13).getDay())==5?true:false;}

[Maximum Edge of a Triangle](https://edabit.com/challenge/nhXofMMyrowMyr9Nv)

    function nextEdge(side1, side2) {
	return side2+side1-1;}

[Printer Levels](https://edabit.com/challenge/QXWM2oo7rQNiyDsip)

    function inkLevels(inks) {
	return Math.min(...(Object.values(inks)));}

[Valid Zip Code](https://edabit.com/challenge/Ysk5M8XAscc4fqaAi)

     function isValid(zip) {
	return zip.length>5?false:(/\d{5}/).test(zip)==true?true:false;}

[Find the Bug: Returning Valid Units of Measure](https://edabit.com/challenge/oGYGaavTNoYDjykJY)

      function hasValidUnitOfMeasure(product = {}) {
	const { unitOfMeasure, comment } = product
	return (((unitOfMeasure==undefined && comment)?true:false)|| unitOfMeasure === 'L' || unitOfMeasure === 'PCE')}

