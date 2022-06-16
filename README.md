1) For the given JSON iterate over all for loops (for, for in, for of, forEach)?
Ans:- 
var jsondata=[{"name":"aziya","subject":"javascript","gender":"female","city":"hyderabad"}];
//for loop

for(var i=0;i<jsondata.length;i++){
console.log(jsondata[i]);
}

//for in loop

for(var i in jsondata){
console.log(jsondata[i]);
}


2)Create your own resume data in JSON format?
Ans:-
var jsondata={"name":"aziya"};
jsondata["studies"]="MTech";
jsondata["country"]="India";
jsondata["email"]="email@gmail.com";
jsondata["Number"]=0123456789;
console.log(jsondata);


3)Read about the difference between window, screen and document in javascript?
Ans:-

Window object:-
            Window object represents the browser's window that a document is displayed in. All global JavaScript varaibles,functions and objects automatically become               members of the Window object.
Document:-
          The Document interface respresents any web page loaded in the browser and servers as an entry point into the web page's content,which is the DOM tree.The              DOM tree inculdes elements such as <body> and <table> among many others.It provides functionality globally to the document,like how to obtain the page's               url and create new element in the document.
Screen:-
        The Screen interface represents a screen,usually the one on which the current window is being rendered and is obtained being using window.screen
  
  
  
  
  
  
