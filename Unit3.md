# codecademy
function unit3(){
var text = ("This is Paul a long string of text so Paul the program can look for my Paul name in it.");

var myName = ("Paul");

var hits = [];

for ( var i = 0; i < text.length; i++){
    if (text[i] === "P"){
        for ( var j = i; j < (i + myName.length); j++){
            hits.push(text[j]);
        }
    }
}
if (hits.length === 0) {
console.log("Your name wasn't found!");
} else {
console.log(hits);
}
}
