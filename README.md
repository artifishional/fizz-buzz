# fizz-buzz

	console.log(Array.apply(0, {length: 100}).map((e, i)=>
		(++i % 3 ? "" : "Fizz") + (i % 5 ? "" : "Buzz") || i
	).join("\n"));
