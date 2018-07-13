# basicAlgorithms
basic algorithm problem solving
/* Basic algorithm scripting to reverse a string */


function reverseString(str) {
/* new var string split is created and the split function is used to separate the string */
  var stringSplit = str.split("");  
/* the former var is uses the reverse function to solve the challenge at hand */
  var reverseArray = stringSplit.reverse();
/*finally the separated and reversed string is put back together with the join function */
  var stringJoin = reverseArray.join("");
  return stringJoin;
}

reverseString("hello");

