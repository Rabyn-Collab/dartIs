void main (){
//int to String
int age = 36;
String ageString = age.toString();
print(ageString);

//double to String
double height = 1.84;
String heightString = height.toString();
String heightString1 = height.toStringAsFixed(0); 

print(heightString);  
print(heightString1); 
  
print(heightString.runtimeType);  
print(heightString1.runtimeType); 
  
//String to int and double
  String ratingString = '4.5';
  String ratingString1 = '4';
  
  double doubleRating = double.parse(ratingString);
  int intRating = int.parse(ratingString1);
  
  print(doubleRating);
  print(intRating);
  print(doubleRating.runtimeType);
  print(intRating.runtimeType);
  
 //double to int
  
  double amount = 90.90;
  int intAmount = amount.round();
  print(intAmount);
  print(intAmount.runtimeType);
  
  
}