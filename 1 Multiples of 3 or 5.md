Problem 1: Multiples of 3 or 5 = If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9.
The sum of these multiples is 23.

function multiplesOf3and5(number) {
var i;
for (i=3; i++; i<number) {
var sum=0;
if (i%5 ===0 || i%3 ===0)
sum=sum+i;

}
return sum;
}

multiplesOf3and5(1000);
