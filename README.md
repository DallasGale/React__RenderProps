# React__RenderProps
Example
`
const sum = ( a, b, rp ) => {
	const result = a + b;
  rp(result);
}

sum(1, 2, (myResult) => {
  console.log('myResult: ', myResult);
})

sum(422, 543, console.log);


const alertFn = (result) => {
  alert(result);
}

sum(43, 1, alertFn);`
