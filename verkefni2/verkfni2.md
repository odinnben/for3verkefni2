**1.Búðu til object með upplýsingar um þig; nafn, heimasími og gsm.Prentaðu út með console.log() síðara símanúmerið(0.5%)**
 ```javascript
 var odinn ={
	name: "odinn",
	gsm:"7770412",
	heimasimi: "555393",

};
console.log(odinn.gsm)
 ```
 **2.Prentapu út með console.log()Nonni(0.5%)**
 ```javascript
 let family = {
"parents": 
{
"fathers": [{"name":"Jakob"},{"name":"Nonni"}],
"mothers":[{"name":"Rakel"},{"name":"Sara"}]
}
};
console.log(family.parents.fathers[1].name)

  ```
 **3.Leystu lið 8 í Objects á Udacity https://classroom.udacity.com/courses/ud803(1%)**
 ```javascript
 let breakfast = {
    name: "The Lumberjack",
    price: "$9.95",
    ingredients: ["eggs","sausage","toast","hashbrowns","pancakes"]
};
console.log(breakfast.name)
console.log(breakfast.price)
console.log(breakfast.ingredients)
 ```
 **4.Leystu lið 9 í Objects á Udacity https://classroom.udacity.com/courses/ud803(1%)**
 ```javascript
  var savingsAccount = {
  balance: 1000,
  interestRatePercent: 1,
  deposit: function addMoney(amount) {
    if (amount > 0) {
      savingsAccount.balance += amount;
    }
  },
  withdraw: function removeMoney(amount) {
    var verifyBalance = savingsAccount.balance - amount;
    if (amount > 0 && verifyBalance >= 0) {
      savingsAccount.balance -= amount;
    }
  },
  printAccountSummary() {
   return("Welcome!\nYour balance is currently $"+savingsAccount.balance+" and your interest rate is "+ savingsAccount.interestRatePercent+"%."); 
  },
}; 

savingsAccount.printAccountSummary();

 ```
 **5.Leystu lið 8 í Objects á Udacity https://classroom.udacity.com/courses/ud803(1%)**
```javascript
var donuts = [
    { type: "Jelly", cost: 1.22 },
    { type: "Chocolate", cost: 2.45 },
    { type: "Cider", cost: 1.59 },
    { type: "Boston Cream", cost: 5.99 }
];

donuts.forEach(function(donuts) {
  console.log(donuts.type +" donuts cost $"+ donuts.cost + " each");
});

```
**6.Búðu til og notaðu smið (e. function constructor) til að búa til tvær mismunandipizzur (objects).Pizzan þarf að hafa; verð, stærð (large,medium, size) og álegg (ostur, skinka, pepperoni,ananas).Dæmi: Stór Magherita (ostur, oregano) kr. 2195.(1%)**
```javascript
function pizza  (name,size,pirce,topping){
	this.name = name;
	this.size = size;
	this.price = pirce;
	this.topping = topping;
};
let pizza1 = new pizza("margarita","medium","2000kr",["ostur","oregano"])
let pizza2 = new pizza("eldorado","big","2590kr",["jealpons","pepporni,rjomaostur,chilli"])

console.log(pizza1)
console.log(pizza2)
```
