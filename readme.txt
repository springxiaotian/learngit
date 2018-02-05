{
	let a=10;
	var b=1;
}
/*console.log(b);
console.log(a);*/
/*var a = [];
for (var i = 0; i < 10; i++) {
  a[i] = function () {
    console.log(i);
  };
}
a[1](); // 1
for (let i = 0; i < 10; i++) {
  // ...
}

console.log(i);*/
function f() { console.log('I am outside!'); }

(function () {
  function f() { console.log('I am inside!'); }
  if (false) {
  }
  f();
}());

