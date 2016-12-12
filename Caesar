
let caesarShift = function(str, amount) {

	if (amount < 0)
		return caesarShift(str, amount + 26);

		let result = '';


	for (let i = 0; i < str.length; i ++) {


		let x = str[i];


		if (x.match(/[a-z]/i)) {


			let code = str.charCodeAt(i);


			if ((code >= 65) && (code <= 90)) {
				x = String.fromCharCode(((code - 65 + amount) % 26) + 65);
			}

			else if ((code >= 97) && (code <= 122)) {
				x = String.fromCharCode(((code - 97 + amount) % 26) + 97);
			}

		}

		result += x;

	}

	return result;

};

