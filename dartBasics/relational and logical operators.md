
```dart

void main (){
  //operators name
 
  print(5 == 2);  //equal
  print(5 != 2);  // not equal
  print(5 > 2);  //greater than
  print(5 < 2);  // less than
  print(5 >= 2); //greater or equal to 
  print(5 <= 2); // less or equal to 
   
  //logical operators
  
  print(5 < 2 || 5 < 7); // one condition have to be true to print true
  print(5 > 2 && 5 < 7); // both condition have to be true to print true
 
  String email = 'test@example.com';
  print(email.isNotEmpty && email.contains('@'));
  
  
 /*
  
  you can comapare print(5 < 2); both are numbers
  but you can't compare  number to string (5 < 'hello');
   
   */
  
  
}