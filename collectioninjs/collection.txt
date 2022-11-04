document.write("hello from external fil ");

let myarray = ["one",1,"two",2];
console.log(myarray);
myarray.length=5;
console.log(myarray);
//new array with 10 elemens 
let myarray2=new Array(10);

console.log(myarray2);
let myarray3 = new Array(20)
myarray3[0]="one";
myarray3[1]="two";
myarray3[2]="three";
myarray3[3]="four";
console.log(myarray3);
console.log('traditional for loop:')
for(let i=0; i<mayarray3.length;i++){
    console.log(myarray3[i]);
}
console.log('functional foreach loop:')
myarray3.forEach(function(element){console.log(element);});