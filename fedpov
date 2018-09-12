function fedpov(house,income,percentage){
	// Determines if your income is less than or equal to 
	// a percentage of the 2018 federal poverty guidelines 
	// for the contiguous United States. See
	// https://www.federalregister.gov/documents/2018/01/18/2018-00814/annual-update-of-the-hhs-poverty-guidelines
	
		var line = NaN;
	
		if (house == 1) {
			line = 12140;
		} else if (house > 1) {
			line = 12140 + (house-1)*4320;
		}	

		if (income <= (line*(percentage/100))) {
			return true;
		} else {
			return false;
		}
	}	
