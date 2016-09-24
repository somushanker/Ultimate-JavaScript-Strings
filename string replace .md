var  myString = "Attack winterfell at dawn !"  
undefined  
myString.replace("Winterfell","casterly Rock");  
"Attack winterfell at dawn !"  
var myString2 = "Bob says Bob's burgers has the best burgers."  
undefined  
myString2.replace("burgers","chicken");  // when we use replace with "double quotes " it will replace only first word  
"Bob says Bob's chicken has the best burgers."  
myString2.replace(/burgers/g,"chicken");  
"Bob says Bob's chicken has the best chicken."  // when we use /before and after /g ,then we can replace it in entire  
![string replacement](https://cloud.githubusercontent.com/assets/20327319/18811031/50a7f3ea-825a-11e6-9028-573884869be9.png)
