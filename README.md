# My portfolio

Welcome to my portfolio .

For Now I Know :

1.HTML

2.CSS

3.Java Script

4.Nodejs

5.Repl.it

Quiz 

how much your friends knows you:

var readlineSync = require("readline-sync");

var score = 0;
var userName = readlineSync.question("What's Your Name? ");

console.log("Welcome!" + userName +  " Do You Know Rachana");
function play(question,answer){
var userAnswer = readlineSync.question(question);

if(userAnswer === answer){
  console.log("Right!");
  score = score + 1;
  }
  else{
    console.log("wrong!");
  }

  console.log("current score is: ",score);
  console.log("_______");
}

var highscore = [{name:"soumya",score:"3"},{ name:"rashmi",
  score:"3"}];

var questions = [ {
  question:"what is Rachana's fav colour? ",
  answer:"black"},{
    question:"what is Rachana's fav food? ",
    answer:"pulav"},{
      question:"who is Rachana's fav actress? ",answer:"deepika padukone"},{
        question:"what is Rachana's fav sweet? ",
      answer:"gulab jamun"}];

for(var i=0; i<questions.length;i++){
  var currentquestion = questions[i];
  play(currentquestion.question,currentquestion.answer);
}
console.log("YAY! Total score is:",score);

console.log("Send me a ss  if u have high score",highscore);
